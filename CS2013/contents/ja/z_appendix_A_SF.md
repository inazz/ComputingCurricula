
# システム基礎 (SF)

The underlying hardware and software infrastructure upon which applications are constructed is
collectively described by the term "computer systems." Computer systems broadly span the subdisciplines of operating systems, parallel and distributed systems, communications networks, and
computer architecture. Traditionally, these areas are taught in a non-integrated way through
independent courses. However these sub-disciplines increasingly share important common
fundamental concepts within their respective cores. These concepts include computational
paradigms, parallelism, cross-layer communications, state and state transition, resource
allocation and scheduling, and so on. The Systems Fundamentals Knowledge Area is designed
to present an integrative view of these fundamental concepts in a unified albeit simplified
fashion, providing a common foundation for the different specialized mechanisms and policies
appropriate to the particular domain area.


**SF. システム基礎 [必修 18時間, 選択必修 9時間]**

| 知識単位 | 必修時間 | 選択必修時間 | 含選択科目 |
| -------- | -------- | ------------ | ---------- |
| SF/計算パラダイム                   | 3 |   | N |
| SF/レイヤ間通信                     | 3 |   | N |
| SF/状態と状態機械                   | 6 |   | N |
| SF/並列処理                         | 3 |   | N |
| SF/性能評価                         | 3 |   | N |
| SF/リソース割当てとスケジューリング |   | 2 | N |
| SF/近接と性能向上                   |   | 3 | N |
| SF/仮想化と分離                     |   | 2 | N |
| SF/冗長化による信頼性向上           |   | 2 | N |
| SF/定量的評価                       |   |   | Y |



## SF/計算パラダイム
*[必修 3時間]*

The view presented here is the multiple representations of a system across layers, from hardware
building blocks to application components, and the parallelism available in each representation.
Cross-reference PD/Parallelism Fundamentals. 


**トピック:**

* Basic building blocks and components of a computer (gates, flip-flops, registers, interconnections;
Datapath + Control + Memory)
* Hardware as a computational paradigm: Fundamental logic building blocks; Logic expressions,
minimization, sum of product forms
* Application-level sequential processing: single thread
* Simple application-level parallel processing: request level (web services/client-server/distributed), single
thread per server, multiple threads with multiple servers
* Basic concept of pipelining, overlapped processing stages
* Basic concept of scaling: going faster vs. handling larger problems

**学習到達目標:**

1. List commonly encountered patterns of how computations are organized. [Familiarity]
2. Describe the basic building blocks of computers and their role in the historical development of computer
architecture. [Familiarity]
3. Articulate the differences between single thread vs. multiple thread, single server vs. multiple server
models, motivated by real world examples (e.g., cooking recipes, lines for multiple teller machines and
couples shopping for food). [Familiarity]
4. Articulate the concept of strong vs. weak scaling, i.e., how performance is affected by scale of problem vs.
scale of resources to solve the problem. This can be motivated by the simple, real-world examples.
[Familiarity]
5. Design a simple logic circuit using the fundamental building blocks of logic design. [Usage]
6. Use tools for capture, synthesis, and simulation to evaluate a logic design. [Usage]
7. Write a simple sequential problem and a simple parallel version of the same program. [Usage]
8. Evaluate performance of simple sequential and parallel versions of a program with different problem sizes,
and be able to describe the speed-ups achieved. [Assessment]



## SF/レイヤ間通信
*[必修 3時間]*

Cross-reference NC/Introduction, OS/Operating Systems Principles

**トピック:**

* Programming abstractions, interfaces, use of libraries
* Distinction between Application and OS services, Remote Procedure Call
* Application-Virtual Machine Interaction
* Reliability

**学習到達目標:**

1. Describe how computing systems are constructed of layers upon layers, based on separation of concerns,
with well-defined interfaces, hiding details of low layers from the higher layers. [Familiarity]
2. Describe how hardware, VM, OS, and applications are additional layers of interpretation/processing.
[Familiarity]
3. Describe the mechanisms of how errors are detected, signaled back, and handled through the layers.
[Familiarity]
4. Construct a simple program using methods of layering, error detection and recovery, and reflection of error
status across layers. [Usage]
5. Find bugs in a layered program by using tools for program tracing, single stepping, and debugging. [Usage]


## SF/状態と状態機械
*[必修 6時間]*

Cross-reference AL/Basic Computability and Complexity, OS/State and State Diagrams,
NC/Protocols

**トピック:**

* Digital vs. Analog/Discrete vs. Continuous Systems
* Simple logic gates, logical expressions, Boolean logic simplification
* Clocks, State, Sequencing
* Combinational Logic, Sequential Logic, Registers, Memories
* Computers and Network Protocols as examples of state machines

**学習到達目標:**

1. Describe computations as a system characyterized by a known set of configurations with transitions from
one unique configuration (state) to another (state). [Familiarity]
2. Describe the distinction between systems whose output is only a function of their input (Combinational)
and those with memory/history (Sequential). [Familiarity]
3. Describe a computer as a state machine that interprets machine instructions. [Familiarity]
4. Explain how a program or network protocol can also be expressed as a state machine, and that alternative
representations for the same computation can exist. [Familiarity]
5. Develop state machine descriptions for simple problem statement solutions (e.g., traffic light sequencing,
pattern recognizers). [Usage]
6. Derive time-series behavior of a state machine from its state machine representation. [Assessment]



## SF/並列処理
*[必修 3時間]*

Cross-reference PD/Parallelism Fundamentals.

**トピック:**

* Sequential vs. parallel processing
* Parallel programming vs. concurrent programming
* Request parallelism vs. Task parallelism
* Client-Server/Web Services, Thread (Fork-Join), Pipelining
* Multicore architectures and hardware support for synchronization

**学習到達目標:**

1. For a given program, distinguish between its sequential and parallel execution, and the performance
implications thereof. [Familiarity]
2. Demonstrate on an execution time line that parallelism events and operations can take place simultaneously
(i.e., at the same time). Explain how work can be performed in less elapsed time if this can be exploited.
[Familiarity]
3. Explain other uses of parallelism, such as for reliability/redundancy of execution. [Familiarity]
4. Define the differences between the concepts of Instruction Parallelism, Data Parallelism, Thread
Parallelism/Multitasking, Task/Request Parallelism. [Familiarity]
5. Write more than one parallel program (e.g., one simple parallel program in more than one parallel
programming paradigm; a simple parallel program that manages shared resources through synchronization
primitives; a simple parallel program that performs simultaneous operation on partitioned data through task
parallel (e.g., parallel search terms; a simple parallel program that performs step-by-step pipeline
processing through message passing). [Usage]
6. Use performance tools to measure speed-up achieved by parallel programs in terms of both problem size
and number of resources. [Assessment]



## SF/性能評価
*[必修 3時間]*

Cross-reference PD/Parallel Performance.

**トピック:**

* Performance figures of merit
* Workloads and representative benchmarks, and methods of collecting and analyzing performance figures of
merit
* CPI (Cycles per Instruction) equation as tool for understanding tradeoffs in the design of instruction sets,
processor pipelines, and memory system organizations.
* Amdahl’s Law: the part of the computation that cannot be sped up limits the effect of the parts that can

**学習到達目標:**

1. Explain how the components of system architecture contribute to improving its performance. [Familiarity]
2. Describe Amdahl’s law and discuss its limitations. [Familiarity]
3. Design and conduct a performance-oriented experiment. [Usage]
4. Use software tools to profile and measure program performance. [Assessment]



## SF/リソース割当てとスケジューリング
*[選択必修 2時間]*

**トピック:**

* Kinds of resources (e.g., processor share, memory, disk, net bandwidth)
* Kinds of scheduling (e.g., first-come, priority)
* Advantages of fair scheduling, preemptive scheduling

**学習到達目標:**

1. Define how finite computer resources (e.g., processor share, memory, storage and network bandwidth) are
managed by their careful allocation to existing entities. [Familiarity]
2. Describe the scheduling algorithms by which resources are allocated to competing entities, and the figures
of merit by which these algorithms are evaluated, such as fairness. [Familiarity]
3. Implement simple schedule algorithms. [Usage]
4. Use figures of merit of alternative scheduler implementations. [Assessment]



## SF/近接と性能向上
*[選択必修 3時間]*

Cross-reference AR/Memory Management, OS/Virtual Memory

**トピック:**

* Speed of light and computers (one foot per nanosecond vs. one GHz clocks)
* Latencies in computer systems: memory vs. disk latencies vs. across the network memory
* Caches and the effects of spatial and temporal locality on performance in processors and systems
* Caches and cache coherency in databases, operating systems, distributed systems, and computer
architecture
* Introduction into the processor memory hierarchy and the formula for average memory access time

**学習到達目標:**

学習到達目標:
1. Explain the importance of locality in determining performance. [Familiarity]
2. Describe why things that are close in space take less time to access. [Familiarity]
3. Calculate average memory access time and describe the tradeoffs in memory hierarchy performance in
terms of capacity, miss/hit rate, and access time. [Assessment]



## SF/仮想化と分離
*[選択必修 2時間]*

**トピック:**

* Rationale for protection and predictable performance
* Levels of indirection, illustrated by virtual memory for managing physical memory resources
* Methods for implementing virtual memory and virtual machines

**学習到達目標:**

1. Explain why it is important to isolate and protect the execution of individual programs and environments
that share common underlying resources. [Familiarity]
2. Describe how the concept of indirection can create the illusion of a dedicated machine and its resources
even when physically shared among multiple programs and environments. [Familiarity]
3. Measure the performance of two application instances running on separate virtual machines, and determine
the effect of performance isolation. [Assessment]



## SF/冗長化による信頼性向上
*[選択必修 2時間]*

**トピック:**

* Distinction between bugs and faults
* Redundancy through check and retry
* Redundancy through redundant encoding (error correcting codes, CRC, FEC)
* Duplication/mirroring/replicas
* Other approaches to fault tolerance and availability

**学習到達目標:**

1. Explain the distinction between program errors, system errors, and hardware faults (e.g., bad memory) and
exceptions (e.g., attempt to divide by zero). [Familiarity]
2. Articulate the distinction between detecting, handling, and recovering from faults, and the methods for their
implementation. [Familiarity]
3. Describe the role of error correcting codes in providing error checking and correction techniques in
memories, storage, and networks. [Familiarity]
4. Apply simple algorithms for exploiting redundant information for the purposes of data correction. [Usage]
5. Compare different error detection and correction methods for their data overhead, implementation
complexity, and relative execution time for encoding, detecting, and correcting errors. [Assessment]



## SF/定量的評価
*[選択科目]*

**トピック:**

* Analytical tools to guide quantitative evaluation
* Order of magnitude analysis (Big-Oh notation)
* Analysis of slow and fast paths of a system
* Events on their effect on performance (e.g., instruction stalls, cache misses, page faults)
* Understanding layered systems, workloads, and platforms, their implications for performance, and the
challenges they represent for evaluation
* Microbenchmarking pitfalls

**学習到達目標:**

1. Explain the circumstances in which a given figure of system performance metric is useful. [Familiarity]
2. Explain the inadequacies of benchmarks as a measure of system performance. [Familiarity]
3. Use limit studies or simple calculations to produce order-of-magnitude estimates for a given performance
metric in a given context. [Usage]
4. Conduct a performance experiment on a layered system to determine the effect of a system parameter on
figure of system performance. [Assessment]
