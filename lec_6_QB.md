# Software Testing Exam Bank - Lecture 6

**Topic: Test Planning, Risk Analysis & Modeling with LLMs**

---

## **Part 1: Short-Word / Fill-in-the-Blank Questions (70%)**

1.  In the "Imagination vs. Implementation" model, the ******\_\_****** circle represents what we _want_ in a product (requirements, desires, and expectations).
2.  In the "Imagination vs. Implementation" model, the ******\_\_****** circle represents what we _have_ (code, infrastructure, and data).
3.  According to James Lyndsay's strategy model, behaviors that are "Got but not expected" are categorized as ******\_\_******.
4.  The testing process is visualized as a continuous cycle starting with ******\_\_****** test ideas and ending with reporting findings.
5.  ******\_\_****** capability refers to an LLM's ability to create new content, such as synthetic user profiles or risk suggestions.
6.  ******\_\_****** capability refers to an LLM's ability to convert information from one format to another, such as plain text to SQL.
7.  ******\_\_****** capability refers to using an LLM to add detail or explain existing material, such as adding comments to code.
8.  The main driver of any test plan should be the ******\_\_****** to the product and project.
9.  The ******\_\_****** of Effect model illustrates that an individual's abilities (like skepticism and analysis) are the core, which is then enhanced by tools.
10. Weak prompts that lack context lead to ******\_\_****** suggestions from the LLM, often requiring significant rework.
11. A ******\_\_****** is an abstract representation of a system that simplifies reality to focus on specific attributes.
12. A ******\_\_****** Flow Diagram (DFD) models how information moves through a system and is useful for identifying data-handling risks.
13. ******\_\_****** diagrams (like Component diagrams) allow testers to break down a system's architecture to create focused prompts.
14. A ******\_\_****** Flow diagram illustrates the steps a user takes (e.g., Start → Login → View Bookings) and is useful for condition-based prompts.
15. The mnemonic ******\_\_****** stands for Structure, Function, Data, Interfaces, Platform, Operations, and Time.
16. In the SFDIPOT mnemonic, the letter ******\_\_****** refers to "what the product does."
17. In the SFDIPOT mnemonic, the letter ******\_\_****** refers to "how time affects the product" (e.g., concurrency, speed).
18. LLMs should be viewed as ******\_\_****** to the tester, not as authorities that decide what to test.
19. Overreliance on LLM-generated test cases can create a ******\_\_****** of tests, which can reduce product quality instead of improving it.
20. To avoid hallucinations and off-topic suggestions, prompts should include specific ******\_\_****** derived from system models.

---

## **Part 2: Multiple Choice Questions (30%)**

21. **What is the primary goal of testing according to the "Imagination vs. Implementation" model?**
    A. To write as many test cases as possible.
    B. To decrease the gap between what was intended and what was built.
    C. To prove that the code has zero bugs.
    D. To automate the implementation circle.

22. **Which LLM capability is best utilized when asking the model to "Explain what this complex code snippet does"?**
    A. Generative
    B. Transformation
    C. Enhancement
    D. Translation

23. **Why is it recommended to focus on "Risks" rather than "Test Cases" when using LLMs for planning?**
    A. LLMs cannot write test cases.
    B. Asking for test cases limits you to one activity, whereas risks uncover broad testing concerns.
    C. Risks are easier to automate.
    D. Test cases consume more tokens.

24. **In the context of model-based prompting, why is a "Data Flow Diagram" useful?**
    A. It shows the exact UI layout of the application.
    B. It highlights relationships and dependencies between APIs and data sources.
    C. It provides the full source code of the system.
    D. It lists all the project stakeholders.

25. **Which formal modeling technique uses "Component Diagrams" to break down system architecture?**
    A. DFD (Data Flow Diagram)
    B. UML (Unified Modeling Language)
    C. SFDIPOT
    D. Gantt Chart

26. **What does the "T" in the heuristic mnemonic SFDIPOT stand for?**
    A. Testing
    B. Tools
    C. Time
    D. Technology

27. **What is the "Area of Effect" model intended to demonstrate?**
    A. That tools should replace human testers.
    B. That an individual's core skills (analysis, skepticism) are enhanced, not replaced, by tools.
    C. That the area of testing should be as small as possible.
    D. That LLMs have a limited effect on software quality.

28. **If a tester wants to test how a product behaves under "Heavy Load" or "Slow Network," which SFDIPOT aspect are they primarily applying?**
    A. Structure
    B. Platform
    C. Time
    D. Data

---

## **Answer Key**

**Part 1**

1.  Imagination
2.  Implementation
3.  Risky
4.  Formulating
5.  Generative
6.  Transformation
7.  Enhancement
8.  Risks
9.  Area
10. Weak
11. Model
12. Data
13. UML (or Structural)
14. User
15. SFDIPOT
16. F (Function)
17. T (Time)
18. Assistants
19. Monoculture
20. Context

**Part 2** 21. B 22. C 23. B 24. B 25. B 26. C 27. B 28. C
