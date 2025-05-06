# 结构化提示与反馈引导推理助力LLMs实现高效数据解释

发布时间：2025年05月02日

`Agent` `数据分析` `数据科学`

> Structured Prompting and Feedback-Guided Reasoning with LLMs for Data Interpretation

# 摘要

> 大型语言模型（LLMs）在自然语言理解和任务泛化方面表现出色，但在结构化数据分析中仍面临挑战，如模式解释不一致、用户意图与模型输出对齐问题以及有限的自我纠正能力。本文提出STROT框架（结构化任务推理与输出转换），通过结构化提示和反馈驱动的转换逻辑生成，提升基于LLM的分析工作流的可靠性和语义对齐性。

STROT从轻量级模式内省和基于样本的字段分类开始，动态构建上下文，捕捉输入数据的结构和统计特性。这些上下文信息嵌入到结构化提示中，引导模型生成特定任务的可解释输出。为应对复杂查询中的常见失败模式，STROT集成了一个完善机制，模型根据执行反馈和验证信号迭代修订输出。

与传统依赖静态提示或单次推理的方法不同，STROT将LLM视为嵌入在受控分析循环中的推理代理，能够通过规划和修正调整输出轨迹。最终，STROT提供了一个稳健且可重复的框架，适用于需要可解释性、稳定性和正确性的各种数据探索和分析任务。

> Large language models (LLMs) have demonstrated remarkable capabilities in natural language understanding and task generalization. However, their application to structured data analysis remains fragile due to inconsistencies in schema interpretation, misalignment between user intent and model output, and limited mechanisms for self-correction when failures occur. This paper introduces the STROT Framework (Structured Task Reasoning and Output Transformation), a method for structured prompting and feedback-driven transformation logic generation aimed at improving the reliability and semantic alignment of LLM-based analytical workflows. STROT begins with lightweight schema introspection and sample-based field classification, enabling dynamic context construction that captures both the structure and statistical profile of the input data. This contextual information is embedded in structured prompts that guide the model toward generating task-specific, interpretable outputs. To address common failure modes in complex queries, STROT incorporates a refinement mechanism in which the model iteratively revises its outputs based on execution feedback and validation signals. Unlike conventional approaches that rely on static prompts or single-shot inference, STROT treats the LLM as a reasoning agent embedded within a controlled analysis loop -- capable of adjusting its output trajectory through planning and correction. The result is a robust and reproducible framework for reasoning over structured data with LLMs, applicable to diverse data exploration and analysis tasks where interpretability, stability, and correctness are essential.

[Arxiv](https://arxiv.org/abs/2505.01636)