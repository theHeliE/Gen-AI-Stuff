# Software Testing Exam Bank - Lecture 3

**Topic: Coverage Criteria & Input Space Partitioning**

---

## **Part 1: Short-Word / Fill-in-the-Blank Questions (70%)**

1.  A path from node $n_i$ to $n_j$ is considered **\*\***\_\_\_\_\_\_**\*\*** if no node appears more than once, except possibly the first and last nodes are the same.
2.  A **\*\***\_\_\_\_\_\_**\*\*** Path is defined as a simple path that does not appear as a proper subpath of any other simple path.
3.  In Input Space Partitioning, the inputs to a program are divided into partitions which typically contain sets of **\*\***\_\_\_\_\_\_**\*\***.
4.  Two critical properties that partitions must satisfy are **\*\***\_\_\_\_\_\_**\*\*** and Completeness (covers all inputs).
5.  **\*\***\_\_\_\_\_\_**\*\***-Based Input Domain Modeling derives characteristics directly from the type of the input parameters.
6.  **\*\***\_\_\_\_\_\_**\*\***-Based Input Domain Modeling derives characteristics from the intended behavior or semantics of the software.
7.  **\*\***\_\_\_\_\_\_**\*\*** Combinations coverage requires that every combination of blocks from all characteristics be used.
8.  **\*\***\_\_\_\_\_\_**\*\*** Choice coverage uses a "base" test by selecting the simplest or most likely value for each characteristic and varying one parameter at a time.
9.  **\*\***\_\_\_\_\_\_**\*\***-Wise coverage requires that every pair of values from any two parameters appears in at least one test case.
10. **\*\***\_\_\_\_\_\_**\*\*** Base Choice is a criterion where one or more base choice blocks are chosen for each characteristic.
11. If a graph has internal loops, a path that traverses the loop more than once cannot be a **\*\***\_\_\_\_\_\_**\*\*** path.
12. **\*\***\_\_\_\_\_\_**\*\*** Coverage requires that every block in every characteristic be used in at least one test case.

---

## **Part 2: Multiple Choice Questions (30%)**

13. **Which of the following best describes a "Prime Path"?**
    A. A path that visits every node in the graph.
    B. A simple path that is not a proper subpath of any other simple path.
    C. A path with at least one cycle.
    D. The shortest path between two nodes.

14. **In the context of Coverage Criteria Subsumption, which statement is true?**
    A. Pair-Wise Coverage subsumes All Combinations Coverage.
    B. Each Choice Coverage subsumes T-Wise Coverage.
    C. All Combinations Coverage subsumes T-Wise Coverage.
    D. Base Choice Coverage subsumes Multiple Base Choice Coverage.

15. **What is the formula for the number of tests in Base Choice (BC) coverage, assuming $Q$ characteristics with $B_i$ blocks each?**
    A. $\prod B_i$
    B. $1 + \sum (B_i - 1)$
    C. $\sum B_i$
    D. $M + \sum (M * (B_i - m_i))$

16. **Which Input Domain Modeling approach requires more design effort but typically results in better tests?**
    A. Interface-Based (IDM)
    B. Functionality-Based (FDM)
    C. Random Testing
    D. Syntax-Based Modeling

17. **If you have characteristics with blocks {A, B} and {1, 2, 3}, which criterion would require the most test cases?**
    A. Each Choice (EC)
    B. Pair-Wise (PW)
    C. Base Choice (BC)
    D. All Combinations (AC)

---

## **Answer Key**

**Part 1**

1. Simple
2. Prime
3. Blocks
4. Disjointness
5. Interface
6. Functionality
7. All
8. Base
9. Pair
10. Multiple
11. Simple
12. Each

**Part 2** 13. B 14. C 15. B 16. B 17. D

