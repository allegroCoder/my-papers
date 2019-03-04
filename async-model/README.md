## Reconfigurable Asynchronous Pipelines: from Formal Models to Silicon

Accepted to Design, Automation and Test in Europe (DATE) conference, 2018.

### Abstract

*Dataflow pipelines* are widely used in the design of high-throughput computation systems. Real-life applications often require *dynamically reconfigurable pipelines* to differently process data items or adjust to the current operating mode. Reconfigurable synchronous pipelines are known since 1980s and are well supported by formal models and tools. *Reconfigurable asynchronous pipelines* on the other hand, have neither a formal behavioural model, nor mature EDA support, making them unattractive to industry. This paper presents a model and an open-source tool for the design and verification of reconfigurable asynchronous pipelines, and validates this approach in silicon.


## Prototyping Resilient Processing Cores in Workcraft

### Abstract

We present a methodology for the design and fast prototyping of processing cores with resilient microarchitecture. The resilience is achieved by equipping the core with a family of datapath components optimised for different operating modes and a flexible control structure that allows to change an instruction implementation at runtime depending on current conditions and application requirements. We use asynchronous design techniques to achieve short-term resilience, i.e. survival in extreme environmental conditions, such as near-threshold or unstable voltage supply. Long-term resilience is achieved through runtime reconfiguration of the processor microarchitecture, which is essential for safety-critical applications that cannot be taken offline for maintenance, such as biomedical implants. By using formal methods one can guarantee the correctness and uninterrupted service during such runtime reconfigurations.

The presented methodology is supported by open-source tool Workcraft, and has been validated by fabricating two ASICs: an Intel 8051 processing core and a reconfigurable dataflow accelerator. To facilitate fast prototyping of resilient processing cores, we introduce a domain-specific language for their formal specification, software-level simulation and hardware synthesis.
