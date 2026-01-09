# Software Testing Exam Bank - Lecture 2

**Topic: Testing Concepts, STLC, & Graph Coverage**

---

## **Part 1: Short-Word / Fill-in-the-Blank Questions (70%)**

1.  The **\*\***\_\_\_\_\_\_**\*\*** (STLC) is a systematic process of testing activities carried out during the software development life cycle to ensure product quality.
2.  The first phase of the STLC is **\*\***\_\_\_\_\_\_**\*\***, where the QA team understands what needs to be tested based on documents like the BRD and SRS.
3.  A **\*\***\_\_\_\_\_\_**\*\*** is a version of the software created by developers (often containing code compilation), whereas a **\*\***\_\_\_\_\_\_**\*\*** is the final version deployed to the customer.
4.  A mistake made by a programmer in the code is called an **\*\***\_\_\_\_\_\_**\*\***.
5.  If a defect is found by the developer before release, it is commonly called a **\*\***\_\_\_\_\_\_**\*\***; if found by the tester, it is called a Defect.
6.  A **\*\***\_\_\_\_\_\_**\*\*** occurs when the software deviates from its expected behavior or requirement due to a defect executing.
7.  **\*\***\_\_\_\_\_\_**\*\*** Testing is performed to verify that the critical functionalities of the system are working fine before accepting the build for further testing.
8.  **\*\***\_\_\_\_\_\_**\*\*** Testing is a subset of regression testing performed to ensure that code changes (like bug fixes) haven't broken the basic functionality.
9.  **\*\***\_\_\_\_\_\_**\*\*** Testing involves executing a test case again to verify that a specific defect has been fixed.
10. **\*\***\_\_\_\_\_\_**\*\*** Testing ensures that recent code changes have not adversely affected existing features.
11. **\*\***\_\_\_\_\_\_**\*\*** Testing checks if the system can handle expected loads (e.g., number of users), while **\*\***\_\_\_\_\_\_**\*\*** Testing pushes the system beyond its limits to find the breaking point.
12. **\*\***\_\_\_\_\_\_**\*\*** Testing allows testers to explore the application without predefined test cases, relying on their intuition and experience.
13. In **\*\***\_\_\_\_\_\_**\*\*** Testing, random inputs are entered into the application to check for crashes (often called "Monkey Testing" if dumb, "Gorilla Testing" if heavy/repetitive).
14. A **\*\***\_\_\_\_\_\_**\*\*** is a document describing a set of steps, inputs, and expected results to verify a specific feature.
15. In Graph Coverage, a **\*\***\_\_\_\_\_\_**\*\*** is a sequence of nodes where each pair of adjacent nodes corresponds to an edge.
16. **\*\***\_\_\_\_\_\_**\*\*** Coverage (NC) requires the test set to visit every node in the graph at least once.
17. **\*\***\_\_\_\_\_\_**\*\*** Coverage (EC) requires the test set to traverse every edge in the graph at least once.
18. A path is considered **\*\***\_\_\_\_\_\_**\*\*** if it visits a node or edge that cannot be reached from the start node.

---

## **Part 2: Multiple Choice Questions (30%)**

19. **Which document is the primary output of the "Test Planning" phase in STLC?**
    A. Requirement Traceability Matrix (RTM)
    B. Test Strategy & Test Plan Document
    C. Defect Report
    D. Test Case Document

20. **What is the key difference between "Sanity Testing" and "Smoke Testing"?**
    A. Smoke testing is deep; Sanity testing is wide.
    B. Smoke testing verifies critical health; Sanity testing verifies rationality after changes.
    C. Sanity testing is scripted; Smoke testing is always random.
    D. Smoke testing is done by developers; Sanity testing is done by users.

21. **Which testing type focuses on verifying the "Look and Feel" of the application (e.g., alignment, fonts, colors)?**
    A. Usability Testing
    B. GUI Testing
    C. Functional Testing
    D. Security Testing

22. **In the context of positive vs. negative testing, what is the goal of "Negative Testing"?**
    A. To verify the system works with valid input.
    B. To ensure the system handles invalid input gracefully without crashing.
    C. To test the system's performance under low load.
    D. To find UI defects.

23. **What does "Edge-Pair Coverage" (EPC) require?**
    A. Visiting every node twice.
    B. Traversing all paths of length up to 2, inclusive.
    C. Visiting every edge in the graph.
    D. Traversing all possible paths in the graph.

24. **Which test document maps user requirements to test cases to ensure full coverage?**
    A. Test Scenario
    B. Test Plan
    C. Requirement Traceability Matrix (RTM)
    D. Defect Report

25. **If a graph contains a loop, which coverage criterion is technically impossible to achieve in its fullest sense?**
    A. Node Coverage
    B. Edge Coverage
    C. Complete Path Coverage (CPC)
    D. Edge-Pair Coverage

26. **What is the purpose of the "Test Cycle Closure" phase?**
    A. To write new test cases.
    B. To execute the final regression suite.
    C. To prepare a closure report and discuss lessons learned.
    D. To set up the test environment.

---

## **Answer Key**

**Part 1**

1. Software Testing Life Cycle
2. Requirement Analysis
3. Build, Release
4. Error
5. Bug
6. Failure
7. Smoke
8. Sanity
9. Retesting
10. Regression
11. Load, Stress
12. Exploratory
13. Monkey (or Ad-hoc)
14. Test Case
15. Path
16. Node
17. Edge
18. Infeasible

**Part 2** 19. B 20. B 21. B 22. B 23. B 24. C 25. C 26. C
