
# Chapter 5: Introductory Courses

Computer science, unlike many technical disciplines, does not have a well-described list of 
topics that appear in virtually all introductory courses. In considering the changing landscape of 
introductory courses, we look at the evolution of such courses from CC2001 to CS2013. 

CC2001 classified introductory course sequences into six general models: Imperative-first, 
Objects-first, Functional-first, Breadth-first, Algorithms-first, and Hardware-first. While 
introductory courses with these characteristic features certainly still exist today, we believe that 
advances in the field have led to an even more diverse set of approaches in introductory courses 
than the models set out in CC2001. Moreover, the approaches employed in introductory courses 
are in a greater state of flux.

An important challenge for introductory courses, and a key reason the content of such courses 
remains a vigorous discussion topic after decades of debate, is that not everything relevant to a 
computer scientist (programming, software processes, algorithms, abstraction, performance, 
security, professionalism, etc.) can be taught from day one. In other words, not everything can 
come first and as a result some topics must be pushed further back in the curriculum, in some 
cases significantly so. Many topics will not appear in a first course or even a second course, 
meaning that students who do not continue further (for example, non-majors) will lose exposure 
to these topics. Ultimately, choosing what to cover in introductory courses results in a set of 
tradeoffs that must be considered when trying to decide what should be covered early in a 
curriculum.

## Design Dimensions

We structure this chapter as a set of design dimensions relevant to crafting introductory courses, 
concluding each dimension with a summary of the trade-offs that are in tension along the 
dimension. A given introductory course, or course sequence, in computer science will represent 
a set of decisions within this multidimensional design space and achieve distinctive outcomes as 
a result. We note that our discussion here focuses on introductory courses meant as part of an 
undergraduate program in computer science. Notably, we do not discuss the increasingly
common“CS0” courses: precursor courses often focusing on computer fluency or computational 
thinking. Such courses may include some introductory computer science concepts or material, 
but are not part of this Body of Knowledge and are outside the scope of our consideration.

### Pathways Through Introductory Courses

We recognize that introductory courses are not constructed in the abstract, but rather are 
designed for specific target audiences and contexts. Departments know their institutional 
contexts best and must be sensitive to their own students and their needs. Introductory courses 
differ across institutions, especially with regard to the nature and length of an introductory 
sequence (that is, the number of courses that a student must take before any branching is 
allowed). A sequence of courses may also have different entry points to accommodate students 
with significant differences in previous computing experience and/or who come from a wide 
diversity of backgrounds. Having multiple pathways into and through the introductory course 
sequence can help to better align students’ abilities with the appropriate level of coursework. It 
can also help create more flexibility with articulation between two-year and four-year 
institutions, and smooth the transition for students transferring from other colleges/programs. 
Increasingly, computing in general and programming in particular are essential to students in 
other fields. Courses for these non-majors may or may not be distinct from courses that lead to 
years of computer science study. Additionally, having multiple pathways through introductory 
courses may provide greater options to students who choose to start take courses in computing 
late in their college programs.

Building courses for diverse audiences – not just students who are already sure of a major in 
computer science – is essential for making computing accessible to a wide range of students. 
Given the importance of computation across many disciplines, the appeal of introductory 
programming courses has significantly broadened beyond the traditionally accommodated 
engineering fields. For target audiences with different backgrounds, and different expectations, 
the practice of having thematically-focused introductory courses (e.g., computational biology, 
robotics, digital media manipulation, etc.) has become popular. In this way, material is made 
relevant to the expectations and aspirations of students with a variety of disciplinary orientations.

**Tradeoffs:**

* Providing multiple pathways into and through introductory course sequences can make 
computer science more accessible to different audiences, but requires greater investment 
(in work and resources) by a department to construct such pathways and/or provide 
different themed options to students. Moreover, care must be taken to give students 
guidance with regard to choosing an appropriate introductory course pathway. (This is as 
true for those students with extensive prior computing experience as for those with none.) 
* By having longer introductory course sequences (i.e., longer or more structured prerequisite chains), educators can assume more prior knowledge in each course, but such 
lengthy sequences sacrifice flexibility and increase the time before students are able to 
take advanced courses more focused on their areas of interest.

### Programming Focus

The vast majority of introductory courses are programming-focused, in which students learn 
about concepts in computer science (e.g., abstraction, decomposition, etc.) through the explicit 
tasks of learning a given programming language and building software artifacts. A programming 
focus can provide early training in this crucial skill for computer science majors and help elevate 
students with different backgrounds in computing to a more equal footing. Even given a 
programming focus, there is a further subdivision between having students write whole programs 
– to ensure understanding how the pieces fit together and give the full experience of program 
construction – versus having students complete or modify existing programs and skeletons, 
which can be more like real-world experience and allow creating larger and more complex 
programs. Moving away from emphasizing programming, some introductory courses are 
designed to provide a broader introduction to concepts in computing without the constraints of 
learning the syntax of a programming language. They are consciously programming de-focused. 
Such a perspective is roughly analogous to the “Breadth-first” model in CC2001. Whether or not 
programming is the primary focus of their first course, it is important that students do not 
perceive computer science as only learning the specifics of particular programming languages. 
Care must be taken to emphasize the more general concepts in computing within the context of 
learning how to program.

**Tradeoffs:** A programming-focused introductory course can help develop essential skills in 
students early on and provide a lingua franca in which other computer science concepts can be 
described. This programming focus may also be useful for students from other areas of study 
who wish to use programming as a tool in cross-disciplinary work. However, too narrow a 
programming focus in an introductory class, while giving immediate facility in a programming 
language, can also give students a too-narrow (and misleading) view of the place of 
programming in the field. Such a narrow perspective may limit the appeal of computer science 
for some students.

### Programming Paradigm and Choice of Language

A defining factor for many introductory courses is the choice of programming paradigm, which 
then drives the choice of programming language. Indeed, half of the six introductory course 
models listed in CC2001 were described by programming paradigm (Imperative-first, Objectsfirst, Functional-first). Such paradigm-based introductory courses still exist and their relative 
merits continue to be debated. We note that rather than a particular paradigm or language 
coming to be favored over time, the past decade has only broadened the list of programming 
languages now successfully used in introductory courses. There does, however, appear to be a 
growing trend toward “safer” or more managed languages (for example, moving from C to Java) 
as well as the use of more dynamic languages, such as Python or JavaScript. Visual 
programming languages, such as Alice and Scratch, have also become popular choices to provide 
a “syntax-light” introduction to programming; these are often (although not exclusively) used 
with non-majors or at the start of an introductory course. Some introductory course sequences 
choose to provide a presentation of alternative programming paradigms, such as scripting vs. 
procedural programming or functional vs. object-oriented programming, to give students a 
greater appreciation of the diverse perspectives in programming, to avoid language-feature 
fixation, and to disabuse them of the notion that there is a single “correct” or “best” 
programming language. 

**Tradeoffs:** This is an area where there are numerous tradeoffs, including:
* The use of “safer” or more managed languages and environments can help scaffold 
students’ learning. But, such languages may provide a level of abstraction that obscures 
an understanding of actual machine execution and makes is difficult to evaluate 
performance trade-offs. The decision as to whether to use a “lower-level” language to 
promote a particular mental model of program execution that is closer to the actual 
execution by the machine is often a matter of local audience needs.
* The use of a language or environment designed for introductory pedagogy can facilitate 
student learning, but may be of limited use beyond CS1. Conversely, a language or 
environment commonly used professionally may expose students to too much complexity 
too soon.

### Software Development Practices
While programming is the means by which software is constructed, an introductory course may 
choose to present additional practices in software development to different extents. For example, 
the use of software development best practices, such as unit testing, version control systems, 
industrial integrated development environments (IDEs), and programming patterns may be 
stressed to different extents in different introductory courses. The inclusion of such software 
development practices can help students gain an early appreciation of some of the challenges in 
developing real software projects. On the other hand, while all computer scientists should have 
solid software development skills, those skills need not always be the primary focus of the first 
introductory programming course, especially if the intended audience is not just computer 
science majors. Care should be taken in introductory courses to balance the use of software 
development best practices from the outset with making introductory courses accessible to a 
broad population.

**Tradeoffs:** The inclusion of software development practices in introductory courses can help 
students develop important aspects of real-world software development early on. The extent to 
which such practices are included in introductory courses may impact and be impacted by the 
target audience for the course, and the choice of programming language and development 
environment. 

### Parallel Processing
Traditionally, introductory courses have assumed the availability of a single processor, a single 
process, and a single thread, with the execution of the program being completely driven by the 
programmer’s instructions and expectation of sequential execution. Recent hardware and 
software developments have prompted educators to rethink these assumptions, even at the 
introductory level — multicore processors are now ubiquitous, user interfaces lend themselves to 
asynchronous event-driven processing, and “big data” requires parallel processing and 
distributed storage. As a result, some introductory courses stress parallel processing from the 
outset (with traditional single threaded execution models being considered a special case of the 
more general parallel paradigm). While we believe this is an interesting model to consider in the 
long-term, we anticipate that introductory courses will still be dominated by the “single thread of 
execution” model (perhaps with the inclusion of GUI-based or robotic event-driven 
programming) for the foreseeable future. As more successful pedagogical approaches are 
developed to make parallel processing accessible to novice programmers, and paradigms for 
parallel programming become more commonplace, we expect to see more elements of parallel 
programming appearing in introductory courses. 

**Tradeoffs:** Understanding parallel processing is becoming increasingly important for computer 
science majors and learning such models early on can give students more practice in this arena. 
On the other hand, parallel programming remains more difficult in most contemporary 
programming environments.

### Platform
While many introductory programming courses make use of traditional computing platforms 
(e.g., desktop/laptop computers) and are, as a result, somewhat “hardware agnostic,” the past few 
years have seen a growing diversity in the set of programmable devices that are employed in 
such courses. For example, some introductory courses may choose to engage in web 
development or mobile device (e.g., smartphone, tablet) programming. Others have examined 
the use of specialty platforms, such as robots or game consoles, which may help generate more
enthusiasm for the subject among novices as well as emphasizing interaction with the external 
world as an essential and natural focus. Recent developments have led to physically-small, 
feature-restricted computational devices constructed specifically for the purpose of facilitating 
learning programming (e.g., raspberry-pi). In any of these cases, the use of a particular platform 
brings with it attendant choices for programming paradigms, component libraries, APIs, and 
security. Working within the software/hardware constraints of a given platform is a useful 
software-engineering skill, but also comes at the cost that the topics covered in the course may 
likewise be limited by the choice of platform.

**Tradeoffs:** The use of specific platforms can bring compelling real-world contexts into the 
classroom and platforms designed for pedagogy can have beneficial focus. However, it requires 
considerable care to ensure that platform-specific details do not swamp pedagogic objectives. 
Moreover, the specificity of the platform may impact the transferability of course content to 
downstream courses.

## Mapping to the Body of Knowledge
Practically speaking, an introductory course sequence should not be construed as simply 
containing only the topics from the Software Development Fundamentals (SDF) Knowledge 
Area. Rather we encourage implementers of the CS2013 guidelines to think about the design 
space dimensions outlined above to draw on materials from multiple KAs for inclusion in an 
introductory course sequence. For example, even a fairly straightforward introductory course 
sequence will likely augment material from SDF with topics from the Programming Languages 
Knowledge Area related to the choice of language used in the course and potentially some 
concepts from Software Engineering. More broadly, a course using non-traditional platforms 
will draw from topics in Platform-Based Development and those emphasizing multi-processing 
will naturally include material from Parallel and Distributed Computing. We encourage readers 
to think of the CS2013 Body of Knowledge as an invitation for the construction of creative new 
introductory course sequences that best fit the needs of students at one’s local institution. 
