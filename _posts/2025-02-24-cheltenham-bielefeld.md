---
layout: post
title:  "The Cheltenham–Bielefeld and 51.88±0.04°N railways"
date:   2025-02-24 00:01:00 +0000
categories: [silly train ideas]
---

_A version of this content
was originally posted on the [#Railnatter Discord][rn-discord] in October 2024_

A while back,
a discussion on the [#Railnatter Discord][rn-discord]
started around alternative Channel crossings.
In this,
a Felixstowe–Rotterdam high-speed tunnel was suggested.
I noticed that these were almost at the same latitude,
and wondered what would happen if you extended this high-speed railway outwards.

## Searching Wikidata

To understand where this railway could go,
I needed a list of cities filterable by their latitude.
My approach to this problem was to use [Wikidata][wikidata].

I've never used SPARQL
(pronounced "sparkle"),
Wikidata's query language,
before,
so there was a bit of a learning curve to getting the data I needed.
After an hour of prodding,
I got a query something like:

```sparql
SELECT ?town ?townLabel ?population ?coord ?lon ?lat WHERE {
  ?town wdt:P31/wdt:P279* wd:Q1549591.
  OPTIONAL {
    ?town wd:Q4145472 ?population.
  }
  ?town p:P625 ?coordinate.
  ?coordinate ps:P625 ?coord.
  ?coordinate psv:P625 ?coordinate_node.
  ?coordinate_node wikibase:geoLongitude ?lon.
  ?coordinate_node wikibase:geoLatitude ?lat.
  FILTER(?lat >= 51.8 && ?lat <= 52.1). 
  SERVICE wikibase:label { bd:serviceParam wikibase:language "en". }
}
```

Breaking this down a little:

```sparql
SELECT ?town ?townLabel ?population ?coord ?lon ?lat
```

Data I'm interested in:

 - `?town`: A link to the full Wikidata entry
 - `?townLabel`: The name of the town
 - `?population`: The population of the town,
   so I can skip towns with only a handful of people
   (this ended up not working,
   unfortunately)
 - `?coord`: The latitude and longitude in Wikidata's internal format
   (which ended up not being useful,
   but the documentation recommended it)
 - `?lon`: The longitude,
   so I can put the entries in order
 - `?lat`: The latitude,
   so I can filter to a closer fit if I need to

```sparql
WHERE {
```

This syntax is quite SQL-inspired;
so this introduces the filters I want in my query.

```sparql
  ?town wdt:P31/wdt:P279* wd:Q1549591.
```

What I'm referring to as a `town` should match the specification,
which breaks down as:

- `wdt:` means "has a property",
- `P31` is the "is an instance of" property,
- `P279` is the "is a subclass of" property
- `*`,
  similarly to in regular expressions,
  means "match any number of the previous criterion"
- `wd:` refers to Wikidata objects
- `Q1549591` is "[big city][big-city]"

So this query could be read:
"a `town` is an instance of `big city`,
or of any subclass of `big city`,
down any number of generations."

```sparql
  OPTIONAL {
    ?town wd:Q4145472 ?population.
  }
```

Look at the thing I've called `town`,
and if it has attribute `Q4145472` (population)
get that and call it `population`.
(Without the `OPTIONAL`,
the query wouldn't return any objects if they didn't have this attribute.)

```sparql
  ?town p:P625 ?coordinate.
```

Get the the `P625` property
("coordinate location")
and call it `coordinate`.

```sparql
  ?coordinate ps:P625 ?coord.
```

Get the "property statement" of the `coordinate` property,
and call it `coord`.
(I didn't fully understand
the distinction between "properties" and "property statements"
when I wrote this query,
and I definitely don't any more.
But this is what various docs say you need to do,
and it works.)

```sparql
  ?coordinate psv:P625 ?coordinate_node.
```

Get the value associated with the `coordinate`,
and call it `coordinate_node`.
(Actually,
we never use the `coord` except to print the Wikidata-formatted value we don't use,
so perhaps the previous block wasn't necessary?)

```sparql
  ?coordinate_node wikibase:geoLongitude ?lon.
```

Use the `wikibase:geoLongitude` function to
pull the longitude out of the `coordinate_node` entity,
and call it `lon`.

```sparql
  ?coordinate_node wikibase:geoLatitude ?lat.
```

Use the `wikibase:geoLatitude` function to
pull the latitude out of the `coordinate_node` entity,
and call it `lat`.

```sparql
  FILTER(?lat >= 51.8 && ?lat <= 52.1).
```

Reject any entities where the latitude isn't in the range [51.8, 52.1].
This gives a reasonable margin around the latitudes of the cities of interest,
not returning every city in the world,
but still potentially looking relatively flat on a map.

```sparql
  SERVICE wikibase:label { bd:serviceParam wikibase:language "en". }
}
```

Get the data from Wikidata in English.

I also wanted to make sure if there were any significant airports
inside the range,
but their attached cities were not,
they were included.
This gave another query:

```sparql
SELECT ?airport ?airportLabel ?coord ?lon ?lat WHERE {
  ?airport wdt:P31/wdt:P279* wd:Q1248784.
  ?airport p:P625 ?coordinate.
  ?coordinate ps:P625 ?coord.
  ?coordinate psv:P625 ?coordinate_node.
  ?coordinate_node wikibase:geoLongitude ?lon.
  ?coordinate_node wikibase:geoLatitude ?lat.
  FILTER(?lat > 51.8 && ?lat < 52.1). 
  SERVICE wikibase:label { bd:serviceParam wikibase:language "en". }
}
```

This is largely similar to the previous one,
but making use of the [`Q1248784`][airport] class.

Each query gave back a CSV file,
that I opened in Numbers to massage further.

Since for whatever reason
("whatever reason" being "my inexperience with SPARQL and Wikidata")
I didn't get the population information,
I needed to go through the list by hand and get population information from Wikipedia.
Once I had this,
I could filter the list to the latitudes and populations I was interested in.

While in the process doing this,
I spotted that both London Luton and London Stansted airports
were at almost exactly the same latitude,
(51.874°N and 51.885°N respectively),
so thought they would be a good centre for the route,
and centering a region on the mean of these two
(51.88°N)
meant that allowing a ±0.04° margin
gave a good number of results.

## GIS

At this point,
I exported my filtered data as a CSV,
and imported it into [QGIS][qgis].
While I've used QGIS before,
I'm not that comfortable or fluent with it,
so wanted to do the minimum possible,
and do the rest in [Inkscape][inkscape],
which I'm a lot more familiar with.

I got QGIS to display a base map of aerial imagery,
and on top of this place dots at each of the coordinates in my CSV.
I exported this as a high-resolution PNG
both with and without the dots,
and imported the former into Inkscape.

## Inkscape

In Inkscape,
I joined the dots to form the line,
added captions,
and then swapped out the base imagery for the dotless version,
so any points I decided to skip didn't show up in the final image.

(If you're interested in seeing roughly the sort of thing I did,
check out
[the video I made on sketching up railway diagrams in Inkscape][inkscape-video],
which is closely based on Gareth Dennis's
[#Railnatter on how to do this with PowerPoint][rn-powerpoint].)

## The 51.88±0.04°N high-speed railway

![Map of northern central and western Europe,
with a horizontal railway line in pink calling at
the stations listed below..](/images/single-latitude/tight.png){: .displaypic}

We start in western Ireland in Kenmare,
latitude 51.880°N,
population 2,566.
(In principle,
we could have started in Porthmagee,
latitude 51.886°N,
but with a population of 116,
this seemed a bit of a stretch.)
From there,
we head east to Cork,
before crossing the Irish Sea to St Davids.
(This is not one of the crossings suggested in
[the #Railnatter on Irish Sea fixed links][rn-irish-sea]

I aimed for a station spacing of roughly 1° longitude,
where there were reasonably-sized population centres available
(typically in the tens of thousands)
except for where sparsity made that hard to achieve,
where either I used smaller towns,
or had no stops.

In Wales,
we then call at Carmarthen,
before heading straight across the Brecon Beacons
(Brecon itself being just a few kilometres too far north to be considered),
and stopping next at Gloucester, in England.
We then stop at Bicester Village,
London Luton Airport,
London Stansted Airport,
and Colchester,
before heading under the North Sea.
While a little bit random,
these are all places that deserve decent rail connections,
albeit not necessarily to each other.

Surfacing in the Netherlands,
we stop at Rotterdam Beurs
(because Rotterdam Centraal is a few hundred metres too far north),
then Nijmegen,
before crossing the border into Germany
and calling at Borken,
Gütersloh,
Bad Gandersheim,
Halberstadt,
Staßfurt,
Lutherstadt Wittenberg,
and Lübbenau.

There is then a large sparse area as we cross the border into Poland,
but eventually we find some smaller Polish towns worth stopping at:
Leszno,
Pleszew,
Zgierz,
and Grójec (population 16,674).

## The Cheltenham–Bielefeld High-Speed Railway

Reader,
you may have noticed that in my excitement around Luton and Stansted airports,
I have got side-tracked from the initial brief,
a tunnel from Felixstowe to Rotterdam.

I only spotted this when I came to post the image on Discord
(a few months after the original post).
So before doing this,
I went back and took a slightly wider look at latitudes,
and came up with a slightly sparser,
but potentially more sensible line.

Once again we start in Ireland,
but this time skip the connection to a small town in the middle of nowhere,
instead starting in Cork.
From there,
we head straight to Carmarthen,
then to Cheltenham rather than Gloucester.
We still call at London Luton and London Stansted airports,
before heading to Felixstowe.

Down under the North Sea,
up again in Rotterdam,
and then east to Münster and Bielefeld.
The only two remaining significant cities in the latitude range
are Zielona Góra, Poland
(population 140,403),
and Brest, Belarus
(population 344,470).
This gives a very long distance without stops however,
so in this region only I broadened the search range further,
and came up with Magdeburg, Germany
(population 239,364)
and Lódz, Poland
(population 665,279).

![Map of northern central and western Europe,
with an almost horizontal railway line in pink calling at
the stations listed above.](/images/single-latitude/loose.png){: .displaypic}

As you can see,
this gives a bit more wobble than the previous railway,
but is potentially slightly more practical.
(I wouldn't realistically use the word "practical" to describe either proposal,
but these things are relative.)

## And beyond?

This work seems quite European-centric;
this is not entirely by design.
It turns out that going further afield,
there are very few cities at this latitude.
One or two in the Far East,
and one or two in North America.
Not enough that a railway makes any degree of sense
(in the twisted way that the one mapped above kind of does,
if you squint),
and the map would be really annoying to draw,
so I decided that restricting to Europe made for a better final picture.



[airport]: https://www.wikidata.org/wiki/Q1248784
[big-city]: https://www.wikidata.org/wiki/Q1549591
[inkscape]: https://www.inkscape.org
[inkscape-video]: https://www.youtube.com/watch?v=OvqIv7c2WdY
[rn-discord]: https://garethdennis.co.uk/discord
[rn-irish-sea]: https://www.youtube.com/watch?v=TeRuyO_VpWg
[rn-powerpoint]: https://www.youtube.com/watch?v=reQ_uXrGF1o
[qgis]: https://qgis.org
[wikidata]: https://wikidata.org