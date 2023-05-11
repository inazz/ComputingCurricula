
# Information Management (IM)

Information Management is primarily concerned with the capture, digitization, representation,
organization, transformation, and presentation of information; algorithms for efficient and
effective access and updating of stored information; data modeling and abstraction; and physical
file storage techniques. The student needs to be able to develop conceptual and physical data
models, determine which IM methods and techniques are appropriate for a given problem, and be
able to select and implement an appropriate IM solution that addresses relevant design concerns
including scalability, accessibility and usability.

We also note that IM is related to fundamental information security concepts that are described
in the Information Assurance and Security (IAS) topic area, IAS/Fundamental Concepts.


**IM. Information Management (1 Core-Tier1 hour; 9 Core-Tier2 hours)**

|                   | Core-Tier1 hours | Core-Tier2 hours | Includes Electives |
| --- | --- | --- | --- |
| IM/Information Management Concepts | 1 | 2 | N |
| IM/Database Systems                |   | 3 | Y |
| IM/Data Modeling                   |   | 4 | N |
| IM/Indexing                        |   |   | Y |
| IM/Relational Databases            |   |   | Y |
| IM/Query Languages                 |   |   | Y |
| IM/Transaction Processing          |   |   | Y |
| IM/Distributed Databases           |   |   | Y |
| IM/Physical Database Design        |   |   | Y |
| IM/Data Mining                     |   |   | Y |
| IM/Information Storage And Retrieval |   |   | Y |
| IM/MultiMedia Systems |   |   | Y |

**IM. Information Management-related topics (distributed) (1 Core-Tier1 hour, 2 Core-Tier2 hours)**

|                   | Core-Tier1 hours | Core-Tier2 hours | Includes Electives |
| --- | --- | --- | --- |
| IAS/Fundamental Concepts[^1] | 1 | 2 | N |

[^1]: See Information Assurance and Security Knowledge Area for a description of this topic area.



## IM/Information Management Concepts
*[1 Core-Tier1 hour; 2 Core-Tier2 hours]*

**Topics:**

[Core-Tier1]
* Information systems as socio-technical systems
* Basic information storage and retrieval (IS&R) concepts
* Information capture and representation
* Supporting human needs: searching, retrieving, linking, browsing, navigating
[Core-Tier2]
* Information management applications
* Declarative and navigational queries, use of links
* Analysis and indexing
* Quality issues: reliability, scalability, efficiency, and effectiveness

**Learning Outcomes:**

[Core-Tier1]
1. Describe how humans gain access to information and data to support their needs. [Familiarity]
2. Describe the advantages and disadvantages of central organizational control over data. [Assessment]
3. Identify the careers/roles associated with information management (e.g., database administrator, data
modeler, application developer, end-user). [Familiarity]
4. Compare and contrast information with data and knowledge. [Assessment]
5. Demonstrate uses of explicitly stored metadata/schema associated with data. [Usage]
6. Identify issues of data persistence for an organization. [Familiarity]
[Core-Tier2]
7. Critique an information application with regard to satisfying user information needs. [Assessment]
8. Explain uses of declarative queries. [Familiarity]
9. Give a declarative version for a navigational query. [Familiarity]
10. Describe several technical solutions to the problems related to information privacy, integrity, security, and
preservation. [Familiarity]
11. Explain measures of efficiency (throughput, response time) and effectiveness (recall, precision).
[Familiarity]
12. Describe approaches to scale up information systems. [Familiarity]
13. Identify vulnerabilities and failure scenarios in common forms of information systems. [Usage]



## IM/Database Systems
*[3 Core-Tier2 hours]*

**Topics:**

[Core-Tier2]
* Approaches to and evolution of database systems
* Components of database systems
* Design of core DBMS functions (e.g., query mechanisms, transaction management, buffer management,
access methods)
* Database architecture and data independence
* Use of a declarative query language
* Systems supporting structured and/or stream content

[Elective]

* Approaches for managing large volumes of data (e.g., noSQL database systems, use of MapReduce). 

**Learning Outcomes:**

[Core-Tier2]

1. Explain the characteristics that distinguish the database approach from the approach of programming with
data files. [Familiarity]
2. Describe the most common designs for core database system components including the query optimizer,
query executor, storage manager, access methods, and transaction processor. [Familiarity]
3. Cite the basic goals, functions, and models of database systems. [Familiarity]
4. Describe the components of a database system and give examples of their use. [Familiarity]
5. Identify major DBMS functions and describe their role in a database system. [Familiarity]
6. Explain the concept of data independence and its importance in a database system. [Familiarity]
7. Use a declarative query language to elicit information from a database. [Usage]
8. Describe facilities that datatbases provide supporting structures and/or stream (sequence) data, e.g., text.
[Familiarity]

[Elective]

9. Describe major approaches to storing and processing large volumes of data. [Familiarity]



## IM/Data Modeling
*[4 Core-Tier2 hours]*

**Topics:**

* Data modeling
* Conceptual models (e.g., entity-relationship, UML diagrams)
* Spreadsheet models
* Relational data models
* Object-oriented models (cross-reference PL/Object-Oriented Programming)
* Semi-structured data model (expressed using DTD or XML Schema, for example)

**Learning Outcomes:**

1. Compare and contrast appropriate data models, including internal structures, for different types of data.
[Assessment]
2. Describe concepts in modeling notation (e.g., Entity-Relation Diagrams or UML) and how they would be
used. [Familiarity]
3. Define the fundamental terminology used in the relational data model. [Familiarity]
4. Describe the basic principles of the relational data model. [Familiarity]
5. Apply the modeling concepts and notation of the relational data model. [Usage]
6. Describe the main concepts of the OO model such as object identity, type constructors, encapsulation,
inheritance, polymorphism, and versioning. [Familiarity]
7. Describe the differences between relational and semi-structured data models. [Assessment]
8. Give a semi-structured equivalent (e.g., in DTD or XML Schema) for a given relational schema. [Usage]



## IM/Indexing
*[Elective]*

**Topics:**

* The impact of indices on query performance
* The basic structure of an index
* Keeping a buffer of data in memory
* Creating indexes with SQL
* Indexing text
* Indexing the web (e.g., web crawling)

**Learning Outcomes:**

1. Generate an index file for a collection of resources. [Usage]
2. Explain the role of an inverted index in locating a document in a collection. [Familiarity]
3. Explain how stemming and stop words affect indexing. [Familiarity]
4. Identify appropriate indices for given relational schema and query set. [Usage]
5. Estimate time to retrieve information, when indices are used compared to when they are not used. [Usage]
6. Describe key challenges in web crawling, e.g., detecting duplicate documents, determining the crawling
frontier. [Familiarity]



## IM/Relational Databases
*[Elective]*


**Topics:**

* Mapping conceptual schema to a relational schema
* Entity and referential integrity
* Relational algebra and relational calculus
* Relational Database design
* Functional dependency
* Decomposition of a schema; lossless-join and dependency-preservation properties of a decomposition
* Candidate keys, superkeys, and closure of a set of attributes
* Normal forms (BCNF)
* Multi-valued dependency (4NF)
* Join dependency (PJNF, 5NF)
* Representation theory

**Learning Outcomes:**

1. Prepare a relational schema from a conceptual model developed using the entity- relationship model.
[Usage]
2. Explain and demonstrate the concepts of entity integrity constraint and referential integrity constraint
(including definition of the concept of a foreign key). [Usage]
3. Demonstrate use of the relational algebra operations from mathematical set theory (union, intersection,
difference, and Cartesian product) and the relational algebra operations developed specifically for relational
databases (select (restrict), project, join, and division). [Usage]
4. Write queries in the relational algebra. [Usage]
5. Write queries in the tuple relational calculus. [Usage]
6. Determine the functional dependency between two or more attributes that are a subset of a relation.
[Assessment]
7. Connect constraints expressed as primary key and foreign key, with functional dependencies. [Usage]
8. Compute the closure of a set of attributes under given functional dependencies. [Usage]
9. Determine whether a set of attributes form a superkey and/or candidate key for a relation with given
functional dependencies. [Assessment]
10. Evaluate a proposed decomposition, to say whether it has lossless-join and dependency-preservation.
[Assessment]
11. Describe the properties of BCNF, PJNF, 5NF. [Familiarity]
12. Explain the impact of normalization on the efficiency of database operations especially query optimization.
[Familiarity]
13. Describe what is a multi-valued dependency and what type of constraints it specifies. [Familiarity]



## IM/Query Languages
*[Elective]*

**Topics:**

* Overview of database languages
* SQL (data definition, query formulation, update sublanguage, constraints, integrity)
* Selections
* Projections
* Select-project-join
* Aggregates and group-by
* Subqueries
* QBE and 4th-generation environments
* Different ways to invoke non-procedural queries in conventional languages
* Introduction to other major query languages (e.g., XPATH, SPARQL)
* Stored procedures

**Learning Outcomes:**

1. Create a relational database schema in SQL that incorporates key, entity integrity, and referential integrity
constraints. [Usage]
2. Use SQL to create tables and retrieve (SELECT) information from a database. [Usage]
3. Evaluate a set of query processing strategies and select the optimal strategy. [Assessment]
4. Create a non-procedural query by filling in templates of relations to construct an example of the desired
query result. [Usage]
5. Embed object-oriented queries into a stand-alone language such as C++ or Java (e.g., SELECT
Col.Method() FROM Object). [Usage]
6. Write a stored procedure that deals with parameters and has some control flow, to provide a given
functionality. [Usage]



## IM/Transaction Processing
*[Elective]*

**Topics:**

* Transactions
* Failure and recovery
* Concurrency control
* Interaction of transaction management with storage, especially buffering

**Learning Outcomes:**

1. Create a transaction by embedding SQL into an application program. [Usage]
2. Explain the concept of implicit commits. [Familiarity]
3. Describe the issues specific to efficient transaction execution. [Familiarity]
4. Explain when and why rollback is needed and how logging assures proper rollback. [Assessment]
5. Explain the effect of different isolation levels on the concurrency control mechanisms. [Assessment]
6. Choose the proper isolation level for implementing a specified transaction protocol. [Assessment]
7. Identify appropriate transaction boundaries in application programs. [Assessment]



## IM/Distributed Databases
*[Elective]*

**Topics:**

* Distributed DBMS
 * Distributed data storage
 * Distributed query processing
 * Distributed transaction model
 * Homogeneous and heterogeneous solutions
 * Client-server distributed databases (cross-reference SF/Computational Paradigms)
* Parallel DBMS
 * Parallel DBMS architectures: shared memory, shared disk, shared nothing;
 * Speedup and scale-up, e.g., use of the MapReduce processing model (cross-reference
CN/Processing, PD/Parallel Decomposition)
 * Data replication and weak consistency models

**Learning Outcomes:**

1. Explain the techniques used for data fragmentation, replication, and allocation during the distributed
database design process. [Familiarity]
2. Evaluate simple strategies for executing a distributed query to select the strategy that minimizes the amount
of data transfer. [Assessment]
3. Explain how the two-phase commit protocol is used to deal with committing a transaction that accesses
databases stored on multiple nodes. [Familiarity]
4. Describe distributed concurrency control based on the distinguished copy techniques and the voting
method. [Familiarity]
5. Describe the three levels of software in the client-server model. [Familiarity]



## IM/Physical Database Design
*[Elective]*

**Topics:**

* Storage and file structure
* Indexed files
* Hashed files
* Signature files
* B-trees
* Files with dense index
* Files with variable length records
* Database efficiency and tuning

**Learning Outcomes:**

1. Explain the concepts of records, record types, and files, as well as the different techniques for placing file
records on disk. [Familiarity]
2. Give examples of the application of primary, secondary, and clustering indexes. [Familiarity]
3. Distinguish between a non-dense index and a dense index. [Assessment]
4. Implement dynamic multilevel indexes using B-trees. [Usage]
5. Explain the theory and application of internal and external hashing techniques. [Familiarity]
6. Use hashing to facilitate dynamic file expansion. [Usage]
7. Describe the relationships among hashing, compression, and efficient database searches. [Familiarity]
8. Evaluate costs and benefits of various hashing schemes. [Assessment]
9. Explain how physical database design affects database transaction efficiency. [Familiarity]



## IM/Data Mining
*[Elective]*

**Topics:**

* Uses of data mining
* Data mining algorithms
* Associative and sequential patterns
* Data clustering
* Market basket analysis
* Data cleaning
* Data visualization (cross-reference GV/Visualization and CN/Interactive Visualization)

**Learning Outcomes:**

1. Compare and contrast different uses of data mining as evidenced in both research and application.
[Assessment]
2. Explain the value of finding associations in market basket data. [Familiarity]
3. Characterize the kinds of patterns that can be discovered by association rule mining. [Assessment]
4. Describe how to extend a relational system to find patterns using association rules. [Familiarity]
5. Evaluate different methodologies for effective application of data mining. [Assessment]
6. Identify and characterize sources of noise, redundancy, and outliers in presented data. [Assessment]
7. Identify mechanisms (on-line aggregation, anytime behavior, interactive visualization) to close the loop in
the data mining process. [Familiarity]
8. Describe why the various close-the-loop processes improve the effectiveness of data mining. [Familiarity]



## IM/Information Storage and Retrieval
*[Elective]*

**Topics:**

* Documents, electronic publishing, markup, and markup languages
* Tries, inverted files, PAT trees, signature files, indexing
* Morphological analysis, stemming, phrases, stop lists
* Term frequency distributions, uncertainty, fuzziness, weighting
* Vector space, probabilistic, logical, and advanced models
* Information needs, relevance, evaluation, effectiveness
* Thesauri, ontologies, classification and categorization, metadata
* Bibliographic information, bibliometrics, citations
* Routing and (community) filtering
* Multimedia search, information seeking behavior, user modeling, feedback
* Information summarization and visualization
* Faceted search (e.g., using citations, keywords, classification schemes)
* Digital libraries
* Digitization, storage, interchange, digital objects, composites, and packages
* Metadata and cataloging
* Naming, repositories, archives
* Archiving and preservation, integrity
* Spaces (conceptual, geographical, 2/3D, VR)
* Architectures (agents, buses, wrappers/mediators), interoperability
* Services (searching, linking, browsing, and so forth)
* Intellectual property rights management, privacy, and protection (watermarking)

**Learning Outcomes:**

1. Explain basic information storage and retrieval concepts. [Familiarity]
2. Describe what issues are specific to efficient information retrieval. [Familiarity]
3. Give applications of alternative search strategies and explain why the particular search strategy is
appropriate for the application. [Assessment]
4. Design and implement a small to medium size information storage and retrieval system, or digital library.
[Usage]
5. Describe some of the technical solutions to the problems related to archiving and preserving information in
a digital library. [Familiarity]



## IM/Multimedia Systems
*[Elective]*

**Topics:**

* Input and output devices, device drivers, control signals and protocols, DSPs
* Standards (e.g., audio, graphics, video)
* Applications, media editors, authoring systems, and authoring
* Streams/structures, capture/represent/transform, spaces/domains, compression/coding
* Content-based analysis, indexing, and retrieval of audio, images, animation, and video
* Presentation, rendering, synchronization, multi-modal integration/interfaces
* Real-time delivery, quality of service (including performance), capacity planning, audio/video
conferencing, video-on-demand

**Learning Outcomes:**

1. Describe the media and supporting devices commonly associated with multimedia information and
systems. [Familiarity]
2. Demonstrate the use of content-based information analysis in a multimedia information system. [Usage]
3. Critique multimedia presentations in terms of their appropriate use of audio, video, graphics, color, and
other information presentation concepts. [Assessment]
4. Implement a multimedia application using an authoring system. [Usage]
5. For each of several media or multimedia standards, describe in non-technical language what the standard
calls for, and explain how aspects of human perception might be sensitive to the limitations of that
standard. [Familiarity]
6. Describe the characteristics of a computer system (including identification of support tools and appropriate
standards) that has to host the implementation of one of a range of possible multimedia applications.
[Familiarity]
