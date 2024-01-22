# CSC 460/660: Compiler Construction

**Instructor:** Matt Pedersen
**Phone:** 702-895-2557
**Office:** TBE B-384
**Email:** <matt.pedersen@unlv.edu>

**Class Websites:**

- General: [http://www.egr.unlv.edu/~matt](http://www.egr.unlv.edu/~matt)
- Teaching: [CSC 460/660](http://www.egr.unlv.edu/~matt)

**Communication:** We use Canvas and Discord.

## Catalogue Description

Current methods in the design and implementation of compilers. Construction of the components of an actual compiler as a term project.

## Course Description

The course has two major components:

- A 6-phase programming assignment in which the student gets hands-on experience with implementing a real compiler for a real language (The Espresso language is almost 100% Java 1.0 without exceptions and slightly altered imports).
- Lectures covering the theoretical aspects of compiler writing and string manipulation. A large amount of time is devoted to scanning, parsing, type checking, and code generation. Certain parts of the theoretical aspects are explained in terms of the assignment – the handout for the assignment is approximately 175 pages long.

## Textbook

- "Practical Compiler Construction with Java and the JVM" available on [lulu.com](https://www.lulu.com/).
- "Java Essentials for C and C++ Programmers" by Barry Boone (Recommended if the student does not know Java).

## Student Outcomes Covered by This Course

CSC 460/660 covered student outcome B: Apply design and development principles in the construction of software systems. This outcome was chosen as the 6-phase project/assignment is such an integral part of this course. The students get to write a real compiler for a real programming language. At the end, it is expected that they have approximately 15,000 lines of Java code.

Upon completion of the course, it is expected that the successful student will:

- Understand the theory behind scanning, parsing, type checking, and code generation.
- Be able to use existing programming tools like JFlex (a scanner generator) and Java CUP (a parser generator).
- Be able to implement all aspects of a semantic checker (name resolution, type checking, modifier checking) for a compiler for the Espresso Language.
- Be able to implement a code generator that generates code for the JVM virtual machine for the Espresso Language.

## Prerequisites

To qualify for this course, the student must have earned a C or better in CSC326 (Programming Languages) and CSC456 (Automata and Formal Languages).

## Grading

The following breakdown will be used in calculating the student’s grade:

- Programming Assignments (Espresso/Espresso+/Espresso*):
  - Scanning and Parsing: 5%
  - Parse Trees: 5%
  - Name Resolution: 7.5%
  - Type Checking: 10%
  - Modifier Checking: 7.5%
  - Code Generation: 15% = 50%*
- Midterm: 10%**
- Final Exam: 40%**

- If a student taking CSC460 also implements Espresso+, they get another 5% per phase, and if they implement Espresso\* then they get an additional 5%. This means that a CSC460 student can earn 10% extra on their assignments. A CSC660 student must implement Espresso+ as part of the requirement that the 6-hundred level students do more work. If a CSC660 student implements Espresso* they can earn 5% extra.

** If a student gets a better score on their final than on their midterm, the midterm will count for 0% and the final for 50%.

Course grades are calculated using this scale:

- \>91 A
- 86-90 A-
- 81-86 B+
- 76-80 B
- 70-75 B-
- 65-69 C+
- 60-64 C
- 55-63 C-
- 50-54 D
- <50 F

It should be noted, a score of 50% is required to pass. Furthermore, it is required that the student achieves a score of 50% on the overall score as well as a score of at least 50% on the written final exam to pass the course.

## Assessment

A 20 question assessment test covering student outcome B is given on the last day of the semester. These assessments are categorized into ‘Unsatisfactory’, ‘Below Expectation’, ‘Satisfactory’, and ‘Exceeds expectation’. The result of the assessment test is reported in the ABET material.
