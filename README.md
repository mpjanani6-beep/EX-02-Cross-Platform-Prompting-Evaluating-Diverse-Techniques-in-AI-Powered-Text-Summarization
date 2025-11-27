# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

## Scenario:
You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

THEORY
1. Prompting Techniques in AI:
Zero-shot Prompting:
The AI model is given a direct instruction without any examples.
Example: “Summarize this article about blockchain in simple words.”
Few-shot Prompting:
The AI is shown 1–2 examples of good summaries before being asked to perform the task.
This helps the model learn the expected tone and style.
Example: Providing short sample summaries before asking for a new one.
Chain-of-Thought (CoT) Prompting:
The AI is asked to think step-by-step before generating the final answer.
This approach improves logical reasoning and content structure.
Example: “First identify the main points of the article, then write the summary.”
Role-based Prompting:
The AI is assigned a specific role or persona to guide its tone and style.
Example: “You are a science educator. Write a summary for undergraduate students.”

2. Platforms Used:
ChatGPT (OpenAI): Known for balanced performance, coherent output, and accuracy.
Gemini (Google): Good factual summarization and natural tone.
Claude (Anthropic): Prioritizes context retention and ethical summarization.
Copilot (Microsoft): Optimized for speed and integration within Microsoft tools.

SCENARIO
You are part of an educational content creation team responsible for delivering concise and understandable summaries of technical research papers to undergraduate students.
Your task is to test various AI tools and prompting techniques on the same 500-word article about “The Basics of Blockchain Technology.”
The article covers:
The concept of decentralized ledgers
The working of blocks, hashing, and consensus mechanisms
Applications in finance, supply chain, and security
Benefits such as transparency and immutability
Your objective is to find which AI tool and prompting style give the best results for academic summaries.

ALGORITHM
Input Selection:
Select a 500-word article titled “The Basics of Blockchain Technology.”
Platform Selection:
Use four platforms — ChatGPT, Gemini, Claude, and Copilot.
Prompting Techniques:
Apply the following methods for each AI platform:
Zero-shot prompting
Few-shot prompting
Chain-of-thought prompting
Role-based prompting
Execution Steps:
Enter the same article text into each platform.
Apply each prompting technique separately.
Record the time taken to generate responses.
Save the generated summaries for comparison.
Evaluation Parameters:
Each summary is rated (out of 5) on:
Accuracy: Correctness of key technical points.
Coherence: Logical flow and connection of ideas.
Simplicity: Ease of understanding for students.
Speed: Time taken to produce the summary.
User Experience: Ease of use and response formatting.
Comparison and Analysis:
Prepare a comparative table and determine the top-performing combination.

RESULT
Platform
Prompting Technique
Accuracy (5)
Coherence (5)
Simplicity (5)
Speed (5)
User Experience (5)
Total (25)

ChatGPT
Role-based
5
5
5
4
5
24

ChatGPT
Chain-of-thought
5
4
4
4
5
22

Gemini
Few-shot
4
4
4
5
4
21

Claude
Zero-shot
4
4
5
4
4
21

Copilot
Zero-shot
3
3
4
5
4
19


DISCUSSION
ChatGPT provided the most balanced and context-aware summaries, especially when using Role-based prompting, as it adapted tone and style effectively for students.
Gemini performed well in terms of fluency and speed, though it occasionally simplified too much.
Claude produced ethically balanced and clear summaries but lacked deeper technical precision.
Copilot responded fastest but provided less detailed or coherent explanations.
Among prompting methods:
Role-based prompting improved clarity and engagement.
Chain-of-thought prompting enhanced logical flow but increased response time.
Few-shot prompting improved consistency when prior examples were relevant.
Zero-shot prompting worked best for short and simple summaries.

CONCLUSION
After evaluating different combinations, it was observed that:
✅ Best Overall Performance: ChatGPT + Role-based Prompting
→ Produced clear, accurate, and concise summaries ideal for educational use.
⚡ Fastest Response: Copilot + Zero-shot Prompting
→ Quick but with less technical accuracy.
💡 Best Logical Flow: ChatGPT + Chain-of-thought Prompting
→ Well-structured but slightly slower.
Thus, Role-based prompting with ChatGPT is the most effective method for AI-powered summarization in educational content creation.

## Result
Thus the program is executed.


