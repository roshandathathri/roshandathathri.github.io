---
permalink: /
title: "Homepage"
excerpt: "Homepage"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
  - /~roshan/
---

I am a Ph.D. student working with [Dr. Keshav Pingali](https://www.cs.utexas.edu/~pingali/) 
in the [Intelligent Software Systems Lab](http://iss.ices.utexas.edu/) at the 
[University of Texas at Austin](https://www.cs.utexas.edu/). I received my masters from the 
[Indian Institute of Science](http://www.csa.iisc.ac.in/), where I worked with 
[Dr. Uday Bondhugula](http://drona.csa.iisc.ernet.in/~uday/).

During the summer of 2018 and 2019, I was a research intern in 
[Microsoft Research](https://www.microsoft.com/en-us/research/group/research-in-software-engineering-rise/), 
where I collaborated with several researchers including 
[Dr. Olli Saarikivi](https://www.microsoft.com/en-us/research/people/olsaarik/), 
[Dr. Kim Laine](https://www.microsoft.com/en-us/research/people/kilai/), and 
[Dr. Madan Musuvathi](https://www.microsoft.com/en-us/research/people/madanm/).

# Research interests

I am broadly interested in improving the performance of parallel and distributed programs. 
I work on designing and building programming models, compilers, and runtime systems that 
enable programmers to extract performance from parallel architectures like clusters of CPUs and GPUs. 

**Distributed Graph Analytics**: For graph analytical applications, I have designed 
programming substrates and developed runtime systems that exploit domain knowledge to 
partition graphs, optimize communication, and scale-out to distributed CPUs and GPUs, 
while providing fault-tolerance. 
[[PLDI 2018](https://roshandathathri.github.io/publication/2018-pldi), 
[ASPLOS 2019](https://roshandathathri.github.io/publication/2019-asplos), 
[VLDB 2018](https://roshandathathri.github.io/publication/2018-vldb), 
[PPoPP 2019](https://roshandathathri.github.io/publication/2019-ppopp), 
[PACT 2019](https://roshandathathri.github.io/publication/2019-pact), 
[IPDPS 2019](https://roshandathathri.github.io/publication/2019-ipdps), 
[IPDPS 2018](https://roshandathathri.github.io/publication/2018-ipdps), 
[Euro-Par 2018](https://roshandathathri.github.io/publication/2018-europar), 
[BigData 2017](https://roshandathathri.github.io/publication/2017-bigdata)]

**Privacy-Preserving Computation Using Homomorphic Encryption**: I have designed and 
developed an optimizing compiler for translating tensor programs like neural-network 
inferencing to run on encrypted data using Fully Homomorphic Encryption (FHE) libraries 
efficiently, while guaranteeing security and accuracy of the computation. 
[[PLDI 2019](https://roshandathathri.github.io/publication/2019-pldi)]

**Threat Detection Using Graph Querying**: In this project supported by DARPA, property 
graphs with attributes are built from event logs on machines. Advanced Persistent 
Threats (APT) on these machines are detected by querying the property graphs for 
specific patterns. I have designed a compiler for running these queries efficiently 
so that APTs can be detected in real-time.

**Affine Loop Nests**: In the past, I have developed compiler techniques using the 
polyhedral model to automatically extract tasks from sequential affine loop nests and 
dynamically schedule them to run on distributed CPUs and GPUs with efficient data 
movement code. 
[[PACT 2013](https://roshandathathri.github.io/publication/2013-pact), 
[PPoPP 2015](https://roshandathathri.github.io/publication/2015-ppopp), 
[TOPC 2016](https://roshandathathri.github.io/publication/2016-topc)]

# News

* Our paper on [Distributed Triangle Counting on GPUs (DistTC)](https://roshandathathri.github.io/publication/2019-graphchallenge) was accepted to **IEEE HPEC GraphChallenge 2019** and it won the **Student Innovation Award**.
* Our paper on [Bulk-Asynchronous Gluon system](https://roshandathathri.github.io/publication/2019-pact) for distributed and heterogeneous graph analytics was accepted to **PACT 2019** and was **Nominated for Best Paper**.
* Our work on analyzing massive graph datasets using [Intel Optance DC Persistent Memory](https://arxiv.org/abs/1904.07162) is now on arxiv (Read about our work in the [SIGARCH blog](https://www.sigarch.org/using-intel-optane-dc-persistent-memory-for-in-memory-graph-analytics/)).
* I presented our [Gluon substrate](https://roshandathathri.github.io/publication/2018-pldi) work at a mini-symposium in **SIAM CSE 2019**.
* Our [Compiler for Fully-Homomorphic Neural-Network Inferencing (CHET)](https://roshandathathri.github.io/publication/2019-pldi) was accepted to **PLDI 2019**.
* Our [Customizable Streaming Edge Partitioner (CuSP)](https://roshandathathri.github.io/publication/2019-ipdps) paper was accepted to **IPDPS 2019**.
* Our [Partitioning Policies](https://roshandathathri.github.io/publication/2018-vldb) paper was accepted to **PVLDB 12(4) 2018**.
* Our [Min-Rounds Betweenness Centrality (MRBC)](https://roshandathathri.github.io/publication/2019-ppopp) paper was accepted to **PPoPP 2019** (Read about our work in the [R&D magazine article](https://www.rdmag.com/article/2019/04/determining-importance-connections-unstructured-data)).
* Our [Phoenix resilience](https://roshandathathri.github.io/publication/2019-asplos) paper was accepted to **ASPLOS 2019**.
* My "Partitioning Policies for Distributed Graph Analytics" poster won **IPDPS 2018** Outstanding Poster Presentation Award, 3rd Place.
* Our [Abelian compiler](https://roshandathathri.github.io/publication/2018-europar) paper was accepted to **EuroPar 2018**.
* Our [Gluon substrate](https://roshandathathri.github.io/publication/2018-pldi) paper was accepted to **PLDI 2018**.
* Our [Light-weight Communication Interface (LCI)](https://roshandathathri.github.io/publication/2018-ipdps) paper was accepted to **IPDPS 2018**.
