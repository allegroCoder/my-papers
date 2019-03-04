## Language and Hardware Acceleration Backend for Graph Processing

Accepted to _Forum on Specification & Design Languages_ (FDL) conference, 2017. And as chapter of the book _Languages, Design Methods, and Tools for Electronic System Design_, Springer, 2018. [paper](https://github.com/allegroCoder/my-papers/blob/master/network-analysis/graphs-on-fpga.pdf)

### Abstract

Graphs are important in many applications however
their analysis on conventional computer architectures is generally
inefficient because it involves highly irregular access to memory
when traversing vertices and edges. As an example, when finding
a path from a source vertex to a target one the performance is
typically limited by the memory bottleneck whereas the actual
computation is trivial.

This paper presents a methodology for embedding graphs
into silicon, where graph vertices become finite state machines
communicating via the graph edges. With this approach many
common graph analysis tasks can be performed by propagating
signals through the physical graph and measuring signal
propagation time using the on-chip clock distribution network.
This eliminates the memory bottleneck and allows thousands
of vertices to be processed in parallel. We present a domain-specific
language for graph description and transformation, and
demonstrate how it can be used to translate application graphs
into an FPGA board, where they can be analysed up to 1000x
faster than on a conventional computer.

## Distributed event-based computing

Accepted to _Parellel Computing_ (PaRco) conference, 2017. And as book chapter of the book _Parallel Computing is Everywhere_, 2018. [paper](https://github.com/allegroCoder/my-papers/blob/master/network-analysis/distributed-event-based-computing.pdf)

### Abstract

As computing systems get larger in capability - a good thing - they also
get larger in ways less desirable: cost, volume, power requirements and so on.
Further, as the datastructures necessary to support large computations grow
physically, the proportion of wallclock time spent communicating increases
dramatically at the expense of the time spent calculating. This state of affairs is
currently unacceptable and will only get worse as exa-scale machines move from
the esoteric to the commonplace. As the unit cost of non-trivial cores continues to
fall, one powerful approach is to build systems that have immense numbers of
relatively small cores embedded (both geometrically and topologically) in a vast
distributed network of stored state data: take the compute to the data, rather than
the other way round. In this paper, we describe POETS - Partially Ordered Event
Triggered Systems. This is a novel kind of computing architecture, built upon the
neuromorphic concept that has inspired such machines as SpiNNaker and
BrainScaleS. The central idea is that a problem is broken down into a large set
of interacting devices, which communicate asynchronously via small, hardware
brokered packets (the arrival of which is an event). The set of devices is the task
graph. You cannot take a conventional codebase and port it to a POETS
architecture; it is necessary to strip the application back to the underlying
mathematics and reconstruct the algorithm in a manner sympathetic to the solution
capabilities of the machine. However, for the class of problems for which this
approach is suitable, POETS has already demonstrated solution speedups of a
factor of 200 over conventional techniques.
