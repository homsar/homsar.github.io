---
layout: post
title:  "Beyond London on the Channel Tunnel"
date:   2026-03-05 20:30:00 +0000
categories: [silly train ideas]
---

When the Channel Tunnel was under construction,
there were plans for "Regional Eurostar" services to run "North of London".
Rolling stock was even procured for this purpose.
However,
by the time the tunnel opened,
these services were scrapped,
in the wake of rail privatisation in the UK,
the change of plan from on-board passport checks to passport control at stations,
and the rise of low-cost flights,
among other reasons.

Given there is now increased increase in international train travel,
perhaps it is worth revisiting what such services might look like.

## Constraints

I'll work with the following constraints,
which are similar
(but not identical)
to those used by [Jon Worth][jonworth]
in his [#CrossChannelRail][crosschannelrail] work
(but I'll be rather more liberal about what is considered "major work",
and what services may be considered viable):

- **No new track**.
  Adding track explodes costs rapidly.
- **Electric trains only**.
  Running diesel through the tunnel is appalling to me.
  We will however need batteries
  to deal with a couple of small instances of discontinuous electrification.
- **Stations need passport control and secured platforms**.
  While I'd prefer the UK to join Schengen,
  or at least for the Home Office to allow passport checks on board,
  there is no realistic prospect of this happening any time soon.

I will however assume that secure, segregated platforms are only required for departure,
not arrivals.

## Where can we go

The line emerging from the Channel Tunnel connects directly to High Speed 1.
This passes through Ashford International,
Ebbsfleet International,
and Stratford International,
before arriving into St Pancras International.
It has junctions:

- at Ashford, with branches towards
  - Canterbury in the northeast
  - Maidstone in the northwest
  - Tonbridge in the west
  - Hastings in the southwest
- before Ebbsfleet,
  onto the old slow line into Waterloo,
  used before the final phase of HS1 was completed
- in the St Pancras station throat,
  onto the Midland Main Line and East Coast Main Line.

Of these,
the Maidstone and Waterloo branches funnel us into London,
so aren't interesting.
The line through Canterbury doesn't really offer many destinations;
given that any service would need to pass through
(and should call at)
Ashford,
passengers from the Canterbury area
could easily take a local train and change at Ashford.
The junctions at St Pancras don't really work,
as one has to make some very awkward manoeuvres going in and out of St Pancras,
disrupting other traffic;
this gives little value over passengers changing trains,
as the available lines already call at Kings Cross or St Pancras.

The HS1&ndash;HS2 link is not being built,
and likely never will be,
so we are not able to have through high-speed services to the north.
We're thus limited to heading to the southwest and west.

## Rolling stock

Since we will be heading off High Speed 1 in the southeast,
we will be travelling through
the part of the UK rail network powered by 750V third rail electrification.
As such,
any train we run will need to be at least bi-mode,
allowing 750V DC third rail and 25kV AC overhead electrification.
Additionally,
the range of places we can go
without hitting at least a short distance without electrification
is vanishingly small,
so we'll need a small amount of battery per train too.

While there are around 6 complete class 373/3 "North of London" trains in storage,
built to allow this,
they are very long in the tooth,
and have been put to a number of other purposes since they were procured;
I'm not certain,
but I suspect they no longer have their third rail shoes.
They also don't have batteries,
and a retrofit at this stage in their life would be absurd.

A new train order would seem to be needed, then.
Manufacturers with recent experience of UK third-rail electrification are:

- Stadler: supplying Merseyrail and the Sheffield Supertram,
  but only for relatively low-speed trains.
- Bombardier: supplying the London Overground,
  but only for relatively low-speed trains.
- Siemens: supplying the Southwestern and West Midlands networks,
  but not for high-speed trains.
- Hitachi:
  supplying the class 395 _Javelin_ trains
  based on their AT300 platform.
  These already run on High Speed 1,
  and through the third rail parts of the Southeastern network,
  so would seem to have an advantage.

Whatever train was chosen would need to run at full speed on the high-speed lines;
a 140mph-limited train like the Class 395 wouldn't cut it.
(However,
on the third rail network,
all trains are limited to at most 100mph.)
So this couldn't be a follow-on to any previous order;
it would need a new (or at least tweaked) design.

Hitachi would seem to have the advantage;
however,
the Class 395 design is derived from the 400 series Shinkansen design from 1992,
which was limited to 240km/h in service,
and does not have batteries.
A new design,
perhaps based on the E6 Shinkansen
(capable of 320km/h),
would seem warranted,
but this would incur development expense.

The other front runner as I see it would be Stadler,
who have a proven history about having
particularly flexible and modular design.
The [FLIRT][flirt] is incredibly successful
and comes in a huge variety of shapes and electrification technologies.
However,
it is not high-speed capable;
Stadler's high-speed train is the [SMILE][smile];
currently only 250km/h examples of this exist,
but I've seen discussion of a 300km/h variant.
If anyone could efficiently kit-bash their various technologies
to give a 300km/h capable train
with both 25kV AC overhead line and 750V third rail electrification,
plus a small battery for areas with discontinuous electrification,
it would be Stadler.

For reasons that will become clear,
similarly to as Jon found to be optimal for many European routes,
the trains would need to be 200m long,
coupling together to form 400m units to go through the tunnel.
I will assume that we need 6 200m trains:
two
(i.e. one 400m pair)
operating in each direction at any time,
with an additional hot spare pair in reserve.

## Destinations

With everything north of London ruled out,
the next best corridor would seem to be the Great Western route.
To get there,
we would head west from Ashford towards Reading,
and after joining the GWML there,
call at Bristol Parkway and Cardiff Central.
However,
Reading station only has 200m platforms
(a very common limitation;
longer trains are exceedingly rare in the UK),
so ideally we want a second route,
to maximise the number of passengers benefiting from our path through the tunnel.
The only other route realistically available follows south coast,
calling at Brighton and Southampton.

On the other side of the Channel,
all services would call at Lille.
(It may or may not make sense to additionally call at Calais Fréthun;
but doing so would provide a [handy cross-channel shuttle][minimal].)
From there,
one could alternate services between Paris and Brussels,
or one could split the train at Lille and send one half to each.
This would mean you would effectively have,
for example,
a Cardiff&ndash;Brussels service,
and a Southampton&ndash;Paris service;
however,
passengers from Cardiff to Paris or from Southampton to Brussels
could make a same-platform transfer at Lille
(and at Ashford on the return leg).

I don't think it makes sense for this service to also try and solve
the problem of finding additional destinations in Europe
beyond Paris, Brussels, and Amsterdam.
At most,
perhaps a common rolling stock order could be made,
but even that would likely be sub-optimal,
since other orders wouldn't need third rail.

## The route in detail

Let's go through each step of the route now,
and outline the enabling work needed at each point.

### Cardiff

Cardiff Central is a busy eight-platform through station,
with a grand, grade I listed city-facing entrance to the north
(with a very small car park attached),
and a smaller entrance to the south connected to larger car parks
(which will shortly be redeveloped
to enable the South Wales Metro tram-train connection to Cardiff Bay).

Most platforms at Cardiff Central
have multiple staircases connecting them to two underpasses.
This makes them impossible to secure.
Platform zero,
however,
has only two entry points,
both entirely separate from the rest of the station:
a staircase from inside the main station building,
and a ramp from the smaller of the station's car parks.

A complication,
however,
is that platform 0 is only 154m long,
potentially extendable to 180m if the small structure
(presumably electrical plant equipment)
at the west end of the platform is relocated.
The east end is bounded by the Grade I listed station building.
Platform 0 sees 1&ndash;2 trains per hour,
so temporarily securing it for boarding an international departure
would likely be possible without too much disruption to other services.

The proposal therefore would be to take over part of the car park,
and build a small terminal building,
with an additional route for non-international platform access.
This would need to comply with restrictions on modifying listed buildings.
The western end of the inside of the station would be concurrently upgraded,
to improve access to platform 0 for passengers with restricted mobility.

Selective door opening would be required;
depending on whether the platform is extended,
passengers for the front 1&ndash;2 carriages
would need to board a more rearward coach and walk through.
In principle,
the ticket booking system could prioritise seats further back in the train
for passengers from Cardiff,
minimising the number of passengers this would impact.

![Diagram of the proposal described in the text for Cardiff.](/images/beyond-london/cardiff.png)

(A lot of these complications would be avoided if we could instead
[put Cardiff Central station in a museum][st-fagans]
and instead build a new station with a full-length platform 0.)

#### Swansea?

A complication of adding new services at Cardiff is that
the station throat on the west side of the station is extremely congested,
limiting the number of new terminating services that can be added.

The line west of Cardiff is not electrified&mdash;this
this was originally planned during the line from London to Cardiff,
but cancelled mid-way.
If these plans were reinstated,
running to Swansea would likely be simpler than terminating at Cardiff.

Swansea is a four-platform terminus station,
around 50 minutes west of Cardiff.
As discussed in [a previous article][slip-sleepers],
Swansea already has a disused platform across from platform 1.
(However,
the tracks have long since been lifted,
so these would need to be added back.)
The directly adjacent building formerly used for [Red Star Parcels][parcels]
could be used as a terminal.
The available platform length is 210m,
providing sufficient length for a 200m train.

![Diagram of the proposal described in the text for Swansea.](/images/beyond-london/swansea.png)

Were the Welsh or UK government to fund electrification to Swansea,
then adapting Swansea to add platform 0
would likely be simpler than the adaptations required at Cardiff,
provided the pointwork to add the tracks into the new platform
could be installed while the line was already closed to enable the electrification.
The primary waiting areas for platform 1 are beyond the end of the would-be platform 0,
so the remainder of the platform could be temporarily secured as necessary
without causing significant disruption to the rest of the station.

### Bristol Parkway

Bristol Parkway is a four-platform through station.
Each platforms sees many trains per hour,
and platforms are all accessed from a single footbridge,
which is integrated with the station building.
Securing any of the current platforms seems logistically impossible.

However,
Bristol Parkway also benefits from two bypass/through tracks,
one on the north and one on the south side,
and a wealth of car parking on the north side,
directly adjacent to the main station building.
Bristol Parkway is a major interchange point,
and all passenger trains will stop here;
thus the bypass tracks will only be used for freight
while trains are blocking all four platform tracks
(or simply to reduce risk to passengers on the platform).

The proposal here would then be
to take over part of the ground floor of the multi-storey car park,
the part closest to the station building,
to turn into a Channel terminal,
directly connected on the ground floor,
and construct a new secure 250m platform[^1]
directly between the current car park building and the through track,
dedicated to departing Channel services.

![Diagram of the proposal described in the text for Bristol Parkway.](/images/beyond-london/parkway.png)

#### Bristol Temple Meads?

Bristol Parkway is,
as the name suggests,
situated well outside of Bristol city centre.
A potentially preferable alternative would be
to have departures from the city centre's Temple Meads station instead.

This has a number of challenges:
firstly,
none of the lines into Temple Meads is electrified;
similarly to Swansea,
this was proposed in the early 2010s as part of the Great Western electrification,
but ultimately didn't happen,
and shows no prospect of happening in the near future.

Additionally,
Bristol Temple Meads sits on a much more constrained site than Parkway.
Similarly to Parkway,
securing any of the current platforms would be
too disruptive to the rest of the station's operations to work.
In principle
it may be possible to add a new 220m platform 16 to the east side of the station
stretching the length between Cattle Market Road and the Floating Harbour,
and borrow land from the new University of Bristol campus to construct a terminal,
which would connect directly to the new eastern entrance..
This would serve the same track as platform 15,
so additional measures may need to be taken to secure the platform;
the pathing works,
however,
as trains towards Reading already depart from this platform.

![Diagram of the proposal described in the text for Bristol Template Meads.](/images/beyond-london/temple-meads.png)

This route would,
however,
increase the journey times for passengers from points west.
Since most passengers would arrive at Temple Meads by train anyway,
Parkway seems the more prudent option even if electrification were not a barrier.

### Reading

Reading is a fifteen-platform through station
(with six of these being bay platforms,
three facing west and three east).
Platforms 1&ndash;7 are all directly connected to each other and the station concourse,
so could not be secured.
The remainder are accessed from a single footbridge,
so none could be secured without significantly disrupting the rest of the station.

Unlike Bristol Parkway,
there are no bypass tracks.
However,
similarly to Bristol Temple Meads,
there is a little disused land to the north of the station,
adjacent to the secondary station entrance;
the car park of a disused Royal Mail sorting office.
This site has been earmarked for redevelopment;
however,
as of the latest Google Street View imagery,
work does not seem to have been started yet.

A new secure platform 16 could be built to 195m
without interfering with the current station building,
or disrupting pedestrian access along Caversham Road.
This would permit 200m trains,
with the front and rear few metres extending beyond the platform
but not interfering with any points.
Similarly to Bristol Temple Meads,
this would serve the same track as platform 15,
so additional security considerations may be needed;
for example,
platform screen doors to prevent
passengers at the domestic platform accessing international trains.

![Diagram of the proposal described in the text for Reading.](/images/beyond-london/reading.png)

Should it become desirable to run 400m trains along the route in future,
alterations to the north entrance building would allow up to a 320m platform,
or up to 450m with additional alterations to the car park and bus station access road.

East of Reading,
trains would use the currently freight-only dive-under to pass under the GWML
and join the 750V third rail network to Wokingham.
The line south from here is not currently electrified,
with Network Rail describing infill electrification as "poor value for money"
and recommending battery trains.
We rejoin the 750V DC network east of Aldershot,
and head east to Guildford,
then encounter another non-electrified section to Redhill.

Here we hit the problem that
almost every single junction in the south east
is designed to direct trains into London.
To continue onward towards Ashford,
therefore,
we need to reverse direction at Redhill.

### Redhill

Since we need to reverse at Redhill,
might it make sense to make a station call here?

Redhill was the 153rd busiest station in 2024/25[^2],
counting entrances, exits, and interchanges;
this is less busy than most stations discussed here,
but still a relatively busy station;
much busier than Swansea or Ashford International.
It is about halfway between Reading and Ashford,
so would be in about the right place for a stop,
assuming that one is justified.

Redhill has three through platforms and one bay platform,
plus two through tracks in between the tracks at platforms 2 and 3.
These are connected by an underpass,
which connects directly to the western entrance of the station;
from the eastern entrance,
one must traverse platform 3.
Additionally,
there is a seemingly disused pedestrian overbridge
connecting directly to the Royal Mail facility to the east of the station,
north of the eastern station entrance.
Platform 0 would likely be the simplest to secure,
and is plenty long enough at 300m;
in principle 100m of the platform could be left unsecured
to allow domestic passengers to continue waiting for their services.
However,
the platform sees three trains per hour;
I'd guess that this is borderline as to whether
temporarily securing the platform and blocking the line
would disrupt domestic services.

Assuming that the pathing and number of potential passengers made sense,
a terminal could use some space from the station car park,
or could displace some of the trees currently growing behind and around the bike sheds;
either way,
it could open directly onto platform 0.

![Diagram of the proposal described in the text for Redhill.](/images/beyond-london/redhill.png)

(If the Royal Mail facility were to close,
another option would be to reuse this,
and reopen the existing footbridge;
however,
this would likely require renovation or replacement to allow step-free access,
and would require securing platforms 1 and 2,
which would be more disruptive to traffic than using platform 0.)

From Redhill,
it's a straight shot along the
(shockingly straight,
to the point that it's disappointing that third rail prevents higher speed running)
Redhill to Tonbridge line and South Eastern Main Line,
before arriving into Ashford on the international platforms.

## Southampton

Southampton Central station has four through platforms,
as well as an unnumbered west-facing bay platform.
Platform 1 would be the natural choice for departing services for London,
but unfortunately,
all other platforms are accessed via a footbridge from platform 1,
so the full length couldn't be secured without shutting the entire station down.

The section of platform to the west of the footbridge would give 150m,
extensible to 170 without demolishing any existing buildings.
Similarly to platform 0 at Cardiff,
this might be sufficient for a service starting at this station
with selective door opening.
A terminal building could be built taking over some of the station car park,
or some of the buildings in the industrial estate immediately to its west
could be bought and replaced.

A problem with this approach,
however,
is the A3057 bridge over the station.
It seems unlikely that
a platform could be considered secure enough for international traffic
when in principle someone could easily drop down onto it from above.
This would then seem to necessitate building a partial or full train shed
for Southampton Central,
integrating the A3057 bridge such that
accessing the platforms from above were prevented.

![Diagram of the first proposal described in the text for Southampton.](/images/beyond-london/southampton-1.png)

The other option would be the portion of platform to the east of the footbridge.
This appears potentially easier in that it is closer to the current station building,
which is decidedly large,
and so it may be possible to site the terminal inside the existing building.
However,
the current platform only provides 100m of length;
this seems insufficient for 200m trains even with selective door opening.
It seems like it would be _just_ possible to fit a platform extension to 200m
to the west of where the pointwork starts
(so that trains sitting at the platform wouldn't block trains leaving platform 2);
this would however necessitate re-siting
a lot of the plant currently to the east of the platform,
and a pedestrian overbridge.

![Diagram of the second proposal described in the text for Southampton.](/images/beyond-london/southampton-2.png)

Southampton Central sees four trains per hour on platform 1 during the rush,
so operationally this would be a challenging one.
Having an extended platform where at least part can be kept secure at all times
would likely be the best option here.

### Brighton

Brighton is an 8-platform terminus station.
Platforms 1&ndash;3 have access to the line west to Southampton,
while platforms 3&ndash;8 can access the lines to the north and east,
including to Ashford.
As such,
platform 3 is the only viable platform for
a through service from Ashford to Southampton or vice-versa.
Unfortunately,
platform 3 is basically impossible to secure
in such a way that it could be accessed from a hypothetical Channel terminal.

A possible,
if awkward,
workaround would be to have services from Southampton take the Cliftonville Spur
onto the Brighton Main Line,
and then immediately reverse back into one of the high-numbered platforms at Brighton.
The question then becomes how to secure a platform.

![Diagram of the route into platform 8 of Brighton from the west.](/images/beyond-london/brighton-approach.png)

Similarly to other stations,
the track at platform 8 has additional space on the far side.
For part of the station this forms a pedestrian station entrance,
but it could just be possible to squeeze in a 200m platform northwest of this
without fouling the station throat,
taking only some car park spaces.
This would however result in the terminal being
quite awkwardly-locate relative to the station,
and would take a significant chunk of the car park.

![Diagram of the first proposal described in the text for Brighton.](/images/beyond-london/brighton-1.png)

The other option would be to secure _part_ of platforms 7/8.
The platform is a full 300m long,
meaning that 100m could be kept open for local services,
with the remaining 200m being for international services.
Based on skimming RealTimeTrains,
trains using platforms 7 and 8 are typically only three or four carriages long,
which would fit into the 100m not secured.
This would,
however,
require that the terminal fit _on the platform_.
The platform is wide&mdash;23
metres wide at its widest point&mdash;and
already has a 25m&times;8m structure on it.

10 &times; 200m gives two thousand square metres,
more than enough room for a combined terminal,
waiting area,
and secure platform.
Assuming that this was built facing platform 8,
then there would still be enough platform width left
to access the full length of platform 7.
(Certainly more width than
the very narrow existing platform 1/2 is already constrained to!)
If this were built at the near end of platform 8,
it would allow local trains to arrive and depart
while the international service was boarding,
at the expense of passengers needing to walk the full 200m
to reach their train from the main concourse.
Alternatively,
siting the terminal at the far end
would minimise disruption to local passengers reaching their trains,
but trains would be forced into platform 7 instead
while international trains were boarding.

![Diagram of the second proposal described in the text for Brighton, with the secure area at the northern end of platform 8.](/images/beyond-london/brighton-2.png)

![Diagram of the third proposal described in the text for Brighton, with the secure area at the southern end of platform 8.](/images/beyond-london/brighton-3.png)

Assuming that all of this is possible,
trains would then leave Brighton towards Lewes,
passing through Hastings onto the Marshlink line.
This is another of the very few unelectrified lines in the south east.[^3]
Unlike the above routes,
Network Rail haven't dismissed this one out of hand,
but they have put a half-billion pound price tag on it.[^4]

### Ashford

Frustratingly,
the Marshlink line approach to Ashford doesn't connect to the international platforms;
as such,
trains must pass platform 1 or 2 onto the South Eastern Main Line,
and then reverse back into an international platform.[^5]

![Diagram illustrating the above manoeuvre](/images/beyond-london/ashford-approach.png)

Once done,
the two units couple,
and proceed similarly to previous Eurostar services from Ashford:
heading along High Speed 1 into the tunnel,
and then either heading to Paris,
Brussels,
or decoupling to go to both.

## Summary of work needed

That was a lot of words;
let's sum things up in a table:

| Station | Work needed | Routing complications | Other notes |
| - | - | - | - |
| _Swansea_ | Adapt former parcel facility into terminal. New switch at end of platform 1. New track into platform 0. Secure platform 0. | None | Likely only viable if Cardiff&ndash;Swansea electrified. |
| Cardiff Central | Extend and secure platform 0, relocating existing structures. New terminal building using space in car park, and new accessible route from main station building. | Turning trains around at Cardiff is hard due to congestion. | None. |
| Bristol Parkway | New platform 5. Alterations to multi-storey car park to integrate new terminal. | None | None |
| _Bristol Temple Meads_ | Construct new secure platform 16. New terminal building on University of Bristol campus site. Underpass extension to connect new terminal. | Route crosses most of the station throat. | Likely only viable if both lines into Bristol are electrified. Incompatible with using Bristol Parkway. |
| Reading | Construct new secure platform 16. New terminal building on former Royal Mail site. Alterations to north entrance to link to new terminal building. | None. | None. |
| _Redhill_ | Secure northern 200m of platform 0. New terminal building using space in car park. | Train reverses here. | Subject to further study of possible traffic patterns. |
| - | - | - | - |
| Southampton Central | Extend and secure platform 1 to give 200m of platform east of the station footbridge. Re-site existing plant equipment. Adapt part of station interior to new terminal. | None | Very rapid boarding of passengers required. |
| Brighton | Secure northern end of platform 7/8. Modify existing structure on platform 7/8 to terminal, or replace with new terminal building on platform. | Train must reverse on approach to access platform 8. | Security arrangement is relatively non-standard.[^6] |
| Ashford International | None | Train from Southampton must traverse station and reverse back in. Trains couple here. | None |

(Stations in _italics_ are optional additions,
not part of the core plan.)

## Potential costs

Estimating rail project costs is hard for experts,
and I'm no expert.
So any numbers I can put on things are likely meaningless,
but per the [#Railnatter rules for crayonistas][crayonistas] I need to suggest some:

| Station | Work item | Cost estimate | Justification |
| - | - | - | - |
| Cardiff | Platform remodelling | £10m | [Cost of partial reconstruction at Chesterfield][chesterfield] |
| Cardiff | New terminal building | £2m | [£2450 median cost per square metre of new builds.][build-cost] [2300 square metre size of Amsterdam terminal][amsterdam-size], divided by three since the previous terminal of 1/4 the size was functional, and lower demand is anticipated here. |
| Bristol Parkway | New platform | £20m | As for Cardiff, but doubled as full length is required rather than only extension and remodelling. |
| Bristol Parkway | New terminal inside existing building | £1m | Cost of construction inside existing building anticipated to be lower than new build. Internal fit-out will cost the same. |
| Reading | New platform | £20m | As for Bristol |
| Reading | New terminal building | £6m | As for Cardiff, but: additional requirement to acquire land; larger terminal likely required due to higher demand; higher construction costs in south east. |
| Southampton | Platform remodelling | £15m | As for Cardiff, but increased length and requirement to relocate plant. |
| Southampton | New terminal inside existing building | £1m | As for Bristol Parkway |
| Brighton | Platform security alterations | £0.5m | Surely, this has to be less than the cost of constructing a full platform. |
| Brighton | New terminal building on existing platform | £3m | As for Cardiff, but with complication of working on a railway platform. |
| &mdash; | New rolling stock | £175m | [£400m cost for 33 five-car bi-mode class 810 units][class-810], pro rata per car, adding 50% extra for small order and batteries. |
| - | - | - | - |
| **Total** | | **£253.5m** | |

## Possible timetable

Here,
I use typical UK rail journey times between each station pair,
and allow a five-minute dwell time at each station where international passengers board,
or where trains split or join.
For other calls,
two minutes are allowed for disembarkation only.

| Station | Arrive | Depart |
| - | - | - |
| _Swansea_ | | 0800 |
| Cardiff Central | 0853 | 0858 |
| Bristol Parkway | 0932 | 0937 |
| Reading | 1027 | 1032 |
| _Redhill_ | 1153 | 1158 |
|  |  |  |
| Southampton Central | | 0924 |
| Brighton | 1104 | 1109 |
|  |  |  |
| Ashford International | 1308 | 1313 |
| Lille Europe | 1519 | 1524 |
| Bruxelles-Midi | 1602 | |
| Paris Nord | 1638 | |

| Station | Arrive | Depart |
| - | - | - |
| Paris Nord | | 0800 |
| Bruxelles-Midi | | 0836 |
| Lille Europe | 0914 | 0919 |
| Ashford International | 0925 | 0930 |
|  |  |  |
| Brighton | 1129 | 1131 |
| Southampton Central | 1316 | |
|  |  |  |
| _Redhill_ | 1040 | 1042 |
| Reading | 1203 | 1205 |
| Bristol Parkway | 1255 | 1257 |
| Cardiff Central | 1331 | 1333 |
| Swansea | 1426 | |

Comparing journey times with the current fastest routes given by Interrail Planner:

| Route | Current time | Current changes | Proposed time | Proposed changes |
| - | - | - | - | - |
| Cardiff&ndash;Bruxelles | 6:15 | 2* | 6:09 | 0 |
| Southampton&ndash;Lille | 5:26 | 2&ndash;3* | 5:00 | 0 |
| Brighton&ndash;Paris | 5:11 | 1 | 4:29 | 0 |

\* _These are marked by Interrail Planner as one change,
but this does not count the cross-London transfer
from Paddington or Waterloo to St Pancras.
From Paddington,
this is a single train on the Circle or Hammersmith and City line;
from Waterloo,
this requires taking either the Bakerloo and Victoria,
or the Northern and Piccadilly,
or taking the Northern to Euston and then walking to St Pancras._

While this itinerary would seem to work best for a one-per-day timetable,
in principle,
the circa 7-hour journey time end to end
(eight including the extension to Swansea)
means that two services could be run in a day with no extra rolling stock:
an early morning departure, arriving early afternoon,
and a mid-afternoon departure,
arriving late evening.

## Is this worthwhile?

The route along the south coast is incredibly complicated,
both in terms of the initial setup and the day to day operations.
It doesn't give a massive improvement in journey time over the current solution,
particularly once you allow for check-in time at the origin station
(which is currently included in the journey time at St Pancras).

Perhaps this is because the timings I've used are for stopping services,
but likely there aren't many diagrams available for expresses along these routes,
so we may be constrained to the slower timings anyway.
Looking at OpenRailRouting,
if one could go at line speed the entire way,
then Reading&ndash;Ashford could be done in 1:21
(allowing the 5 minutes at Redhill discussed above);
this would be a significant improvement on the 2:41 that current train speeds allow.

If Redhill to Ashford could go at a speed commensurate with the straightness of the track,
this would improve further,
although the windy line from Reading to Redhill would likely still be a significant limitation.

Having direct trains to the west certainly seems
an endeavour more worthy of investigation than direct trains to the north.
This is not just because of the current lack of track to do the latter,
but also because of station placement in London:
coming from the North, one arrives at Euston, Kings Cross, or St Pancras;
these are extremely closely situated.
Euston is the furthest from the Eurostar terminal,
but there are discussions of a travelator being added as part of the High Speed 2 works.
From the south,
express trains do not arrive at a useful station,
although Thameslink trains will go to St Pancras directly.
However,
from the west,
one invariably arrives at Paddington or Marylebone,
on completely the wrong side of London,
so must negotiate a transfer across London,
potentially with luggage,
and while trying to make a hard check-in deadline.

## Conclusion

While the costs are not insubstantial,
they are more modest than the £50&ndash;100m work being done on St Pancras,
and the multi-billion new Eurostar train order.
While the journey time improvement is modest at best,
it would be another way of overcoming the bottleneck in London.
Likely the sticking point would be
the operational cost of staffing so many border control points;
this is seemingly what has deterred Eurostar
from resuming services from Ashford and Ebbsfleet.

[^1]: In principle a 400m+ platform would fit in the available space,
      future-proofing in case longer trains were desirable in future.
      This would be dependent on additional electrification,
      as nowhere on the line west of Bristol could take them;
      they could however in principle head southwest towards Exeter
      or north towards Gloucester and Birmingham,
      if the wires were there.

[^2]: [ORR station usage data][orr-data]

[^3]: It's amazing how the desirable routes hit
      almost all of the unelectrified segments in the south east.
      I guess it's because we are looking for an orbital route,
      and all the electrification focused on radial routes into London.

[^4]: For some reason,
      OpenRailwayMap shows the opposite:
      this route is marked as unelectrified,
      with the routes closer to Reading being marked as "electrification proposed".

[^5]: An alternative would be to instead head north from Brighton,
      and meet the Reading train at Redhill instead.
      This would have a number of advantages:
      the line to Redhill is already electrified,
      and in principle the minimum journey time at line speed is shorter.
      However,
      there is insufficient platform length at Redhill to board a 400m train,
      and the line is busy enough that
      it would be hard to wait long enough to couple the trains,
      let alone have the earlier-arriving train wait for its counterpart to arrive.
      Ashford International on the other hand has
      a largely-unused platform for international services;
      international trains not stopping at Ashford have separate bypass tracks.
      Extending the platform at Redhill southbound is blocked by the pointwork;
      northbound it would require modifying structures and acquiring additional land.

[^6]: As much as there is a standard.

[crayonistas]: <https://www.youtube.com/watch?v=j_IsetENhss>
[crosschannelrail]: <https://crosschannelrail.eu>
[flirt]: <https://en.wikipedia.org/wiki/Stadler_FLIRT>
[jonworth]: <https://jonworth.eu>
[minimal]: <{% post_url 2025-03-29-minimal-channel %}>
[orr-data]: <https://dataportal.orr.gov.uk/statistics/usage/estimates-of-station-usage/>
[parcels]: <https://en.wikipedia.org/wiki/Red_Star_Parcels>
[slip-sleepers]: <{% post_url 2025-02-25-slip-sleepers %}>
[smile]: <https://en.wikipedia.org/wiki/SBB_RABe_501>
[st-fagans]: <{% post_url 2025-02-23-st-fagans %}>

[amsterdam-size]: <https://www.zja.nl/en/Nieuwe-Eurostar-UK-Terminal-in-Amsterdam-Centraal-geopend>
[build-cost]: <https://costmodelling.com/building-costs>
[chesterfield]: <https://www.networkrailmediacentre.co.uk/news/chesterfield-stations-gbp-3-3m-platform-reconstruction-gets-under-way>
[class-810]: <https://en.wikipedia.org/wiki/British_Rail_Class_810>
