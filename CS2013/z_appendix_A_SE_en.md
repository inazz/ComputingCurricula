
# Software Engineering (SE)

In every computing application domain, professionalism, quality, schedule, and cost are critical
to producing software systems. Because of this, the elements of software engineering are
applicable to developing software in all areas of computing. A wide variety of software
engineering practices have been developed and utilized since the need for a discipline of
software engineering was first recognized. Many trade-offs between these different practices
have also been identified. Practicing software engineers have to select and apply appropriate
techniques and practices to a given development effort in order to maximize value. To learn how
to do so, they study the elements of software engineering.

Software engineering is the discipline concerned with the application of theory, knowledge, and
practice to effectively and efficiently build reliable software systems that satisfy the requirements
of customers and users. This discipline is applicable to small, medium, and large-scale systems.
It encompasses all phases of the lifecycle of a software system, including requirements
elicitation, analysis and specification; design; construction; verification and validation;
deployment; and operation and maintenance. Whether small or large, following a traditional
plan-driven development process, an agile approach, or some other method, software engineering
is concerned with the best way to build good software systems.

Software engineering uses engineering methods, processes, techniques, and measurements. It
benefits from the use of tools for managing software development; analyzing and modeling
software artifacts; assessing and controlling quality; and for ensuring a disciplined, controlled
approach to software evolution and reuse. The software engineering toolbox has evolved over the
years. For instance, the use of contracts, with requires and ensure clauses and class invariants, is
one good practice that has become more common. Software development, which can involve an
individual developer or a team or teams of developers, requires choosing the most appropriate
tools, methods, and approaches for a given development environment.

Students and instructors need to understand the impacts of specialization on software engineering
approaches. For example, specialized systems include:
 
* Real time systems
* Client-server systems
* Distributed systems
* Parallel systems
* Web-based systems
* High integrity systems
* Games
* Mobile computing
* Domain specific software (e.g., scientific computing or business applications)

Issues raised by each of these specialized systems demand specific treatments in each phase of
software engineering. Students must become aware of the differences between general software
engineering techniques and principles and the techniques and principles needed to address issues
specific to specialized systems.

An important effect of specialization is that different choices of material may need to be made
when teaching applications of software engineering, such as between different process models,
different approaches to modeling systems, or different choices of techniques for carrying out any
of the key activities. This is reflected in the assignment of core and elective material, with the
core topics and learning outcomes focusing on the principles underlying the various choices, and
the details of the various alternatives from which the choices have to be made being assigned to
the elective material.

Another division of the practices of software engineering is between those concerned with the
fundamental need to develop systems that implement correctly the functionality that is required
for them and those concerned with other qualities for systems and the trade-offs needed to
balance these qualities. This division too is reflected in the assignment of core and elective
material, so that topics and learning outcomes concerned with the basic methods for developing
such system are assigned to the core and those that are concerned with other qualities and tradeoffs between them are assigned to the elective material.

In general, students can best learn to apply much of the material defined in the Sofware
Engineering KA by participating in a project. Such projects should require students to work on a
team to develop a software system through as much of its lifecycle as is possible. Much of
software engineering is devoted to effective communication among team members and
stakeholders. Utilizing project teams, projects can be sufficiently challenging to require students
to use effective software engineering techniques and to develop and practice their
communication skills. While organizing and running effective projects within the academic
framework can be challenging, the best way to learn to apply software engineering theory and
knowledge is in the practical environment of a project. The minimum hours specified for some
knowledge units in this document may appear insufficient to accomplish associated applicationlevel learning outcomes. It should be understood that these outcomes are to be achieved through
project experience that may even occur later in the curriculum than when the topics within the
knowledge unit are introduced.

Further, there is increasing evidence that students learn to apply software engineering principles
more effectively through an iterative approach, where students have the opportunity to work
through a development cycle, assess their work, and then apply the knowledge gained through
their assessment to another development cycle. Agile and iterative lifecycle models inherently
afford such opportunities. 

Software lifecycle terminology in this document is based on that used in earlier sources, such as
the Software Engineering Body of Knowledge (SWEBOK) and the ACM/IEEE-CS Software
Engineering 2004 Curriculum Guidelines (SE2004). While some terms were originally defined
in the context of plan-driven development processes, they are treated here as generic, and thus
equally applicable to agile processes.

Note: The SDF/Development Methods knowledge unit includes 9 Core-Tier1 hours that
constitute an introduction to certain aspects of software engineering. The knowledge units,
topics and core hour specifications in this Software Engineering Knowledge Area must be
understood as assuming previous exposure to the material described in SDF/Development
Methods.

**SE. Software Engineering (6 Core-Tier1 hours; 21 Core-Tier2 hours)**

|                   | Core-Tier1 hours | Core-Tier2 hours | Includes Electives |
| --- | --- | --- | --- |
| SE/Software Processes                   | 2 | 1 | Y |
| SE/Software Project Management          |   | 2 | Y |
| SE/Tools and Environments               |   | 2 | N |
| SE/Requirements Engineering             | 1 | 3 | Y |
| SE/Software Design                      | 3 | 5 | Y |
| SE/Software Construction                |   | 2 | Y |
| SE/Software Verification and Validation |   | 4 | Y |
| SE/Software Evolution                   |   | 2 | Y |
| SE/Software Reliability                 |   | 1 | Y |
| SE/Formal Methods                       |   |   | Y |



## SE/Software Processes
*[2 Core-Tier1 hours; 1 Core-Tier2 hour]*

**Topics:**

[Core-Tier1]

* Systems level considerations, i.e., the interaction of software with its intended environment (crossreference IAS/Secure Software Engineering)
* Introduction to software process models (e.g., waterfall, incremental, agile)
 * Activities within software lifecycles
* Programming in the large vs. individual programming

[Core-Tier2]

* Evaluation of software process models

[Elective]

* Software quality concepts
* Process improvement
* Software process capability maturity models
* Software process measurements

**Learning Outcomes:**

[Core-Tier1]

1. Describe how software can interact with and participate in various systems including information
management, embedded, process control, and communications systems. [Familiarity]
2. Describe the relative advantages and disadvantages among several major process models (e.g., waterfall,
iterative, and agile). [Familiarity]
3. Describe the different practices that are key components of various process models. [Familiarity]
4. Differentiate among the phases of software development. [Familiarity]
5. Describe how programming in the large differs from individual efforts with respect to understanding a large
code base, code reading, understanding builds, and understanding context of changes. [Familiarity]

[Core-Tier2]

6. Explain the concept of a software lifecycle and provide an example, illustrating its phases including the
deliverables that are produced. [Familiarity]
7. Compare several common process models with respect to their value for development of particular classes
of software systems taking into account issues such as requirement stability, size, and non-functional
characteristics. [Usage]

[Elective]

8. Define software quality and describe the role of quality assurance activities in the software process.
[Familiarity]
9. Describe the intent and fundamental similarities among process improvement approaches. [Familiarity]
10. Compare several process improvement models such as CMM, CMMI, CQI, Plan-Do-Check-Act, or
ISO9000. [Assessment]
11. Assess a development effort and recommend potential changes by participating in process improvement
(using a model such as PSP) or engaging in a project retrospective. [Usage]
12. Explain the role of process maturity models in process improvement. [Familiarity]
13. Describe several process metrics for assessing and controlling a project. [Familiarity]
14. Use project metrics to describe the current state of a project. [Usage]


## SE/Software Project Management
*[2 Core-Tier2 hours]*

**Topics:**

[Core-Tier2]

* Team participation
 * Team processes including responsibilities for tasks, meeting structure, and work schedule
 * Roles and responsibilities in a software team
 * Team conflict resolution
 * Risks associated with virtual teams (communication, perception, structure)
* Effort Estimation (at the personal level)
* Risk (cross reference IAS/Secure Software Engineering)
 * The role of risk in the lifecycle
 * Risk categories including security, safety, market, financial, technology, people, quality, structure
and process

[Elective]

* Team management
 * Team organization and decision-making
 * Role identification and assignment
 * Individual and team performance assessment
* Project management
 * Scheduling and tracking
 * Project management tools
 * Cost/benefit analysis
* Software measurement and estimation techniques
* Software quality assurance and the role of measurements
* Risk
 * Risk identification and management
 * Risk analysis and evaluation
 * Risk tolerance (e.g., risk-adverse, risk-neutral, risk-seeking)
 * Risk planning
* System-wide approach to risk including hazards associated with tools

**Learning Outcomes:**

[Core-Tier2]

1. Discuss common behaviors that contribute to the effective functioning of a team. [Familiarity]
2. Create and follow an agenda for a team meeting. [Usage]
3. Identify and justify necessary roles in a software development team. [Usage]
4. Understand the sources, hazards, and potential benefits of team conflict. [Usage]
5. Apply a conflict resolution strategy in a team setting. [Usage]
6. Use an ad hoc method to estimate software development effort (e.g., time) and compare to actual effort
required. [Usage]
7. List several examples of software risks. [Familiarity]
8. Describe the impact of risk in a software development lifecycle. [Familiarity]
9. Describe different categories of risk in software systems. [Familiarity]

[Elective]

10. Demonstrate through involvement in a team project the central elements of team building and team
management. [Usage]
11. Describe how the choice of process model affects team organizational structures and decision-making
processes. [Familiarity]
12. Create a team by identifying appropriate roles and assigning roles to team members. [Usage]
13. Assess and provide feedback to teams and individuals on their performance in a team setting. [Usage]
14. Using a particular software process, describe the aspects of a project that need to be planned and monitored,
(e.g., estimates of size and effort, a schedule, resource allocation, configuration control, change
management, and project risk identification and management). [Familiarity]
15. Track the progress of some stage in a project using appropriate project metrics. [Usage]
16. Compare simple software size and cost estimation techniques. [Usage]
17. Use a project management tool to assist in the assignment and tracking of tasks in a software development
project. [Usage]
18. Describe the impact of risk tolerance on the software development process. [Assessment]
19. Identify risks and describe approaches to managing risk (avoidance, acceptance, transference, mitigation),
and characterize the strengths and shortcomings of each. [Familiarity]
20. Explain how risk affects decisions in the software development process. [Usage]
21. Identify security risks for a software system. [Usage]
22. Demonstrate a systematic approach to the task of identifying hazards and risks in a particular situation.
[Usage]
23. Apply the basic principles of risk management in a variety of simple scenarios including a security
situation. [Usage]
24. Conduct a cost/benefit analysis for a risk mitigation approach. [Usage]
25. Identify and analyze some of the risks for an entire system that arise from aspects other than the software.
[Usage]



## SE/Tools and Environments
*[2 Core-Tier2 hours]*

**Topics:**

* Software configuration management and version control
* Release management
* Requirements analysis and design modeling tools
* Testing tools including static and dynamic analysis tools
* Programming environments that automate parts of program construction processes (e.g., automated builds)
 * Continuous integration
* Tool integration concepts and mechanisms

**Learning Outcomes:**

1. Describe the difference between centralized and distributed software configuration management.
[Familiarity]
2. Describe how version control can be used to help manage software release management. [Familiarity]
3. Identify configuration items and use a source code control tool in a small team-based project. [Usage]
4. Describe how available static and dynamic test tools can be integrated into the software development
environment. [Familiarity]
5. Describe the issues that are important in selecting a set of tools for the development of a particular software
system, including tools for requirements tracking, design modeling, implementation, build automation, and
testing. [Familiarity]
6. Demonstrate the capability to use software tools in support of the development of a software product of
medium size. [Usage]



## SE/Requirements Engineering
*[1 Core-Tier1 hour; 3 Core-Tier2 hours]*

The purpose of requirements engineering is to develop a common understanding of the needs,
priorities, and constraints relevant to a software system. Many software failures arise from an
incomplete understanding of requirements for the software to be developed or inadequate
management of those requirements.

Specifications of requirements range in formality from completely informal (e.g., spoken) to
rigorously mathematical (e.g., written in a formal specification language such as Z or first-order
logic). In practice, successful software engineering efforts use requirements specifications to
reduce ambiguity and improve the consistency and completeness of the development team’s
understanding of the vision of the intended software. Plan-driven approaches tend to produce
formal documents with numbered requirements. Agile approaches tend to favor less formal
specifications that include user stories, use cases, and test cases.

**Topics:**

[Core-Tier1]
* Describing functional requirements using, for example, use cases or users stories
* Properties of requirements including consistency, validity, completeness, and feasibility

[Core-Tier2]
* Software requirements elicitation
* Describing system data using, for example, class diagrams or entity-relationship diagrams
* Non-functional requirements and their relationship to software quality (cross-reference IAS/Secure
Software Engineering)
* Evaluation and use of requirements specifications

[Elective]
* Requirements analysis modeling techniques
* Acceptability of certainty / uncertainty considerations regarding software / system behavior
* Prototyping
* Basic concepts of formal requirements specification
* Requirements specification
* Requirements validation
* Requirements tracing

**Learning Outcomes:**

[Core-Tier1]
1. List the key components of a use case or similar description of some behavior that is required for a system.
[Familiarity]
2. Describe how the requirements engineering process supports the elicitation and validation of behavioral
requirements. [Familiarity]
3. Interpret a given requirements model for a simple software system. [Familiarity]

[Core-Tier2]
4. Describe the fundamental challenges of and common techniques used for requirements elicitation.
[Familiarity]
5. List the key components of a data model (e.g., class diagrams or ER diagrams). [Familiarity]
6. Identify both functional and non-functional requirements in a given requirements specification for a
software system. [Usage]
7. Conduct a review of a set of software requirements to determine the quality of the requirements with
respect to the characteristics of good requirements. [Usage]

[Elective]
8. Apply key elements and common methods for elicitation and analysis to produce a set of software
requirements for a medium-sized software system. [Usage]
9. Compare the plan-driven and agile approaches to requirements specification and validation and describe the
benefits and risks associated with each. [Familiarity]
10. Use a common, non-formal method to model and specify the requirements for a medium-size software
system. [Usage]
11. Translate into natural language a software requirements specification (e.g., a software component contract)
written in a formal specification language. [Usage]
12. Create a prototype of a software system to mitigate risk in requirements. [Usage]
13. Differentiate between forward and backward tracing and explain their roles in the requirements validation
process. [Familiarity]



## SE/Software Design
*[3 Core-Tier1 hours; 5 Core-Tier2 hours]*

**Topics:**

[Core-Tier1]
* System design principles: levels of abstraction (architectural design and detailed design), separation of
concerns, information hiding, coupling and cohesion, re-use of standard structures
* Design Paradigms such as structured design (top-down functional decomposition), object-oriented analysis
and design, event driven design, component-level design, data-structured centered, aspect oriented,
function oriented, service oriented
* Structural and behavioral models of software designs
* Design patterns

[Core-Tier2]
* Relationships between requirements and designs: transformation of models, design of contracts, invariants
* Software architecture concepts and standard architectures (e.g. client-server, n-layer, transform centered,
pipes-and-filters)
* Refactoring designs using design patterns
* The use of components in design: component selection, design, adaptation and assembly of components,
components and patterns, components and objects (for example, building a GUI using a standard widget
set)

[Elective]
* Internal design qualities, and models for them: efficiency and performance, redundancy and fault
tolerance, traceability of requirements
* External design qualities, and models for them: functionality, reliability, performance and efficiency,
usability, maintainability, portability
* Measurement and analysis of design quality
* Tradeoffs between different aspects of quality
* Application frameworks
* Middleware: the object-oriented paradigm within middleware, object request brokers and marshalling,
transaction processing monitors, workflow systems
* Principles of secure design and coding (cross-reference IAS/Principles of Secure Design)
 * Principle of least privilege
 * Principle of fail-safe defaults
 * Principle of psychological acceptability

**Learning Outcomes:**

[Core-Tier1]
1. Articulate design principles including separation of concerns, information hiding, coupling and cohesion,
and encapsulation. [Familiarity]
2. Use a design paradigm to design a simple software system, and explain how system design principles have
been applied in this design. [Usage]
3. Construct models of the design of a simple software system that are appropriate for the paradigm used to
design it. [Usage]
4. Within the context of a single design paradigm, describe one or more design patterns that could be
applicable to the design of a simple software system. [Familiarity]

[Core-Tier2]
5. For a simple system suitable for a given scenario, discuss and select an appropriate design paradigm.
[Usage]
6. Create appropriate models for the structure and behavior of software products from their requirements
specifications. [Usage]
7. Explain the relationships between the requirements for a software product and its design, using appropriate
models. [Assessment]
8. For the design of a simple software system within the context of a single design paradigm, describe the
software architecture of that system. [Familiarity]
9. Given a high-level design, identify the software architecture by differentiating among common software
architectures such as 3-tier, pipe-and-filter, and client-server. [Familiarity]
10. Investigate the impact of software architectures selection on the design of a simple system. [Assessment]
11. Apply simple examples of patterns in a software design. [Usage]
12. Describe a form of refactoring and discuss when it may be applicable. [Familiarity]
13. Select suitable components for use in the design of a software product. [Usage]
14. Explain how suitable components might need to be adapted for use in the design of a software product.
[Familiarity]
15. Design a contract for a typical small software component for use in a given system. [Usage]

[Elective]
16. Discuss and select appropriate software architecture for a simple system suitable for a given scenario.
[Usage]
17. Apply models for internal and external qualities in designing software components to achieve an acceptable
tradeoff between conflicting quality aspects. [Usage]
18. Analyze a software design from the perspective of a significant internal quality attribute. [Assessment]
19. Analyze a software design from the perspective of a significant external quality attribute. [Assessment]
20. Explain the role of objects in middleware systems and the relationship with components. [Familiarity]
21. Apply component-oriented approaches to the design of a range of software, such as using components for
concurrency and transactions, for reliable communication services, for database interaction including
services for remote query and database management, or for secure communication and access. [Usage]
22. Refactor an existing software implementation to improve some aspect of its design. [Usage]
23. State and apply the principles of least privilege and fail-safe defaults. [Familiarity]


## SE/Software Construction
*[2 Core-Tier2 hours]*

**Topics:**

[Core-Tier2]
* Coding practices: techniques, idioms/patterns, mechanisms for building quality programs (cross-reference
IAS/Defensive Programming; SDF/Development Methods)
 * Defensive coding practices
 * Secure coding practices
 * Using exception handling mechanisms to make programs more robust, fault-tolerant
* Coding standards
* Integration strategies
* Development context: “green field” vs. existing code base
 * Change impact analysis
 * Change actualization

[Elective]
* Potential security problems in programs
 * Buffer and other types of overflows
 * Race conditions
 * Improper initialization, including choice of privileges
 * Checking input
 * Assuming success and correctness
 * Validating assumptions

**Learning Outcomes:**

[Core-Tier2]
1. Describe techniques, coding idioms and mechanisms for implementing designs to achieve desired
properties such as reliability, efficiency, and robustness. [Familiarity]
2. Build robust code using exception handling mechanisms. [Usage]
3. Describe secure coding and defensive coding practices. [Familiarity]
4. Select and use a defined coding standard in a small software project. [Usage]
5. Compare and contrast integration strategies including top-down, bottom-up, and sandwich integration.
[Familiarity]
6. Describe the process of analyzing and implementing changes to code base developed for a specific project.
[Familiarity]
7. Describe the process of analyzing and implementing changes to a large existing code base. [Familiarity]

[Elective]
8. Rewrite a simple program to remove common vulnerabilities, such as buffer overflows, integer overflows
and race conditions. [Usage]
9. Write a software component that performs some non-trivial task and is resilient to input and run-time
errors. [Usage]



## SE/Software Verification and Validation
*[4 Core-Tier2 hours]*

**Topics:**

[Core-Tier2]
* Verification and validation concepts
* Inspections, reviews, audits
* Testing types, including human computer interface, usability, reliability, security, conformance to
specification (cross-reference IAS/Secure Software Engineering)
* Testing fundamentals (cross-reference SDF/Development Methods)
 * Unit, integration, validation, and system testing
 * Test plan creation and test case generation
 * Black-box and white-box testing techniques
 * Regression testing and test automation
* Defect tracking
* Limitations of testing in particular domains, such as parallel or safety-critical systems

[Elective]
* Static approaches and dynamic approaches to verification
* Test-driven development
* Validation planning; documentation for validation
* Object-oriented testing; systems testing
* Verification and validation of non-code artifacts (documentation, help files, training materials)
* Fault logging, fault tracking and technical support for such activities
* Fault estimation and testing termination including defect seeding

**Learning Outcomes:**

[Core-Tier2]
1. Distinguish between program validation and verification. [Familiarity]
2. Describe the role that tools can play in the validation of software. [Familiarity]
3. Undertake, as part of a team activity, an inspection of a medium-size code segment. [Usage]
4. Describe and distinguish among the different types and levels of testing (unit, integration, systems, and
acceptance). [Familiarity]
5. Describe techniques for identifying significant test cases for integration, regression and system testing.
[Familiarity]
6. Create and document a set of tests for a medium-size code segment. [Usage]
7. Describe how to select good regression tests and automate them. [Familiarity]
8. Use a defect tracking tool to manage software defects in a small software project. [Usage]
9. Discuss the limitations of testing in a particular domain. [Familiarity]

[Elective]
10. Evaluate a test suite for a medium-size code segment. [Usage]
11. Compare static and dynamic approaches to verification. [Familiarity]
12. Identify the fundamental principles of test-driven development methods and explain the role of automated
testing in these methods. [Familiarity]
13. Discuss the issues involving the testing of object-oriented software. [Usage]
14. Describe techniques for the verification and validation of non-code artifacts. [Familiarity]
15. Describe approaches for fault estimation. [Familiarity]
16. Estimate the number of faults in a small software application based on fault density and fault seeding.
[Usage]
17. Conduct an inspection or review of software source code for a small or medium sized software project.
[Usage]


## SE/Software Evolution
*[2 Core-Tier2 hour]*

**Topics:**

* Software development in the context of large, pre-existing code bases
 * Software change
 * Concerns and concern location
 * Refactoring
* Software evolution
* Characteristics of maintainable software
* Reengineering systems
* Software reuse
 * Code segments
 * Libraries and frameworks
 * Components
 * Product lines

**Learning Outcomes:**

1. Identify the principal issues associated with software evolution and explain their impact on the software
lifecycle. [Familiarity]
2. Estimate the impact of a change request to an existing product of medium size. [Usage]
3. Use refactoring in the process of modifying a software component. [Usage]
4. Discuss the challenges of evolving systems in a changing environment. [Familiarity]
5. Outline the process of regression testing and its role in release management. [Familiarity]
6. Discuss the advantages and disadvantages of different types of software reuse. [Familiarity]



## SE/Software Reliability
*[1 Core-Tier2]*

**Topics:**

[Core-Tier2]
* Software reliability engineering concepts
* Software reliability, system reliability and failure behavior (cross-reference SF/Reliability Through
Redundancy)
* Fault lifecycle concepts and techniques

[Elective]
* Software reliability models
* Software fault tolerance techniques and models
* Software reliability engineering practices
* Measurement-based analysis of software reliability

**Learning Outcomes:**

[Core-Tier2]
1. Explain the problems that exist in achieving very high levels of reliability. [Familiarity]
2. Describe how software reliability contributes to system reliability. [Familiarity]
3. List approaches to minimizing faults that can be applied at each stage of the software lifecycle.
[Familiarity]
[Elective]
4. Compare the characteristics of three different reliability modeling approaches. [Familiarity]
5. Demonstrate the ability to apply multiple methods to develop reliability estimates for a software system.
[Usage]
6. Identify methods that will lead to the realization of a software architecture that achieves a specified level of
reliability. [Usage]
7. Identify ways to apply redundancy to achieve fault tolerance for a medium-sized application. [Usage



## SE/Formal Methods
*[Elective]*

The topics listed below have a strong dependency on core material from the Discrete Structures
(DS) Knowledge Area, particularly knowledge units DS/Functions Relations and Sets, DS/Basic
Logic and DS/Proof Techniques.

**Topics:**

* Role of formal specification and analysis techniques in the software development cycle
* Program assertion languages and analysis approaches (including languages for writing and analyzing preand post-conditions, such as OCL, JML)
* Formal approaches to software modeling and analysis
 * Model checkers
 * Model finders
* Tools in support of formal methods

**Learning Outcomes:**

1. Describe the role formal specification and analysis techniques can play in the development of complex
software and compare their use as validation and verification techniques with testing. [Familiarity]
2. Apply formal specification and analysis techniques to software designs and programs with low complexity.
[Usage]
3. Explain the potential benefits and drawbacks of using formal specification languages. [Familiarity]
4. Create and evaluate program assertions for a variety of behaviors ranging from simple through complex.
[Usage]
5. Using a common formal specification language, formulate the specification of a simple software system
and derive examples of test cases from the specification. [Usage]
