# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM
To examine and compare how different prompting strategies—such as zero-shot, few-shot, chain-of-thought, and role-based prompting—perform across various AI platforms (ChatGPT, Gemini/Bard, Claude, Copilot, Cohere, and Meta) for a specific task: text summarization.

## Algorithm
## 1.Define the Use Case:
Select a common task (e.g., summarizing text, answering a technical question, creating a story, or generating code) that can be executed consistently across all selected AI platforms.

## 2.Prepare a Uniform Prompt Set:
Design a set of well-structured prompts based on the chosen task.
Ensure the prompts are unambiguous so that all AI tools receive identical input for fair comparison.
Include multiple prompt styles to evaluate different capabilities.

## 3.Execute Prompts Across Platforms:
Run each prompt individually on every AI model (ChatGPT, Claude, Gemini/Bard, Cohere Command, Meta).
Maintain similar testing conditions such as input format, sequence, and environment.
Record response time, output quality, and any technical difficulties.

## 4.Evaluate the Responses:
Assess responses using the following criteria:

Accuracy

Clarity

Depth of explanation

Relevance to the given prompt

## 5.Compare Performance:
Analyze the outputs to identify strengths and weaknesses of each platform.
Highlight platform-specific advantages like response speed, creativity, formatting capability, or contextual understanding.

## 6.Deliverables:

A comparison table summarizing each model’s performance.

A short report outlining conclusions and recommending the best-suited platform depending on the task.
## Algorithm Execution: Test Scenario and Prompt Outputs (Across Platforms)
## 1. Straightforward Prompt

Prompt: “What is the capital of France?”
(All platforms returned: Paris)

## 2. Tabular Prompt

Prompt: “Create a table comparing the features of AI models.”

AI Platform	Response Summary
ChatGPT	Detailed table with features like NLU, context handling, speed, and availability.
Claude	Highlights NLU, speed, and data usage.
Bard	Focuses on contextual understanding, speed, availability.
Cohere Command	Lists speed, contextual abilities, availability.
## 3. Missing Word Prompt

Prompt: “The capital of Italy is ___.”
(All platforms answered: Rome)

## 4. Preceding Question Prompt

Prompt: “Given that the capital of France is Paris, what is the capital of Italy?”
(All platforms answered: Rome)

## 5. Comparative Prompt

Prompt: “Compare the features of Python and Java.”

ChatGPT: Deep, structured comparison.

Claude: Balanced pros and cons.

Bard: Clear, example-based comparison.

Cohere Command: Short, to the point.

Meta: Simple feature comparison.

## 6. Experiential Prompt

Prompt: “What is the best way to improve focus while studying?”

ChatGPT: Practical, step-by-step approach.

Claude: Insightful and thoughtful.

Bard: Goal-based, realistic advice.

Cohere: Factual, straightforward.

Meta: General and simple tips.

## 7. Everyday Prompt

Prompt: “How do I prepare for a job interview?”
(All platforms gave similar steps: research, practice common questions, dress properly, be punctual.)

## 8. Universal Prompt

Prompt: “Explain machine learning in simple terms.”
(All platforms explained ML as pattern-learning from data.)

## Summary of Responses:
| Prompt Type            | ChatGPT                 | Claude         | Bard           | Cohere             | Meta                   |
| ---------------------- | ----------------------- | -------------- | -------------- | ------------------ | ---------------------- |
| Straightforward        | Very accurate & quick   | Concise        | Detailed       | Brief              | Clear                  |
| Tabular                | Excellent formatting    | Decent         | Good           | Limited formatting | Simple                 |
| Missing Word           | Very context-aware      | Accurate       | Good           | Basic              | Accurate               |
| Preceding Question     | Great contextual memory | Moderate       | Good           | Good               | Sometimes inconsistent |
| Comparative            | Highly detailed         | Balanced       | Clear          | Short              | Simple                 |
| Experiential           | Practical & empathetic  | Thoughtful     | Realistic      | Factual            | General                |
| Everyday               | Step-by-step            | Personal touch | Clear examples | Functional         | Straightforward        |
| Universal Explanations | Adaptive & strong       | Versatile      | Good clarity   | Concise            | Moderate depth         |

## Result
Thus the Prompting tools are executed and analysed sucessfully .

