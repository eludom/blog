+++
title = "Choosy Programmers Choose GIF"
author = ["George Jones"]
publishDate = 2020-04-30T00:00:00-04:00
lastmod = 2020-05-01T19:46:03-04:00
tags = ["Wilhite", "CompuServe", "GIF", "History", "Computers", "Emacs", "Programming"]
draft = false
+++

[Steve Wilhite](https://en.wikipedia.org/wiki/Steve%5FWilhite) is the most prolific programmer I've ever known.  He's
mostly remembered for creating [GIF](https://en.wikipedia.org/wiki/gif) but he spent 30 years writing piles
of amazing software which helped set the stage for the Web.

<a id="orge025d83"></a>

{{< figure src="/ox-hugo/XF4MAN.gif" caption="Figure 1: CompuServe XF4 Fortran Manual" >}}

Day 02 of #100DaysToOffload.

<!--more-->

Steve worked at CompuServe (and successors) from 1970 to 2001.  I
was fortunate enough to start my career working with/for him.  My
view of his programming output comes largely from 1985-1995.  I'm
sure there was much more that I missed.


## Things Steve Wrote {#things-steve-wrote}

Steve ran the languages and tools group when I arrived.  _He had just_
_given up on writing at DEC10 ADA compiler_[^fn:1] (Steve is still writing
ADA software), was just beginning to embrace PCs as "real computers"
worthy of his attention, had written a FORTRAN compiler, a BASIC
compiler and associated run-time systems, and a run-time library for
BLISS called BTOOLS.  These were partially in support of
CompuServe's pre-information-service time-sharing services supported
by a homegrown packet-switched networking.  "Cloud computing" in the
1970s :-)

I worked on BTOOLS, SKIMAN (Single Key Index Access Manager), a
B-Tree library Steve had created.  There was a full-fledged database
system written in there somewhere I think.  There were ports and
hacks to various tools such as FINE (Fine Is Not Emacs), a C
compiler, DEC Runoff, laser printer support, source code control
systems, etc.

On top of that, Steve created the HMI (Host Micro Interface)
protocol that rode on top of [CompuServe "B-Protocol"](https://en.wikipedia.org/wiki/b%5Fprotocol) to allow API
driven interactions with the information service (the alternative
being text/command line interfaces).  This was all in an environment
where 9600baud modems were considered "fast".  Compression,
incremental display, etc. were paramount.

He later used that as the substrate for [WinCim](https://en.wikipedia.org/wiki/compuserve%5Finformation%5Fmanager), the graphical interface
to the information service that he created which kept the company
going for a while in the face of the likes of AOL.  Somewhere in
there, there was a graphics library and enough pieces that I was
able to write a web browser that worked inside WinCim, that would
have allowed CompuServe users without an Internet connection (most
everyone then) to browse the web.  Marketing did not want to release
my web browser.  **Sigh**.

Later on (after my time) Steve as pulled into major projects to support
the back end processing for H&R Blocks's TaxCut program when online
tax-filing was a new thing.  _He was also pulled into the WOW project_
_which was supposed to be the AOL killer when it became apparent that_
_CompuServe needed an AOL killer._[^fn:2]  One of those projects succeeded.
Single-handed technical virtuosity could not fix the one that
didn't.

And there was this little side project called GIF.


## Things that got out {#things-that-got-out}


### GIF {#gif}

Be careful what you do and say.  It's often the incidentals that you
are remembered for.  The kind (or unkind) words.  The side projects.

In the world of the mid 80s there were IBM PCs, Apple Macs
(classic), Amigas, Atari-STs, CoCos, and yes, Apple-IIs and
Commodor-68s.  The information service was moving beyond a
text-based, menu-driven system (I like curses and termcap as much as
the next guy, but hey..).  People wanted to share pictures, display
online-shopping catalogs, weather maps, etc.  There were no/few good
portable graphics formats.  So Steve wrote one.  GIF.  Then the web happened.
The web wanted portable images too.  GIF worked.  So the early web
adopted it.  There was the kerfuffle over the LZW compression
algorithm it used resulting in the creation of the PNG format, but,
hey, who in 1987 would ever think that an algorithm published in ACM
might not be free.  OK, [Stallman](https://en.wikipedia.org/wiki/richard%5Fstallman), but who else :-).  And now there
are Giffy's in slack that I turn off because I hate dancing bears.
Thank-you Steve.


## MicroEmacs/mg display hacks {#microemacs-mg-display-hacks}

And then there are the [MiroEmacs](https://www.emacswiki.org/emacs/MicroEmacs) display hacks.  When the Amiga came
out Steve convinced me to buy one (it was that or the AtariST, he
had and was hacking on both).  But there was no Emacs.  Somehow
(Steve?) I became aware that the source to MicroEmacs was included
on with the disks to Mark Williams C compiler for the PC.  So I bought
the C compiler, ported the source to the Amiga (all it needed was
character I/O drivers to work in the native ANSI/VT-100 terminal)
and gave the source to Steve, who, I think, hacked/improved the
screen update logic.  I then posted the source to the USENET group
comp.sources.amiga. It took off from there (thanks to Daniel
Lawerence).  It's rumored that Linus Torvalds uses a version of the
code to this day.


## CompuServe: Groundbreaking events, great teams and amazing individuals. {#compuserve-groundbreaking-events-great-teams-and-amazing-individuals-dot}

At the recent (2019-10-19) CompuServe 50th Anniversary reunion I
was reminded of the revolutionary things that happened there: the
first commercial email, the first online banking, the first
online shopping, the first electronic news wire feed, the first
song released exclusively online (Arrowsmith 1994), online chat
(CB), OS and compiler development, VPNs (X.25 !), data over cable
in 82....and Dan Piskur inventing what we know today as much of
standard online security, incident response and "cyber"/law
enforcement collaboration, all before the Internet.

Of course it all took the efforts of many people and groups:  the
network software team (packet switching c.a. 1972, take that
DARPA), the "monitor group" (TOPS-10 OS development),
MicroComputer Software (terminal emulators forever !), large
systems software (billing et. al.), and of course the genius of
the founders (John Goltz) and the vision of Jeff Wilkins (CEO
1970-1985).

There's a lot to be said for being in the right place at the
right time, and for having a team, but many things do not happen
without the essential contributions of amazing individuals.

Thanks Steve.

<a id="orgaf0d799"></a>

{{< figure src="/ox-hugo/compuserveshirt.gif" caption="Figure 2: It all started..." >}}

[^fn:1]: Steve corrected me. There were never actually plans to write an Ada compiler. But I was unaware of the XBASIC compiler. So 3 compilers in all.
[^fn:2]: Steve informs me he was NOT pulled into the WOW project. Maybe the outcome would have been better if he had...
