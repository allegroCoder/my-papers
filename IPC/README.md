## Process Windows

Accepted to _Application of Concurrency to System Design_ (ACSD) conference, 2017. [paper](https://github.com/allegroCoder/my-papers/blob/master/IPC/process-windows.pdf)

### Abstract

We describe a method for formally representing the
behaviour of complex processes by process windows. Each window
covers a part of the system behaviour, i.e. a part of the underlying
transition system, and is easier to understand and analyse than
the complete transition system. Process windows can overlap and
have shared states and transitions so that the complete system
behaviour is the union of window behaviours. We demonstrate
the advantage of such representations when dealing with complex
system behaviours, and discuss potential applications in circuit
design and process mining.

As a motivational example we consider the problem of covering
transition systems by marked graphs, or more generally choice-free
Petri nets. The obtained windows correspond to choice-free
behavioural scenarios of the system, wherein one window can take
over, or wake up, after another window has become inactive. The
corresponding wake-up conditions and wake-up markings can be
derived automatically.
