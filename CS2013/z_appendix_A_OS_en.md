
# Operating Systems (OS)

An operating system defines an abstraction of hardware and manages resource sharing among
the computer’s users. The topics in this area explain the most basic knowledge of operating
systems in the sense of interfacing an operating system to networks, teaching the difference
between the kernel and user modes, and developing key approaches to operating system design
and implementation. This knowledge area is structured to be complementary to the Systems
Fundamentals (SF), Networking and Communication (NC), Information Assurance and Security
(IAS), and the Parallel and Distributed Computing (PD) knowledge areas. The Systems
Fundamentals and Information Assurance and Security knowledge areas are the new ones to
include contemporary issues. For example, Systems Fundamentals includes topics such as
performance, virtualization and isolation, and resource allocation and scheduling; Parallel and
Distributed Systems includes parallelism fundamentals; and and Information Assurance and
Security includes forensics and security issues in depth. Many courses in Operating Systems
will draw material from across these knowledge areas.

**OS. Operating Systems (4 Core-Tier1 hours; 11 Core Tier2 hours)**

|                   | Core-Tier1 hours | Core-Tier2 hours | Includes Electives |
| --- | --- | --- | --- |
| OS/Overview of Operating Systems  | 2 |   | N |
| OS/Operating System Principles    | 2 |   | N |
| OS/Concurrency                    |   | 3 | N |
| OS/Scheduling and Dispatch        |   | 3 | N |
| OS/Memory Management              |   | 3 | N |
| OS/Security and Protection        |   | 2 | N |
| OS/Virtual Machines               |   |   | Y |
| OS/Device Management              |   |   | Y |
| OS/File Systems                   |   |   | Y |
| OS/Real Time and Embedded Systems |   |   | Y |
| OS/Fault Tolerance                |   |   | Y |
| OS/System Performance Evaluation  |   |   | Y |



## OS/Overview of Operating Systems 
*[2 Core-Tier1 hours]*

**Topics:**

* Role and purpose of the operating system
* Functionality of a typical operating system
* Mechanisms to support client-server models, hand-held devices
* Design issues (efficiency, robustness, flexibility, portability, security, compatibility)
* Influences of security, networking, multimedia, windowing systems

**Learning Outcomes:**

1. Explain the objectives and functions of modern operating systems. [Familiarity]
2. Analyze the tradeoffs inherent in operating system design. [Usage]
3. Describe the functions of a contemporary operating system with respect to convenience, efficiency, and the
ability to evolve. [Familiarity]
4. Discuss networked, client-server, distributed operating systems and how they differ from single user
operating systems. [Familiarity]
5. Identify potential threats to operating systems and the security features design to guard against them.
[Familiarity]


## OS/Operating System Principles
*[2 Core-Tier1 hours]*

**Topics:**

* Structuring methods (monolithic, layered, modular, micro-kernel models)
* Abstractions, processes, and resources
* Concepts of application program interfaces (APIs)
* The evolution of hardware/software techniques and application needs
* Device organization
* Interrupts: methods and implementations
* Concept of user/system state and protection, transition to kernel mode

**Learning Outcomes:**

1. Explain the concept of a logical layer. [Familiarity]
2. Explain the benefits of building abstract layers in hierarchical fashion. [Familiarity]
3. Describe the value of APIs and middleware. [Assessment]
4. Describe how computing resources are used by application software and managed by system software.
[Familiarity]
5. Contrast kernel and user mode in an operating system. [Usage]
6. Discuss the advantages and disadvantages of using interrupt processing. [Familiarity]
7. Explain the use of a device list and driver I/O queue. [Familiarity]


## OS/Concurrency
*[3 Core-Tier2 hours]*

**Topics:**

* States and state diagrams (cross-reference SF/State and State Machines)
* Structures (ready list, process control blocks, and so forth)
* Dispatching and context switching
* The role of interrupts
* Managing atomic access to OS objects
* Implementing synchronization primitives
* Multiprocessor issues (spin-locks, reentrancy) (cross-reference SF/Parallelism)

**Learning Outcomes:**

1. Describe the need for concurrency within the framework of an operating system. [Familiarity]
2. Demonstrate the potential run-time problems arising from the concurrent operation of many separate tasks.
[Usage]
3. Summarize the range of mechanisms that can be employed at the operating system level to realize
concurrent systems and describe the benefits of each. [Familiarity]
4. Explain the different states that a task may pass through and the data structures needed to support the
management of many tasks. [Familiarity]
5. Summarize techniques for achieving synchronization in an operating system (e.g., describe how to
implement a semaphore using OS primitives). [Familiarity]
6. Describe reasons for using interrupts, dispatching, and context switching to support concurrency in an
operating system. [Familiarity]
7. Create state and transition diagrams for simple problem domains. [Usage]


## OS/Scheduling and Dispatch
*[3 Core-Tier2 hours]*

**Topics:**

* Preemptive and non-preemptive scheduling (cross-reference SF/Resource Allocation and Scheduling,
PD/Parallel Performance)
* Schedulers and policies (cross-reference SF/Resource Allocation and Scheduling, PD/Parallel
Performance)
* Processes and threads (cross-reference SF/Computational paradigms)
* Deadlines and real-time issues

**Learning Outcomes:**

1. Compare and contrast the common algorithms used for both preemptive and non-preemptive scheduling of
tasks in operating systems, such as priority, performance comparison, and fair-share schemes. [Usage]
2. Describe relationships between scheduling algorithms and application domains. [Familiarity]
3. Discuss the types of processor scheduling such as short-term, medium-term, long-term, and I/O.
[Familiarity]
4. Describe the difference between processes and threads. [Usage]
5. Compare and contrast static and dynamic approaches to real-time scheduling. [Usage]
6. Discuss the need for preemption and deadline scheduling. [Familiarity]
7. Identify ways that the logic embodied in scheduling algorithms are applicable to other domains, such as
disk I/O, network scheduling, project scheduling, and problems beyond computing. [Usage]



## OS/Memory Management
*[3 Core-Tier2 hours]*

**Topics:**

* Review of physical memory and memory management hardware
* Working sets and thrashing
* Caching (cross-reference AR/Memory System Organization and Architecture)

**Learning Outcomes:**

1. Explain memory hierarchy and cost-performance trade-offs. [Familiarity]
2. Summarize the principles of virtual memory as applied to caching and paging. [Familiarity]
3. Evaluate the trade-offs in terms of memory size (main memory, cache memory, auxiliary memory) and
processor speed. [Assessment]
4. Defend the different ways of allocating memory to tasks, citing the relative merits of each. [Assessment]
5. Describe the reason for and use of cache memory (performance and proximity, different dimension of how
caches complicate isolation and VM abstraction). [Familiarity]
6. Discuss the concept of thrashing, both in terms of the reasons it occurs and the techniques used to recognize
and manage the problem. [Familiarity]


## OS/Security and Protection
*[2 Core-Tier2 hours]*

**Topics:**

* Overview of system security
* Policy/mechanism separation
* Security methods and devices
* Protection, access control, and authentication
* Backups

**Learning Outcomes:**

1. Articulate the need for protection and security in an OS (cross-reference IAS/Security Architecture and
Systems Administration/Investigating Operating Systems Security for various systems). [Assessment]
2. Summarize the features and limitations of an operating system used to provide protection and security
(cross-reference IAS/Security Architecture and Systems Administration). [Familiarity]
3. Explain the mechanisms available in an OS to control access to resources (cross-reference IAS/Security
Architecture and Systems Administration/Access Control/Configuring systems to operate securely as an IT
system). [Familiarity]
4. Carry out simple system administration tasks according to a security policy, for example creating accounts,
setting permissions, applying patches, and arranging for regular backups (cross-reference IAS/Security
Architecture and Systems Administration). [Usage]



## OS/Virtual Machines
*[Elective]*

**Topics:**

* Types of virtualization (including Hardware/Software, OS, Server, Service, Network)
* Paging and virtual memory
* Virtual file systems
* Hypervisors
* Portable virtualization; emulation vs. isolation
* Cost of virtualization

**Learning Outcomes:**

1. Explain the concept of virtual memory and how it is realized in hardware and software. [Familiarity]
5. Differentiate emulation and isolation. [Familiarity]
6. Evaluate virtualization trade-offs. [Assessment]
2. Discuss hypervisors and the need for them in conjunction with different types of hypervisors. [Usage]


## OS/Device Management
*[Elective]*

**Topics:**

* Characteristics of serial and parallel devices
* Abstracting device differences
* Buffering strategies
* Direct memory access
* Recovery from failures

**Learning Outcomes:**

1. Explain the key difference between serial and parallel devices and identify the conditions in which each is
appropriate. [Familiarity]
2. Identify the relationship between the physical hardware and the virtual devices maintained by the operating
system. [Usage]
3. Explain buffering and describe strategies for implementing it. [Familiarity]
4. Differentiate the mechanisms used in interfacing a range of devices (including hand-held devices,
networks, multimedia) to a computer and explain the implications of these for the design of an operating
system. [Usage]
5. Describe the advantages and disadvantages of direct memory access and discuss the circumstances in
which its use is warranted. [Usage]
6. Identify the requirements for failure recovery. [Familiarity]
7. Implement a simple device driver for a range of possible devices. [Usage]

## OS/File Systems
*[Elective]*

**Topics:**

* Files: data, metadata, operations, organization, buffering, sequential, nonsequential
* Directories: contents and structure
* File systems: partitioning, mount/unmount, virtual file systems
* Standard implementation techniques
* Memory-mapped files
* Special-purpose file systems
* Naming, searching, access, backups
* Journaling and log-structured file systems

**Learning Outcomes:**

1. Describe the choices to be made in designing file systems. [Familiarity]
2. Compare and contrast different approaches to file organization, recognizing the strengths and weaknesses
of each. [Usage]
3. Summarize how hardware developments have led to changes in the priorities for the design and the
management of file systems. [Familiarity]
4. Summarize the use of journaling and how log-structured file systems enhance fault tolerance. [Familiarity]

## OS/Real Time and Embedded Systems
*[Elective]*

**Topics:**

* Process and task scheduling
* Memory/disk management requirements in a real-time environment
* Failures, risks, and recovery
* Special concerns in real-time systems

**Learning Outcomes:**

1. Describe what makes a system a real-time system. [Familiarity]
2. Explain the presence of and describe the characteristics of latency in real-time systems. [Familiarity]
3. Summarize special concerns that real-time systems present, including risk, and how these concerns are
addressed. [Familiarity]


## OS/Fault Tolerance
*[Elective]*

**Topics:**

* Fundamental concepts: reliable and available systems (cross-reference SF/Reliability through Redundancy)
* Spatial and temporal redundancy (cross-reference SF/Reliability through Redundancy)
* Methods used to implement fault tolerance
* Examples of OS mechanisms for detection, recovery, restart to implement fault tolerance, use of these
techniques for the OS’s own services

**Learning Outcomes:**

1. Explain the relevance of the terms fault tolerance, reliability, and availability. [Familiarity]
2. Outline the range of methods for implementing fault tolerance in an operating system. [Familiarity]
3. Explain how an operating system can continue functioning after a fault occurs. [Familiarity]


## OS/System Performance Evaluation
*[Elective]*

**Topics:**

* Why system performance needs to be evaluated (cross-reference SF/Performance/Figures of performance
merit)
* What is to be evaluated (cross-reference SF/Performance/Figures of performance merit)
* Systems performance policies, e.g., caching, paging, scheduling, memory management, and security
* Evaluation models: deterministic, analytic, simulation, or implementation-specific
* How to collect evaluation data (profiling and tracing mechanisms)

**Learning Outcomes:**

1. Describe the performance measurements used to determine how a system performs. [Familiarity]
2. Explain the main evaluation models used to evaluate a system. [Familiarity]
