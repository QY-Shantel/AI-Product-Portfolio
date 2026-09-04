# AI-Assisted Bus Journey Analysis

> A Python development project exploring how generative AI can support requirement understanding, implementation, testing, debugging, and iterative improvement.

---

## 📌 Project Overview

This project involved developing a Python-based bus journey analysis program using bus stop, route, and timetable data.

The program was designed to perform tasks including bus stop analysis, route identification, timetable processing, and journey-time calculation.

During the development process, I integrated **ChatGPT and Claude Code** as AI assistants at different stages of the workflow. Rather than using AI simply to generate code, I used it to support requirement understanding, solution exploration, code review, debugging, and iterative improvement.

The overall process followed a **Human-AI collaboration workflow**, where AI-generated suggestions were evaluated through local testing before being incorporated into the final implementation.

---

## 🔄 AI-Assisted Development Workflow

**Requirement Understanding**

↓

**Task Decomposition**

↓

**AI-Assisted Solution Exploration**  
ChatGPT

↓

**Python Implementation**  
VSCodium

↓

**AI-Assisted Code Review & Debugging**  
Claude Code

↓

**Local Testing**

↓

**Result Evaluation**

↓

**Error & Edge-Case Identification**

↓

**AI-Assisted Refinement**

↓

**Re-testing**

↓

**Validated Output**

This created an iterative feedback loop:

> **Build → Review → Test → Evaluate → Refine → Re-test**

---

## 01 | Requirement Understanding & Task Decomposition

Before implementation, I broke the overall problem into smaller functional components and clarified the expected inputs, outputs, constraints, and relationships between different parts of the program.

ChatGPT was used during this stage to support requirement interpretation, explore possible implementation approaches, and help explain unfamiliar Python concepts.

This helped transform a relatively complex programming task into smaller and more manageable components.

### Key Focus

- Understand functional requirements
- Break the problem into smaller tasks
- Clarify input and output structures
- Identify dependencies between functions
- Explore possible implementation approaches

---

## 02 | AI-Assisted Development & Iteration

I implemented and tested the program locally in **VSCodium**, while using **Claude Code** as an AI coding assistant for code review, debugging, and refinement.

Instead of treating AI-generated suggestions as final outputs, I combined AI assistance with manual review and local execution.

When issues were identified, the relevant context was provided to the AI assistant, including the existing implementation, test behaviour, and expected outcome.

The revised solution was then tested again before being accepted.

<img width="290" height="188" alt="image" src="https://github.com/user-attachments/assets/dec5ff39-efec-4135-b4f0-b6ca94563c16" />

### Human-AI Collaboration

**My role:**

- Requirement interpretation
- Task decomposition
- Implementation decisions
- Test design
- Evaluation of outputs
- Final validation

**AI assistance:**

- Solution exploration
- Code explanation
- Code review
- Error analysis
- Debugging suggestions
- Implementation refinement

This allowed AI to function as a **development copilot**, while final decisions remained based on human evaluation and test results.

---

## 03 | Testing & Edge-Case Validation

Testing was an important part of the workflow because AI-generated or AI-modified code was not assumed to be correct automatically.

I designed multiple test scenarios to evaluate whether the implementation behaved as expected under different conditions.

The test cases included both standard scenarios and edge cases, such as:

- Single-route journeys
- Multiple available bus times
- Journeys involving waiting time
- Transfers at exact arrival times
- Different timetable structures
- Duplicate stop names
- Empty journey inputs

<img width="892" height="604" alt="image" src="https://github.com/user-attachments/assets/df829cbd-6ec4-4e6d-aa72-d9997c37164e" />


The testing process provided a structured way to evaluate AI-assisted modifications.

Rather than asking:

> "Does the code look correct?"

the workflow focused on:

> **"Does the output behave correctly across the scenarios that matter?"**

This shifted the evaluation of AI output from subjective judgement to observable test results.

---

## 04 | Debugging & Iterative Refinement

When a test failed or unexpected behaviour appeared, I used the result as feedback for the next iteration.

The refinement process followed:

**1. Run the implementation**

↓

**2. Compare actual and expected behaviour**

↓

**3. Identify the failed scenario**

↓

**4. Provide the relevant context to the AI assistant**

↓

**5. Review the suggested modification**

↓

**6. Re-run the tests**

↓

**7. Accept or continue refining**

This created a continuous feedback loop between **human judgement, AI assistance, and test results**.

A key lesson from this process was that better AI-assisted development does not depend only on better prompts. It also depends on providing useful context and having a clear evaluation mechanism for the generated output.

---

## 05 | Final Validation

After multiple rounds of implementation, review, testing, and refinement, the program was re-tested locally against the defined scenarios.

<img width="265" height="63" alt="image" src="https://github.com/user-attachments/assets/b4fc0160-532a-4df6-97ad-103b3fbf8552" />


The final test results confirmed that the implementation behaved as expected across the tested scenarios.

---

## 💡 Key Learnings

This project helped me understand that effective use of generative AI involves more than simply asking a model to generate a solution.

A more reliable AI workflow requires:

### 1. Clear Context

AI performs better when the task, constraints, existing implementation, and expected behaviour are clearly communicated.

### 2. Task Decomposition

Breaking a complex problem into smaller components makes AI-assisted problem solving easier to control and evaluate.

### 3. Human Evaluation

AI-generated suggestions should be reviewed rather than accepted automatically.

### 4. Structured Testing

Testing provides an objective mechanism for evaluating whether an AI-assisted solution actually works.

### 5. Iterative Feedback

Errors and failed test cases can become useful feedback for improving both the prompt and the implementation.

The experience helped me develop a practical understanding of the following AI workflow:

> **Context → Generation → Evaluation → Feedback → Iteration → Validation**

---

## 🛠 Tools

- **ChatGPT** — requirement understanding, solution exploration, and programming support
- **Claude Code** — code review, debugging, and implementation refinement
- **VSCodium** — local development environment
- **Python** — program implementation
- **GitHub** — project documentation and portfolio presentation

---

## 🎯 Skills Demonstrated

`AI Workflow Design`  
`Prompt Design`  
`Requirement Analysis`  
`Task Decomposition`  
`Human-AI Collaboration`  
`Output Evaluation`  
`Testing & Validation`  
`Debugging`  
`Iterative Improvement`  
`Python`

---

## 🔒 Note

This repository focuses on the **AI-assisted development process and workflow** rather than publishing the complete source code.

The project is presented as a case study of how generative AI can be integrated into problem solving, testing, evaluation, and iterative development.
