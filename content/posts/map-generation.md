---
title: "Map Generation"
date: 2018-11-01T20:21:39-04:00
draft: true
author: Joe Howarth
---

    Part 2 in Historical Simulation series


Societies and peoples cannot exist without a world...
so let's build one!

--------

When starting this project, we could either use Earth as the source of geography and climate,
or attempt to create plausible alternatives. Using Earth brings with it all the expectations
from history about what should happen where and when, even if much of history was based not
on inexorable drives, but chance. Instead we will create a fresh set of terrain for each
simulation, along with climate, biomes and basic geology.


Procedural map generation is almost limitlessly engrossing, see the fantastic work of
Martin O'Leary, Dragons Abound, Fantasy Map Generator, Polygonal Map Generation etc.
Eventually, this project aims to use a continental drift model to create a entire spherical
world, however, initially I am going to focus on the regional scale using
techniques from Martin O'Leary (LINK).
