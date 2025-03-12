# 展望与回顾：面向长期个性化对话代理的反思型内存管理

发布时间：2025年03月11日

`LLM应用

论文摘要讨论了大型语言模型（LLMs）在长期对话中的记忆和检索能力不足的问题，并提出了一种新的机制Reflective Memory Management（RMM）来解决这一问题。这项研究专注于改进LLMs在实际应用中的性能，特别是在对话管理方面，因此属于LLM应用类别。` `对话系统` `个性化应用`

> In Prospect and Retrospect: Reflective Memory Management for Long-term Personalized Dialogue Agents

# 摘要

> 大型语言模型 (LLMs) 在开放对话领域表现优异，但其在长期交互中记忆和检索信息的能力不足，限制了其在个性化应用中的效果。为解决这一问题，我们提出了 Reflective Memory Management (RMM)，一种新型的长期对话代理机制，通过前瞻反思和回顾反思，实现了动态记忆管理和在线优化。实验结果显示，RMM 在 LongMemEval 数据集上相比传统方法，准确率提升了 10% 以上。

> Large Language Models (LLMs) have made significant progress in open-ended dialogue, yet their inability to retain and retrieve relevant information from long-term interactions limits their effectiveness in applications requiring sustained personalization. External memory mechanisms have been proposed to address this limitation, enabling LLMs to maintain conversational continuity. However, existing approaches struggle with two key challenges. First, rigid memory granularity fails to capture the natural semantic structure of conversations, leading to fragmented and incomplete representations. Second, fixed retrieval mechanisms cannot adapt to diverse dialogue contexts and user interaction patterns. In this work, we propose Reflective Memory Management (RMM), a novel mechanism for long-term dialogue agents, integrating forward- and backward-looking reflections: (1) Prospective Reflection, which dynamically summarizes interactions across granularities-utterances, turns, and sessions-into a personalized memory bank for effective future retrieval, and (2) Retrospective Reflection, which iteratively refines the retrieval in an online reinforcement learning (RL) manner based on LLMs' cited evidence. Experiments show that RMM demonstrates consistent improvement across various metrics and benchmarks. For example, RMM shows more than 10% accuracy improvement over the baseline without memory management on the LongMemEval dataset.

[Arxiv](https://arxiv.org/abs/2503.08026)