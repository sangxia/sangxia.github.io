---
layout: page
title: Improved NP-inapproximability for 2-variable linear equations
permalink: /pubs/2lin/
---

Johan Håstad, Sangxia Huang, Rajsekar Manokaran, Ryan O'Donnell, John Wright

\[[PDF]({{ site.baseurl }}{% link pubs/pdf/2lin.pdf %})\]
 \[[Theory of Computing](http://theoryofcomputing.org/articles/v013a019/)\]

## Abstract

An instance of the 2-Lin(2) problem is a system of equations of the form 
$x_i+x_j=b \pmod{2}$.  Given such a system in which it's possible to 
satisfy all but an $\varepsilon$ fraction of the equations, we show it 
is NP-hard to satisfy all but a $C \cdot \varepsilon$ fraction of the 
equations, for any $C < 11/8=1.375$ (and any $0 \le \varepsilon \le 1/8$). 
The previous best result, standing for over 15 years, had $5/4$ in place of 
$11/8$.  Our result provides the best known NP-hardness even for the 
Unique-Games problem, and it also holds for the special case of Max-Cut. 
The precise factor $11/8$ is unlikely to be best possible; we also give 
a conjecture concerning analysis of Boolean functions which, if true, 
would yield a larger hardness factor of $3/2$.

Our proof is by a modified gadget reduction from a pairwise-independent 
predicate. We also show an inherent limitation to this type of gadget 
reduction. In particular, any such reduction can never establish a hardness 
factor $C$ greater than $2.54$.  Previously, no such limitation on gadget 
reductions was known.  

