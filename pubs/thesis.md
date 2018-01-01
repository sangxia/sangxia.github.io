---
layout: page
title: Hardness of Constraint Satisfaction and Hypergraph Coloring
permalink: /pubs/thesis/
---


# Constructions of Probabilistically Checkable Proofs with Perfect Completeness

\[[PDF]({{ site.baseurl }}{% link pubs/pdf/thesis.pdf %})\]
 \[[Errata]({{ site.baseurl }}{% link pubs/pdf/thesis-errata.pdf %})\]

## Abstract

A Probabilistically Checkable Proof (PCP) of a mathematical statement is 
a proof written in a special manner that allows for efficient probabilistic 
verification. The celebrated PCP Theorem states that for every family of 
statements in NP, there is a probabilistic verification procedure that checks 
the validity of a PCP proof by reading only 3 bits from it. This landmark 
theorem, and the works leading up to it, laid the foundation for many 
subsequent works in computational complexity theory, the most prominent 
among them being the study of inapproximability of combinatorial optimization 
problems.

This thesis focuses on a broad class of combinatorial optimization problems 
called Constraint Satisfaction Problems (CSPs). In an instance of a CSP 
problem of arity $k$, we are given a set of variables taking values from 
some finite domain, and a set of constraints each involving a subset of 
at most $k$ variables. The goal is to find an assignment that simultaneously 
satisfies as many constraints as possible. An alternative formulation of 
the goal that is commonly used is Gap-CSP, where the goal is to decide 
whether a CSP instance is satisfiable or far from satisfiable, where the 
exact meaning of being far from satisfiable varies depending on the 
problems.We first study Boolean CSPs, where the domain of the variables is 
$\\{ 0,1 \\}$. The main question we study is the hardness of distinguishing 
satisfiable Boolean CSP instances from those for which no assignment 
satisfies more than some epsilon fraction of the constraints. Intuitively, 
as the arity increases, the CSP gets more complex and thus the hardness 
parameter epsilon should decrease. We show that for Boolean CSPs of 
arity $k$, it is NP-hard to distinguish satisfiable instances from those 
that are at most $2^{\widetilde{O}\left(k^{1/3}\right)}/2^k$-satisfiable.

We also study coloring of graphs and hypergraphs. Given a graph or a 
hypergraph, a coloring is an assignment of colors to vertices, such that 
all edges or hyperedges are non-monochromatic. The gap problem is to 
distinguish instances that are colorable with a small number of colors, 
from those that require a large number of colors. For graphs, we prove 
that there exists a constant $K_0 \ge 0$, such that for any $K \ge K_0$,
it is NP-hard to distinguish $K$-colorable graphs from those that require 
$2^{\Omega\left(K^{1/3}\right)}$ colors.  For hypergraphs, we prove that 
it is quasi-NP-hard to distinguish 2-colorable 8-uniform hypergraphs of 
size $N$ from those that require $2^{(\log N)^{1/10-o(1)}}$ colors.

In terms of techniques, all these results are based on constructions of 
PCPs with perfect completeness, that is, PCPs where the probabilistic proof 
verification procedure always accepts a correct proof. Not only is this 
a very natural property for proofs, but it can also be an essential 
requirement in many applications. It has always been particularly 
challenging to construct PCPs with perfect completeness for NP statements 
due to limitations in techniques. Our improved hardness results build on 
and extend many of the current approaches. Our Boolean CSP result and 
GraphColoring result were proved by adapting the Direct Sum of PCPs idea 
by Siu On Chan to the perfect completeness setting. Our proof for 
hypergraph coloring hardness improves and simplifies the recent work by 
Khot and Saket, in which they proposed the notion of superposition 
complexity of CSPs.

*Abstract in Swedish available on 
[KTH publication database DiVA](http://kth.diva-portal.org/smash/record.jsf?pid=diva2%3A817263&amp;dswid=-2167)*
