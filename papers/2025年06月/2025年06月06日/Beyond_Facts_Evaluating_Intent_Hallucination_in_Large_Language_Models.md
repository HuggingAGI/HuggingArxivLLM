# 超越事实：评估大型语言模型的意图生成能力

发布时间：2025年06月06日

`LLM应用` `信息检索` `模型生成`

> Beyond Facts: Evaluating Intent Hallucination in Large Language Models

# 摘要

> 当前大型语言模型（LLMs）在处理包含多个条件的复杂查询时，往往只能部分满足要求，忽视某些关键条件。为此，我们提出“意图幻觉”这一概念。在这一现象中，LLMs要么忽略查询中的部分内容，要么误解并回应虚构的查询部分，导致生成结果偏离真实意图。为系统评估意图幻觉，我们推出了包含20,068个问题的FAITHQA基准，涵盖仅查询和增强检索生成（RAG）两种模式，涉及广泛的主题和难度等级。作为首个超越事实验证的幻觉基准，FAITHQA专门设计用于揭示意图幻觉的根本原因。通过在FAITHQA上评估多种LLMs，我们发现：（1）意图幻觉是即使是顶尖模型也无法避免的问题；（2）这一现象源于模型的忽略或误解。为推动未来研究，我们开发了自动化的LLM生成评估指标——CONSTRAINT SCORE，用于检测意图幻觉。人工评估结果证实，CONSTRAINT SCORE在检测意图幻觉时的表现更接近人类水平，优于现有基线。

> When exposed to complex queries containing multiple conditions, today's large language models (LLMs) tend to produce responses that only partially satisfy the query while neglecting certain conditions. We therefore introduce the concept of Intent Hallucination. In this phenomenon, LLMs either omit (neglecting to address certain parts) or misinterpret (responding to invented query parts) elements of the given query, leading to intent hallucinated generation. To systematically evaluate intent hallucination, we introduce FAITHQA, a novel benchmark for intent hallucination that contains 20,068 problems, covering both query-only and retrieval-augmented generation (RAG) setups with varying topics and difficulty. FAITHQA is the first hallucination benchmark that goes beyond factual verification, tailored to identify the fundamental cause of intent hallucination. By evaluating various LLMs on FAITHQA, we find that (1) intent hallucination is a common issue even for state-of-the-art models, and (2) the phenomenon stems from omission or misinterpretation of LLMs. To facilitate future research, we introduce an automatic LLM generation evaluation metric, CONSTRAINT SCORE, for detecting intent hallucination. Human evaluation results demonstrate that CONSTRAINT SCORE is closer to human performance for intent hallucination compared to baselines.

[Arxiv](https://arxiv.org/abs/2506.06539)