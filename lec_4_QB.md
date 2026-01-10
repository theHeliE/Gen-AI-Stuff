# Software Testing Exam Bank - Lecture 4

**Topic: Automated Testing & Frameworks**

---

## **Part 1: Short-Word / Fill-in-the-Blank Questions (70%)**

1.  ******\_\_****** is a software testing method that uses specialized tools and scripts to execute tests automatically without human intervention.
2.  A common myth is that automated testing eliminates the need for ******\_\_****** testing, but human insight is still required for usability and exploratory testing.
3.  One major benefit of automation is that it allows for running tests ******\_\_****** (e.g., overnight) without requiring a tester to be present.
4.  Automation is highly recommended for ******\_\_****** testing, where the same test steps need to be executed repeatedly on different builds.
5.  You should **not** automate tests that run only ******\_\_****** because the cost of scripting outweighs the benefits.
6.  Tests that require visual confirmation of elements like colors, font styles, or layout are best suited for ******\_\_****** testing rather than standard functional automation.
7.  The ******\_\_****** Automation Pyramid suggests that the largest number of tests should be Unit Tests, followed by Integration/Service tests, and the fewest should be UI tests.
8.  ******\_\_****** Scripting Framework is the simplest framework where test scripts are recorded and played back sequentially, but it has high maintenance costs.
9.  In a ******\_\_****** Testing Framework, test data is separated from the test scripts, allowing the same test logic to execute with multiple sets of data.
10. The ******\_\_******-Driven Framework uses external files (like Excel) to define actions (e.g., "click", "type") using keywords, allowing non-programmers to write tests.
11. A ******\_\_****** Framework combines different frameworks (e.g., Data-Driven and Keyword-Driven) to leverage the strengths of each.
12. ******\_\_****** testing refers to running UI tests without a visible browser interface, which makes execution faster.
13. A ******\_\_****** test is one that exhibits inconsistent behavior (passes sometimes, fails others) without any code changes, often due to timing issues or environment instability.
14. ******\_\_****** Analytics in AI testing uses machine learning to predict where bugs are likely to occur, helping testers focus on high-risk areas.
15. ******\_\_****** Automation involves AI tools that automatically update test scripts when UI elements change (e.g., ID or XPath changes), reducing maintenance effort.
16. ******\_\_****** is an open-source tool primarily used for automating web applications across different browsers and platforms.
17. ******\_\_****** is the ratio of gain obtained from the automation implementation cost versus the cost of manual execution.

---

## **Part 2: Multiple Choice Questions (30%)**

18. **According to the Test Automation Pyramid, which layer should have the fewest number of tests?**
    A. Unit Tests
    B. API / Service Tests
    C. UI / E2E Tests
    D. Database Tests

19. **Which of the following is a valid criterion for selecting an automation tool?**
    A. It must be the most expensive tool available.
    B. It should support the technology stack of the application (e.g., web, mobile, desktop).
    C. It should replace all developers.
    D. It must strictly use Record and Playback only.

20. **What is the primary disadvantage of the "Record and Playback" (Linear) framework?**
    A. It requires high programming skills.
    B. It separates data from scripts.
    C. Scripts are fragile and hard to maintain if the application changes.
    D. It cannot run on Windows.

21. **Which AI-powered testing capability allows tools to identify visual differences (like color shifts or layout issues) that code-based assertions might miss?**
    A. Self-healing automation
    B. Visual AI Testing
    C. Unit Test Generation
    D. Predictive Analytics

22. **When is the best time to start planning for automation in the STLC?**
    A. After the software is completely deployed to production.
    B. During the Requirement Analysis and Test Planning phases.
    C. Only when a critical bug is found.
    D. When the manual testers go on vacation.

23. **Which framework focuses on breaking the application into separate functions or classes (e.g., Login, Logout) to reuse code across different test scripts?**
    A. Linear Framework
    B. Modular Testing Framework
    C. Keyword-Driven Framework
    D. Data-Driven Framework

24. **Which tool is specifically designed for load and performance testing?**
    A. Selenium
    B. Appium
    C. JMeter
    D. Cucumber

---

## **Answer Key**

**Part 1**

1. Automated Testing
2. Manual
3. Unattended (or 24/7)
4. Regression
5. Once
6. Manual (or Visual)
7. Test
8. Linear
9. Data-Driven
10. Keyword
11. Hybrid
12. Headless
13. Flaky
14. Predictive
15. Self-healing
16. Selenium
17. ROI (Return on Investment)

**Part 2** 18. C 19. B 20. C 21. B 22. B 23. B 24. C
