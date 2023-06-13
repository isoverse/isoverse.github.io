---
title: isotopia
layout: default
weight: 6
repo: isotopia
binder:
---

Stable isotope biogeochemistry uses a number of different representations of isotopic information and processes (ratios, abundances, delta values, alpha values, epsilon values, fractionation factors, reference frame shifts, mass balance calculations, mass-independent effects, etc., etc.) that are constantly being converted back and forth and used for different kinds of isotope arithmetic. Very frequently, the tangle of keeping track of this information and how all the calculations are done properly makes code very hard to read and prone to small mistakes that can make an enormous difference. The [**isotopia**](http://isotopia.isoverse.org/) package helps with this type of isotope math by defining elemental isotopic data classes (`ratio`, `abundance`, `delta`, `fractionation_factor` and `intensity`) so that it can automatically keep track of what is a ratio, what is a delta value (and is it in permil notation or in ppm), etc., and implement a variety of safe guards to perform isotope arithmetic correctly.
