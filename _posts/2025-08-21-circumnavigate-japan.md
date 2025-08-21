---
layout: post
title:  "Circumnavigating Japan by rail"
date:   2025-08-21 01:00
categories: [hypothetical rail journeys]
---

A few months ago,
I was looking wistfully at a railway map of Kyushu,
when I realised just how many railway lines there were near to the coast.
This got me wondering:
what would it take to circumnavigate Japan by rail?
That is to say,
do a loop around Japan,
taking all of the rail lines closest to the sea.

## Rules

Of course,
that's a little vague;
it'd be good to better formalise exactly what that means.
The aim would be to ride over every metre of track that is
"the closest" to the coast.
That is,
form a closed loop of ridden track,
where at each point,
there is no other track in between you and the sea along the shortest line.
(The actual journey itself can't exactly be this loop,
since there are points where different railway lines cross,
so the two sections of line will need to be ridden in separate trips.)
This may not be a sufficiently stringent requirement&mdash;a
stronger one would be to require
the closest railway line to each point on the coast to be covered;
an even stronger one that it not be possible
to reach the inside of the loop from the sea without crossing the track loop.
I'll aim for the first and largely the second;
the third may be impossible in some circumstances
at least while maintaining the "coastal loop" idea,
so I'll bear it in mind but not stick to it strictly.
Either way,
this is designed to be an interesting diversion,
not a professional sport or exercise in applied mathematics,
so I won't be providing a mathematical proof that
my proposed route meets any of these criteria.

To avoid a lot of extra journeys one stop out of a station,
let's additionally say that walking the length of a station platform
counts as riding that length of track.
Multiple tracks on the same alignment also count as one,
to avoid worrying about needing to reverse a leg to get closer to the sea.

Regarding the Shinkansen,
the stop spacing is so different that
if Shinkansen tracks were included on the same footing as other tracks,
then there would be horrific amount of doubling back needed to pick up sections
where it crosses local railways to be closes to the sea.
Instead,
we will only take the Shinkansen if:

1. It is the closest to the sea for an entire station&ndash;station trip, and
2. It is _significantly_ more convenient.
   (I.e. not just a slightly faster journey on a similar alignment,
   but cutting noticeable corner.)

We only meet these criteria twice in the journey,
so I'll comment more when we get there.

The simplified version of the rules allows for one additional exception:
any track that would require you to reverse along the same stretch is exempt.
This omits a lot of spur lines,
where you would go A&ndash;B&ndash;A,
just to say you'd covered the stretch of track.
This seems out of line with the idea of a circumnavigation,
so I'll use this exception for now;
I'll highlight at some points where this might make a significant difference.
(On the other hand,
where a smaller loop can be made that is more coastal than not riding it,
this is still in scope;
only straight line out-and-back journeys are exempt.)

## Outline

Japan has four islands that have a meaningful amount of railway[^1].
Hokkaido, Shikoku, and Kyushu
each have a single rail connection to Honshu,
so we can decompose the task of circumnavigating Japan
into the four subsidiary tasks of circumnavigating each island
(plus making the connections between them).

Some statistics:

| Island | Number of legs | Number of days | Total distance | Maximum cost |
| = | = | = | = | = |
| Honshu | 110 | 15 | 4514.1km | ¥115,807 |
| Shikoku | 19 | 3–4 | 667.6km | ¥20,440 |
| Kyushu | 27 | 4 | 1218.8km | ¥35,260 |
| Hokkaido | 14 | 4–5 | 1453.9km | ¥38,080 |
| = | = | = | = | = |
| **All Japan** | **176** | **~28** | **8073.6km** | **¥216,357** |

I say "maximum cost" here because I've computed the cost of each leg separately
(and in some cases parts of a leg separately,
due to the way I assembled the route initially).
The actual cost will likely be lower,
since multiple legs can share a ticket
(and will likely want to,
since there are some tight connections).
I'll discuss how rail passes impact on this at the end.
Most routes use local trains,
either because we need the shorter stop density,
or because the express routes are further inland,
and I'll aim to use them more generally to keep the budget down,
but there are a few points where limited express services are either compulsory,
or make the scheduling significantly easier.

## The route

Since spending a full month[^2] on trains is beyond most people,
I'll describe each island's circumnavigation separately,
calling out the points where they connect
(and starting each one apart from Honshu at the point where you'd arrive from Honshu).

I'll aim to start each day at 9am
(or slightly before if it significantly improves the schedule),
have at least an hour's break for lunch,
and finish by 7pm
(but allowing later if schedules are awkward and there was a late start or long lunch).

### Honshu

#### Day 1 <!-- Honshu -->

![Map of the area described in the text with the route described marked.](/images/circumnavigate-japan/honshu-1.png)

We start our journey at Haneda Airport Terminal 1/2,
potentially having just arrived by plane.
We take the 09:09 Keikyu departure to Keikyu Kamata,
subsequently changing at Keikyu Kawasaki,
and then Hatchou-Nawate,
where we switch to JR to go to Hama-Kawasaki and Tsurumi,
Keikyu from Keikyu Tsurumi to Yokohama,
and back to JR Shin-Sugita.
We ride the Yokohama Seaside Line to Kanazawa-Hakkei,
and from there we're back on Keisei,
heading to Horinouchi and Keikyu Kurihama.
JR then takes us from Kurihama to Zushi and then Kamakura.
From Kamakura we ride the Enoden
(made famous by the [Rascal Does Not Dream series][aobuta])
to Enoshima,
where we arrive at 13:29 and stop for a slightly late lunch.

Where possible I've tried to line up lunches with interesting spots,
although that's easier in large cities where the timetables are denser.
This morning is something of a baptism of fire&mdash;we're
already up to 12 individual trains!
The Greater Tokyo Area
has a very dense rail network with many lines that cross over each other,
and few that hug close to the coast,
so we have very many short legs.

Things calm down as we head out of the city.
From Enoshima,
we take the 14:56 Enoden service to Fujisawa,
then make an out-of-station interchange to the JR station,
from where we head to Atami,
and then to Hamamatsu,
where we arrive at 18:55 and finish our first day.
(Hamamatsu station is a little inland,
so if you wanted you could continue onwards to Maisaka or Bentenjima,
sleep with the sound of the waves,
and get a headstart on day 2.)

#### Day 2

![Map of the area described in the text with the route described marked.](/images/circumnavigate-japan/honshu-2.png)

From Hamamatsu,
we continue our journey along the JR Tokaido line with the 09:10 departure to Toyohashi,
and then from there to Gamagori.
We're now entering the Chubu region,
so start to pick up Meitetsu services,
starting with a train to Kira Yoshida,
then Kita Anjo.
After a short walk to JR's Anjo station[^3],
we catch a train to Obu,
then to Taketoyo.
From there it's a short walk to either Chita Taketoyo or Age,
to catch a Meitetsu service to Kanayama[^4].
From Kanayama we take the less common JR service
(rather than the more frequent Meitetsu one,
which runs along a separate alignment a few dozen metres further inland)
to Nagoya station,
where we stop for a late lunch at 13:36.

Hopefully we have a little time to marvel at the Chuo Shinkansen construction site,
but we only have an hour,
as we need to catch the 14:36 JR service to Hatta.
You can tell we're getting further west,
as we now switch over to Kintetsu,
heading first to Kintetsu-Kanie,
and then to Tsu.
The Kintetsu and JR lines do a little dance with each other here;
in the more difficult ruleset we would need to double back here
to take both lines along this section.
From Tsu,
we take a JR service to Matsusaka,
switch back to Kintetsu to Iseshi,
and then back to JR to Toba,
and back to Kintetsu again back into Iseshi,
making a little loop and finishing day 2 at 18:21.

Iseshi is slightly inland;
if you want a really coastal night's sleep,
then you might prefer to stop early in Toba,
and have an earlier start the next day back into Iseshi.

#### Day 3 <!-- Honshu -->

![Map of the area described in the text with the route described marked.](/images/circumnavigate-japan/honshu-3.png)

Day 3 is comparatively simple,
and entirely on JR.
We have a slightly early start to catch the 08:48 service from Iseshi to Taki,
then a limited express from Taki to Shingu,
arriving at 11:34 for a long lunch.
(If you don't mind not having a lunch break and eating on the train,
then you could alternatively take the local train,
arriving at Shingu at 13:20.)
At 13:29 we take the limited express Kuroshio to Wakayama,
and then the local train to Wakayamashi,
finishing the day at 17:17.
A relatively early finish,
but it avoids trying to fight the commuter rush to get into Osaka in the early evening,
and perhaps you might want to explore some of the spur lines to Wakayamako or Kada.

#### Day 4 <!-- Honshu -->

![Map of the area described in the text with the route described marked.](/images/circumnavigate-japan/honshu-4.png)

Osaka is almost as chaotic as Tokyo,
so it's another busy morning.
We start with the 09:00 Nankai service to Sakai,
and then to Kishinosato-tamade.
From there,
we ride the Osaka Metro to Suminoekouen, Cosmosquare, Bentencho, and Nishikujo,
with a few relatively tight transfers.
Then,
continuing to head west,
we take the Hanshin service to Amagasaki,
and then Kobe-Sannomiya.
From Sannomiya there is an automated guideway transit service,
the Port Liner,
that runs in a loop around Port Island
(with an additional newer,
and now more trafficked,
spur to Kobe Airport).
We use this to take a tour around Port Island,
checking out such sites as Keisan Kagaku Centre
(formerly K Computer Mae),
home of Japan's national supercomputer,
one of the fastest in the world,
arriving back into Sannomiya at 12:46 in time for lunch
(although there may not be enough time for wagyu today).

After taking the Kobe City Subway to Shinnagata at 13:50,
we take a JR service to Akashi,
then a Sanyo train to Sanyo-Himeji.
After a short walk back to JR's Himeji station,
where we catch the service to Banshu-Ako,
and then to Okayama,
where we end day 4 at 18:03.

If Okayama is too far inland for you,
you might want to head out to Uno,
although it would require an early start to day 5.
Alternatively,
if you're doing Shikoku as well as Honshu,
you'd want to head down to Kojima or across to Utazu,
ready to start Shikoku Day 1.

#### Day 5

![Map of the area described in the text with the route described marked.](/images/circumnavigate-japan/honshu-5.png)

Day 5
(or later,
if we've just returned from Shikoku)
departs from Okayama at 09:03,
on the JR service to Itozaki.
From there,
we continue to Hiro and Mihara,
before arriving in Hiroshima for a late lunch at 13:53.
We then spend the afternoon playing around on Hiroshima's tram network,
departing Hiroshima station at 15:11,
calling at Minami-machi 6-chome,
Tokaichimachi,
Dobashi,
and Hiroden Miyajima-guchi,
before taking the JR service from Miyajimaguchi towards Iwakuni.
From there,
we continue to Tokuyama,
arriving at 19:01 to end day 5.

Tokuyama Station and nearby hotels overlook Tokuyama Port on the Seto Inland Sea,
so you should enjoy some fantastic views.

#### Day 6

![Map of the area described in the text with the route described marked.](/images/circumnavigate-japan/honshu-6.png)

So far I've assumed we've been travelling on weekdays.
If we started on a Monday, then day 6 will be on a Saturday,
so timetables are a little more restrictive
(although not as much as in some countries),
and as a traveller you're likely to want a break.
So I've aimed for less travel,
perhaps that could even be spread out across the weekend,
before continuing with day 7 on Monday.

That said,
one itinerary would be to depart Tokuyama
on the JR service for Shin-Yamaguchi at 08:52,
and then connect onto the service for Ubeshinkawa,
arriving at 11:09 for a long lunch.
Then at 13:06,
we continue with JR onwards towards Onoda,
and from there to Shimonoseki,
arriving at 14:19 and rounding off the day.

If we were continuing to Kyushu,
this is where we would branch off,
taking the local train from Shimonoseki to Kokura
(one of the few legs of this journey that I've previously taken myself!),
and starting Kyushu Day 1 on the next weekday.

Like Tokuyama,
Shimonoseki station is very close to Shimonoseki Port,
on the Kanmon Strait.
Since Shimonoseki is on a peninsula,
and the station on a narrow section of it,
it's also very close to the smaller harbour to the west,
opening out onto the Sea of Japan.

#### Day 7

![Map of the area described in the text with the route described marked.](/images/circumnavigate-japan/honshu-7.png)

Day 7 has another early start,
at 08:40 with a JR service to Kogushi.
From there we pick up a rail replacement bus service&mdash;due
to severe weather in 2023,
much of the extremely coastal track from Kogushi to Nagatoshi
is currently impassible.
It's hard to get a feel for if or when this will reopen,
but it seems less of a lost cause than
the lines in eastern Tohoku that I'll discuss later.
I was in two minds as to whether to keep this leg,
but the alternative route to Kogushi involves doubling back halfway to Yamaguchi,
meaning you'd only go through Shimonoseki if you were continuing to Kyushu,
which skips a lot of coast.

So we take the rail replacement bus at 09:51,
crossing our fingers that rail service will one day be restored,
and arrive in Nagatoshi at 11:39,
where we stop for an early lunch.
This is one of the parts of Japan where the timetable is quite restrictive,
so to keep a reasonable rate of progress we need to be flexible with our timings.
After lunch,
we take the JR service departing at 12:38 to Masuda,
and change there for the limited express _Super Oki_ to Tottori,
ending day 7 at 18:19.

Tottori is a couple of miles inland;
one might prefer to continue onwards to Higashihama.
(The late start on Day 8 means you might wonder about alighting early on day 7,
but the _Super Oki_ tends to stop a little inland,
going non-stop through the local coastal stations in between,
so you'd need an extra local train leg to stop in,
for example,
Yabase or Tomari.)

#### Day 8

![Map of the area described in the text with the route described marked.](/images/circumnavigate-japan/honshu-8.png)

Day 8 is a relatively quiet one.
We have a slightly later start,
taking the 09:45 JR service to Hamasaka.
Then we have an hour and a half to ourselves in Hamasaka,
before catching the 12:05 to Toyooka,
where we stop for lunch at 13:17.
After lunch,
we catch the Kyoto Tango Railway service to Nishi-Maizuru,
and then cross town on the JR service to Higashi-Maizuru,
arriving at 17:38 to end day 8.

Higashi-Maizuru station is only half a mile from the sea,
but for a truly coastal finish to the day,
you might get a headstart on day 9 and continue on to Wakasa-Wada station,
which is only around 50 metres away from the harbour
(although there are no hotels quite that close).

#### Day 9

![Map of the area described in the text with the route described marked.](/images/circumnavigate-japan/honshu-9.png)

We start day 9 with the 08:44 JR departure to Tsuruga.
(On the way we pass through the most presidential Japanese city,
[Obama][obama].)
From there,
we enter the region covered by the [Hokuriku Shinkansen][hokuriku].

As sections of the Hokuriku Shinkansen have opened,
the JR companies responsible for the original lines along the parallel route
have not been able to financially justify retaining services,
as most passengers will now use the new Shinkansen lines instead.
Rather than close them completely,
in order to retain local services,
the lines are divested to "third sector" companies.
We get to ride a few of these next.

From Tsuruga,
we ride the Hapi-Line Fukui to Takefu,
and then the Fukui Railway to Tawaramachi,
arriving at 13:25 for a late lunch.
We don't quite get a full lunch hour here,
as we need to catch the Echizen Railway service to Fukui station at 14:21.
From there,
we are once again on a Hapi-Line Fukui service,
which turns into an Ishikawa Tetsudo service to Kanazawa.
We have a 5-minute connection there to another Ishikawa Tetsudo service,
which turns into an Ainokaze Toyama Tetsudo service to Uozu,
arriving at 18:07 to finish day 9.

For whatever reason,
the operational routes of particular train services
don't seem to align particularly well
with the service boundaries of the various third sector companies.

#### Day 10

![Map of the area described in the text with the route described marked.](/images/circumnavigate-japan/honshu-10.png)

We start day 10 with a little shuffle as
the Toyama Chiho Railway and the Ainokaze Toyama Tetsudo
cross each other.
We take the 09:48 Toyama Chiho Railway departure to Dentetsu-Kurobe station,
and then have a short walk from there to Kurobe station,
to pick up the Ainokaze service to Tomari.
From there,
we stay with Ainokaze initially for a service that changes into
a Tokitetsu service to Naoetsu.
This stretch looks to be pretty spectacular on the map,
hugging very close to the sea to avoid
the mountains rising up immediately to the southeast,
with a special shoutout to Ichiburi,
which looks close enough to the sea that
you could fish from the platform when the tide is in
(but please don't,
because it's an island platform,
so you'd need to cast the line over a live railway track
with overhead line equipment above it).
From Naoetsu we return to JR,
heading to Kashiwazaki where we arrive at 13:10 and stop for a long lunch.

From Kashiwazaki we stick with JR as we continue north to Yoshida on the 15:27 service,
and from there continue to Niigata where we finish day 10 at 18:35.

#### Day 11

![Map of the area described in the text with the route described marked.](/images/circumnavigate-japan/honshu-11.png)

We have an early start in Niigata,
taking the JR _Inaho_ limited express departing at 08:23.
(The alternative would be waiting until lunch time,
so the early start is worthwhile.)
We arrive into Akita at 11:57,
where we can enjoy a leisurely lunch.
At 14:00,
we board the _Resort Shirakami_ tourist train,
which boasts some absolutely beautiful rolling stock
and passes through a world heritage mountain range.
We alight at Shin-Aomori at 19:27,
where we end the day having ridden only two trains,
the lowest number we'll ride during the whole trip[^5].
From Shin-Aomori we can
take the Hokkaido Shinkansen through the Seikan Tunnel
to circumnavigate Hokkaido next,
or we can continue straight on to day 12.

#### Day 12

![Map of the area described in the text with the route described marked.](/images/circumnavigate-japan/honshu-12.png)

The scheduling of legs gives us a relatively late start in Aomori,
where we depart Shin-Aomori on the 10:46 Aoimori Railway service to Hachinohe,
arriving at 12:17.
(The Tohoku Shinkansen here gives us another couple of third sector railways.)
After a leisurely lunch in Hachinohe,
we take the 14:25 JR service to Kuji,
where we change to the Sanriku Railway for a service to Miyako,
and then a second to Kamaishi,
where we arrive at 19:18 and close out day 12.

Kamaishi Station sits on the Kasshi river,
about a mile from where it enters the Pacific Ocean,
but is itself only about half a mile from the ocean;
the river is lengthened by the long pier of the port of Kamaishi.

#### Day 13

![Map of the area described in the text with the route described marked.](/images/circumnavigate-japan/honshu-13.png)

Day 13 is unlucky for some,
and unlucky indeed for the railway in this part of Japan,
which was devastated by the 2011 Tohoku earthquake and tsunami[^6].
From Kamaishi you can still head south as far as Sakari,
but the lines from there to Kesennuma,
and from there onwards to Yanaizu,
have been permanently replaced with Bus Rapid Transit.

Since from a rail perspective that now makes the line to Sakari a spur,
we instead head inland on the JR service to Shin-Hanamaki departing at 09:02.
From Shin-Hanamaki to Ichinoseki,
the Tohoku Shinkansen is the closest non-spur line to the sea,
so we make use of it to speed through a section of the journey
where we're many miles away from the sea,
arriving into Ichinoseki at 11:47 for a quick lunch.

We depart Ichinoseki for Kogota at 12:44,
and then head to Ishinomaki,
where we're once again near the coast.
Another local JR service takes us to Sendai along the coastal route,
arriving at 15:48 where we call an early end to the day.

If you're willing to consider BRT as an ersatz railway,
an alternative itinerary for day 13 would be to take
the 09:35 Sanriku Railway service to Sakari,
and change for the BRT to Kesennuma,
arriving at 11:57 and having lunch.
From there,
the 13:05 BRT departure will take you to Yanaizu,
from where you can get JR services to Maeyachi,
Ishinomaki,
and Sendai to reconnect with the main schedule,
arriving at 18:50.
This option would give more financial support to
local businesses in the area most heavily affected by the tsunami.
It may also convince JR to better support the BRT due to the higher ridership;
there seems to be little chance of the rails being reinstated,
regardless of traffic levels.

#### Day 14

![Map of the area described in the text with the route described marked.](/images/circumnavigate-japan/honshu-14.png)

We're into the final stretch on the approach to Tokyo now.
We start off at 10:36 taking the JR service to Haranomachi,
changing there for Iwaki,
where we arrive at 13:17 for lunch.
From there,
we take the 14:18 departure to Mito,
transferring to the Kashima Rinkai Railway to get to Kashimajingu,
where there is almost an hour of downtime waiting for the JR service to Katori,
and from there to Matsugishi,
where we arrive at 18:58 to round out day 14.

If you prefer a longer break en route,
you could also take the _Hitachi-Tokiwa_ limited express from Sendai at 08:48,
getting you into Iwaki  at 11:08 or Mito at 12:26.
One option would be to explore Oarai,
the city featured in shipboard form in _[Girls und Panzer][garupan].

Matsugishi is a quarter of a mile from the Tone estuary;
to get even more coastal,
you might spend the evening exploring the Choshi Electric Railway to Cape Inubo.

#### Day 15

![Map of the area described in the text with the route described marked.](/images/circumnavigate-japan/honshu-15.png)

The final day will take us back through Tokyo,
but first we need to explore Chiba.
Staying in JR territory for a while,
we start off with the 09:15 departure from Matsugishi to Naruto.
After that we change at Oami,
Kazusa-Ichinomiya,
and Awa-Kamogawa,
before stopping in Tateyama at 12:41 for lunch.
We depart again at 13:44 towards Kimitsu,
where we change for Soga,
and then Shin-Kiba.
There we change for the Rinkai line to Tennozu Isle,
and finally from there we take the Tokyo Monorail to Haneda Airport Terminal 2,
arriving at 17:16,
potentially in time for a flight back out the following morning.

#### Summary <!-- Honshu -->

Out-of-station interchanges and changes of operator are marked in **bold**;
they may require a longer connection time.

| Day | Depart | | | Arrive | Operator |
| = | = | = | = | = | = |
| 1 | Haneda Airport Terminals 1/2 | 09:09 | 09:19 | Keikyu Kamata | Keikyu |
| 1 | Keikyu Kamata | 09:24 | 09:29 | Keikyu Kawasaki | Keikyu |
| 1 | Keikyu Kawasaki | 09:32 | 09:34 | Hatchou-nawate | Keikyu |
| 1 | Hatchou-nawate | 09:39 | 09:46 | Hama-Kawasaki | **JR East** |
| 1 | Hama-Kawasaki | 10:11 | 10:24 | Tsurumi | JR East |
| 1 | **Keikyu Tsurumi** | 10:37 | 10:45 | Yokohama | **Keikyu** |
| 1 | Yokohama | 10:55 | 11:13 | Shin-Sugita | **JR East** |
| 1 | Shin-Sugita | 11:17 | 11:45 | Kanazawa-Hakkei | **Yokohama Seaside Line** |
| 1 | Kanazawa-Hakkei | 11:51 | 12:09 | Keikyu Kurihama | **Keikyu** |
| 1 | **Kurihama** | 12:24 | 12:44 | Zushi | **JR East** |
| 1 | Zushi | 12:52 | 12:56 | Kamakura | JR East |

| 1 | Kamakura | 13:04 | 13:29 | Enoshima | **Enoden** |
| - | - | - | - | - | - |
| 1 | Enoshima | 14:56 | 15:05 | Fujisawa | Enoden |
| 1 | Fujisawa | 15:12 | 16:07 | Atami | **JR East** |
| 1 | Atami | 16:17 | 18:55 | Hamamatsu | **JR Central** |
| = | = | = | = | = | = |
| 2 | Hamamatsu | 09:10 | 09:43 | Toyohashi | JR Central |
| 2 | Toyohashi | 09:50 | 10:01 | Gamagori | JR Central |
| 2 | Gamagori | 10:11 | 10:39 | Kira Yoshida | **Meitetsu** |
| 2 | Kira Yoshida | 10:45 | 11:29 | Kita Anjou | Meitetsu |
| 2 | **Anjo** | 11:31 | 11:45 | Obu | **JR Central** |
| 2 | Obu | 11:51 | 12:23 | Taketoyo | JR Central |
| 2 | Age | 12:46 | 13:24 | Kanayama | **Meitetsu** |
| 2 | Kanayama | 13:32 | 13:36 | Nagoya | **JR Central** |
| - | - | - | - | - | - |
| 2 | Nagoya | 14:36 | 14:47 | Hatta | JR Central |
| 2 | **Kintetsu-Hatta** | 14:59 | 15:06 | Kintetsu-Kanie | **Kintetsu** |
| 2 | Kintetsu-Kanie | 15:10 | 16:04 | Tsu | Kintetsu |
| 2 | Tsu | 16:32 | 16:50 | Matsusaka | **JR Central** |
| 2 | Matsusaka | 17:09 | 17:23 | Iseshi | **Kintetsu** |
| 2 | Iseshi | 17:34 | 17:55 | Toba | **JR Central** |
| 3 | Toba | 18:05 | 18:21 | Iseshi | **Kintetsu** |
| = | = | = | = | = | = |
| 3 | Iseshi | 08:48 | 09:10 | Taki | **JR Central** |
| 3 | Taki | 09:24 | 11:34 | Shingu | JR Central |
| - | - | - | - | - | - |
| 3 | Shingu | 13:29 | 16:48 | Wakayama | **JR West** |
| 3 | Wakayama | 17:11 | 17:17 | Wakayamashi | JR West |
| = | = | = | = | = | = |
| 4 | Wakayamashi | 09:00 | 09:48 | Sakai | **Nankai Electric Railway** |
| 4 | Sakai | 09:53 | 10:17 | Kishinosato-tamade | Nankai Electric Railway |
| 4 | **Kishinosato** | 10:36 | 10:44 | Suminoekouen | **Osaka Metro** |
| 4 | Suminoekouen | 10:48 | 11:07 | Cosmosquare | Osaka Metro |
| 4 | Cosmosquare | 11:10 | 11:18 | Bentencho | Osaka Metro |
| 4 | Bentencho | 11:20 | 11:22 | Nishikujo | Osaka Metro |
| 4 | Nishikujo | 11:26 | 11:33 | Amagasaki | **Hanshin** |
| 4 | Amagasaki | 11:38 | 11:58 | Kobe-Sannomiya | Hanshin |
| 4 | **Sannomiya** | 12:05 | 12:46 | Sannomiya | **Kobe New Transit** |
| - | - | - | - | - | - |
| 4 | **Sannomiya-Hanadokeimae** | 13:50 | 14:04 | Shinnagata | **Kobe City Subway** |
| 4 | **Shin-nagata** | 14:20 | 14:39 | Akashi | **JR West** |
| 4 | Sanyo-Akashi | 14:48 | 15:22 | Sanyo-Himeji | **Sanyo** |
| 4 | **Himeji** | 15:34 | 16:05 | Banshu-Ako | **JR West** |
| 4 | Banshu-Ako | 16:36 | 18:03 | Okayama | JR West |
| = | = | = | = | = | = |
| 5 | Okayama | 09:03 | 10:45 | Itozaki | JR West |
| 5 | Itozaki | 11:20 | 11:24 | Hiro | JR West |
| 5 | Hiro | 11:37 | 13:03 | Mihara | JR West |
| 5 | Mihara | 13:04 | 13:53 | Hiroshima | JR West |
| - | - | - | - | - | - |
| 5 | Hiroshima | 15:11 | 15:28 | Minami-machi 6-chome | **Hiroshima Electric Railway** |
| 5 | Minami-machi 6-chome | 15:39 | 16:05 | Tokaichimachi | Hiroshima Electric Railway |
| 5 | Tokaichimachi | 16:07 | 16:09 | Dobashi | Hiroshima Electric Railway |
| 5 | Dobashi | 16:15 | 17:09 | Hiroden Miyajima-guchi | Hiroshima Electric Railway |
| 5 | **Miyajimaguchi** | 17:13 | 17:34 | Iwakuni | **JR West** |
| 5 | Iwakuni | 17:43 | 19:01 | Tokuyama | JR West |
| = | = | = | = | = | = |
| 6 | Tokuyama | 08:52 | 09:36 | Shin-yamaguchi | JR West |
| 6 | Shin-yamaguchi | 10:19 | 11:09 | Ubeshinkawa | JR West |
| - | - | - | - | - | - |
| 6 | Ubeshinkawa | 13:06 | 13:36 | Onoda | JR West |
| 6 | Onoda | 13:38 | 14:19 | Shimonoseki | JR West |
| = | = | = | = | = | = |
| 7 | **Shimonoseki** | 08:40 | 09:31 | Kogushi | **JR West** |
| 7 | Kogushi | 09:51 | 11:39 | Nagatoshi | JR West |
| - | - | - | - | - | - |
| 7 | Nagatoshi | 12:38 | 14:31 | Masuda | JR West |
| 7 | Masuda | 14:34 | 18:19 | Tottori | JR West |
| = | = | = | = | = | = |
| 8 | Tottori | 09:45 | 10:28 | Hamasaka | JR West |
| 8 | Hamasaka | 12:05 | 13:17 | Toyooka | JR West |
| - | - | - | - | - | - |
| 8 | Toyooka | 14:51 | 17:01 | Nishi-Maizuru | **Kyoto Tango Railway** |
| 8 | Nishi-Maizuru | 17:32 | 17:38 | Higashi-Maizuru | **JR West** |
| = | = | = | = | = | = |
| 9 | Higashi-Maizuru | 08:44 | 10:37 | Tsuruga | JR West |
| 9 | Tsuruga | 11:20 | 11:51 | Takefu | **Hapi-Line Fukui** |
| 9 | **Takefu-shin** | 12:15 | 13:25 | Tawaramachi | **Fukui Railway** |
| - | - | - | - | - | - |
| 9 | Tawaramachi | 14:21 | 14:31 | Fukui | **Echizen Railway** |
| 9 | Fukui | 15:15 | 16:37 | Daishoji | **Hapi-Line Fukui/Ishikawa Tetsudo** |
| 9 | Kanazawa | 16:42 | 18:07 | Uozu | Ishikawa Tetsudo/Ainokaze Toyama Tetsudo |
| = | = | = | = | = | = |
| 10 | **Shin-Uozu** | 09:48 | 09:57 | Dentetsu-Kurobe | **Toyama Chiho Railway** |
| 10 | **Kurobe** | 10:09 | 10:29 | Tomari | **Ainokaze Toyama Tetsudo** |
| 10 | Tomari | 10:51 | 12:04 | Ichiburi | Ainokaze Toyama Tetsudo/Tokitetsu |
| 10 | Naoetsu | 12:26 | 13:10 | Kashiwazaki | **JR East** |
| - | - | - | - | - | - |
| 10 | Kashiwazaki | 15:27 | 17:33 | Yoshida | JR East |
| 10 | Yoshida | 17:39 | 18:35 | Niigata | JR East |
| = | = | = | = | = | = |
| 11 | Niigata | 08:23 | 11:57 | Akita | JR East |
| - | - | - | - | - | - |
| 11 | Akita | 14:00 | 19:27 | Shin-Aomori | JR East |
| = | = | = | = | = | = |
| 12 | Shin-Aomori | 10:31 | 10:37 | Aomori | JR East |
| 12 | Aomori | 10:46 | 12:17 | Hachinohe | **Aoimori Railway** |
| - | - | - | - | - | - |
| 12 | Hachinohe | 14:25 | 16:09 | Kuji | **JR East** |
| 12 | Kuji | 16:14 | 17:45 | Miyako | **Sanriku Railway** |
| 12 | Miyako | 17:51 | 19:18 | Kamaishi | Sanriku Railway |
| = | = | = | = | = | = |
| 13 | Kamaishi | 09:02 | 11:11 | Shin-Hanamaki | **JR East** |
| 13 | Shin-Hanamaki | 11:20 | 11:47 | Ichinoseki | JR East |
| - | - | - | - | - | - |
| 13 | Ichinoseki | 12:44 | 13:31 | Kogota | JR East |
| 13 | Kogota | 13:36 | 14:14 | Ishinomaki | JR East |
| 13 | Ishinomaki | 14:24 | 15:48 | Sendai | JR East |
| = | = | = | = | = | = |
| 14 | Sendai | 10:36 | 11:56 | Haranomachi | JR East |
| 14 | Haranomachi | 11:59 | 13:17 | Iwaki | JR East |
| - | - | - | - | - | - |
| 14 | Iwaki | 14:18 | 15:26 | Mito | JR East |
| 14 | Mito | 15:34 | 16:53 | Kashimajingu | **Kashima Rinkai Railway** |
| 14 | Kashimajingu | 17:50 | 18:03 | Katori | **JR East** |
| 14 | Katori | 18:20 | 18:58 | Matsugishi | JR East |
| = | = | = | = | = | = |
| 15 | Matsugishi | 09:15 | 10:06 | Naruto | JR East |
| 15 | Naruto | 10:21 | 10:43 | Oami | JR East |
| 15 | Oami | 10:47 | 11:02 | Kazusa-Ichinomiya | JR East |
| 15 | Kazusa-Ichinomiya | 11:05 | 11:59 | Awa-Kamogawa | JR East |
| 15 | Awa-Kamogawa | 12:02 | 12:41 | Tateyama | JR East |
| - | - | - | - | - | - |
| 15 | Tateyama | 13:44 | 14:46 | Kimitsu | JR East |
| 15 | Kimitsu | 14:50 | 15:29 | Soga | JR East |
| 15 | Soga | 15:35 | 16:14 | Shin-Kiba | JR East |
| 15 | Shin-Kiba | 16:23 | 16:34 | Tennozu Isle | **Rinkai** |
| 15 | Tennozu Isle | 16:50 | 17:16 | Haneda Airport Terminal 2 | **Tokyo Monorail** |

### Shikoku

Shikoku is the only of Japan's four main islands to not have any Shinkansen,
and while it is more blessed with rails than many countries,
its network is significantly sparser than the other three islands we're covering.

#### Day 1 <!-- Shikoku -->

![Map of the area described in the text with the route described marked.](/images/circumnavigate-japan/shikoku-1.png)

We start our circumnavigation of Shikoku in Utazu,
the closest station to Shikoku's only rail connection to Honshu.
(Of course,
if I had anything to do with it,
there'd be a [direct maglev connection to Osaka][maglev],
but that'd be a long way in the future.)

We depart Utazu at 09:13 on the JR service to Matsuyama,
where we take a couple of short trains around the city:
we walk from JR's Matsuyama Station
to Iyotetsu's confusingly named JR Matsuyama station,
where we head to Komachi,
from there to Matsuyama City,
and then to Gunchuko,
where we arrive at 12:09 and stop for a leisurely lunch.

Rather than heading back to Iyotetsu's Gunchuko station,
we instead cross the road to JR's Iyoshi station,
departing at 13:39 to Uwajima,
then to Ewasaki,
and from there towards Kubokawa,
on a service that starts off as a JR train and ends up a Tosa Kuroshio Railway service,
ending the first day at 19:44.

Kubokawa is quite a way inland;
unfortunately this entire stretch is,
and you don't arrive into Kubokawa early enough to be able to
catch a train down the spur line to Tosa-shirahama or Sagakoen,
where the stations are a mere hundred metres from the sea.

#### Day 2&mdash;3

![Map of the area described in the text with the route described marked.](/images/circumnavigate-japan/shikoku-2-3.png)

We start day 2 with a JR train to Ino,
on the western outskirts of Kochi,
departing at 10:04.
Kochi is blessed with a substantial tram network;
if you don't believe trams should be part of this challenge,
then you're free to stay on this train all the way through Kochi;
however,
for our rules,
we will need to explore some of the tram network.
We change to another JR train to Asakura,
where we walk over to Asakurajinja-mae tram stop[^7],
and take the Tosaden Kotsu service to Harimabayashi in central Kochi,
where we stop for lunch.
At 13:27,
we then catch another tram to Gomenmachi,
where we transfer to the similarly-named Gomen Machi station.

Here we have a conundrum:
southeastern Shikoku has two very long,
very coastal spur railways that don't connect in the middle.
If we follow our rules strictly and ignore these,
then the largest closed loop takes us almost back up to the northern coast,
when we should be exploring the southern one.
This is sufficiently dissatisfying that instead,
I'd propose exploring this area more thoroughly,
starting with the Tosa Kuroshio Railway service to Nahari,
arriving at 15:46..
From there,
we need to make our way east to Kannoura,
for which we have a couple of options.
One option would be to take a pair of buses,
one down the west coast of the peninsula,
and one back up the east coast.
Total journey time would be around two hours,
so this could easily be done by the end of day 2.

I'm not a fan of buses,
however,
so I would instead propose walking this gap.
One option is to do the direct 31-mile route,
cutting across country.
This is quite hilly,
however,
so one may prefer to follow the coastal path to Cape Muroto,
similarly to the bus journey.
This would be flatter,
and have nicer sea views,
but would be a full ten miles longer.
Either way,
this option is for those with decent walking stamina,
and needs appropriate weather.
But in the middle of multiple weeks of riding trains all day,
a day and a half of walking could be a welcome break.
In principle,
one could walk to Cape Muroto immediately after arriving at Nahari on day 2,
sleep there,
and then walk up to Kannoura the following day,
ready to start from there on day 4.

Either way,
if you're travelling with more than the most minimal luggage,
even if you haven't had trouble with it on most railway connections,
I'd recommend using a forwarding service to send it from Kubokawa directly to Kannoura,
rather than trying to carry it on the bus/hike.

#### Day 4 <!-- Shikoku -->

(_Or day 3 if you took the bus option._)

![Map of the area described in the text with the route described marked.](/images/circumnavigate-japan/shikoku-4.png)

Kannoura is served by the ASA Seaside Railway,
another third-sector railway company.
It has an awkward schedule,
meaning we have an early start to the day,
catching the 07:46 service to Awa-kainan.
(Perhaps you might want to spend a day or two resting in Kannoura
if you've just walked 40 miles;
it might make sense to line this up with a weekend.)

We reconnect with JR in Awa-kainan,
taking a service to Tokushima,
and from there to Ikenotani,
where we arrive at 11:19 for an early lunch.
We depart again at 12:43 for Shido,
where we transfer to Tosaden-Shido station
(taking the time to explore both stations,
to avoid leaving gaps in our tracks),
and head to Kawaramachi,
and then to Takamatsu-chikko.
Takamatsu-chikko is a short walk from JR's Takamatsu station;
again,
this technically leaves a small gap in our loop,
but I'm classing this as an out-of-station interchange,
since otherwise the route here would be a boring in-and-out of Takamatsu with JR,
and we'd miss exploring the dense Kotoden network at all.
From Takamatsu we can take a JR train back to Utazu,
arriving at 16:04,
completing our loop of Shikoku
and allowing time to get back to Okayama to resume the Honshu loop.

#### Summary <!-- Shikoku -->

Out-of-station interchanges and changes of operator are marked in **bold**;
they may require a longer connection time.

| Day | Depart | | | Arrive | Operator |
| = | = | = | = | = | = |
| 1 | Utazu | 09:13 | 11:15 | Matsuyama | JR Shikoku |
| 1 | **JR Matsuyama** | 11:20 | 11:25 | Komachi | **Iyotetsu** |
| 1 | Komachi | 11:30 | 11:34 | Matsuyama City | Iyotetsu |

| 1 | Matsuyama City | 11:45 | 12:09 | Gunchuko | Iyotetsu |
| - | - | - | - | - | - |
| 1 | **Iyoshi** | 13:39 | 15:03 | Uwajima | **JR Shikoku** |
| 1 | Uwajima | 15:27 | 16:36 | Ekawasaki | JR Shikoku |
| 1 | Ekawasaki | 18:41 | 19:44 | Kubokawa | JR Shikoku/Tosa Kuroshio Railway |
| = | = | = | = | = | = |
| 2 | Kubokawa | 10:04 | 10:54 | Ino | JR Shikoku |
| 2 | Ino | 11:02 | 11:10 | Asakura | JR Shikoku |
| 2 | **Asakurajinja-mae** | 11:36 | 12:06 | Harimabayashi | **Tosaden Kotsu** |
| - | - | - | - | - | - |
| 2 | Harimabayashi | 13:27 | 14:05 | Gomenmachi | Tosaden Kotsu |
| 2 | **Gomen Machi** | 14:45 | 15:46 | Nahari | **Tosa Kuroshio Railway** |
| 2/3 | Nahari | | | Kannoura | _Walk or bus_ |
| = | = | = | = | = | = |
| 4 | Kannoura | 07:46 | 08:06 | Awa-kainan | ASA Seaside Railway |
| 4 | Awa-kainan | 08:25 | 10:42 | Tokushima | **JR Shikoku** |
| 4 | Tokushima | 10:58 | 11:19 | Ikenotani | JR Shikoku |
| - | - | - | - | - | - |
| 4 | Ikenotani | 12:43 | 14:21 | Shido | JR Shikoku |
| 4 | **Kotoden-Shido** | 14:46 | 15:25 | Kawaramachi | **Kotoden** |
| 4 | Kawaramachi | 15:30 | 15:35 | Takamatsu-chikko | Kotoden |
| 4 | **Takamatsu** | 15:40 | 16:04 | Utazu | **JR Shikoku** |

### Kyushu

Kyushu is quite interesting,
having a very dense rail network on the west side,
and very little on the east.

#### Day 1 <!-- Kyushu -->

![Map of the area described in the text with the route described marked.](/images/circumnavigate-japan/kyushu-1.png)

We start off in the city of Kitakyushu.
If you're coming from Honshu then you'll arrive in Kokura.
If you're only doing a loop of Kyushu you might want to start off in Kanmonkaikyo,
where there is a coastal heritage railway;
while it is a spur,
starting there means you don't need to reverse on it,
so you get some more coastal track,
although not part of a continuous loop.
I haven't scheduled that in, however, so instead...

We depart Kokura at 09:01 on a JR service that will take us to Kashii.
Hopping over to the adjacent Nishitetsu Kashii station[^8],
we take a Nishitetsu service to Kaizuka,
then the Fukuoka City Subway to Nakasu-Kawabata and then Meinohama,
where we take JR services to Chikuzen-Maebaru and then Nishi-Karatsu,
arriving at 12:31 and stopping for lunch.

Departing again at 13:33,
we head to Yamamoto and then Imari,
where we transfer to Matsuura Railway
which will take us along the Nishi-Kyushu line to Sasebo,
arriving at 18:06.
This takes us through the most westerly station in Japan
(excluding the Okinawa monorail),
Tabirahiradoguchi;
one might like to alight there to have a look around.
There are trains every hour or so,
with the last train departing at 19:17,
so there is plenty of time to explore.

Sasebo station overlooks Sasebo port,
and has many nearby hotels with similar vantages.

#### Day 2 <!-- Kyushu -->

![Map of the area described in the text with the route described marked.](/images/circumnavigate-japan/kyushu-2.png)

Day 2 is an all-JR day,
(except for the trams).
We start at Sasebo station at 09:05,
departing for Haiki.
From there we head to Isahaya,
and then to Nagasaki,
arriving at 12:55 for lunch.

My suggestion then is to spend the afternoon exploring Nagasaki.
While there are earlier departures,
they introduce an extra change,
and needs long waits at the connecting station.
One thing to do in Nagasaki
(either to locate,
or after having lunch)
is to do a loop of the trams:
from Nagasaki Eki-mae,
take the Nagasaki Electric Tramway number 2 tram as far as City Hall,
and then take the number 3 tram back to the station.
This is unfortunately as close as we can get to
circumnavigating the Nishi-Sonoki Peninsula by rail.

From Nagasaki,
we need to make our way back up towards Fukuoka
before we can continue our journey south.
The new [Nishi Kyushu Shinkansen][nishi-kyushu]
is the closest line to the
(wonderfully named)
Tachibana Bay
for the entire stretch Nagasaki&ndash;Isahaya,
(aside froma short stretch on the approach to Isahaya
that we covered in the morning),
so we'll take advantage of that,
departing from Nagasaki at 17:13.
There we transfer to the local service to Hizen-Hama,
which skirts the edge of the Shimabara Bay in the Ariake sea,
and from there we continue to Tosu,
a major railway and highway junction town in norther Kyushu,
arriving at 19:47 to close out day 2.

#### Day 3 <!-- Kyushu -->

![Map of the area described in the text with the route described marked.](/images/circumnavigate-japan/kyushu-3.png)

We've spent two days and barely left northwest Kyushu;
it's time to pick up the pace and speedrun the rest of the island.
We start off with the 09:05 JR departure to Kurume,
and from there a local train to Kurumekokomae.
From there,
we walk north to Hanabatake,
to pick up the Nishitetsu service to Omuta,
and then change for the JR service to Uto,
the JR Kagoshima Line giving us a view of the opposite side of Shimabara bay from Day 1,
albeit only briefly,
since it sits further inland for most of its length.
We arrive in Uto at 12:28 in time for lunch.

We again have something of a long lunch break due to the way the timetables line up.
If hanging around and exploring Uto isn't your cup of tea,
there is enough time to take the JR service to Misumi and back,
letting you see
(parts of)
both the north and south coasts of the Uto peninsula.

From Uto,
one could take the Kyushu Shinkansen as far as Shin-Yatsuhiro,
since it is a good mile more coastal than the Kagoshima line for most of the stretch;
however,
that would add an extra change,
so instead I propose taking the slower JR service to the original Yatsuhiro station,
departing at 15:07,
and then changing to the Hisatsu Orange Railway service to Sendai.
(Not [that Sendai][sendai],
[this Sendai][satsumasendai].)
From there,
it's a 50-minute JR ride to Kagoshima-Chuo,
where we end day 3 at the southernmost station on our itinerary at 19:22.
We've now made it halfway around Kyushu;
we have one day left to get back up the east coast.

One thing that omitting spurs does mean here
is that we miss out on the southernmost station in Japan
(outside Okinawa).
Taking the Ibusukimakurazaki line all the way to Makurazaki takes almost 3 hours,
so just this spur would add almost a day to the itinerary.
It's definitely a line I want to ride at some point,
however.

#### Day 4 <!-- Kyushu -->

![Map of the area described in the text with the route described marked.](/images/circumnavigate-japan/kyushu-4.png)

Given the complexity of previous days,
this is something of an anticlimax:
only three trains,
all limited expresses.
We start at Kagoshima-chuo at 08:49,
and take the JR _Kirishima_ limited express to Miyazaki,
arriving at 10:57.
There we have a long lunch,
and then at 14:06 board the JR _Nichirin_ service to Oita,
where we change to the JR _Sonic_ service to Kokura,
closing out day 4 and our circumnavigation of Kyushu at 19:03.

Alternatively,
there is a direct _Nichirin Seagaia_ limited express
from Miyazaki all the way to Kokura,
but that is a relatively late departure,
only arriving in Kokura at 21:10.

We have again skipped a long seaside railway that doesn't connect back up;
this time the line south then west from Miyazaki to Shibushi.
If you wanted to add an extra day to the itinerary,
and wanted a long walk,
you could alight early from the _Kirishima_ at Miyakonojo,
and walk south to Shibushi
(a bit less than a day's walk),
and then catch a 2.5-hour service up the Nichinan line to Miyazaki.

From Kokura,
it's two stops on a local train to get back to Shimonoseki to resume the loop of Honshu,
if that's your plan.

#### Summary <!-- Kyushu -->

Out-of-station interchanges and changes of operator are marked in **bold**;
they may require a longer connection time.

| Day | Depart | | | Arrive | Operator |
| = | = | = | = | = | = |
| 1 | Kokura | 09:01 | 10:11 | Kashii | JR Kyushu |
| 1 | Nishitetsu Kashii | 10:27 | 10:38 | Kaizuka | Nishitetsu |
| 1 | Kaizuka | 10:40 | 10:50 | Nakasu-Kawabata | Fukuoka City Subway |
| 1 | Nakasu-Kawabata | 10:54 | 11:09 | Meinohama | Fukuoka City Subway |
| 1 | Meinohama | 11:11 | 11:35 | Chikuzen-Maebaru | JR Kyushu |

| 1 | Chikuzen-Maebaru | 11:38 | 12:31 | Nishi-Karatsu | JR Kyushu |
| - | - | - | - | - | - |
| 1 | Nishi-Karatsu | 13:33 | 13:58 | Yamamoto | JR Kyushu |
| 1 | Yamamoto | 14:38 | 15:18 | Imari | JR Kyushu |
| 1 | Imaru | 15:33 | 18:06 | Sasebo | Matsuura Railway |
| = | = | = | = | = | = |
| 2 | Sasebo | 09:05 | 09:14 | Haiki | JR Kyushu |
| 2 | Haiki | 09:33 | 10:38 | Isahaya | JR Kyushu |
| 2 | Isahaya | 12:07 | 12:55 | Nagasaki | JR Kyushu |
| - | - | - | - | - | - |
| 2 | Nagasaki Eki-mae | ~14:00 | ~14:16 | City Hall (Nagasaki) | Nagasaki Electric Tramway |
| 2 | City Hall (Nagasaki) | ~14:20 | ~14:25 | Nagasaki Eki-mae | Nagasaki Electric Tramway |
| 2 | Nagasaki | 17:13 | 17:22 | Isahaya | JR Kyushu (Shinkansen) |
| 2 | Isahaya | 17:32 | 18:38 | Hizen-Hama | JR Kyushu |
| 2 | Hizen-Hama | 18:41 | 19:47 | Tosu | JR Kyushu |
| = | = | = | = | = | = |
| 3 | Tosu | 09:05 | 09:12 | Kurume | JR Kyushu |
| 3 | Kurume | 09:16 | 09:19 | Kurumekokomae | JR Kyushu |
| 3 | Hanabatake | 10:04 | 10:34 | Omuta | Nishitetsu |
| 3 | Omuto | 11:21 | 12:28 | Uto | JR Kyushu |
| - | - | - | - | - | - |
| 3 | Uto | 15:07 | 15:31 | Yatsushiro | JR Kyushu |
| 3 | Yatsushiro | 15:42 | 18:06 | Sendai (Satsumasendai) | Hisatsu Orange Railway |
| 3 | Sendai | 18:32 | 19:22 | Kagoshima-Chuo | JR Kyushu |
| = | = | = | = | = | = |
| 4 | Kagoshima-chuo | 08:49 | 10:57 | Miyazaki | JR Kyushu |
| - | - | - | - | - | - |
| 4 | Miyazaki | 14:06 | 17:24 | Oita | JR Kyushu |
| 4 | Oita | 17:44 | 19:03 | Kokura | JR Kyushu |

### Hokkaido

Unlike most of Japan,
most of Hokkaido's railways are inland,
especially once you get past Sapporo.
That said,
it is vast,
and it wouldn't do to ignore it after spending so much time on the other three islands.

#### Day 1 <!-- Hokkaido -->

![Map of the area described in the text with the route described marked.](/images/circumnavigate-japan/hokkaido-1.png)

We start our Hokkaido adventure in Kikonai,
having arrived on the Hokkaido Shinkansen,
perhaps from an in-progress circumnavigation of Honshu.
We depart at 09:12 on a South Hokkaido Railway
(another third-sector company)
service to Hakodate.
Since the Hokkaido Shinkansen hasn't opened past Hakodate yet,
and Hokkaido was never dense enough to justify a large number of private operators
like is seen in the major cities further south,
every other service in Hokkaido will be JR.

From Hakodate,
we head to Oshamambe,
arriving at 12:14 for an extended lunch.
We depart again at 16:39 for Otaru,
and from there head to Sapporo,
finishing day 1 at 20:42.

Central Sapporo isn't that coastal,
and we have a late start on day 2,
so if you wanted,
you could alight early at Asari or Zenbiko,
each 50m or less from the sea,
and catch up in the morning.

#### Day 2 <!-- Hokkaido -->

![Map of the area described in the text with the route described marked.](/images/circumnavigate-japan/hokkaido-2.png)

We start at 11:06 by heading from Sapporo to Iwamizawa,
and then from there head to Asahikawa,
arriving at 13:37 for a late lunch.

Here is another missed opportunity of the spurless route:
we miss out on the long line to Wakkanai,
Japan's northernmost and arguably most remote station,
250km from the junction at Asahikawa.
The trains on this line are Not Fast,
averaging less than 50km/h on local and less than 70km/h on limited expresses,
and are also not that frequent.
Frustratingly,
the afternoon service departs two minutes before our arrival,
so if you did want to add an excursion to Wakkanai,
you'd need to stay in Asahikawa all afternoon
and take a train arriving at almost midnight.
Similarly on the return leg you'd need to depart at 06:36
to be able to meet the post-lunch departure from Asahikawa,
so if you only added one extra day to your itinerary,
you'd get less than seven hours in Wakkanai,
potentially none of them in daylight.
(Realistically,
if you did want to visit Wakkanai,
you'd also want to rearrange the rest of this schedule around it,
to better line up with the limited available timings.)

From Asahikawa
(regardless of whether we took an excursion to Wakkanai),
we take the _Kitami_ limited rapid train to Abashiri,
ending day 2 at 19:41.

#### Day 3 <!-- Hokkaido -->

![Map of the area described in the text with the route described marked.](/images/circumnavigate-japan/hokkaido-3.png)

Departing Abashiri at 10:24 on the service to Kushiro,
we're treated to our first section of coastal railway since Oshamambe,
before turning to the south across country
and arriving into Kushiro at 13:33 for lunch.

Here we skip another interesting spur,
this time eastward to Nemuro,
the easternmost station in Japan.
Kushiro&ndash;Nemuro is over two hours each way,
but the trains are at least more frequent than those to Wakkanai,
so an extra day would likely be enough to get a decent look at Nemuro.

After another long lunch and an afternoon in Kushiro,
we catch the 17:06 service to Obihiro,
finishing day 3 at 19:26.
(This uses a local train;
there's also a limited express available on the same route
that might be more convenient timing-wise,
depending where you want to spend your free time.)

#### Day 4/5

![Map of the area described in the text with the route described marked.](/images/circumnavigate-japan/hokkaido-4.png)

We have an early start to day 4,
catching the 08:42 departure to Oiwake,
where we arrive at 10:47 and stop for another long lunch break.
(Long lunch breaks seem to be,
for some reason,
a feature of Hokkaido's railway timetable.)
At 14:09 we depart again for Tomakomai,
then head to Higashi-Muroran,
and then back to Oshamambe,
arriving at 17:55.

![Map of the area described in the text with the route described marked.](/images/circumnavigate-japan/hokkaido-5.png)

If we aren't pedantic about the rules,
then we might consider ourselves done here,
but there is in fact a loop of track along the Pacific coast
that provides a second route from Mori to Onuma,
and a second slightly further south,
east of Shin-Hakodate-Hokuto station,
which are only traversed by local trains.
Therefore,
we need to take a local train from Oshamambe to Hakodate
to close these loops.
This pushes us slightly into day 5
(unless you're happy to tolerate a very late end to day 4),
with a 13:38 departure from Oshamambe, arriving into Hakodate at 16:32.

If you need to reconnect with the Honshu route,
then from here you'd likely want to take
the Hokkaido Shinkansen from Shin-Hakodate-Hokuto to Shin-Aomori.

#### Summary <!-- Hokkaido -->

| Day | Depart | | | Arrive | Operator |
| = | = | = | = | = | = |
| 1 | Kikonai | 09:12 | 10:12 | Hakodate | South Hokkaido Railway |
| 1 | Hakodate | 10:45 | 12:14 | Oshamambe | JR Hokkaido |
| - | - | - | - | - |
| 1 | Oshamambe | 16:39 | 19:49 | Otaru | JR Hokkaido |
| 1 | Otaru | 19:45 | 20:42 | Sapporo | JR Hokkaido |
| = | = | = | = | = |
| 2 | Sapporo | 11:06 | 11:47 | Iwamizawa | JR Hokkaido |
| 2 | Iwamizawa | 12:00 | 13:37 | Asahikawa | JR Hokkaido |
| - | - | - | - | - |
| 2 | Asahikawa | 15:10 | 19:41 | Abashiri | JR Hokkaido |
| = | = | = | = | = |
| 3 | Abashiri | 10:24 | 13:33 | Kushiro | JR Hokkaido |
| - | - | - | - | - |
| 3 | Kushiro | 17:06 | 19:26 | Obihiro | JR Hokkaido |
| = | = | = | = | = |
| 4 | Obihiro | 08:42 | 10:47 | Oiwake | JR Hokkaido |
| = | = | = | = | = |
| 4 | Oiwake | 14:09 | 14:45 | Tomakomai | JR Hokkaido |
| 4 | Tomakomai | 15:11 | 16:07 | Higashi-Muroran | JR Hokkaido |
| 4 | Higashi-Muroran | 16:17 | 17:55 | Oshamambe | JR Hokkaido |
| = | = | = | = | = |
| 5 | Oshamambe | 13:38 | 16:32 | Hakodate | JR Hokkaido |

## Rail passes

Japan offers a variety of rail passes for foreign tourists,
which can often give better prices than buying individual tickets.
That said,
the nationwide Japan Rail Pass has lost value in recent years as the price has risen,
and is generally only considered worth it if you are planning a lot of Shinkansen trips.
The only pass covering the full length and time of the loop around Honshu
would be this pass,
costing ¥100,000 for 21 days;
this would save a maximum of around ¥18,000&mdash;most likely less than this.
(I.e. a maximum saving of around 10% of the total cost.)
You would still need to use an IC card on non-JR lines,
too,
which might get confusing
if you tried to use your Japan Rail Pass at a private operator.
It'd arguably be better then to use an IC card everywhere,
to make getting through ticket barriers quicker at tight connections,
since the savings are minimal.

On the other hand,
some areas have local passes.
For example,
Shikoku has the ALL SHIKOKU Rail Pass,
which covers all of the private operators in Shikoku in addition to JR.
The four-day pass,
sufficient for the Shikoku loop,
costs ¥15,000,
and saves up to ¥5,440,
over 25% of the cost.
This might be worthwhile,
if the logistics for picking up the ticket at a designated station can be managed.

There are also regional rail passes within Honshu;
for example,
the JR West 7-day all-access pass costs ¥26,000,
and would save almost ¥20,000 on the maximum fare for our stay in the JR West region.
(It would only be sufficiently long,
however,
if we didn't do the Kyushu loop.)

| Loop | Maximum cost | Possible pass | Pass length | Pass cost | Total maximum cost with pass | Saving |
| = | = | = | = | = | = | = |
| Honshu | ¥115,807 | JR West All Access pass + JR East Rail Pass | 7 + 5 days | ¥26,000 + ¥30,000 | ¥76,561 | ¥39,246 |
| Shikoku | ¥20,440 | ALL SHIKOKU Rail Pass | 4 days | ¥15,000 | ¥15,000 | ¥5,440 |
| Kyushu | ¥35,260 | JR All Kyushu Rail Pass | 5 days | ¥24,000 | ¥30,740 | ¥4,520 |

| Hokkaido | ¥38,080 | JR Hokkaido Rail Pass | 7 days | ¥28,000 | ¥29,290 | ¥8,790 |
| - | - | - | - | - | - | - |
| All-Japan | ¥216,357 | JR East Rail Pass + JR Hokkaido Rail Pass + ALL SHIKOKU Rail Pass + JR All Kyushu Rail Pass | 5 + 7 + 4 + 5 days | ¥97,000 | ¥177,841 | ¥38,516 |

Of these passes,
only the JR Hokkaido rail pass is available to residents of Japan.

## Hard mode

I haven't
(yet…)
produced a timetable for the full hard mode,
including all spur lines,
and including other reversals to pick up skipped stretches of track.
To give a feel for it,
here's how the length of track and estimated total time on trains[^9] stacks up:

| Region | Total length (easy mode) | Total travel time (easy mode) | Maximum cost (easy mode) || Total length with spurs (hard mode) | Total travel time (hard mode) | Maximum cost (hard mode) |
| = | = | = | = || = | = | = |
| Honshu | 4514.5km | 3 days 14 hours | ¥115,807 || 6427.5km | 5 days 14 hours | ¥183,873 |
| Shikoku | 667.6km | 15 hours | ¥20,440 || 845.0km | 20 hours | ¥26,520 |
| Kyushu | 1218.8km | 22 hours | ¥35,260 || 1783km | 1 day 15 hours | ¥49,750 |
| Hokkaido | 1453.9km | 1 day 2 hours | ¥38,080 || 2443.7km | 1 day 21 hours | ¥63,790 |
| - | - | - | - || - | - | - |
| All-Japan | 8073.6km | 6 days 9 hours | ¥216,357 || 11,701km | 10 days 2 hours | ¥332,743 |

Depending whether you measure it by finances, distance, or time,
hard mode adds between 40%&ndash;60%.
In reality it'll likely add more,
since as we saw in Hokkaido,
scheduling gets harder on less-trafficked spur lines.

## Conclusions

Circumnavigating Japan by rail is possible,
and looks like it'd be a blast.
It'd take a month of travel days,
but more likely around 5 weeks of weekday travel.
It'd be very tricky to do while remote working,
due to the frequency of changing trains
and the difficulty of getting work done on a local train.

I really want to have a go at this,
if I can find enough time off work
and can fund it.

## Footnotes

[^1]: (Okinawa has 17km of monorail,
      but since this is disconnected from the rest of the rail network,
      and doesn't make a loop,
      I'll discount this.)

[^2]: Actually longer,
      since I assume mostly travelling on working days;
      schedules differ at weekends.

[^3]: There's a small hole in our track loop here
      that's not easy to plug without shuttling in and out of Nishi-Okazaki;
      one other option would be a loop via Shin-Anjo,
      Okazakikoen-Mae/Nakaokazaki,
      and Okazaki,
      but that's a long way to go for a few hundred metres of track,
      and would likely add another day to the full journey
      because of how things line up.

[^4]: This creates a small hole at least from the strictest perspective,
      but without it we shouldn't be on these branches at all,
      since they both are excluded.
      It seems a shame to not explore the Chita peninsula at all
      given how many railway lines head onto it,
      so I'm classing it as a loop;
      those who disagree are welcome to design their own hypothetical loops!

[^5]: There's a one-train day in Hokkaido day 5,
      but that only applies if you're doing Hokkaido in isolation;
      if you count "this trip" on Honshu as including Hokkaido,
      then that day will include another train to escape Hokkaido back to Shin-Aomori.

[^6]: This obviously had far more devastating effects on local people;
      it is not my intent here to say that
      the worst consequence of the tragedy was the loss of coastal train lines.

[^7]: Asakuraekimae would be closer,
      but would leave more of a gap in the track coverage,
      and we have the time to spare here way due to the tram schedules.

[^8]: There is a small gap here,
      that could be closed by adding a reverse out of Kashii to Wajiro,
      and starting on the Nishitetsu service there rather than at Nishitetsu Kashii,
      but the timing of the Kashii&ndash;Wajiro service aligns poorly with our journey.

[^9]: Train time estimates are from my first pass at routing,
      so don't precisely tie up with the timings in the final itinerary.

[aobuta]: https://en.wikipedia.org/wiki/Rascal_Does_Not_Dream
[garupan]: https://en.wikipedia.org/wiki/Girls_und_Panzer
[hokuriku]: https://en.wikipedia.org/wiki/Hokuriku_Shinkansen
[maglev]: ./2025-02-19-planes-trains-japan-jakarta.md
[nishi-kyushu]: https://en.wikipedia.org/wiki/Nishi_Kyushu_Shinkansen
[obama]: https://en.wikipedia.org/wiki/Obama,_Fukui
[sendai]: https://en.wikipedia.org/wiki/Sendai
[satsumasendai]: https://en.wikipedia.org/wiki/Satsumasendai,_Kagoshima
