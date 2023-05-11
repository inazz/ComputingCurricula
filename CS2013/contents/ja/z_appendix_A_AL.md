
# アルゴリズムと計算量 (AL)
Algorithms are fundamental to computer science and software engineering. The real-world
performance of any software system depends on: (1) the algorithms chosen and (2) the suitability
and efficiency of the various layers of implementation. Good algorithm design is therefore
crucial for the performance of all software systems. Moreover, the study of algorithms provides
insight into the intrinsic nature of the problem as well as possible solution techniques
independent of programming language, programming paradigm, computer hardware, or any
other implementation aspect.

An important part of computing is the ability to select algorithms appropriate to particular
purposes and to apply them, recognizing the possibility that no suitable algorithm may exist. This
facility relies on understanding the range of algorithms that address an important set of welldefined problems, recognizing their strengths and weaknesses, and their suitability in particular
contexts. Efficiency is a pervasive theme throughout this area.

This knowledge area defines the central concepts and skills required to design, implement, and
analyze algorithms for solving problems. Algorithms are essential in all advanced areas of
computer science: artificial intelligence, databases, distributed computing, graphics, networking,
operating systems, programming languages, security, and so on. Algorithms that have specific
utility in each of these are listed in the relevant knowledge areas. Cryptography, for example,
appears in the new Knowledge Area on Information Assurance and Security (IAS), while parallel
and distributed algorithms appear the Knowledge Area in Parallel and Distributed Computing
(PD).

As with all knowledge areas, the order of topics and their groupings do not necessarily correlate
to a specific order of presentation. Different programs will teach the topics in different courses
and should do so in the order they believe is most appropriate for their students.


**AL. アルゴリズムと計算量 (必修 19時間, 選択必修 9時間)**

| 知識単位 | 必修時間 | 選択必修時間 | 含選択科目 |
| -------- | -------- | ------------ | ---------- |
| AL/計算量の解析                             | 2 | 2 | N |
| AL/アルゴリズム設計の手法                   | 5 | 1 | N |
| AL/基本データ構造とアルゴリズム             | 9 | 3 | N |
| AL/形式言語・計算可能性・計算量の基礎       | 3 | 3 | N |
| AL/高度な計算量理論                         |   |   | Y |
| AL/高度な形式言語理論・計算可能性理論       |   |   | Y |
| AL/高度なデータ構造やアルゴリズムとその解析 |   |   | Y |



## AL/計算量の解析
*[必修 2時間, 選択必修 2時間]*

**トピック:**

[Core-Tier1]
* Differences among best, expected, and worst case behaviors of an algorithm
* Asymptotic analysis of upper and expected complexity bounds
* Big O notation: formal definition
* Complexity classes, such as constant, logarithmic, linear, quadratic, and exponential
* Empirical measurements of performance
* Time and space trade-offs in algorithms

[Core-Tier2]
* Big O notation: use
* Little o, big omega and big theta notation
* Recurrence relations
* Analysis of iterative and recursive algorithms
* Some version of a Master Theorem

**学習到達目標:**

[Core-Tier1]

1. Explain what is meant by “best”, “expected”, and “worst” case behavior of an algorithm. [Familiarity]
2. In the context of specific algorithms, identify the characteristics of data and/or other conditions or
assumptions that lead to different behaviors. [Assessment]
3. Determine informally the time and space complexity of simple algorithms. [Usage]
4. State the formal definition of big O. [Familiarity]
5. List and contrast standard complexity classes. [Familiarity]
6. Perform empirical studies to validate hypotheses about runtime stemming from mathematical analysis.
Run algorithms on input of various sizes and compare performance. [Assessment]
7. Give examples that illustrate time-space trade-offs of algorithms. [Familiarity]

[Core-Tier2]

8. Use big O notation formally to give asymptotic upper bounds on time and space complexity of algorithms.
[Usage]
9. Use big O notation formally to give expected case bounds on time complexity of algorithms. [Usage]
10. Explain the use of big omega, big theta, and little o notation to describe the amount of work done by an
algorithm. [Familiarity]
11. Use recurrence relations to determine the time complexity of recursively defined algorithms. [Usage]
12. Solve elementary recurrence relations, e.g., using some form of a Master Theorem. [Usage]



## AL/アルゴリズム設計の手法
*[必修 5時間, 選択必修 1時間]*

An instructor might choose to cover these algorithmic strategies in the context of the algorithms
presented in “Fundamental Data Structures and Algorithms” below. While the total number of
hours for the two knowledge units (18) could be divided differently between them, our sense is
that the 1:2 ratio is reasonable.

**トピック:**

[Core-Tier1]

* Brute-force algorithms
* Greedy algorithms
* Divide-and-conquer (cross-reference SDF/Algorithms and Design/Problem-solving strategies)
* Recursive backtracking
* Dynamic Programming

[Core-Tier2]
* Branch-and-bound
* Heuristics
* Reduction: transform-and-conquer

**学習到達目標:**

[Core-Tier1]

1. For each of the strategies (brute-force, greedy, divide-and-conquer, recursive backtracking, and dynamic
programming), identify a practical example to which it would apply. [Familiarity]
2. Use a greedy approach to solve an appropriate problem and determine if the greedy rule chosen leads to an
optimal solution. [Assessment]
3. Use a divide-and-conquer algorithm to solve an appropriate problem. [Usage]
4. Use recursive backtracking to solve a problem such as navigating a maze. [Usage]
5. Use dynamic programming to solve an appropriate problem. [Usage]
6. Determine an appropriate algorithmic approach to a problem. [Assessment]

[Core-Tier2]

7. Describe various heuristic problem-solving methods. [Familiarity]
8. Use a heuristic approach to solve an appropriate problem. [Usage]
9. Describe the trade-offs between brute force and heuristic strategies. [Assessment]
10. Describe how a branch-and-bound approach may be used to improve the performance of a heuristic
method. [Familiarity]



## AL/基本データ構造とアルゴリズム
*[必修 9時間, 選択必修 3時間]*

This knowledge unit builds directly on the foundation provided by Software Development
Fundamentals (SDF), particularly the material in SDF/Fundamental Data Structures and
SDF/Algorithms and Design.

**トピック:**

[Core-Tier1]

* Simple numerical algorithms, such as computing the average of a list of numbers, finding the min, max,
and mode in a list, approximating the square root of a number, or finding the greatest common divisor
* Sequential and binary search algorithms
* Worst case quadratic sorting algorithms (selection, insertion)
* Worst or average case O(N log N) sorting algorithms (quicksort, heapsort, mergesort)
* Hash tables, including strategies for avoiding and resolving collisions
* Binary search trees
 * Common operations on binary search trees such as select min, max, insert, delete, iterate over tree
* Graphs and graph algorithms
 * Representations of graphs (e.g., adjacency list, adjacency matrix)
 * Depth- and breadth-first traversals

[Core-Tier2]

* Heaps
* Graphs and graph algorithms
 * Shortest-path algorithms (Dijkstra’s and Floyd’s algorithms)
 * Minimum spanning tree (Prim’s and Kruskal’s algorithms)
* Pattern matching and string/text algorithms (e.g., substring matching, regular expression matching, longest
common subsequence algorithms)

**学習到達目標:**

[Core-Tier1]

1. Implement basic numerical algorithms. [Usage]
2. Implement simple search algorithms and explain the differences in their time complexities. [Assessment]
3. Be able to implement common quadratic and O(N log N) sorting algorithms. [Usage]
4. Describe the implementation of hash tables, including collision avoidance and resolution. [Familiarity]
5. Discuss the runtime and memory efficiency of principal algorithms for sorting, searching, and hashing.
[Familiarity]
6. Discuss factors other than computational efficiency that influence the choice of algorithms, such as
programming time, maintainability, and the use of application-specific patterns in the input data.
[Familiarity]
7. Explain how tree balance affects the efficiency of various binary search tree operations. [Familiarity]
8. Solve problems using fundamental graph algorithms, including depth-first and breadth-first search. [Usage]
9. Demonstrate the ability to evaluate algorithms, to select from a range of possible options, to provide
justification for that selection, and to implement the algorithm in a particular context. [Assessment]

[Core-Tier2]

10. Describe the heap property and the use of heaps as an implementation of priority queues. [Familiarity]
11. Solve problems using graph algorithms, including single-source and all-pairs shortest paths, and at least
one minimum spanning tree algorithm. [Usage]
12. Trace and/or implement a string-matching algorithm. [Usage]


## AL/形式言語・計算可能性・計算量の基礎
*[必修 3時間, 選択必修 3時間]*

**トピック:**

[Core-Tier1]

* Finite-state machines
* Regular expressions
* The halting problem

[Core-Tier2]

* Context-free grammars (cross-reference PL/Syntax Analysis)
* Introduction to the P and NP classes and the P vs. NP problem
* Introduction to the NP-complete class and exemplary NP-complete problems (e.g., SAT, Knapsack)

**学習到達目標:**

[Core-Tier1]

1. Discuss the concept of finite state machines. [Familiarity]
2. Design a deterministic finite state machine to accept a specified language. [Usage]
3. Generate a regular expression to represent a specified language. [Usage]
4. Explain why the halting problem has no algorithmic solution. [Familiarity]

[Core-Tier2]

5. Design a context-free grammar to represent a specified language. [Usage]
6. Define the classes P and NP. [Familiarity]
7. Explain the significance of NP-completeness. [Familiarity]



## AL/高度な計算量理論
*[選択科目]*

**トピック:**
* Review of the classes P and NP; introduce P-space and EXP
* Polynomial hierarchy
* NP-completeness (Cook’s theorem)
* Classic NP-complete problems
* Reduction Techniques

**学習到達目標:**
1. Define the classes P and NP. (Also appears in AL/Basic Automata, Computability, and Complexity).
[Familiarity]
2. Define the P-space class and its relation to the EXP class. [Familiarity]
3. Explain the significance of NP-completeness. (Also appears in AL/Basic Automata, Computability, and
Complexity). [Familiarity]
4. Provide examples of classic NP-complete problems. [Familiarity]
5. Prove that a problem is NP-complete by reducing a classic known NP-complete problem to it. [Usage]



## AL/高度な計算量理論
*[選択科目]*

**トピック:**
* Sets and languages
 * Regular languages
 * Review of deterministic finite automata (DFAs)
 * Nondeterministic finite automata (NFAs)
 * Equivalence of DFAs and NFAs
 * Review of regular expressions; their equivalence to finite automata
 * Closure properties
 * Proving languages non-regular, via the pumping lemma or alternative means
* Context-free languages
 * Push-down automata (PDAs)
 * Relationship of PDAs and context-free grammars
 * Properties of context-free languages
* Turing machines, or an equivalent formal model of universal computation
* Nondeterministic Turing machines
* Chomsky hierarchy
* The Church-Turing thesis
* Computability
* Rice’s Theorem
* Examples of uncomputable functions
* Implications of uncomputability

**学習到達目標:**
1. Determine a language’s place in the Chomsky hierarchy (regular, context-free, recursively enumerable).
[Assessment]
2. Convert among equivalently powerful notations for a language, including among DFAs, NFAs, and regular
expressions, and between PDAs and CFGs. [Usage]
3. Explain the Church-Turing thesis and its significance. [Familiarity]
4. Explain Rice’s Theorem and its significance. [Familiarity]
5. Provide examples of uncomputable functions. [Familiarity]
6. Prove that a problem is uncomputable by reducing a classic known uncomputable problem to it. [Usage]



## AL/高度なデータ構造やアルゴリズムとその解析
*[選択科目]*

Many programs will want their students to have exposure to more advanced algorithms or
methods of analysis. Below is a selection of possible advanced topics that are current and timely
but by no means exhaustive.

**トピック:**

* Balanced trees (e.g., AVL trees, red-black trees, splay trees, treaps)
* Graphs (e.g., topological sort, finding strongly connected components, matching)
* Advanced data structures (e.g., B-trees, Fibonacci heaps)
* String-based data structures and algorithms (e.g., suffix arrays, suffix trees, tries)
* Network flows (e.g., max flow [Ford-Fulkerson algorithm], max flow – min cut, maximum bipartite
matching)
* Linear Programming (e.g., duality, simplex method, interior point algorithms)
* Number-theoretic algorithms (e.g., modular arithmetic, primality testing, integer factorization)
* Geometric algorithms (e.g., points, line segments, polygons. [properties, intersections], finding convex hull,
spatial decomposition, collision detection, geometric search/proximity)
* Randomized algorithms
* Stochastic algorithms
* Approximation algorithms
* Amortized analysis
* Probabilistic analysis
* Online algorithms and competitive analysis

**学習到達目標:**

1. Understand the mapping of real-world problems to algorithmic solutions (e.g., as graph problems, linear
programs, etc.). [Assessment]
2. Select and apply advanced algorithmic techniques (e.g., randomization, approximation) to solve real
problems. [Assessment]
3. Select and apply advanced analysis techniques (e.g., amortized, probabilistic, etc.) to algorithms.
[Assessment]

