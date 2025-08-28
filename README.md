# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

## Scenario:
You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:
Accuracy

Coherence

Simplicity

Speed

User experience

---

## **Algorithm**

# Step 1: Select the Article

Choose a ~500-word technical article on "The Basics of Blockchain Technology" (same article used across all tests to ensure fairness).

# Step 2: Define Prompting Techniques

*Zero-shot*: "Summarize the following article in under 150 words."

*Few-shot*: Provide 2–3 example summaries of different short texts, then ask for the blockchain article summary.

*Chain-of-thought*: "Summarize the article step by step: first extract key ideas, then condense them into a coherent summary."

*Role-based*: "You are an educational content curator for undergraduates. Write a clear, simple summary of this article."

# Step 3: Run Across AI Platforms

Input the same article and prompts into ChatGPT, Gemini, Claude, Copilot.

Collect 16 summaries (4 prompting techniques × 4 platforms).

# Step 4: Evaluation Metrics
Evaluate each summary using:

Accuracy – Fidelity to original content (measured by expert or rubric).

Coherence – Logical flow, readability.

Simplicity – Accessibility for undergraduates.

Speed – Response time (measured or approximated).

User Experience – Subjective ease of use, formatting, clarity.

# Step 5: Scoring System

Use a 1–5 Likert scale for each criterion.

Example:

Accuracy: 1 = misleading, 5 = highly faithful

Coherence: 1 = fragmented, 5 = smooth flow

Simplicity: 1 = too complex, 5 = very simple

Speed: 1 = >30s, 5 = <5s

User Experience: 1 = confusing output, 5 = very clear

# Step 6: Aggregation

Compute average score per technique per platform.

Identify the best-performing combination.

## Results (Hypothetical Example)
| Platform | Technique        | Accuracy | Coherence | Simplicity | Speed | UX  | Avg Score |
| -------- | ---------------- | -------- | --------- | ---------- | ----- | --- | --------- |
| ChatGPT  | Zero-shot        | 4.5      | 4.2       | 4.0        | 4.8   | 4.5 | **4.4**   |
| ChatGPT  | Few-shot         | 4.7      | 4.6       | 4.2        | 4.6   | 4.6 | **4.5**   |
| ChatGPT  | Chain-of-thought | 4.8      | 4.7       | 3.9        | 4.4   | 4.4 | **4.4**   |
| ChatGPT  | Role-based       | 4.9      | 4.8       | 4.7        | 4.5   | 4.8 | **4.7**   |
| Gemini   | Zero-shot        | 4.0      | 3.9       | 4.0        | 4.7   | 4.2 | **4.1**   |
| Gemini   | Few-shot         | 4.3      | 4.2       | 4.1        | 4.6   | 4.4 | **4.3**   |
| Claude   | Role-based       | 4.8      | 4.7       | 4.6        | 4.2   | 4.7 | **4.6**   |
| Copilot  | Zero-shot        | 3.5      | 3.6       | 3.9        | 4.8   | 3.8 | **3.9**   |


Key Findings (example):

Best combo: ChatGPT + Role-based prompting (avg 4.7)

Most accurate: ChatGPT (Chain-of-thought & Role-based)

Fastest: Copilot (but lower coherence)

Best for simplicity: Claude (Role-based)


Thus,the Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization prompted in ai tools
The best combination was ChatGPT with role-based prompting, as it gave the most accurate, coherent, and student-friendly summaries. Claude with role-based prompting was a close second, excelling in simplicity and readability. Copilot (zero-shot) was the fastest but less accurate, while Gemini was balanced but not the strongest in any single area.

Overall, role-based prompting works best because it tailors the summary to the educational context, ensuring clarity and usefulness for undergraduates.
