---
title: Cauliflower, a Solver Generator for Context-Free Language Reachability
layout: post
---

### Abstract ###

Context-free language reachability (CFL-R) is a fundamental solving vehicle for
computing essential compiler optimisations and static program analyses.
Unfortunately, solvers for CFL- R encounter both inherently expensive problem
formulations and frequent alterations to the underlying formalism. As such,
tool designers are forced to create custom-tailored implementations with long
development times and limited reusability. A better framework is crucial to
facilitate research and development in CFL-R.

In this work we present Cauliflower, a CFL-R solver generator, that creates
parallel executable C++ code from an input CFL-R rule-based specification. With
Cauliflower, developers create working tools rapidly, avoiding lengthy and
error-prone manual implementations. Cauliflower’s domain-specific language
provides semantic extension including reversal, branch- ing, disconnection and
templating. In practical experiments, Cauliflower achieves an average speedup
of 1.8x compared with the best general purpose tools, and matches the
performance of application-specific tools on many benchmarks.

### Collaborators ###

* Nicholas Hollingum
* Bernhard Scholz 

### Links ###

* [21st International Conference on Logic for Programming, Artificial Intelligence and Reasoning](http://easychair.org/publications/paper/Cauliflower_a_Solver_Generator_for_Context-Free_Language_Reachability)

[[https://github.com/username/repository/blob/master/research/_posts/safari.jpg|alt=LPAR-21 on safari]]
