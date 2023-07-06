+++
title = "Projects"
+++

## Research Projects

* **[C++11] -- Spatiotemporal Join processing for Indoors Moving Objects**

In this project, we develop a distributed framework for detecting indoor contacts between two individuals and measuring the individual risk of infection for respiratory transmitted diseases (e.g., COVID-19). The framework carries out the queries locally on the individual users’ devices to protect their privacy, achieve scalability, and reduce energy consumption at their devices. Furthermore, we developed a novel in-memory structure, named (e-Racoon), that optimizes temporal aggregation joins for trajectories. The e-Racoon structure enables efficient trajectory joins with the duration of contacts cumulatively between an individual and a single other individual, while considering the exposure across other users.

* **[C++11] -- DCS: Detection of Correlated Streams**

In this project, we develop a real-time monitoring framework of large volumes of data streams that are produced at high velocity. Typically, pairs of most recently arrived data streams need to be correlated within a specified delay target in order for their analysis to lead to actionable results. We address this need by: (i) segmenting data streams into micro-batches; and (ii) leveraging incremental sliding window computation, priority scheduling, and caching techniques, to avoid unnecessary re-computations and I/O. Furthermore, we devise and evaluate exploration strategies that effectively steer the processing of data stream correlations based on the monitoring objective.

* **[Java] -- Environmentally Aware Urban Analytics**

In this project, our goal is to reduce energy consumption and reduce atmospheric pollution. To achieve that, data processing and decision-making need to be carried out at the network edge, specifically as close to the physical system as possible, where data is generated and used. This facilitates processing and generating results in real-time and make sure the data is not exposed to privacy and security risks. Thus, we leverage scheduling principles and statistical techniques in the context of two applications, namely aiming to reduce duty cycle of HVAC systems in smart homes and to mitigate road congestion in a smart cities. The first aim is approached through leveraging intelligent scheduling of the HVAC systems duty cycles in residential buildings. The second aim is achieved by introducing the concept of virtual bus lanes, that combines on demand creation of bus lanes in conjunction with dynamic control of traffic lights.

---

## Selected Course Work Projects

* **[Java] -- Distributed Systems -- Simple Remote Procedure Call System**

We implemented a client, server, and a port-mapper components of an RPC system. We addressed issues related to parameter passing, binding, exception handling, call semantics, performance and data representation. We achieved server high availability and load balancing through replication and name resolution respectively.

* **[Java] -- Distributed Systems -- MiniGoogle: Document Indexing and Querying**

We implemented a basic data-intensive application to index and search large documents. The goal is to design a simple search engine, referred to as tiny-Google, to retrieve documents relevant to simple search queries submitted by users. We did implement a replicated and reliable client/server model that consists of: the client, the server (has the indexing and querying masters), the helpers (for the mapping and reducing), and the name-server (for name resolution).


* **[JAVA] Distributed Systems and Networks -- Simplified File Transfer Protocol System**

The purpose of a file transfer protocol is to enable the transfer of files between machines, typically under the command of a user. We addressed several issues in the design including dealing with differences in file name conventions, text and data representation, and directory structure. Furthermore, the protocol ensured reliable transfer of files from one system to another. We did implement the system in a layered fashion with a replicated and load balanced servers and name-servers. Also, we did implement an error simulation module to introduce unreliability to the medium. We used the Go-Back-N as a sliding window protocol. Consequently, we did conduct a thorough analysis of the performance of the system with multiple experiments. Those involved different packet error rates, different packet drop rates, and different re-transmission timeouts.


* **[Java] -- MiniGoogle: Document Indexing and Querying**

The main objective of this project is to design and implement a basic data-intensive application to index and search large documents. More specifically, the goal is to design a simple search engine, referred to as tiny-Google, to retrieve documents relevant to simple search queries submitted by users. We did implement a replicated and reliable client/server model that consists of: the client, the server (has the indexing and querying masters), the helpers (for the mapping and reducing), and the name-server (for the name resolution).

* **[JAVA] Principles of DBMSs -- myTRC: my Transactional Row Column store DBMS**

The objective of the project is to develop a Transactional Row Column store (myTRC) that efficiently supports concurrent execution of OLTP (i.e., transactions) and OLAP (i.e., aggregate queries) workloads. myTRC provides limited transactional support. Limited support means that it does not support full durability. In addition to serializable and atomic access, it also provides the standard uncontrolled access to files.

* **[JAVA] Computer Architecture -- Simulator for a modified PowerPc 604 and 620 Architectures**

The goal was to design, implement, and evaluate the performance of a dynamically scheduled processor. Thus, we implemented the simulator using Tomasulo algorithm with out of order execution, renaming registers, and reordering buffers. Also, we did implement a dynamic branch prediction using a target buffer.

* **[JAVA] Computer Architecture -- Simulators for cache coherence protocols (MSI, MESI) in CMPs**

The goal was to build a CMP with dynamically configured cores, and each core has its own L1 private cache, and they all share a unified L2 cache. The protocols are writing back with invalidation. We implemented the simulator and evaluated the performance of each protocol.

* **[Python] Artificial Intelligence -- Checkers Solver**

In this individual project, I developed a Checkers solver engine that competed against my classmates’ engines. The engine was developed using minimax algorithm with alpha-beta pruning, and some cutoff techniques using some common heuristics, as well as some of my own developed heuristics, I was able to win the tournament of my class.
