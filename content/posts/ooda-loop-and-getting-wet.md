+++
title = "Thoughts on the OODA loop and falling out of a canoe"
author = ["George Jones"]
publishDate = 2020-05-26
lastmod = 2020-05-27T08:06:52-04:00
tags = ["cybersecurity", "outdoors", "SOC", "OODA"]
draft = false
+++

In my never ending quest for synthesis, this post combines thoughts on
[the OODA loop](https://en.wikipedia.org/wiki/OODA%5Floop) and falling out of a canoe twice this weekend in rapids
on the Shenandoah river.  There is a connection.  Maybe.

If you want to see the full trip report, pictures, etc. go here [Things
that fall in the river get wet](https://eludom.github.io/blog/get-wet/).  If you're interested in how this relates to
the OODA loop or, better, if you have experience/thoughts on applying
the OODA loop to operational cybersecurity settings, read on (and
comment !)

{{< figure src="/ox-hugo/paddling.jpg" caption="Figure 1: On the river during calm between crisis events" width="400px" >}}

<!--more-->


## The OODA Loop {#the-ooda-loop}

[The OODA loop](https://en.wikipedia.org/wiki/OODA%5Floop) is a concept cybersecurity has borrowed from the US Air Force.
"OODA" stands for "Observe, Orient, Decide, Act".
The OODA loop began as a very fighter-pilot-centric view of a problem
space.  I always think of Snoopy and the Red Barron.  Snoopy
**observes** the Red Barron at a distance, **orients** his Sopwith-Camel
towards the Red Barron, **decides** to fire, and then **acts** by firing-away.
Then repeat the OODA loop.  **Observe**: what was the effect of your
action (the Red Barron went down in flames, or you missed and now he's on your
tail)...


## The OODA Loop and falling out of a canoe {#the-ooda-loop-and-falling-out-of-a-canoe}

The OODA loop parallels my decision making process in the rapids this
weekend.  In one of our two crisis events I **observed** the other
canoe flip in the rapids ahead.  I **oriented** my canoe towards shore.
I **decided** to grab a tree root to buy time to sit and contemplate
options.  I **acted** by grabbing the tree root.  We flipped due to the
strong current.
REPEAT.
I **observed** that we were in the water 10 or 20 yards (9 to 18 meters)
from the start
of the rapids.  I **oriented** myself towards shore.  I **decided** to
swim to shore at all costs (loosing the canoe and all our gear) rather
than float the rapids in life jackets.  I **acted** by swimming to shore.
REPEAT.
I **observed** that we were safe on shore without our boat, gear or
friends.  I **oriented** myself downstream.  I **decided** to walk in
search of boat, gear and friends.  I **acted** by walking...


## Where does the OODA loop work well? {#where-does-the-ooda-loop-work-well}

The OODA loop seems to be a good model for rapidly changing situations
where the personal stakes to the actor are high, the actor is
receiving relevant information in a timely fashion and has the ability
to decide on appropriate action and execute in a very short
timescale.  There were elements of this in Bill Cheswick's classic [An
Evening with Berferd](https://www.cheswick.com/ches/papers/berferd.pdf) and Cliff Stoll's [The Cuckoo's Egg](https://en.wikipedia.org/wiki/The%5FCuckoo%27s%5FEgg), but I am
wondering how many of these conditions apply, to, say the modern SOC?


## Does the OODA loop work in SOCs? {#does-the-ooda-loop-work-in-socs}

How do the characteristics of crisis situations such has that
described above or a fighter pilot in dogfight map to the modern SOC?
Does a SOC have a rapidly changing situation?  Probably.  Are there
personal stakes for the actor (analyst)?  It depends.  Is it just
"work my shift and go home after the hand-off"?  Are the actors
(analysts) receiving relevant information in a timely fashion?  Or are
they waiting for a weeks-long (months-long?) approval process for the
ingest of needed data, the provisioning of enough storage and compute
power to run the queries they need?  Are they empowered to take action
in a short timescale?  Or are there three levels of management
approval needed and reports to be written before any action can taken?
Can they take machines offline, implement blocks, etc?  Even if it
impacts production?  Can they observe, orient, decide and act, or is
it time to put your feet up, hope for the best and float through the
rapids?

Your thoughts?  Experiences?

Days 17 of #100DaysToOffload <https://100daystooffload.com/>
