---
layout: post
title:  "The minimal Channel Tunnel foot passenger service"
date:   2025-03-31 00:11:00 +0100
categories: [silly train ideas]
---

[Jon Worth][jon-worth] is currently in the middle of
the [#CrossChannelRail project][cross-channel-rail],
which has me thinking about some of my pet Channel Tunnel ideas,
as well as others exploring similar ideas on the Fediverse.

Jon's project deals primarily with long-distance routes,
including possible new destinations further into Europe,
but will also look at other previous, existing, and potential routes
that make use of existing stations.

I'm interested in a related but slightly different question:
what is the minimal possible service
that can take passengers from one end of the tunnel to the other,
avoiding as many of the current problems as possible?
The intention is to allow those in southeast Kent
a quick and easy way to get to their neighbours in northern France
without needing to do a two-hour roundtrip into London to get to where they started.

(As usual for this blog,
this is just me exorcising some ponderings cluttering up the back of my mind;
don't expect anything as polished or well-reasoned as Jon's work here.)

## Option 1: Simply become a bike

[Le Shuttle][le-shuttle],
operated by [GetLink],
does not allow foot passengers on their services.
The reasoning behind this is relatively clear:
there's no easy way for foot passengers to get to their terminals,
which are only accessible by road,
and primarily optimised for car and lorry traffic from the motorway network.
However,
cyclists _can_ cross the channel with Le Shuttle,
and not by cycling directly to the terminal;
instead,
they are picked up in a bus from a hotel near the terminal,
and dropped at the CIFFCO railway training facility in Coquelles.

Why foot passengers can't be picked up by these buses as well is unclear.
But even with the current service,
all a prospective foot passenger needs to do is hire a bike.
Having a pair of automated bike hire hubs similar to Nextbike,
one at the Holiday Inn Folkestone,
and one at CIFFCO,
would allow foot passengers to cross.
How they would get to those locations is unclear,
however.
Another option would be an additional pair of bike hire hubs,
near [Folkestone West][folkestone-west] and [Calais-Fréthun][calais-frethun] stations,
allowing passengers to cycle the short distance from the station to the pickup point
(and look less like they had just picked up a bike to be able to ride the bus);
this would however require foot passengers to be able and willing to ride a bike.

An additional issue with this approach is that unlike the for cars,
where you can book same-day,
you need to give a _ten days'_ notice that you'll be travelling by bike,
and rather than having a standard booking page like for all other vehicles,
you have to fill out a contact form.
[The entire information page][getlink-bike] gives the impression that
GetLink really don't want your business in this department,
and would be much happier if you just used a motor vehicle like everyone else.

Setting up some bike racks,
bikes,
and payment infrastructure
likely wouldn't cost more than a few tens of thousands,
so I really don't see why someone hasn't already done this!

## Option 2: Just run a bus

So,
GetLink have established that you can take passengers without motor vehicles,
and put them on a bus to take them through the tunnel.
GetLink don't really want to support this,
especially for non-cyclists,
but can another company step in to fill the gap?

Is there any barrier to running a local bus service that starts in,
for example,
Folkestone Central or Dover Priory,
makes a few local calls
(for example,
at Folkestone West and Cheriton),
then loads onto Le Shuttle.
At the other end,
it could drop off at Cité Europe
(for folks making quick shopping trips to France)
and [Calais-Fréthun][calais-frethun] for those making onward TGV connections.
(A service into the Calais city centre might also be valuable,
but would be harder to use for onward connections,
as [Calais-Ville station][calais-ville] is less well connected than Calais-Fréthun.

Having never organised a coach trip via the Channel Tunnel,
I'm not sure how much notice is required for passenger numbers and passport details.
I suspect that operating this as a turn-up-and-go local bus service
would not be possible without special cooperation from GetLink.
But for a booked-in-advance service,
this seems eminently possible.

Given that the highway&ndash;highway crossing requires 90 minutes during busy periods,
allowing for travel time in and out of the towns at each end,
you would probably need a fleet of at least six buses
to run an hourly service each way.
With more vehicles,
a half-hourly service could be possible,
as this is the minimum cadence of passenger vehicle shuttles through the tunnel.
Vehicles would need to be bespoke,
as doors would be needed on both sides&mdash;otherwise,
passengers in one or other country
would need to be picked up from and dropped off in the middle of the road,
due to the differing traffic conventions in the UK and France.
Given that a significant amount of time will be spent
not moving under their own propulsion,
the buses would be an ideal case for battery electrification.

Electric buses can apparently be had for £250k,
but bespoke ones are likely to cost more.
However,
it would be likely possible to test the waters with a three-hourly service
operated using two buses,
charged using the public rapid charging network,
for a total capital cost in the low single-digit millions of pounds sterling.

Running costs and possible fares are harder to compute.
GetLink provides a [rate card][getlink-coaches] for coaches,
but loadings on a local bus are likely to be
light enough that the standard consumer pricing may be more economical
than the bulk rates given to coach operators.
Unfortunately,
GetLink/Le Shuttle don't provide price estimates without you entering
a lot of vehicle information
not immediately available to a blogger just looking at possibilities.

## Enough about buses already, what about trains?

Any bus service is going to have a frustrating amount of
waiting around to get onto the shuttle train.
It would be far more preferable to have a passenger train service.

### Can we stick within GetLink infrastructure?

![Map of the Folkestone area](/images/minimal-channel/folkestone.png){: .displaypic}

One of the difficulties of running passenger trains through the tunnel is that
the operator needs to work with three different track access organisations
([SNCF Réseau][sncf-reseau],
[GetLink][getlink],
and either <s>High Speed 1</s> [St Pancras High Speed][sphs]
or [Network Rail][network-rail]),
work to three different sets of regulations and loading gauges,
and certify rolling stock for two countries plus the tunnel,
which has a separate certification.

It would be much easier if only one set of infrastructure could be used.
Would it be possible to run a service entirely within GetLink's infrastructure?
Currently there are no stations inside the area of GetLink's concession,
so any passenger service not leaving that area
would require the construction of new stations at both ends.
Potentially
the existing passport control infrastructure for Le Shuttle could be shared.
But is there a good side for a passenger station at all?
Both the Folkestone and Calais terminals are a long way outside their respective towns,
and the tracks are surrounded by vast amounts of motor vehicle infrastructure,
so realistically,
there is no viable route for pedestrians to access platforms for passenger trains.
This would necessitate buses,
and once you're running buses anyway,
deboarding everyone to board a passenger train
is even worse than waiting to load a bus onto a vehicle shuttle.

Long story short,
this appears to be a non-starter
But what would be the minimal amount of
High Speed 1 and LGV Nord track
that would be needed to run a viable passenger service?

### Ashford International

I hadn't planned to talk much about Ashford,
because it already exists so isn't hypothetical enough for my interests,
but to seriously discuss alternatives,
it does make sense to know what Ashford does well.
This subsection is likely to overlap with some [#CrossChannelRail][cross-channel-rail] work.
If there is any discrepancy between what is stated here and what Jon reports,
Jon is almost certainly correct,
as he has done the leg work and I haven't.

![Diagram showing the various lines converging at Ashford International](/images/minimal-channel/ashford.svg){: .displaypic}

[Ashford International][ashford] is currently
the closest passenger station to the Channel Tunnel.
It has separate international platforms
(Platforms 3 and 4),
and the necessary baggage and passport handling facilities for international services.
It hasn't been used
since it closed due to the collapse in passenger numbers during the pandemic,
so it was likely never adapted
to have separate British and French border controls after Brexit.

High Speed 1 itself passes to the north of the station,
with international trains stopping at Ashford turning off to call there.
This means that given the current lack of any international trains from Ashford,
Platforms 3 and 4 should be completely unused,
and stopping trains there for arbitrary amounts of time
should not obstruct any other services.
There is a double crossover for the international tracks to the east of the station,
so trains can turn around at either international platform.

![Diagram showing the platform layout of Ashford International](/images/minimal-channel/ashford-platforms.svg){: .displaypic}

All domestic high speed services from St Pancras International via Ashford International
use the domestic platforms 5 and 6
before continuing on to the Southeastern Main Line,
and no services join HS1 there,
so the paths for domestic services on HS1 from St Pancras to Ashford International
should be available for
international services from Ashford International to the Channel Tunnel.

In terms of domestic connectivity,
Ashford International sits at a major junction between High Speed 1,
the Southeastern Main Line,
the Ashford to Ramsgate line,
the Kent Downs line,
and the Marshlink line.

All in all,
Ashford International is pretty well-placed for
a minimal shuttle train to the continent.
Its only drawbacks are the ones discussed above:
a significant amount of HS1 is used,
so the complications of a second type of infrastructure are unavoidable,
as are HS1's track access charges,
and it still sits some way inland from Folkestone,
so residents of eastern Kent have to go a few miles the wrong way.
Compared to St Pancras though,
the complications are massively reduced.

### Sandling

![Diagram of a hypothetical Sandling International station](/images/minimal-channel/sandling.png){: .displaypic}

What if,
hypothetically,
we really wanted to minimise the length of HS1 that gets used?
That would reduce the track access charges payable,
and may allow some form of derogation for Channel Tunnel-certified trains
rather than requiring rolling stock to be fully approved for running on HS1.

We still want to have a connection with the British Rail network,
so we can get passengers to the station.
As discussed above,
there is nowhere within GetLink's concession area that can do this;
heading west out of it across the M20,
we come to the Dollands Moor freight yard,
which HS1 diverges around,
making it very difficult to build a connecting station.
[Sandling station][sandling] is the first station to the west of here
on the Southeastern Main Line,
and comes just before the two HS1 tracks begin to diverge,
making it the best available site for a new international station.
There is ample space to the north of the current Sandling station
to build a new international terminal;
the current Victorian station would likely also need to be rebuilt
to accommodate the larger passenger numbers
and to give a better experience connecting to international trains.

In principle,
the majority of construction could be done without possession of HS1 or the SEML.
However,
some possessions for constructing the overbridges would be inevitable,
making this an expensive proposition.
Lessons would need to be learned from HS2's innovative construction techniques
minimising the amount of possession needed to construct overbridges.

Assuming that the discussions suggesting that Channel Tunnel regulations have been relaxed,
such that 400m trains are no longer required,
it may be sufficient to build 200m international platforms;
however,
there is space for 400m platforms if required.

Similarly to Ashford,
paths should be available where domestic high speed services turn off onto the SEML.
However,
trains would need to occupy the main HS1 line,
so timings would need to be tighter than at Ashford
where the platforms could be occupied without blocking the running line.

Aside from the high construction cost,
and the need to re-time domestic high speed services to additionally call at Sandling
(to allow better connections for those from points west),
the main issue is the lack of an easy way to turn trains around.
In principle,
a train could reverse into the Dollands Moor Chord,
and then reverse back out onto the other line.
Both HS1 lines are signalled for bidirectional operation,
so from a signalling perspective this is not a problem,
but it would make pathing significantly more difficult,
due to
the increase in the amount of time the line is occupied during the reversing operation.
While waiting for the next service,
trains could perhaps be stabled in the Dollands Moor yard,
if space allowed.

Compared to the 18.6km required from Ashford International,
only 3.7km of HS1 track would be needed
from Sandling International to the Channel Tunnel boundary east of the M20.

### Westenhanger

![Diagram of a hypothetical Westenhanger station](/images/minimal-channel/westenhanger.png){: .displaypic}

The next station on the SEML to the west of Sandling is Westenhanger.
Compared to Sandling,
this offers some advantages:
firstly,
there are two crossovers on HS1 to the north and easy of the current SEML station.
This could allow trains to easily reverse here,
provided that deboarding and boarding both happened very quickly.
There is also a better road connection from the M20,
for those treating it as a park and ride station.

The considerations for pathing and station construction
are basically the same as at Sandling.
5.6km of HS1 route would be needed,
less than double that of using Sandling,
and less than a third of that required for Ashford.

### Calais

Again,
because Calais-Fréthun has served Channel Tunnel trains before,
this subsection will have some overlap with [#CrossChannelRail][cross-channel-rail].
If there is any discrepancy between what is stated here and what Jon reports,
Jon is almost certainly correct,
as he has done the leg work and I haven't.

![Diagram of the area including the Calais Eurotunnel terminal and Calais-Fréthun station](/images/minimal-channel/calais.png){: .displaypic}

Even before the pandemic,
the number of services to [Calais-Fréthun][calais-frethun] was small,
and the number calling at both Ashford International and Calais-Fréthun
was so small as to be useless.
The timetable for 2011
showed a single Ashford&ndash;Calais service on weekdays,
and a single Calais&ndash;Ashford service on a Sunday.

However,
I would assert
(without proof)
that a shuttle service to Calais-Fréthun is
much easier to start a disruptive service with
than continuing to [Lille-Europe][lille-europe]
as Eurostar was previously inclined to do.

Calais-Fréthun is barely outside the GetLink concession area,
and a derogation to use it for trains not fully certified for the TGV network
seems far more likely to be granted.
Calais&ndash;Lille takes longer than Sandling&ndash;Calais,
so double the number of trains would be required to maintain the same level of service.

And of course,
we have the same issue as in reverse on the British side:
those living in Calais shouldn't need to travel a hundred kilometres inland
to access the cross-Channel infrastructure that they live next door to
(and that has caused them significant disruption).

A 31-minute Ashford&ndash;Calais connection,
or a 25-minute Sandling&ndash;Calais one,
would allow an hourly service to be operated using only two trains.
(Five-minute turnarounds seem a little ambitious,
so trying to run an hourly service with one train,
or a half-hourly service with two,
is probably too prone to delays throwing the entire timetable out.)

Calais-Fréthun,
similarly to Ashford,
has platforms on station loops separate from the main tracks for trains not stopping.
This allows services to stop here with minimal disruption to
other high-speed paths for long-distance services.
Similarly to Ashford,
it stopped receiving international services during the pandemic,
so some work may be needed to update the border control,
but otherwise all necessary facilities are there.
It has good onward connections with French TGV services towards Lille and Paris Nord,
and some local services around northern France.
(More local services depart from Calais-Ville however,
and train connections between the two are surprisingly sparse.)

The only potential complication with Calais-Fréthun is
the potential lack of ability to turn trains around.
There are no crossovers in or adjacent to the station,
so services would need to arrive on platform 4,
then on departure,
reverse for 1.5km to the crossover near the junction for Calais-Ville,
before they could cross over to run in the correct direction back through the tunnel.
This would have some knock-on effect on pathing compared to
if the crossover could be made without entering the main running lines.

### Which route is best?

If the crossovers at Westenhanger and Calais-Fréthun could be made to work,
then a shuttle service from a new Westenhanger International station
to Calais-Fréthun,
taking around 26 minutes,
would be the minimal service.
Only two trains would be needed to deliver a one train per hour service level.
Based on current Eurostar services,
this may seem to be overkill,
but there may be significant amounts of suppressed latent demand
that such a shuttle service would unlock.

If these crossovers weren't acceptable to use,
then the next best alternative would be
a service from Ashford International to Lille-Europe,
with calls at a new Sandling International and Calais-Fréthun.
Total journey time would be around one hour and thirteen minutes,
with a rough timetable:

| Station | Arrive | Depart |
| - | - | - |
| Ashford International | &mdash; | 0:00 |
| Sandling International | 0:06 | 0:11 |
| Calais-Fréthun | 0:36 | 0:38 |
| Lille-Europe | 1:13 | &mdash; |

### Example journey times

Let's look at a couple of example journeys.
"Current" times are the best time available using Interrail's Rail Planner app;
"potential" times assume the timings above,
plus a 15-minute average connection time at each connecting station
(since I have no way of knowing how the timetables would line up),
and an extra hour for checking in for international services
(as is currently needed on Eurostar).

| Route | Current | Potential |
| - | - | - |
| Folkestone Central&ndash;Calais-Ville | **5:23** (change at St Pancras and Lille-Europe) | **2:12** (change at Sandling International and Calais-Fréthun) |
| Dover Priory&ndash;Dunkerque | **5:31** (change at St Pancras and Lille-Europe | **3:21** (change at Sandling International and Lille-Europe) |
| Hastings&ndash;Boulogne | **6:24** (change at Charing Cross, St Pancras, Lille-Europe, and Calais-Fréthun) | **3:20** (change at Ashford International and Calais-Fréthun) |

As anticipated,
on these journeys multiple hours are taken off the travel time,
in some cases reducing the journey time by more than half.
Of course,
better still would be to streamline or remove the need for passport checks,
bringing these geographically non-distant locales
far closer to each other sociologically.

Now,
does anyone have a couple of Channel Tunnel-compatible trains they could lend me?

_All map images shown are from [OpenRailwayMap][orm],
including data from [OpenStreetMap][osm] contributors._


[ashford]: https://en.wikipedia.org/wiki/Ashford_International_station
[calais-frethun]: https://en.wikipedia.org/wiki/Calais-Fréthun_station
[calais-ville]: https://en.wikipedia.org/wiki/Calais-Ville_station
[ebbsfleet]: https://en.wikipedia.org/wiki/Ebbsfleet_International_station
[cross-channel-rail]: https://crossborderrail.trainsforeurope.eu/projects/crosschannelrail/
[folkestone-west]: https://en.wikipedia.org/wiki/Folkestone_West_railway_station
[getlink]: https://www.getlinkgroup.com
[getlink-bike]: https://www.leshuttle.com/uk-en/travelling-with-us/travelling-with-different-vehicles/bicycles
[getlink-coaches]: https://www.leshuttle.com/getmedia/1b391282-8c0f-46fd-b6ab-d6f1784c20c9/LeShuttle-Coach-Calendar-2025-UK.pdf
[jon-worth]: https://jonworth.eu
[le-shuttle]: https://www.leshuttle.com
[lille-europe]: https://en.wikipedia.org/wiki/Lille-Europe_station
[orm]: https://openrailwaymap.org
[osm]: https://openstreetmap.org
[sandling]: https://en.m.wikipedia.org/wiki/Sandling_railway_station
[sncf-reseau]: https://www.sncf-reseau.com/
[sphs]: https://stpancras-highspeed.com
[stratford]: https://en.wikipedia.org/wiki/Stratford_International_station