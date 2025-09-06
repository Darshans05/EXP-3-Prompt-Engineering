# EXP-3-PROMPT-ENGINEERING-

## Aim: 
Evaluation of 2024 Prompting Tools Across Diverse AI Platforms: 
ChatGPT, Claude, Bard, Cohere Command, and Meta
Experiment:
Within a specific use case (e.g., summarizing text, answering technical questions), compare the performance, user experience, and response quality of prompting tools across these different AI platforms.
Evaluation of Prompting Tools Across AI Platforms: A Comparative Study on Answering Technical Questions and Summarizing Text
## Abstract:

Large Language Models (LLMs) are increasingly being used in academia, business, and personal productivity. Their effectiveness, however, depends not only on the model’s raw capabilities but also on the prompting techniques and interfaces provided by the platform. This study evaluates five leading LLM-based prompting tools—ChatGPT (OpenAI), Claude (Anthropic), Bard/Gemini (Google DeepMind), Cohere Command, and Meta AI (LLaMA 3.1)—across two high-value use cases: answering technical questions (TQA) and summarizing text (ST).

The evaluation focuses on performance, user experience (UX), and response quality, using a structured rubric across dimensions of accuracy, depth, creativity, adaptability, latency, and clarity. Results show that ChatGPT and Claude consistently outperform other platforms in technical accuracy and structured reasoning. Bard/Gemini excels in accessibility and engaging language, Cohere in concise enterprise-ready outputs, and Meta AI in speed and casual usability. These findings highlight the importance of task-specific platform selection: ChatGPT and Claude for technical/academic contexts, Cohere for business reports, Bard for creative summarization, and Meta AI for lightweight general use.

## 1. Introduction:

The evolution of generative AI has redefined how knowledge is accessed, processed, and communicated. From supporting academic research to powering enterprise workflows, prompt engineering has emerged as the critical link between human intent and machine output. Prompt engineering refers to the structured design of inputs to guide AI systems toward desired outcomes. In 2024, as multiple competing LLM platforms have matured, their prompting tools present diverse capabilities and limitations.

# 1.1 Background:

Prompt engineering is not merely a technical skill but a cognitive interface that influences response accuracy, creativity, and efficiency. Early models such as GPT-2 (2019) and GPT-3 (2020) demonstrated impressive generative capabilities but lacked reliability for high-stakes domains. In recent years, advanced models like GPT-4.1, Claude 3.5, Gemini 1.5, Cohere Command-R+, and LLaMA 3.1 have incorporated alignment techniques, retrieval capabilities, and extended context windows. These advancements enable applications ranging from software development to education and content creation.

# 1.2 Motivation:

While platform comparisons exist, most benchmarks evaluate general performance (e.g., MMLU, Big-Bench). Few studies systematically compare specific use cases relevant to researchers, students, and enterprises. Among the most common tasks are:

Answering technical questions (TQA): requiring precision, structured reasoning, and domain knowledge.

Summarizing text (ST): requiring clarity, brevity, and context retention.

This study addresses this gap by conducting a comparative evaluation across five platforms within these two scenarios.

# 1.3 Aim and Research Questions:

The aim is to identify strengths, weaknesses, and task-appropriate use of prompting tools across AI platforms. The study investigates:

How do platforms differ in accuracy and depth for technical Q&A?

How effectively do they summarize complex text into coherent abstracts?

What are the trade-offs in user experience, adaptability, and latency?

Which platforms are best suited for different application domains?

## 2. Literature Review:

Prior evaluations of LLMs highlight both strengths and shortcomings. Brown et al. (2020) demonstrated GPT-3’s few-shot learning, but later studies (Perez et al., 2022) emphasized hallucination risks. Anthropic’s Claude, trained with Constitutional AI, has been noted for ethical alignment and long-context reasoning (Bai et al., 2023). Google’s Gemini, formerly Bard, integrates search retrieval, allowing near real-time information updates. Cohere Command specializes in enterprise summarization, prioritizing concise and consistent outputs (Cohere AI, 2024). Meta’s LLaMA models prioritize accessibility and open research, though technical depth remains limited.

Comparative studies (Zhou et al., 2023) suggest that while GPT-based models excel in accuracy and reasoning, alternative models trade precision for speed, brevity, or accessibility. However, no single platform dominates across all use cases, reinforcing the need for context-specific evaluation.

## 3. Methodology:
# 3.1 Use Cases:

Two tasks were selected for systematic evaluation:

1.Answering Technical Questions (TQA)
Example prompt:
“Explain the difference between O(n log n) and O(n²) time complexity with examples in sorting algorithms.”

2.Summarizing Text (ST)
Example prompt:
“Summarize the following 2000-word article on AI ethics in 150 words, focusing on key arguments and conclusion.”

# 3.2 Platforms Evaluated :

ChatGPT (GPT-4.1, OpenAI)

Claude 3.5 (Anthropic)

Bard/Gemini 1.5 (Google DeepMind)

Cohere Command-R+

Meta AI (LLaMA 3.1)

# 3.3 Evaluation Metrics :

A rubric-based scoring system (1 = poor, 5 = excellent) assessed:

Accuracy (factual correctness)

Depth of Response (reasoning, completeness)

Creativity & Adaptability (flexibility in style/tone)

User Experience (UX) (interface, prompting flexibility, refinement ease)

Latency (response time, measured in seconds)

Response Quality (clarity, structure, readability)

# 3.4 Experimental Workflow :

Task Selection → Two use cases (TQA, ST).

Prompt Design → Standardized, identical prompts.

Execution → Submitted across all platforms.

Output Capture → Recorded verbatim responses.

Scoring → Evaluated independently by two researchers, averaged scores.

A simplified workflow diagram:

Prompt → Platform → Response → Human Scoring → Comparative Analysis

 ## 4. Results:
# 4.1 Technical Question Answering (TQA):
Platform	Accuracy	Depth	Quality	UX	Latency	Notes
ChatGPT	5.0	5.0	5.0	5.0	Medium	Structured, includes examples and pseudocode.
Claude	4.5	5.0	4.8	4.5	Fast	Deep reasoning, verbose, over 600 words.
Bard/Gemini	4.5	4.3	4.2	4.5	Variable	Good analogies, weaker formal structure.
Cohere	4.0	4.0	4.0	4.0	Medium	Concise, enterprise-friendly, lacks detail.
Meta AI	3.5	3.5	3.5	4.0	Fast	Simple, informal, missed technical rigor.
# 4.2 Summarizing Text (ST):
Platform	Accuracy	Depth	Quality	UX	Latency	Notes
ChatGPT	5.0	5.0	5.0	5.0	Medium	Balanced, clear abstracts.
Claude	4.7	4.8	4.8	4.5	Fast	Rich summaries, slightly verbose.
Bard/Gemini	4.5	4.3	4.2	4.5	Variable	Accessible, less nuanced.
Cohere	4.2	4.0	4.0	4.0	Medium	Concise summaries, enterprise focus.
Meta AI	3.7	3.5	3.5	4.0	Fast	Simplified, omits details.
# 4.3 Example Case Study (TQA):

Prompt: “Explain O(n log n) vs O(n²) in sorting.”

ChatGPT: Explained with QuickSort vs Bubble Sort, included pseudocode and graph illustration (described). Clear, academic style.

Claude: Provided mathematical intuition, extended explanation, analogy with classroom seating. Very detailed but long.

Bard: Gave analogy of organizing books, simplified, lacked pseudocode. Engaging but less technical.

Cohere: Very short—“MergeSort O(n log n), Insertion Sort O(n²). Faster for large n.” Missed nuances.

Meta AI: Casual—“Imagine stacking cards. One method is faster.” Lacked formal rigor.

# 4.4 Example Case Study (ST):

Prompt: “Summarize a 2000-word article on AI ethics.”

ChatGPT: Condensed into ~170 words, structured into introduction, issues, and conclusion. Balanced.

Claude: Generated ~300 words, detailed ethical frameworks, highlighted long-term risks. Too long but insightful.

Bard: ~150 words, easy to read, simplified key issues. Lacked nuance.

Cohere: ~120 words, concise, business-report style. Missing ethical depth.

Meta AI: ~100 words, casual phrasing, skipped critical arguments.

## 5. Discussion:

The results highlight a clear trade-off between depth, accuracy, and accessibility.

ChatGPT consistently provided structured, academic responses, excelling in both technical rigor and summarization.

Claude excelled in nuanced reasoning, particularly beneficial for research contexts, but produced overly verbose outputs.

Bard demonstrated strengths in engaging phrasing and readability, useful for general audiences but less reliable in technical precision.

Cohere prioritized conciseness and enterprise needs, suitable for business reports but weak in technical reasoning.

Meta AI offered fast, casual responses, adequate for lightweight queries but not rigorous analysis.

The dual-task evaluation reveals that models optimized for technical precision may be less effective in brevity-based tasks, and vice versa.

## 6. Recommendations:

Academia & Research: Use ChatGPT for structured clarity or Claude for deep analytical reasoning.

Education: ChatGPT for lecture notes; Claude for contextual depth.

Business Reports: Cohere Command for concise executive summaries.

Creative Writing: Bard/Gemini for engaging style.

Casual Use: Meta AI for quick, accessible insights.

Decision-making framework:

Need depth → Claude
Need structure → ChatGPT
Need brevity → Cohere
Need creativity → Bard
Need speed → Meta AI

## 7. Limitations and Future Work:

Limited to two use cases; other tasks (coding, translation, creative writing) not tested.

Human scoring bias may affect evaluations.

Model updates (e.g., GPT-5, Gemini 2) may alter results.

Future studies should integrate quantitative NLP metrics (ROUGE, BLEU, BERTScore) alongside human assessment.

Expanding to multimodal tasks (text+image/video) would provide broader insights.

## 8. Conclusion:

This comparative study demonstrates that no single platform is universally superior. Instead, performance depends on the task requirements:

ChatGPT: Best all-rounder, structured and accurate.

Claude: Best for nuance and depth, though verbose.

Bard: Best for creativity and accessible summaries.

Cohere: Best for concise enterprise applications.

Meta AI: Best for casual, fast interactions.

Ultimately, selecting the right platform requires aligning task demands (accuracy, brevity, creativity, speed) with platform strengths.
