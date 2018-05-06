---
layout: archive
title: "Master's Thesis"
permalink: /mastersthesis
author_profile: true
redirect_from:
  - /msthesis
---

{% include base_path %}

# Compiling for a Dataflow Runtime on Distributed-Memory Parallel Architectures

A thesis submitted for the Degree of Master of Science (Engineering) in Computer Science and Engineering, Indian Institute of Science

**Advisor:** [Dr. Uday Bondhugula](http://drona.csa.iisc.ernet.in/~uday/)

[Download thesis here](https://www.cs.utexas.edu/~roshan/Roshan_MSc_Thesis.pdf)

### Abstract

Programming for parallel architectures that do not have a shared address space
is tedious due to the need for explicit communication between memories of
different compute devices. A heterogeneous system with CPUs and multiple GPUs,
or a distributed-memory cluster are examples of such systems. Past works that
try to automate data movement for such architectures can lead to excessive
redundant communication. In addition, current de-facto parallel programming
models like MPI make it difficult to extract task-level dataflow parallelism as
opposed to bulk-synchronous parallelism. Thus, task parallel approaches that use
point-to-point synchronization between dependent tasks in conjunction with
dynamic scheduling dataflow runtimes are becoming attractive. Although good
performance can be extracted for both shared and distributed memory using these
approaches, there is very little compiler support for them. In this thesis, we
propose a fully automatic compiler-assisted runtime framework that takes
sequential code containing affine loop nests as input, extracts coarse-grained
dataflow parallelism, statically analyzes data to be communicated, and
generates the components of the dynamic scheduling dataflow runtime along with
efficient data movement code for distributed-memory architectures.

Firstly,
we describe an automatic data movement scheme that minimizes the volume of
communication between compute devices in heterogeneous and distributed-memory
systems. We show that by partitioning data dependences in a particular
non-trivial way, one can generate data movement code that results in the minimum
volume for a vast majority of cases. The techniques are applicable to any
sequence of affine loop nests and work on top of any choice of loop
transformations, parallelization, and computation placement. The data movement
code generated minimizes the volume of communication for a particular
configuration of these. We use a combination of powerful static analyses
relying on the polyhedral compiler framework and lightweight runtime routines
they generate, to build a source-to-source transformation tool that
automatically generates communication code. We demonstrate that the tool is
scalable and leads to substantial gains in efficiency. On a heterogeneous
system, the communication volume is reduced by a factor of 11× to 83× over
state-of-the-art, translating into a mean execution time speedup of 1.53×. On a
distributed-memory cluster, our scheme reduces the communication volume by a
factor of 1.4× to 63.5× over state-of-the-art, resulting in a mean speedup of
1.55×. In addition, our scheme yields a mean speedup of 2.19× over hand-
optimized Unified Parallel C (UPC) codes.

Secondly, we describe the design of
compiler-runtime interaction to automatically extract coarse-grained dataflow
parallelism in affine loop nests on both shared and distributed memory. We use
techniques from the polyhedral compiler framework to extract tasks and generate
components of the runtime which are used to dynamically schedule the generated
tasks. The runtime includes a distributed decentralized scheduler that
dynamically schedules tasks on a node. The schedulers on different nodes
cooperate with each other through asynchronous point-to-point communication of
data required to preserve program semantics – all of this is achieved
automatically by the compiler.  While running on 32 nodes with 8 threads each,
our compiler-assisted runtime yields a mean speedup of 143.6× over the
sequential version, and a mean speedup of 1.6× over the state-of-the-art
automatic parallelization approach that uses bulk-synchronous parallelism while
using our own efficient data movement scheme. We also compare our system with
past work that addresses some of these challenges on shared-memory, and an
emerging runtime (Intel Concurrent Collections) that demands higher programmer
input and effort in parallelizing. To the best of our knowledge, ours is also
the first automatic scheme that allows for dynamic scheduling of affine loop
nests on a cluster of multicores.
