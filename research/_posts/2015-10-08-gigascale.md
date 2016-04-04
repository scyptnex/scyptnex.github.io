---
title: Giga-Scale Exhaustive Points-To Analysis for Java in Under a Minute
layout: post
---

### Abstract ###

Computing a precise points-to analysis for very large Java programs remains
challenging despite the large body of research on points-to analysis. Any
approach must solve an underlying dynamic graph reachability problem, for which
the best algorithms have near-cubic worst-case runtime complexity, and, hence,
previous work does not scale to programs with millions of lines of code. In
this work, we present a novel approach for solving the field-sensitive
points-to problem for Java with the means of (1) a transitive-closure
data-structure, and (2) a pre-computed set of potentially matching load/store
pairs to accelerate the fix-point calculation. Experimentation on Java
benchmarks validates the superior performance of our approach over the standard
context-free language reachability implementations. Our approach computes a
points-to index for the OpenJDK with over 1.5 billion tuples in under a minute.

### Collaborators ###

* Jens Deitrich (Massey Univ.)
* Nicholas Hollingum
* Bernhard Scholz (Oracle inc.)

### Links ###

* [2015 Object-Oriented Programming, Systems, Languages, and Applications](https://dx.doi.org/10.1145/2858965.2814307)
