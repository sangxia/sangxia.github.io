---
layout: page
title: $2^{(\log N)^{1/10-o(1)}}$ Hardness for Hypergraph Coloring
permalink: /pubs/hypergraph/
---

Sangxia Huang

\[[PDF]({{ site.baseurl }}{% link pubs/pdf/hypergraph.pdf %})\]

## Abstract


We show that it is quasi-NP-hard to color 2-colorable 8-uniform hypergraphs 
with $2^{(\log N)^{1/10-o(1)}}$ colors, where $N$ is the number of vertices. 
There has been much focus on hardness of hypergraph coloring recently. 
Guruswami, Håstad, Harsha, Srinivasan and Varma showed that it is 
quasi-NP-hard to color 2-colorable 8-uniform hypergraphs with 
$2^{2^{\Omega(\sqrt{\log\log N})}}$ colors. Their result is obtained by 
composing standard Label Cover with an inner-verifier based on Low Degree 
Long Code, using Reed-Muller code testing results by Dinur and Guruswami. 
Using a different approach, Khot and Saket constructed a new variant of 
Label Cover, and composed it with Quadratic Code to show quasi-NP-hardness 
of coloring 2-colorable 12-uniform hypergraphs with $2^{(\log N)^c}$ colors, 
for some $c$ around $1/20$. Their construction of Label Cover is based on a 
new notion of superposition complexity for CSP instances. The composition 
with inner-verifier was subsequently improved by Varma, giving the same 
hardness result for 8-uniform hypergraphs.

Our construction uses both Quadratic Code and Low Degree Long Code, 
and builds upon the work by Khot and Saket. We present a different approach 
to construct CSP instances with superposition hardness by observing that when 
the number of assignments is odd, satisfying a constraint in superposition 
is the same as "odd-covering" the constraint. We employ Low Degree Long 
Code in order to keep the construction efficient. In the analysis, we 
also adapt and generalize one of the key theorems by Dinur and Guruswami 
in the context of analyzing probabilistically checkable proof systems. 
