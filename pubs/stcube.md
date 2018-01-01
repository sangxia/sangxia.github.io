---
layout: page
title: Approximation Resistance on Satisfiable Instances for Predicates with Few Accepting Inputs
permalink: /pubs/stcube/
---

Sangxia Huang

\[[PDF]({{ site.baseurl }}{% link pubs/pdf/stcube.pdf %})\]
 \[[Theory of Computing](https://theoryofcomputing.org/articles/v010a014/)\]

## Abstract

For every integer $k \ge 3$, we prove that there is a predicate $P$ on
$k$ Boolean variables with $2^{\widetilde{O}(k^{1/3})}$ accepting assignments 
that is approximation resistant even on satisfiable instances. That is, 
given a satisfiable CSP instance with constraint $P$, we cannot achieve 
better approximation ratio than simply picking random assignments. 
This improves the best previously known result by Håstad and Khot where the 
predicate has $2^{O(k^{1/2})}$ accepting assignments.

Our construction is inspired by several recent developments. One is the 
idea of using direct sums to improve soundness of PCPs, developed by Chan. 
We also use techniques from Wenner to construct PCPs with perfect completeness 
without relying on the $d$-to-1 Conjecture.

