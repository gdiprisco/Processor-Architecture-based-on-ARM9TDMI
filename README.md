# Processor Architecture based on ARM9TDMI
Top level design of a processor architecture based on ARM9TDMI, a 32-bit Harvard architecture with 5-stage pipeline. The main features being implemented are:
* Branch Prediction Unit
* Control Unit
* Forwarding Unit
* Hazard Unit
* Out-of-Order Execution with Re-Ordering Buffer
* 2nd level Cache for both Instructions and Data
* Virtual Memory
* Memory Management Unit


A combined use of these features allows to avoid some issues regarding performances and opens to new solutions such as Speculative Execution, Instruction-level Parallelism or in-execution Forwarding.
At this issue, only the position of the main blocks inside the pipeline and the i/o signals were established, providing detailed and thorough documentation. Deliverable D0 deadline on 03 November 2018.

Block level design of a processor architecture based on ARM9TDMI. The purpose is that of adding to the basic architecture the necessary elementary logic blocks, providing detailed and thorough documentation. Deliverable D1&D2 deadline on 15 December 2018. Deliverable D1: CPU architecture, deliverable D2: MMU architecture.

Architecture Logical Blocks implementation to describe the logical blocks implementation of some non-trivial combinatorial networks in terms of logical ports, provide an approximate account of the cost of the designed architecture and show the MMU performance, providing detailed and thorough documentation. Deliverable D3 deadline on 4 January 2019.

Main purpose of the design submitted was to keep a good trade-off among cost, complexity and performance; metrics adopted follow the idea of saving resources in absence of significant performances improvements.
