# Software Testing Exam Bank - Lecture 5

**Topic: Introduction to Generative AI for Software Testing**

---

## **Part 1: Short-Word / Fill-in-the-Blank Questions (70%)**

1.  ******\_\_****** stands for Large Language Model, a type of AI trained on massive text data to generate human-like language.
2.  The core function of an LLM is ******\_\_****** prediction, constantly calculating the most probable next word based on learned patterns.
3.  LLMs use a special architecture called the ******\_\_****** to understand the full context of the input text.
4.  A ******\_\_****** is the natural language input or instruction sent to an LLM to elicit a response.
5.  ******\_\_****** Learning with Human Feedback (RLHF) is a process where human interaction guides the model's fine-tuning to produce more relevant responses.
6.  Unlike logic-based systems, LLMs are ******\_\_******, meaning their outputs are based on likelihood rather than a fixed repository of truth.
7.  The three key tenets to fully leverage LLMs are Mindset, Technique, and ******\_\_******.
8.  ******\_\_****** occurs when an LLM confidently produces information that is factually inaccurate, fabricated, or logically inconsistent.
9.  ******\_\_****** refers to understanding the origin of an LLM's training data, including how it was collected and whether it contains sensitive content.
10. ******\_\_****** is the risk of sensitive or private information unintentionally leaving an organization's control through model inputs or outputs.
11. ******\_\_****** Engineering is the practice of designing and refining prompts to ensure the model produces accurate and structured outputs.
12. Using characters like `###`, `"""`, or XML tags to separate instructions from data in a prompt is known as using ******\_\_******.
13. Requesting ******\_\_****** output (like JSON or a Table) ensures that the LLM's response is consistent and easy to process programmatically.
14. ******\_\_****** prompting involves providing a few examples (input/output pairs) within the prompt to guide the model's behavior.
15. The principle of "Giving the model time to ******\_\_******" involves asking it to break down tasks or work out a solution before finalizing an answer.
16. ******\_\_****** prompting is the process of revising a prompt step-by-step (like debugging) until the output matches expectations.
17. The ******\_\_****** count refers to the number of statistical weights in a model; generally, a higher number indicates better performance but higher cost.

---

## **Part 2: Multiple Choice Questions (30%)**

18. **Which of the following best describes "Generative AI"?**
    A. AI that searches a database for exact matches.
    B. AI that creates new, original content like text or code.
    C. AI that only classifies images.
    D. AI that strictly follows if-then logic rules.

19. **What is the primary "garbage in, garbage out" risk associated with LLMs?**
    A. High server costs.
    B. Slow response times.
    C. Providing vague or context-free prompts leads to shallow or irrelevant responses.
    D. The model runs out of memory.

20. **Which prompt engineering tactic is used to prevent the model from making up answers by asking it to verify its own work first?**
    A. Few-shot prompting.
    B. Use delimiters.
    C. Instruct the model to work out its own solution first.
    D. Ask for JSON output.

21. **Why might a tester use "Few-Shot Prompting"?**
    A. To reduce the cost of the API call.
    B. To guide the model to imitate a specific format or logic style by providing examples.
    C. To encrypt the data being sent.
    D. To force the model to hallucinate new ideas.

22. **Which of the following is a method used to train LLMs _not_ to leak data?**
    A. Increasing the parameter count.
    B. Reinforcement Learning from Human Feedback (RLHF).
    C. Removing all delimiters from the training data.
    D. Disabling the context window.

23. **What is "Cognitive Bias" in the context of using LLMs?**
    A. The model's tendency to prefer English over other languages.
    B. The hardware limitation of the GPU.
    C. The user's tendency to overtrust or undertrust the AI due to psychological shortcuts.
    D. The cost difference between GPT-4 and Llama 3.

24. **When comparing LLMs, which attribute allows a model to be integrated into existing systems or fine-tuned for specific needs?**
    A. Parameter Count
    B. Extensibility and Integration
    C. Training Data Size
    D. Hallucination Rate

25. **What was the issue with the "Weak Prompt" example: "Fix this function to clean emails"?**
    A. It was too long.
    B. It didn't define what "clean" meant or handle edge cases.
    C. It used Python instead of Java.
    D. It contained a virus.

---

## **Answer Key**

**Part 1**

1. LLM (or Large Language Model)
2. Statistical
3. Transformer
4. Prompt
5. Reinforcement
6. Probabilistic
7. Context
8. Hallucination
9. Data Provenance
10. Data Leakage
11. Prompt
12. Delimiters
13. Structured
14. Few-shot
15. Think
16. Iterative
17. Parameter

**Part 2** 18. B 19. C 20. C 21. B 22. B 23. C 24. B 25. B
