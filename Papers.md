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

4) Cache-Conscious Wavefront Scheduling & CACHE-CONSCIOUS THREAD SCHEDULING FOR MASSIVELY MULTITHREADED PROCESSORS, Timothy G. Rogers, Mike O'Conner, Tor M. Aamodt, published 2012/2013
    - https://engineering.purdue.edu/tgrogers/publication/rogers-micro-2012/rogers-micro-2012.pdf
    - https://engineering.purdue.edu/tgrogers/publication/rogers-toppicks-2013/rogers-toppicks-2013.pdf
  
5) Efficient Instruction Scheduling for a Pipelined Architecture, Phillip B. Gibbons & Stephen S. Muchnick, published 1984
    - https://dl.acm.org/doi/abs/10.1145/12276.13312 (pdf available on acm)
      
6) Performance from Architecture: comaring a RISC and a CISC with Similar Hardware Organization, Dileep Bhandarkar, doublas W. Clark
    - https://dl.acm.org/doi/10.1145/106972.107003
      
7) VLSI Implementation of Early Branch Prediction Circuits for High Performance Computing, Aamir A. Farooqui, Vojin G. Oklobdzija, pub 1999
    - https://www.cecs.uci.edu/~papers/compendium94-03/papers/1999/glsvlsi99/pdffiles/glsvlsi99_030.pdf

8) Dark Silicon and the end of multicore scaling, Hadi Esmaeilzadeh, Emily Blem, Renée St. Amant, Karthikeyan Sankaralingam, Doug Burger
    - published 2014
    - 
    - https://dl.acm.org/doi/10.1145/2000064.2000108
9) Parallel Processing: A Smart Compiler and a Dumb Machine, Joseph A. Fisher, John R. Ellis, John C. Ruttenberg, and Alexandru Nicolau
    - published 1984
  
    - http://aggregate.ee.engr.uky.edu/EE685/vliwpaper.pdf
10) Investigating the Cause and Effect of an AMD Zen Energy Management Anomaly
    - published 2021
    - https://research.spec.org/icpe_proceedings/2021/companion/p103.pdf
