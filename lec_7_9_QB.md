# Generative AI for Software Testing - Comprehensive Exam Bank

**Covering Lectures 7, 8, & 9**

---

## **Lecture 7: Rapid Data Creation & Exploratory Testing**

### **Part 1: Short-Word / Fill-in-the-Blank Questions (70%)**

1.  LLMs are described as **\*\***\_\_\_\_\_\_**\*\*** text generators, which implies they predict the next word based on likelihood rather than understanding truth[cite: 23].
2.  To improve the quality of JSON output and reduce hallucinations, prompts should apply the **\*\***\_\_\_\_\_\_**\*\*** principle, instructing the LLM to check its work before outputting[cite: 45].
3.  When prompting for data generation, characters like `%` or `|` are used as **\*\***\_\_\_\_\_\_**\*\*** to set clear rules for parameters and data structures[cite: 54, 58].
4.  If a prompt is vague about relationships (e.g., between room type and bed count), the LLM may fill in details on its own, often resulting in **\*\***\_\_\_\_\_\_**\*\*** or inaccurate outputs[cite: 147].
5.  To generate valid XML data, it is more efficient to use a standard specification format like **\*\***\_\_\_\_\_\_**\*\*** in the prompt rather than defining all rules manually[cite: 433].
6.  Using **\*\***\_\_\_\_\_\_**\*\*** V3.0 specifications in prompts increases the likelihood of accurate generation because LLMs have likely been trained on these standard frameworks[cite: 315].
7.  When generating SQL statements, asking the LLM to create both the **\*\***\_\_\_\_\_\_**\*\*** table statement and the INSERT statement provides better context for data types and constraints[cite: 228].
8.  To ensure data consistency across multiple SQL tables (e.g., `rooms` and `bookings`), it is recommended to use the **\*\***\_\_\_\_\_\_**\*\*** tactic by providing examples within the prompt[cite: 566].
9.  Prompts should be stored in **\*\***\_\_\_\_\_\_**\*\*** files to allow for reuse and easier maintenance by non-technical team members[cite: 621].
10. Using real user data or intellectual property in prompts can violate **\*\***\_\_\_\_\_\_**\*\*** policies, so dummy data structures should be used instead[cite: 629].
11. **\*\***\_\_\_\_\_\_**\*\*** Testing is defined as a software testing approach that combines simultaneous learning, test design, and test execution[cite: 649].
12. Exploratory Testing relies on the tester's **\*\***\_\_\_\_\_\_**\*\*** and intuition rather than pre-written test scripts[cite: 651].
13. ET is not "testing without **\*\***\_\_\_\_\_\_**\*\***"; testers must still document their insights and findings[cite: 661].
14. A **\*\***\_\_\_\_\_\_**\*\*** map helps visually organize ideas, flows, and test conditions to quickly uncover areas worth exploring[cite: 686].
15. **\*\***\_\_\_\_\_\_**\*\***-based exploratory testing focuses efforts on areas with the highest potential impact or likelihood of failure[cite: 708].
16. **\*\***\_\_\_\_\_\_**\*\*** guessing is a technique where the tester uses experience to predict where defects are most likely to occur (e.g., blank fields)[cite: 720].
17. Testing values at the limits of functionality, such as age 17 or 66 for an 18-65 range, is known as **\*\***\_\_\_\_\_\_**\*\*** exploration[cite: 726].

### **Part 2: Multiple Choice Questions (30%)**

18. **Why is the "time-to-think" principle applied when prompting LLMs for JSON data generation?**
    A. To speed up the generation process.
    B. To ensure the output is in XML format.
    C. To reduce the risk of hallucinations by asking the model to check its work before outputting.
    D. To encrypt the data for privacy.
    _[cite: 45, 83]_

19. **Which of the following is a primary benefit of using OpenAPI or XSD standards in prompts?**
    A. They allow the LLM to generate data without any delimiters.
    B. They are standard structures likely present in the LLM's training data, increasing output accuracy.
    C. They automatically execute the test data against the database.
    D. They represent the only way to generate boolean values.
    _[cite: 315]_

20. **When generating SQL data across multiple tables (e.g., Orders and Customers), what is the recommended prompting strategy to ensure data consistency?**
    A. Provide only the `INSERT` statements for the first table.
    B. Provide only the `CREATE TABLE` statements.
    C. Provide both `CREATE TABLE` and `INSERT` statements, along with few-shot examples.
    D. Ask for the data in CSV format first, then convert it manually.
    _[cite: 592-594]_

21. **Which of the following best defines Exploratory Testing (ET)?**
    A. A testing approach where test cases are written weeks in advance.
    B. Simultaneous learning, test design, and test execution.
    C. Randomly clicking buttons to see if the application crashes.
    D. A technique used solely for verifying User Interface (UI) elements.
    _[cite: 649]_

22. **Which Exploratory Testing approach involves time-boxed sessions guided by a clear mission or charter?**
    A. Mind Mapping
    B. Error Guessing
    C. Session-Based Testing
    D. Boundary Exploration
    _[cite: 714]_

23. **Regarding data privacy in GenAI for testing, what is the critical warning mentioned in the lecture?**
    A. Always use real production data to ensure the test is realistic.
    B. LLMs cannot process real user data, so it doesn't matter.
    C. Avoid violating policies/laws by using dummy data instead of real IP or user data.
    D. Privacy is only a concern when generating SQL, not JSON.
    _[cite: 628-629]_

24. **In the context of SQL data generation, what risk increases if you only provide `INSERT` statements without `CREATE TABLE` statements?**
    A. The LLM will generate XML instead.
    B. The LLM receives less context, increasing the risk of foreign keys linking to non-existent records.
    C. The query execution time will double.
    D. The database will reject the prompt immediately.
    _[cite: 594]_

---

## **Lecture 8: Assisting ET & Customized LLMs (RAG vs. Fine-tuning)**

### **Part 1: Short-Word / Fill-in-the-Blank Questions (70%)**

1.  **\*\***\_\_\_\_\_\_**\*\*** is a testing approach that combines simultaneous learning, test design, and test execution[cite: 789].
2.  The maximum prompt size an LLM can handle is determined by its **\*\***\_\_\_\_\_\_**\*\*** window[cite: 1244].
3.  To validate code understanding during exploratory testing, a tester should build their own **\*\***\_\_\_\_\_\_**\*\*** model before checking it against the LLM's explanation to avoid hallucinations[cite: 917, 921].
4.  **\*\***\_\_\_\_\_\_**\*\*** is the process of further training a model that has already been trained, often to bias it toward a specific tone or style[cite: 1346].
5.  In a RAG framework, a corpus of information is queried to find the most **\*\***\_\_\_\_\_\_**\*\*** document to add to the prompt[cite: 1311].
6.  If data privacy and control over the model are critical enterprise requirements, **\*\***\_\_\_\_\_\_**\*\*** is the preferred approach over RAG[cite: 1556, 1586].
7.  A test **\*\***\_\_\_\_\_\_**\*\*** defines the goal, scope, focus, and time box of an exploratory testing session [cite: 874-875].
8.  When creating a mind map with an LLM, you can request the output in specific formats for visualization, such as **\*\***\_\_\_\_\_\_**\*\*** or JSON[cite: 865].
9.  **\*\***\_\_\_\_\_\_**\*\*** are structured triggers (like PAOLO or CRUD) used to help generate diverse test ideas when natural creativity slows down[cite: 985].
10. The mnemonic **\*\***\_\_\_\_\_\_**\*\*** stands for Create, Read, Update, Delete and is primarily used for API/Backend testing[cite: 992].
11. A testing **\*\***\_\_\_\_\_\_**\*\*** is a report created after an ET session that describes what was learned, what was tested, and bugs discovered [cite: 1023-1024].
12. LLMs process text by slicing it into smaller units called **\*\***\_\_\_\_\_\_**\*\***, which are converted into integers[cite: 1173].
13. Larger prompts require more hardware usage and often incur higher **\*\***\_\_\_\_\_\_**\*\*** fees [cite: 1232-1233].
14. **\*\***\_\_\_\_\_\_**\*\*** enhances prompting to include more context, whereas Fine-tuning embeds context directly into the model [cite: 1272-1273].
15. RAG is generally considered to have a **\*\***\_\_\_\_\_\_**\*\*** learning curve compared to fine-tuning[cite: 1426].
16. If your data context changes frequently (e.g., daily or weekly), **\*\***\_\_\_\_\_\_**\*\*** is the recommended approach over fine-tuning[cite: 1568].
17. Fine-tuning requires **\*\***\_\_\_\_\_\_**\*\*** quality datasets to be successful[cite: 1512].

### **Part 2: Multiple Choice Questions (30%)**

18. **Which mnemonic is specifically designed to trigger test ideas regarding screen orientation and rendering (e.g., Portrait, Landscape)?**
    A. CRUD
    B. SFDIPOT
    C. PAOLO
    D. RAG
    _[cite: 1007]_

19. **What is the primary function of a "Test Charter" in exploratory testing?**
    A. To generate automated test scripts.
    B. To define the goal, scope, and time box for a testing session.
    C. To limit the tester to a strict set of instructions.
    D. To list all known bugs in the system.
    _[cite: 877-879]_

20. **What is "Tokenization" in the context of LLMs?**
    A. The process of encrypting data for security.
    B. The process of slicing natural language into integers the model can process.
    C. The fee paid to OpenAI for every request.
    D. A method for fine-tuning a model.
    _[cite: 1180-1181]_

21. **Which of the following scenarios best justifies using RAG (Retrieval-Augmented Generation) over Fine-tuning?**
    A. You need the model to adopt a very specific, quirky persona.
    B. You have a massive budget and need total control over the model weights.
    C. Your data changes daily (e.g., dynamic news or stock prices).
    D. You have a static dataset that hasn't changed in years.
    _[cite: 1504-1506]_

22. **Which statement accurately describes the difference between RAG and Fine-tuning?**
    A. RAG modifies the model's internal parameters; Fine-tuning modifies the prompt.
    B. RAG embeds context into the prompt; Fine-tuning embeds context into the model itself.
    C. RAG requires a GPU for training; Fine-tuning only requires an API key.
    D. Fine-tuning is generally faster to implement than RAG.
    _[cite: 1272-1273]_

23. **Which method is recommended for summarizing testing notes into a structured report using an LLM?**
    A. The Dot Product Method
    B. The Cornell Method
    C. The Random Forest Method
    D. The Vector Method
    _[cite: 1050, 1053]_

24. **When comparing costs, which approach generally has a lower _initial_ tooling cost but potentially higher ongoing API costs?**
    A. Fine-tuning
    B. RAG
    C. Training a model from scratch
    D. Buying a server farm
    _[cite: 1463-1464]_

---

## **Lecture 9: RAG Details & Fine-Tuning Process**

### **Part 1: Short-Word / Fill-in-the-Blank Questions (70%)**

1.  **\*\***\_\_\_\_\_\_**\*\*** is the process of converting text (like a data chunk) into a numerical vector representation[cite: 1779].
2.  In RAG, the **\*\***\_\_\_\_\_\_**\*\*** phase involves combining the original query with retrieved chunks to create an augmented prompt[cite: 1870].
3.  When fine-tuning, iterating over the entire dataset multiple times is referred to as training for multiple **\*\***\_\_\_\_\_\_**\*\***[cite: 2219].
4.  **\*\***\_\_\_\_\_\_**\*\*** is a metric used during fine-tuning that measures how far the model’s predicted probabilities are from the correct answer (lower is better)[cite: 2375].
5.  If a prompt exceeds the model's **\*\***\_\_\_\_\_\_**\*\*** length, the extra tokens will be truncated, potentially leading to incomplete instructions[cite: 2310].
6.  **\*\***\_\_\_\_\_\_**\*\*** similarity is a retrieval algorithm that measures the angle between two vectors, with a range of -1 to 1[cite: 1829, 1836].
7.  The three main phases of the RAG framework are Indexing, **\*\***\_\_\_\_\_\_**\*\***, and Generation[cite: 1711].
8.  During the Indexing phase, documents are broken down into smaller sections in a process called **\*\***\_\_\_\_\_\_**\*\***[cite: 1760].
9.  A **\*\***\_\_\_\_\_\_**\*\*** store (or database) is used to store vectors and supports similarity searches [cite: 1790-1792].
10. To prevent losing meaning at the borders of text chunks, it is common to include an **\*\***\_\_\_\_\_\_**\*\*** of 10-20% between chunks[cite: 1762].
11. **\*\***\_\_\_\_\_\_**\*\*** product is a retrieval algorithm often used in production because it is faster than cosine similarity[cite: 1851].
12. The goal of fine-tuning should focus on the type of **\*\***\_\_\_\_\_\_**\*\*** wanted (e.g., tone), not just specific facts[cite: 1942].
13. **\*\***\_\_\_\_\_\_**\*\*** data is often used in fine-tuning to expand small datasets or avoid privacy issues associated with real-world data[cite: 2012, 2015].
14. The preferred data format for fine-tuning often consists of pairs of **\*\***\_\_\_\_\_\_**\*\*** and Outputs[cite: 2055].
15. When preparing code for fine-tuning, it is better to parse it into **\*\***\_\_\_\_\_\_**\*\*** sections (like methods) rather than line-by-line[cite: 2110].
16. **\*\***\_\_\_\_\_\_**\*\*** is an automated approach to testing a fine-tuned model using a dataset different from the training data[cite: 2413].
17. The **\*\***\_\_\_\_\_\_**\*\*** score evaluates a model by measuring how many words in the output match the reference text (Precision)[cite: 2376].

### **Part 2: Multiple Choice Questions (30%)**

18. **Why is "overlap" important during the chunking phase of RAG?**
    A. It reduces the total storage size of the vector database.
    B. It ensures that context is not lost at the boundaries between two chunks.
    C. It allows the LLM to process data faster.
    D. It automatically encrypts the data for security.
    _[cite: 1763-1764]_

19. **Which retrieval algorithm measures similarity by calculating the actual distance between two vector points in space?**
    A. Cosine Similarity
    B. Dot Product
    C. Euclidean Distance
    D. Cross-Entropy Loss
    _[cite: 1858]_

20. **In the context of fine-tuning, why might a team use "Synthetic Data"?**
    A. Because real data is always too expensive to store.
    B. To avoid exposing intellectual property or privacy issues found in real data.
    C. Because synthetic data is always more accurate than real-world data.
    D. To reduce the hardware requirements for the GPU.
    _[cite: 2015, 2027]_

21. **When preparing code datasets for fine-tuning, what is the recommended approach for parsing the code?**
    A. Line-by-line to ensure every character is captured.
    B. By logical sections (e.g., class declarations, methods) to preserve context.
    C. Randomly splitting the code into 50-character segments.
    D. Removing all comments to save token space.
    _[cite: 2110]_

22. **Which evaluation metric specifically measures "Recall" (how much of the reference text appears in the model's output)?**
    A. BLEU Score
    B. BERTScore
    C. ROUGE Score
    D. Cross-Entropy Loss
    _[cite: 2378]_

23. **What happens during the "Parameter Update" step of the fine-tuning loop?**
    A. The model sends the data back to the vector store.
    B. The model's internal weights are adjusted to align closer to the expected output.
    C. The tokenizer is swapped for a different language model.
    D. The synthetic data is deleted.
    _[cite: 2213]_

24. **Which component converts the user's query into a vector during the Retrieval phase of RAG?**
    A. The Chunking Algorithm
    B. The Embedding Model
    C. The Generator
    D. The SQL Parser
    _[cite: 1816]_

---

# Answer Key

**Lecture 7**

1. Probabilistic
2. Time-to-think
3. Delimiters
4. Inaccurate
5. XSD (or XML Schema Definition)
6. OpenAPI
7. CREATE
8. Few-shot
9. External
10. Data privacy
11. Exploratory
12. Creativity
13. Thinking
14. Mind
15. Risk
16. Error
17. Boundary
18. C
19. B
20. C
21. B
22. C
23. C
24. B

**Lecture 8**

1. Exploratory Testing
2. Context
3. Conceptual (or Mental)
4. Fine-tuning
5. Relevant
6. Fine-tuning
7. Charter
8. Markdown
9. Mnemonics
10. CRUD
11. Story
12. Tokens
13. API
14. RAG
15. Smaller (or Easier)
16. RAG
17. High
18. C
19. B
20. B
21. C
22. B
23. B
24. B

**Lecture 9**

1. Embedding
2. Generation
3. Epochs
4. Cross-Entropy (or Cross-Entropy Loss)
5. Context
6. Cosine
7. Retrieval
8. Chunking
9. Vector
10. Overlap
11. Dot
12. Behavior
13. Synthetic
14. Instructions
15. Logical
16. Inference
17. BLEU
18. B
19. C
20. B
21. B
22. C
23. B
24. B
