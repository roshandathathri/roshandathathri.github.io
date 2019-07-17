---
title: "Abelian: A Compiler for Graph Analytics on Distributed, Heterogeneous Platforms"
collection: publications
permalink: /publication/2018-europar
date: 2018-08-01
venue: 'International European Conference on Parallel and Distributed Computing (Euro-Par)'
paperurl: 'https://link.springer.com/chapter/10.1007/978-3-319-96983-1_18'
citation: 'Gurbinder Gill, <b>Roshan Dathathri</b>, Loc Hoang, Andrew Lenharth, Keshav Pingali, “Abelian: A Compiler for Graph Analytics on Distributed, Heterogeneous Platforms,” Proceedings of the 24th International European Conference on Parallel and Distributed Computing (Euro-Par), August 2018.'
---
[(Download publication here)](https://www.cs.utexas.edu/~roshan/Abelian.pdf) [(Download slides here)](https://www.cs.utexas.edu/~roshan/Abelian.pptx)

### Abstract

The trend towards processor heterogeneity and distributed-memory has significantly increased the complexity of parallel programming. In addition, the mix of applications that need to run on parallel platforms today is very diverse, and includes graph applications that typically have irregular memory accesses and unpredictable control-flow. To simplify the programming of graph applications on such platforms, we have implemented a compiler called Abelian that translates shared-memory descriptions of graph algorithms written in the Galois programming model into efficient code for distributed-memory platforms with heterogeneous processors. The compiler manages inter-device synchronization and communication while leveraging state-of-the-art compilers for generating device-specific code. The experimental results show that the novel communication optimizations in the Abelian compiler reduce the volume of communication by 23x, enabling the code produced by Abelian to match the performance of handwritten distributed CPU and GPU programs that use the same runtime. The programs produced by Abelian for distributed CPUs are roughly 2.4x faster than those in the Gemini system, a third-party distributed CPU-only system, demonstrating that Abelian can manage heterogeneity and distributed-memory successfully while generating high-performance code.

