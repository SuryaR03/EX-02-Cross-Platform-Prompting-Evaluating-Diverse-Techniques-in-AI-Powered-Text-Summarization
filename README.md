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

Input:
"The Basics of Blockchain Technology" – 500-word article (technical, detailed).

Zero-shot Example (ChatGPT)

“Blockchain is a decentralized system of recording transactions. It works without a central authority by using cryptography. It is widely applied in cryptocurrencies, finance, and supply chain management.”

✅ Accurate but too short, lacks depth.

Few-shot Example (Gemini)

“Blockchain is a distributed ledger that records transactions across multiple computers. This ensures transparency, immutability, and security. Each transaction is verified by consensus and added in a ‘block’. Applications include cryptocurrency, healthcare data security, and voting systems.”

✅ Better detail, structured.

⚠️ Still slightly technical for undergrads.

Chain-of-Thought Example (Claude)

“Step 1: Identify core ideas – decentralization, distributed ledger, consensus.
Step 2: Explain in simple terms.
Final Summary: Blockchain is like a shared online notebook where everyone can see and agree on the entries. Once information is added, it cannot be erased. This makes it secure and trustworthy. It is used in digital money (Bitcoin), supply chains, and secure voting systems.”

✅ Very clear, structured reasoning.

Role-based Example (ChatGPT)

“As an educational content curator, here’s a summary for students: Blockchain is a digital system that records information in a way that is nearly impossible to change. It stores data in units called blocks, which link together to form a chain. This ensures security and transparency without needing a central authority. The technology is mainly used in cryptocurrencies but also in areas like supply chain tracking and healthcare. For undergraduates, the key takeaway is that blockchain makes digital records more secure, transparent, and reliable.”

✅ Best balance of clarity + accuracy + student-friendly tone.

Across platforms:

ChatGPT scored highest overall.

Gemini performed well in simplicity and coherence.

Claude balanced accuracy and clarity.

Copilot lagged, struggling with coherence and depth.

## Result
The best combination for educational text summarization was:
👉 Role-based Prompting + ChatGPT
This pairing provided accurate, concise, and student-friendly summaries with excellent user experience.

