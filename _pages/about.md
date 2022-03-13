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

I lead the Graph Engine team in [Katana Graph](https://katanagraph.com/),
the startup based in part on my PhD research.
The startup was founded in 2020 by
[Dr. Keshav Pingali](https://www.cs.utexas.edu/~pingali/) and
[Dr. Chris Rossbach](https://www.cs.utexas.edu/~rossbach/).
We are looking for motivated engineers. Please look at the
[careers](https://katanagraph.com/company/careers) page and
apply directly if you are interested.

I received my PhD from the [University of Texas at Austin](https://www.cs.utexas.edu/),
where I was advised by [Dr. Keshav Pingali](https://www.cs.utexas.edu/~pingali/).
I received my masters from the
[Indian Institute of Science](http://www.csa.iisc.ac.in/), where I was advised by
[Dr. Uday Bondhugula](http://drona.csa.iisc.ernet.in/~uday/).

During the summer of 2018 and 2019, I was a research intern in
[Microsoft Research](https://www.microsoft.com/en-us/research/group/research-in-software-engineering-rise/),
where I collaborated with several researchers including
[Dr. Olli Saarikivi](https://www.microsoft.com/en-us/research/people/olsaarik/),
[Dr. Kim Laine](https://www.microsoft.com/en-us/research/people/kilai/), and
[Dr. Madan Musuvathi](https://www.microsoft.com/en-us/research/people/madanm/).

# Research Interests

My research interests are broadly in the field of
**programming languages and systems**,
with an emphasis on optimizing compilers and runtime systems for
*distributed* and *heterogeneous* architectures.
Currently, my focus is on building
large-scale graph databases and systems for machine learning. In recent work,
I have built programming languages, compilers, and runtime systems for
**distributed, heterogeneous graph processing** and
**privacy-preserving neural network inferencing**.
This work has been published in PLDI, ASPLOS, VLDB, IPDPS, PPoPP, PACT, and IISWC.
A brief summary of my past work can be found below.
<!-- My goal is to build domain-specific
**programming languages, compilers, and runtime systems**
that make it easy to develop efficient
**graph processing**
on large-scale *distributed* clusters,
while utilizing *heterogeneous* architectures.
<!-- Towards this goal,
I have built programming systems for
*distributed and heterogeneous graph analytics*
and
*privacy-preserving neural network inferencing*.
My vision is to enable
developers to express their application
in a domain-specific language
and run it efficiently on a variety of architectures
under different scenarios like sparsity or privacy of the datasets. -->
<!-- and
introduces new techniques in programming systems
for sparse computing and privacy-preserving applications respectively.  -->

<!-- Existing computers have complex parallel architectures including
heterogeneous processors like CPUs and GPUs, non-uniform memory, and
non-volatile memory.
It is tedious for application developers to get good performance
without utilizing the architectural features.
Existing programs come from diverse application domains and are written
by experts in those domains, rather than experts in parallel programming.
It is also difficult to get good performance unless
the domain expertise is exploited.
I aim to bridge the gap between application domain experts and
parallel architectures
by working on *programming models, compilers, and
runtimes that enable application developers to extract performance
from parallel architectures with little effort*.  -->

**Distributed and Heterogeneous Graph Processing**:
Unstructured datasets are used by applications in areas such as
machine learning,
data mining, bioinformatics, network science, and security.
These datasets may be represented as graphs and these graphs may have
billions of nodes and trillions of edges.
One way to process such large datasets is to use distributed clusters.
For graph analytical applications, I have designed and built
programming systems that exploit domain knowledge to partition graphs
and optimize communication,
while providing application-specific fault-tolerance.
Existing shared-memory graph analytics frameworks or applications
can use our system to scale out to distributed CPUs and GPUs.
[[PLDI 2018](https://roshandathathri.github.io/publication/2018-pldi),
[ASPLOS 2019](https://roshandathathri.github.io/publication/2019-asplos),
[VLDB 2018](https://roshandathathri.github.io/publication/2018-vldb),
[PPoPP 2019](https://roshandathathri.github.io/publication/2019-ppopp),
[PACT 2019](https://roshandathathri.github.io/publication/2019-pact),
[IPDPS 2021](https://roshandathathri.github.io/publication/2021-ipdps),
[IPDPS 2020](https://roshandathathri.github.io/publication/2020-ipdps),
[IPDPS 2019](https://roshandathathri.github.io/publication/2019-ipdps),
[IPDPS 2018](https://roshandathathri.github.io/publication/2018-ipdps),
[Euro-Par 2018](https://roshandathathri.github.io/publication/2018-europar),
[HPEC GraphChallenge 2019](https://roshandathathri.github.io/publication/2019-graphchallenge),
[BigData 2017](https://roshandathathri.github.io/publication/2017-bigdata)]
<!-- I intend to build on this to support
*distributed and heterogeneous systems for sparse computation
like graph databases, graph mining, graph embeddings,
sparse deep learning, and mesh-based numerical simulation*. -->

**Single Machine Graph Processing**:
Graph pattern mining applications are used in chemical engineering,
bioinformatics, and social sciences. I have worked on building a
high-level programming language and runtime system that can execute
such applications on shared-memory CPUs or a GPU. For graph analytical
applications, I have worked on improving the performance of graph
analytics systems on byte-addressable memory like Intel Optane DC Persistent Memory.
I have also compared different language abstractions and
runtime systems for graph analytics on shared-memory CPUs, and
identified their performance bottlenecks.
[[VLDB 2020](https://roshandathathri.github.io/publication/2020-vldb-1),
[VLDB 2020](https://roshandathathri.github.io/publication/2020-vldb-2),
[ICS 2021](https://dl.acm.org/doi/10.1145/3447818.3460359),
[IISWC 2020](https://roshandathathri.github.io/publication/2020-iiswc-1),
[IISWC 2020](https://roshandathathri.github.io/publication/2020-iiswc-2)]

**Privacy-Preserving Neural Network Inferencing**:
In many applications, privacy of the datasets used must be preserved.
Fully-Homomorphic Encryption (FHE) enables computation on encrypted data
without requiring the secret key.
However, cryptographic domain expertise is required to use FHE.
In my view, FHE libraries are akin to specialized parallel architectures.
I have developed an optimizing compiler for
translating tensor programs like neural network inferencing
to run on encrypted data using FHE libraries
efficiently, while guaranteeing security and accuracy
of the computation.
[[PLDI 2020](https://roshandathathri.github.io/publication/2020-pldi),
[PLDI 2019](https://roshandathathri.github.io/publication/2019-pldi)]
<!-- Building on this, I intend to help program *privacy-preserving
applications including large-scale data analytics and databases*. -->

<!-- **Threat Detection Using Graph Querying**: In this project supported by DARPA, property
graphs with attributes are built from event logs on machines. Advanced Persistent
Threats (APT) on these machines are detected by querying the property graphs for
specific patterns. I have designed a compiler for running these queries efficiently
so that APTs can be detected in real-time. -->

**Affine Loop Nests**:
Any sequence of arbitrarily nested loops with affine bounds and accesses
are known as regular or affine loop nests.
Examples include
stencil-style computations, linear algebra kernels,
and alternating direction implicit integrations.
During my masters, I developed compiler techniques using the polyhedral model
to automatically extract tasks from sequential affine loop nests and
dynamically schedule them to run on distributed CPUs and
GPUs with efficient data movement code.
I also helped generate distributed-memory code for loop nests
that contain both affine and irregular accesses.
[[PACT 2013](https://roshandathathri.github.io/publication/2013-pact),
[PPoPP 2015](https://roshandathathri.github.io/publication/2015-ppopp),
[TOPC 2016](https://roshandathathri.github.io/publication/2016-topc)]

# News

* I'm serving on the Program Committee for **IPDPS 2022**.
* Our [Sandslash: A Two-Level Framework for Efficient Graph Pattern Mining](https://dl.acm.org/doi/10.1145/3447818.3460359) paper was accepted to **ICS 2021**.
* Our [GraphAny2Vec Distributed Training of Embeddings using Gluon](https://roshandathathri.github.io/publication/2021-ipdps) paper was accepted to **IPDPS 2021**.
* I'm serving on the Program Committee for **IPDPS 2021**.
* Our study on [Matrix-based vs. Graph-based APIs](https://roshandathathri.github.io/publication/2020-iiswc-2) was accepted to **IISWC 2020**.
* Our study on [Performance of Graph Analytics Frameworks](https://roshandathathri.github.io/publication/2020-iiswc-1) was accepted to **IISWC 2020**.
* I'm serving on the External Review Committee for **ASPLOS 2021**.
* Our paper on [Encrypted Vector Arithmetic (EVA) Language and Compiler for Homomorphic Computation](https://roshandathathri.github.io/publication/2020-pldi) was accepted to **PLDI 2020**.
* Our paper on analyzing massive graph datasets using [Intel Optance DC Persistent Memory](https://roshandathathri.github.io/publication/2020-vldb-2) was accepted to **PVLDB 13(8) 2020** (Read about our work in the [SIGARCH blog](https://www.sigarch.org/using-intel-optane-dc-persistent-memory-for-in-memory-graph-analytics/)).
* Our paper on [Pangolin Graph Pattern Mining](https://roshandathathri.github.io/publication/2020-vldb-1) framework on a CPU or GPU was accepted to **PVLDB 13(8) 2020** (Read about our work in the [UTCS blog](https://www.cs.utexas.edu/news/2020/pangolin-efficient-and-flexible-graph-mining-system-cpu-and-gpu)).
* Our work on [GraphAny2Vec Distributed Training of Embeddings using Gluon](http://arxiv.org/abs/1909.03359) is now on arxiv.
* Our [Graph Analytics on Distributed GPUs](https://roshandathathri.github.io/publication/2020-ipdps) paper was accepted to **IPDPS 2020**.
* Our work on an [Adaptive Load Balancer on GPUs](https://arxiv.org/abs/1911.09135) is now on arxiv.
* Our paper on [Distributed Triangle Counting on GPUs (DistTC)](https://roshandathathri.github.io/publication/2019-graphchallenge) was accepted to **IEEE HPEC GraphChallenge 2019** and it won the **Student Innovation Award**.
* Our paper on [Bulk-Asynchronous Gluon system](https://roshandathathri.github.io/publication/2019-pact) for distributed and heterogeneous graph analytics was accepted to **PACT 2019** and was **Nominated for Best Paper**.
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
