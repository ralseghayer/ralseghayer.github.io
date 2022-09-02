+++
title = "Projects"
+++

## Research Projects

* **Spatiotemporal Join processing for Indoors Moving Objects**

Contact tracing (CT) is a category of analytics that monitors whether two objects have come to close distance of (i.e., intersects with) each other for a certain period of time. Spatiotemporal join operator is essential to such analytics, where two sets of data streams are being checked for intersection in spatial and/or temporal dimension in real-time for trajectory data. 

The nature of the aforementioned analytics category and its application require processing of huge number of users’ trajectories. This poses a computational challenge as well as a a privacy concern, since the trajectory data of users need to be collected and co-located for contact tracing processing. 

This work approaches the above problem by devising efficient processing schemes of such spatiotemporal joins in an energy consumption aware approach due to the typical battery restrictions of mobile devices, while protecting users' privacy.

* **DCS: Detection of Correlated Streams**

The DCS framework detects correlations in pairs of data streams and timeseries by employing caching concepts, scheduling techniques, and enforcing policies to navigate the exploration task space efficiently.

On-line analytics processing (OLAP) tasks are vital for the field of data processing due to the increasing demand for real-time analysis of large volumes of timeseries or data streams that are produced at high velocity. Data analytics help data scientists in their daily tasks, where they need tools to search for and detect patterns and relationships in the vast data they explore.

An important indicator for finding such patterns is to find the correlation between pairs of timeseries or data streams. The correlation can be used to finding similarity (or dissimilarity) measures, running threshold queries, or reducing the size of the data, yet, preserving some of its characteristics.

In this research, we try to optimize the task of detecting correlation between data streams and timeseries. We do this through employing scheduling techniques, such that the exploration task is more efficient and more insightful. The three angles of this research are the use of (1) incremental sliding-window computation of aggregates, to avoid unnecessary re-computations, (2) intelligent scheduling of computation steps and operations, driven by a utility function, and (3) an exploration policy that tunes the utility function based on some observed data insights.

* **Environmentally Aware Urban Analytics**

IoT has been enabling solutions for problems in the connected environment that is surrounding us (i.e., smart homes and smart cities), but only recently, the use of sensors and IoT has been proposed to address issues related to energy efficiency. In this project, we aim at reducing energy consumption and reducing atmospheric pollution. To achieve that, data processing and decision-making need to be carried out at the network edge, specifically as close to the physical system as possible, where data is generated and used. This facilitates processing and generating results in real-time and make sure the data is not exposed to privacy and security risks. In this project, we leverage scheduling principles and statistical techniques in the context of two applications, namely aiming to reduce duty cycle of HVAC systems in smart homes and to mitigate road congestion in a smart cities. The first aim is approached through leveraging intelligent scheduling of the HVAC systems duty cycles in residential buildings. The second aim is achieved by introducing the concept of virtual bus lanes, that combines on demand creation of bus lanes in conjunction with dynamic control of traffic lights.

---

## Course Work Projects

* **Simulator for a modified PowerPc 604 and 620 Architectures**

 The goal was to design, implement, and evaluate the performance of a dynamically scheduled processor. Thus, we implemented the simulator using Tomasulo algorithm with renaming registers and reordering buffers. Also, we did implement a dynamic branch prediction using a target buffer.

* **Simulators for cache coherence protocols (MSI, MESI) in CMPs**

The goal was to build a CMP with dynamically configured cores, and each core has its own L1 private cache, and they all share a unified L2 cache. The protocols are writing back with invalidation. We implemented the simulator and evaluated the performance of each protocol. 

* **Simple Remote Procedure Call System**

In this project, we were asked to design, implement, and evaluate the performance of a sRPC system. We implemented a client, server, and a port-mapper. We addressed issues related to parameter passing, binding, exception handling, call semantics, performance and data representation. We achieved server high availability and load balancing through replication and name resolution respectively. 

* **MiniGoogle: Document Indexing and Querying**

The main objective of this project is to design and implement a basic data-intensive application to index and search large documents. More specifically, the goal is to design a simple search engine, referred to as tiny-Google, to retrieve documents relevant to simple search queries submitted by users. We did implement a replicated and reliable client/server model that consists of: the client, the server (has the indexing and querying masters), the helpers (for the mapping and reducing), and the name-server (for the name resolution).

* **Simplified File Transfer Protocol System**

The purpose of a file transfer protocol is to enable the transfer of files between machines, typically under the command of a user. Several issues need to be addressed in the design of a file transfer protocol, including dealing with differences in file name conventions, text and data representation, and directory structure. Furthermore, the protocol must ensure reliable transfer of files from one system to another. We did implement the system in a layered fashion with a replicated and load balanced servers and name-servers. Also, we did implement an error simulation module to introduce unreliability to the medium. We used the Go-Back-N as a sliding window protocol. Consequently, we did conduct a thorough analysis of the performance of the system with multiple experiments. Those involved different packet error rates, different packet drop rates, and different retransmission timeouts. 

* **myTRC: my Transactional Row Column store DBMS**

The objective of the project is to develop the Transactional Row Column store myTRC that efficiently supports concurrent execution of OLTP (i.e., transactions) and OLAP (i.e., aggregate queries) workloads. myTRC provides limited transactional support. Limited support means that it does not support full durability. In addition to serializable and atomic access, it also provides the standard uncontrolled access to files.

* **Checkers Solver**

Developed a Checkers solver model that competed against my classmates’ engines. The engine was developed using minimax algorithm with alpha beta pruning, and some cutoff techniques using some common heuristics, as well as some of my own developed heuristics, I was able to win the tournament of my class. 

* **PASTRI: PAirwise STream CoRrelation Identifier (only Time series no data streams)**

Developed a system that aims at finding accurate results of correlations between pairs of time series in real-time. By doing this, we minimize the time to the first produced results - i.e. achieve interactive response of the system and keeps refining the results, while the user is busy, exploring a subset of the provided results. Our approach modeled the length of each time series, which is of interest, and used a utility cost function, to identify the highly correlated streams. Our experiments show a speedup of 10 times producing the first results, compared to other systems. 