## Efficient Composition of Scenario-based Hardware Specifications

Accepted to _IET Computers & Digital Techniques_ journal, 2018. [paper](https://github.com/allegroCoder/my-papers/blob/master/behavioural-synthesis/scenario-composition.pdf)

### Abstract

Complex hardware systems can be designed by
breaking down their behaviour into high-level descriptions of
constituent scenarios and then composing these scenarios into
an efficient hardware implementation using a form of high-level
synthesis. There are a few existing methodologies for such
scenario-based specification and synthesis, and in this paper
we focus on highly concurrent systems, whose scenarios are
typically described using explicit concurrency models such as
partial orders.

We propose a new algorithm for composition of partial order
scenarios. Unlike previously published methods, the proposed
algorithm supports composition constraints, which allow the
designer to restrict certain aspects of the composition in order
to reuse legacy IP. Furthermore, our implementation is more
scalable and can cope with specifications comprising hundreds
of scenarios at the cost of only ~5% of area overhead compared
to optimal solutions obtained by exhaustive search.

The proposed algorithm is implemented in an open-source
EDA tool, validated on a set of benchmarks, and compared to the
state-of-the-art behavioural composition approaches and to other
existing methodologies that make use of behavioural synthesis.


## A Heuristic Algorithm for Deriving Compact Models of Processor Instruction Sets

Accepted to _Application of Concurrency to System Design_ (ACSD) conference, 2015. [paper](https://github.com/allegroCoder/my-papers/blob/master/behavioural-synthesis/ISA-design.pdf)

### Abstract

Finding a compact formal representation of a processor
instruction set is important for easier comprehension by
the designer, as well as for synthesis of an efficient hardware
implementation of the processor’s microcontroller.

We present a new heuristic algorithm for deriving compact
models of processor instruction sets. The algorithm is based on
finding similarities between pairs of instructions and assigning
similar opcodes (using a Hamming distance metric) to similar
instructions (using a newly introduced instruction similarity
metric). We demonstrate that this heuristic produces results with
an average overhead, in terms of area, of 7.8% in comparison
to the global optimum on the benchmarks we studied (subsets
of instructions of ARM Cortex M0+, Texas Instruments MSP430
and Intel 8051 processors).

The algorithm is implemented as an open-source plugin for the
Workcraft framework and is validated on a case study of a subset
of 61 (out of 68) instructions of ARM Cortex M0+ processor.
We compare the presented algorithm against a number of other
available implementations.
