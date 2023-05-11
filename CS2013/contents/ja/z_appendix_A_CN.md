
# 計算科学 (CN)

Computational Science is a field of applied computer science, that is, the application of computer
science to solve problems across a range of disciplines. In the book Introduction to
Computational Science [^3], the authors offer the following definition: “the field of computational
science combines computer simulation, scientific visualization, mathematical modeling,
computer programming and data structures, networking, database design, symbolic computation,
and high performance computing with various disciplines.” Computer science, which largely
focuses on the theory, design, and implementation of algorithms for manipulating data and
information, can trace its roots to the earliest devices used to assist people in computation over
four thousand years ago. Various systems were created and used to calculate astronomical
positions. Ada Lovelace’s programming achievement was intended to calculate Bernoulli
numbers. In the late nineteenth century, mechanical calculators became available, and were
immediately put to use by scientists. The needs of scientists and engineers for computation have
long driven research and innovation in computing. As computers increase in their problemsolving power, computational science has grown in both breadth and importance. It is a
discipline in its own right[^2] and is considered to be “one of the five college majors on the rise
[^1].” An amazing assortment of sub-fields have arisen under the umbrella of Computational
Science, including computational biology, computational chemistry, computational mechanics,
computational archeology, computational finance, computational sociology and computational
forensics.

Some fundamental concepts of computational science are germane to every computer scientist
(e.g., modeling and simulation), and computational science topics are extremely valuable
components of an undergraduate program in computer science. This area offers exposure to
many valuable ideas and techniques, including precision of numerical representation, error
analysis, numerical techniques, parallel architectures and algorithms, modeling and simulation,
information visualization, software engineering, and optimization. Topics relevant to
computational science include fundamental concepts in program construction (SDF/Fundamental
Programming Concepts), algorithm design (SDF/Algorithms and Design), program testing
(SDF/Development Methods), data representations (AR/Machine Representation of Data), and
basic computer architecture (AR/Memory System Organization and Architecture). At the same
time, students who take courses in this area have an opportunity to apply these techniques in a
wide range of application areas, such as molecular and fluid dynamics, celestial mechanics,
economics, biology, geology, medicine, and social network analysis. Many of the techniques
used in these areas require advanced mathematics such as calculus, differential equations, and
linear algebra. The descriptions here assume that students have acquired the needed
mathematical background elsewhere.
 In the computational science community, the terms run, modify, and create are often used to
describe levels of understanding. This chapter follows the conventions of other chapters in this
volume and uses the terms familiarity, usage, and assessment.

[^1]: Fischer, K. and Glenn, D., “5 College Majors on the Rise,” The Chronicle of Higher
Education, August 31, 2009.
[^2]: President’s Information Technology Advisory Committee, 2005: p. 13.
http://www.nitrd.gov/pitac/reports/20050609_computational/computational.pdf
[^3]: Shiflet, A. B. and Shiflet, G. W. Introduction to Computational Science: Modeling and
Simulation for the Sciences, Princeton University Press, 2006: p. 3.

**CN. 計算科学(必修 1時間, 選択必修 0時間)**

| 知識単位 | 必修時間 | 選択必修時間 | 含選択科目 |
| -------- | -------- | ------------ | ---------- |
| CN/モデリングとシミュレーションへの導入 | 1 | | N |
| CN/モデリングとシミュレーション         | | | Y |
| CN/プロセッシング                       | | | Y |
| CN/対話的な視覚化                       | | | Y |
| CN/データ・情報・知識                   | | | Y |
| CN/数値解析                             | | | Y |


## CN/モデリングとシミュレーションへの導入
*[必修 1時間]*

Abstraction is a fundamental concept in computer science. A principal approach to computing is
to abstract the real world, create a model that can be simulated on a machine. The roots of
computer science can be traced to this approach, modeling things such as trajectories of artillery
shells and the modeling cryptographic protocols, both of which pushed the development of early
computing systems in the early and mid-1940’s.

Modeling and simulation of real world systems represent essential knowledge for computer
scientists and provide a foundation for computational sciences. Any introduction to modeling
and simulation would either include or presume an introduction to computing. In addition, a
general set of modeling and simulation techniques, data visualization methods, and software
testing and evaluation mechanisms are also important. 


**トピック:**
* Models as abstractions of situations
* Simulations as dynamic modeling
* Simulation techniques and tools, such as physical simulations, human-in-the-loop guided simulations, and
virtual reality
* Foundational approaches to validating models (e.g., comparing a simulation’s output to real data or the
output of another model)
* Presentation of results in a form relevant to the system being modeled

**学習到達目標:**

1. Explain the concept of modeling and the use of abstraction that allows the use of a machine to solve a
problem. [Familiarity]
2. Describe the relationship between modeling and simulation, i.e., thinking of simulation as dynamic
modeling. [Familiarity]
3. Create a simple, formal mathematical model of a real-world situation and use that model in a simulation.
[Usage]
4. Differentiate among the different types of simulations, including physical simulations, human-guided
simulations, and virtual reality. [Familiarity]
5. Describe several approaches to validating models. [Familiarity]
6. Create a simple display of the results of a simulation. [Usage]



## CN/モデリングとシミュレーション
*[Elective]*

**トピック:**

* Purpose of modeling and simulation including optimization; supporting decision making, forecasting,
safety considerations; for training and education
* Tradeoffs including performance, accuracy, validity, and complexity
* The simulation process; identification of key characteristics or behaviors, simplifying assumptions;
validation of outcomes
* Model building: use of mathematical formulas or equations, graphs, constraints; methodologies and
techniques; use of time stepping for dynamic systems
* Formal models and modeling techniques: mathematical descriptions involving simplifying assumptions
and avoiding detail. Examples of techniques include:
 * Monte Carlo methods
 * Stochastic processes
 * Queuing theory
 * Petri nets and colored Petri nets
 * Graph structures such as directed graphs, trees, networks
 * Games, game theory, the modeling of things using game theory
 * Linear programming and its extensions
 * Dynamic programming
 * Differential equations: ODE, PDE
 * Non-linear techniques
 * State spaces and transitions
* Assessing and evaluating models and simulations in a variety of contexts; verification and validation of
models and simulations
* Important application areas including health care and diagnostics, economics and finance, city and urban
planning, science, and engineering
* Software in support of simulation and modeling; packages, languages


**学習到達目標:**

1. Explain and give examples of the benefits of simulation and modeling in a range of important application
areas. [Familiarity]
2. Demonstrate the ability to apply the techniques of modeling and simulation to a range of problem areas.
[Usage]
3. Explain the constructs and concepts of a particular modeling approach. [Familiarity]
4. Explain the difference between validation and verification of a model; demonstrate the difference with
specific examples[^4]. [Assessment]
5. Verify and validate the results of a simulation. [Assessment]
6. Evaluate a simulation, highlighting the benefits and the drawbacks. [Assessment]
7. Choose an appropriate modeling approach for a given problem or situation. [Assessment]
8. Compare results from different simulations of the same situation and explain any differences. [Assessment]
9. Infer the behavior of a system from the results of a simulation of the system. [Assessment]
10. Extend or adapt an existing model to a new situation. [Assessment]

[^4]: Verification means that the computations of the model are correct. If we claim to compute total time, for example,
the computation actually does that. Validation asks whether the model matches the real situation.



## CN/プロセッシング
*[Elective]*

The processing topic area includes numerous topics from other knowledge areas. Specifically,
coverage of processing should include a discussion of hardware architectures, including parallel
systems, memory hierarchies, and interconnections among processors. These are covered in
AR/Interfacing and Communication, AR/Multiprocessing and Alternative Architectures,
AR/Performance Enhancements.

**トピック:**

* Fundamental programming concepts:
 * The concept of an algorithm consisting of a finite number of well-defined steps, each of which
completes in a finite amount of time, as does the entire process.
 * Examples of well-known algorithms such as sorting and searching.
 * The concept of analysis as understanding what the problem is really asking, how a problem can be
approached using an algorithm, and how information is represented so that a machine can process
it.
 * The development or identification of a workflow.
 * The process of converting an algorithm to machine-executable code.
 * Software processes including lifecycle models, requirements, design, implementation, verification
and maintenance.
 * Machine representation of data computer arithmetic.
* Numerical methods
 * Algorithms for numerically fitting data (e.g., Newton’s method)
 * Architectures for numerical computation, including parallel architectures
* Fundamental properties of parallel and distributed computation:
 * Bandwidth.
 * Latency.
 * Scalability.
 * Granularity.
 * Parallelism including task, data, and event parallelism.
 * Parallel architectures including processor architectures, memory and caching.
 * Parallel programming paradigms including threading, message passing, event driven techniques,
parallel software architectures, and MapReduce.
 * Grid computing.
 * The impact of architecture on computational time.
 * Total time to science curve for parallelism: continuum of things.
* Computing costs, e.g., the cost of re-computing a value vs. the cost of storing and lookup.



**学習到達目標:**

1. Explain the characteristics and defining properties of algorithms and how they relate to machine
processing. [Familiarity]
2. Analyze simple problem statements to identify relevant information and select appropriate processing to
solve the problem. [Assessment]
3. Identify or sketch a workflow for an existing computational process such as the creation of a graph based
on experimental data. [Familiarity]
4. Describe the process of converting an algorithm to machine-executable code. [Familiarity]
5. Summarize the phases of software development and compare several common lifecycle models.
[Familiarity]
6. Explain how data is represented in a machine. Compare representations of integers to floating point
numbers. Describe underflow, overflow, round off, and truncation errors in data representations.
[Familiarity]
7. Apply standard numerical algorithms to solve ODEs and PDEs. Use computing systems to solve systems of
equations. [Usage]
8. Describe the basic properties of bandwidth, latency, scalability and granularity. [Familiarity]
9. Describe the levels of parallelism including task, data, and event parallelism. [Familiarity]
10. Compare and contrast parallel programming paradigms recognizing the strengths and weaknesses of each.
[Assessment]
11. Identify the issues impacting correctness and efficiency of a computation. [Familiarity]
12. Design, code, test and debug programs for a parallel computation. [Usage]



## CN/対話的な視覚化
*[Elective]*

This sub-area is related to modeling and simulation. Most topics are discussed in detail in other
knowledge areas in this document. There are many ways to present data and information,
including immersion, realism, variable perspectives; haptics and heads-up displays, sonification,
and gesture mapping.

Interactive visualization in general requires understanding of human perception (GV/Basics);
graphics pipelines, geometric representations and data structures (GV/Fundamental Concepts);
2D and 3D rendering, surface and volume rendering (GV/Rendering, GV/Modeling, and
GV/Advanced Rendering); and the use of APIs for developing user interfaces using standard
input components such as menus, sliders, and buttons; and standard output components for data
display, including charts, graphs, tables, and histograms (HCI/GUI Construction, HCI/GUI
Programming).

**トピック:**

* Principles of data visualization
* Graphing and visualization algorithms
* Image processing techniques
* Scalability concerns

**学習到達目標:**

1. Compare common computer interface mechanisms with respect to ease-of-use, learnability, and cost.
[Assessment]
2. Use standard APIs and tools to create visual displays of data, including graphs, charts, tables, and
histograms. [Usage]
3. Describe several approaches to using a computer as a means for interacting with and processing data.
[Familiarity]
4. Extract useful information from a dataset. [Assessment]
5. Analyze and select visualization techniques for specific problems. [Assessment]
6. Describe issues related to scaling data analysis from small to large data sets. [Familiarity]



## CN/データ・情報・知識
*[Elective]*

Many topics are discussed in detail in other knowledge areas in this document, specifically
Information Management (IM/Information Management Concepts, IM/Database Systems, and
IM/Data Modeling), Algorithms and Complexity (AL/Basic Analysis, AL/Fundamental Data
Structures and Algorithms), and Software Development Fundamentals (SDF/Fundamental
Programming Concepts, SDF/Development Methods).

**トピック:**
* Content management models, frameworks, systems, design methods (as in IM. Information Management)
* Digital representations of content including numbers, text, images (e.g., raster and vector), video (e.g.,
QuickTime, MPEG2, MPEG4), audio (e.g., written score, MIDI, sampled digitized sound track) and
animations; complex/composite/aggregate objects; FRBR
* Digital content creation/capture and preservation, including digitization, sampling, compression,
conversion, transformation/translation, migration/emulation, crawling, harvesting
* Content structure / management, including digital libraries and static/dynamic/stream aspects for:
 * Data: data structures, databases
 * Information: document collections, multimedia pools, hyperbases (hypertext, hypermedia),
catalogs, repositories
 * Knowledge: ontologies, triple stores, semantic networks, rules
* Processing and pattern recognition, including indexing, searching (including: queries and query languages;
central / federated / P2P), retrieving, clustering, classifying/categorizing, analyzing/mining/extracting,
rendering, reporting, handling transactions
* User / society support for presentation and interaction, including browse, search, filter, route, visualize,
share, collaborate, rate, annotate, personalize, recommend
* Modeling, design, logical and physical implementation, using relevant systems/software

**学習到達目標:**
1. Identify all of the data, information, and knowledge elements and related organizations, for a computational
science application. [Assessment]
2. Describe how to represent data and information for processing. [Familiarity]
3. Describe typical user requirements regarding that data, information, and knowledge. [Familiarity]
4. Select a suitable system or software implementation to manage data, information, and knowledge.
[Assessment]
5. List and describe the reports, transactions, and other processing needed for a computational science
application. [Familiarity]
6. Compare and contrast database management, information retrieval, and digital library systems with regard
to handling typical computational science applications. [Assessment]
7. Design a digital library for some computational science users/societies, with appropriate content and
services. [Usage]



## CN/数値解析
*[Elective]*

Cross-reference AR/Machine Level Representation of Data

**トピック:**
* Error, stability, convergence, including truncation and round-off
* Function approximation including Taylor’s series, interpolation, extrapolation, and regression
* Numerical differentiation and integration (Simpson’s Rule, explicit and implicit methods)
* Differential equations (Euler’s Method, finite differences)

**学習到達目標:**
1. Define error, stability, machine precision concepts and the inexactness of computational approximations.
[Familiarity]
2. Implement Taylor series, interpolation, extrapolation, and regression algorithms for approximating
functions. [Usage]
3. Implement algorithms for differentiation and integration. [Usage]
4. Implement algorithms for solving differential equations. [Usage]
