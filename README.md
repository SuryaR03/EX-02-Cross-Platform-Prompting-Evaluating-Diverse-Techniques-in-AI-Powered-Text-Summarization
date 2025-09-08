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

## Algorithm
Input Selection

A 500-word technical article on Blockchain Basics was chosen.

Prompting Strategy Design

Zero-shot: Directly ask for a summary.

Few-shot: Provide 2–3 examples of summaries, then ask for the Blockchain one.

Chain-of-Thought: Instruct the AI to reason step by step before producing the summary.

Role-based: Assign a role like “Educational content curator” to shape the response style.

Platform Execution

Run each prompting strategy across ChatGPT, Gemini, Claude, Copilot.

Evaluation Metrics

Accuracy: Does the summary capture blockchain fundamentals correctly?

Coherence: Logical structure and flow.

Simplicity: Is it easy for undergraduate students to understand?

Speed: Response time and efficiency.

User Experience: Readability, tone, and accessibility.

Scoring

Each output scored on a scale of 1–10 across the five metrics.

Final score = average of all metrics.

## Bar Graph
🔹 Comparative Graph 1 – Prompting Techniques Effectiveness

<img width="1400" height="1000" alt="bargraph1" src="https://github.com/user-attachments/assets/7ee8de94-b072-48c4-9867-c5868d5d5e9e" />

(Role-based and Chain-of-Thought prompting outperform others)

🔹 Comparative Graph 2 – Cross-Platform + Prompting Techniques

<img width="2000" height="1200" alt="bargraph2" src="https://github.com/user-attachments/assets/36594a53-5dd0-4f28-83bb-2fba51b606b2" />

(ChatGPT and Gemini handle prompts more effectively; Copilot trails behind)

🔹 Observations

Role-based prompting consistently gave the most clear, student-friendly summaries.

Chain-of-Thought produced well-structured outputs but sometimes exceeded word limits.

Few-shot worked well if good examples were provided.

Zero-shot was fastest but often too generic.

Across platforms:

ChatGPT scored highest overall.

Gemini performed well in simplicity and coherence.

Claude balanced accuracy and clarity.

Copilot lagged, struggling with coherence and depth.

## Result
The best combination for educational text summarization was:
👉 Role-based Prompting + ChatGPT
This pairing provided accurate, concise, and student-friendly summaries with excellent user experience.

