1) A New Golden Age for Computer Architecture by John L. Hennessy and David A. Patterson, published 2019
    - An overview of the growth in computing in the 60s to recent times including highlights in the development of integrated circuits with CISC and x86, multi-core systems, RISC systems, and more
    - Highlights the ending of Moore's Law and Dennard Scaling and some future development areas to enable compute performance improvements
    - future opportunities discussed in Domain-Specific Languages & Architectures, Open Architecture developments, and Security at the hardware level
    - Biases towards Google TPUs and datacenters can be kept in mind as both engineer for Google and Hennessy is chairman of Alphabet Inc.
    - https://www.doc.ic.ac.uk/~wl/teachlocal/arch/papers/cacm19golden-age.pdf

2) REGISTER ALLOCATION & SPILLING VIA GRAPH COLORING by G. J. Chaitin, published 1982
    - A look into the allocation of registers and spilling using a graph coloring technique
    - Graph Coloring is the process of coloring a graph where N colors can color a graph of nodes and edges where each node can be colored and is not connected to a node with the same color, filling the whole graph
    - A dive into the process of building the interference graph, removing unnecessary register copies through coalescing (Subsumption), and handling Spilling variables to main memory by choice through cost estimate
    - A good visual representation example: https://github.com/johnflanigan/graph-coloring-via-register-allocation
    - Bias of using IBM PL/I language as this paper came out of IBM Research
    - https://web.eecs.umich.edu/~mahlke/courses/583f12/reading/chaitin82.pdf
  
3) 3D-Stacked Memory Architectures for Multi-Core Processors by Gabriel H. Loh, published 
    - This paper focuses on the improvements that can be made in 3D-DRAM Memory architecture to address the "Memory Wall" problem
    - Major terms for understanding: Miss status handling register (MSHR), Memory Controller (MC), Memory Request Queue (MRQ), 
    - The issues with L2 cache misses leading to a high latency memory access can be shortened by stacking memory on a processor to reduce access time using traces on a pcb
    - wafer to wafer bonding with through silicon vias stack dies manufactured in a typical 2D technology
    - Explores architectures creating "true" 3D DRAMs and the improvement yields of these architectures vs regular 2D and stacked 2D implementations
    - Assesses the varying combinations of increasing Ranks and memory controllers accessed from the L2 cache
    - equipment grant from Intel gives Bias to using Intel's 45nm "Penryn" model as baseline processor
    - https://courses.grainger.illinois.edu/CS598JT/fa2020/reading_list/12b.pdf
