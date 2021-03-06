---
layout: page
title: Semi-Supervised Algorithms for Approximately Optimal and Accurate Clustering
permalink: /pubs/clustering/
---

Buddhima Gamlath, Sangxia Huang, Ola Svensson

\[[PDF]({{ site.baseurl }}{% link pubs/pdf/clustering.pdf %})\]
 \[[arXiv](https://arxiv.org/pdf/1803.00926)\]

## Abstract

We study $k$-means clustering in a semi-supervised setting. Given an oracle that returns 
whether two given points belong to the same cluster in a fixed optimal clustering, we investigate 
the following question: how many oracle queries are sufficient to efficiently recover a clustering 
that, with probability at least $(1−\delta)$, simultaneously has a cost of at most $(1+\varepsilon)$ times 
the optimal cost and an accuracy of at least $(1−\varepsilon)$?

We show how to achieve such a clustering on $n$ points with $O((k^2 \log n) \cdot m(Q,\varepsilon^4,\delta/(k\log n)))$ oracle queries, 
when the $k$ clusters can be learned with an $\varepsilon'$ error and a failure probability $\delta'$ using $m(Q,\varepsilon′,\delta′)$ 
labeled samples, where $Q$ is the set of candidate cluster centers. We show that $m(Q,\varepsilon′,\delta′)$ is small both for 
$k$-means instances in Euclidean space and for those in finite metric spaces. We further show that, for the Euclidean $k$-means 
instances, we can avoid the dependency on $n$ in the query complexity at the expense of an increased dependency on $k$: specifically, 
we give a slightly more involved algorithm that uses $O(k^4/(\varepsilon^2 \delta)+(k^9/\varepsilon^4)\log(1/\delta)+k\cdot m(Q,\varepsilon^4/k,\delta))$ 
oracle queries.

Finally, we show that the number of queries required for $(1−\varepsilon)$-accuracy in Euclidean $k$-means 
must linearly depend on the dimension of the underlying Euclidean space, whereas, for finite metric space $k$-means, 
this number must at least be logarithmic in the number of candidate centers. This shows that our query complexities 
capture the right dependencies on the respective parameters. 

