---
title: "DistTC: High Performance Distributed Triangle Counting"
collection: publications
permalink: /publication/2019-graphchallenge
date: 2019-09-20
venue: 'IEEE High Performance Extreme Computing (HPEC)'
paperurl: ''
citation: 'Loc Hoang, Vishwesh Jatala, Xuhao Chen, Udit Agarwal, <b>Roshan Dathathri</b>, Gurbinder Gill, Keshav Pingali, “DistTC: High Performance Distributed Triangle Counting,” Proceedings of the IEEE High Performance Extreme Computing (HPEC), September 2019.'
---
[(Download publication here)](https://www.cs.utexas.edu/~roshan/DistTC.pdf) [(Download source code here)](https://github.com/IntelligentSoftwareSystems/Galois)

### Abstract

We describe a novel multi-machine multi-GPU
implementation of triangle counting which exploits a novel
application-agnostic graph partitioning strategy that eliminates
almost all inter-host communication during triangle counting.
Experimental results show that this distributed triangle counting
implementation can handle very large graphs such as clueweb12,
which has almost one billion vertices and 37 billion edges, and
it is up to 1.6x faster than TriCore, the 2018 Graph Challenge
champion.