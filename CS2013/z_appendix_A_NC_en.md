
# Networking and Communication (NC)

The Internet and computer networks are now ubiquitous and a growing number of computing
activities strongly depend on the correct operation of the underlying network. Networks, both
fixed and mobile, are a key part of the computing environment of today and tomorrow. Many
computing applications that are used today would not be possible without networks. This
dependency on the underlying network is likely to increase in the future.

The high-level learning objective of this module can be summarized as follows:
* Thinking in a networked world. The world is more and more interconnected and the use
of networks will continue to increase. Students must understand how the networks
behave and the key principles behind the organization and operation of the networks.
* Continued study. The networking domain is rapidly evolving and a first networking
course should be a starting point to other more advanced courses on network design,
network management, sensor networks, etc.
* Principles and practice interact. Networking is real and many of the design choices that
involve networks also depend on practical constraints. Students should be exposed to
these practical constraints by experimenting with networking, using tools, and writing
networked software. 

There are different ways of organizing a networking course. Some educators prefer a top-down
approach, i.e., the course starts from the applications and then explains reliable delivery, routing
and forwarding. Other educators prefer a bottom-up approach where the students start with the
lower layers and build their understanding of the network, transport and application layers later.

**NC. Networking and Communication (3 Core-Tier1 hours, 7 Core-Tier2 hours)**

|                   | Core-Tier1 hours | Core-Tier2 hours | Includes Electives |
| --- | --- | --- | --- |
| NC/Introduction           | 1.5 |     | N |
| NC/Networked Applications | 1.5 |     | N |
| NC/Reliable Data Delivery |     | 2   | N |
| NC/Routing And Forwarding |     | 1.5 | N |
| NC/Local Area Networks    |     | 1.5 | N |
| NC/Resource Allocation    |     | 1   | N |
| NC/Mobility               |     | 1   | N |
| NC/Social Networking      |     |     | Y |



## NC/Introduction
*[1.5 Core-Tier1 hours]*

Cross-reference IAS/Network Security, which discusses network security and its applications.

**Topics:**

* Organization of the Internet (Internet Service Providers, Content Providers, etc.)
* Switching techniques (e.g., circuit, packet)
* Physical pieces of a network, including hosts, routers, switches, ISPs, wireless, LAN, access point, and
firewalls
* Layering principles (encapsulation, multiplexing)
* Roles of the different layers (application, transport, network, datalink, physical)

**Learning Outcomes:**

1. Articulate the organization of the Internet. [Familiarity]
2. List and define the appropriate network terminology. [Familiarity]
3. Describe the layered structure of a typical networked architecture. [Familiarity]
4. Identify the different types of complexity in a network (edges, core, etc.). [Familiarity]



## NC/Networked Applications 
*[1.5 Core-Tier1 hours]*

**Topics:**

* Naming and address schemes (DNS, IP addresses, Uniform Resource Identifiers, etc.)
* Distributed applications (client/server, peer-to-peer, cloud, etc.)
* HTTP as an application layer protocol
* Multiplexing with TCP and UDP
* Socket APIs

**Learning Outcomes:**

1. List the differences and the relations between names and addresses in a network. [Familiarity]
2. Define the principles behind naming schemes and resource location. [Familiarity]
3. Implement a simple client-server socket-based application. [Usage]



## NC/Reliable Data Delivery
*[2 Core-Tier2 hours]*

This knowledge unit is related to Systems Fundamentals (SF). Cross-reference SF/State and
State Machines and SF/Reliability through Redundancy.

**Topics:**

* Error control (retransmission techniques, timers)
* Flow control (acknowledgements, sliding window)
* Performance issues (pipelining)
* TCP

**Learning Outcomes:**

1. Describe the operation of reliable delivery protocols. [Familiarity]
2. List the factors that affect the performance of reliable delivery protocols. [Familiarity]
3. Design and implement a simple reliable protocol. [Usage] 



## NC/Routing and Forwarding
*[1.5 Core-Tier2 hours]*

**Topics:**

* Routing versus forwarding
* Static routing
* Internet Protocol (IP)
* Scalability issues (hierarchical addressing)

**Learning Outcomes:**

1. Describe the organization of the network layer. [Familiarity]
2. Describe how packets are forwarded in an IP network. [Familiarity]
3. List the scalability benefits of hierarchical addressing. [Familiarity]



## NC/Local Area Networks
*[1.5 Core-Tier2 hours]*

**Topics:**

* Multiple Access Problem
* Common approaches to multiple access (exponential-backoff, time division multiplexing, etc)
* Local Area Networks
* Ethernet
* Switching

**Learning Outcomes:**

1. Describe how frames are forwarded in an Ethernet network. [Familiarity]
2. Describe the differences between IP and Ethernet. [Familiarity]
3. Describe the interrelations between IP and Ethernet. [Familiarity]
4. Describe the steps used in one common approach to the multiple access problem. [Familiarity]



## NC/Resource Allocation
*[1 Core-Tier2 hours]*

**Topics:**

* Need for resource allocation
* Fixed allocation (TDM, FDM, WDM) versus dynamic allocation
* End-to-end versus network assisted approaches
* Fairness
* Principles of congestion control
* Approaches to Congestion (e.g., Content Distribution Networks)

**Learning Outcomes:**

1. Describe how resources can be allocated in a network. [Familiarity]
2. Describe the congestion problem in a large network. [Familiarity]
3. Compare and contrast fixed and dynamic allocation techniques. [Assessment]
4. Compare and contrast current approaches to congestion. [Assessment]



## NC/Mobility
*[1 Core-Tier2 hours]*

**Topics:**

* Principles of cellular networks
* 802.11 networks
* Issues in supporting mobile nodes (home agents)

**Learning Outcomes:**

1. Describe the organization of a wireless network. [Familiarity]
2. Describe how wireless networks support mobile users. [Familiarity]



## NC/Social Networking
*[Elective]*

**Topics:**

* Social networks overview
* Example social network platforms
* Structure of social network graphs
* Social network analysis

**Learning Outcomes:**

1. Discuss the key principles (such as membership, trust) of social networking. [Familiarity]
2. Describe how existing social networks operate. [Familiarity]
3. Construct a social network graph from network data. [Usage]
4. Analyze a social network to determine who the key people are. [Usage]
5. Evaluate a given interpretation of a social network question with associated data. [Assessment]
