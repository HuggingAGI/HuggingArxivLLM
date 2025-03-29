# 意图驱动的对话：大型语言模型中的SWI探索

发布时间：2025年03月27日

`LLM应用` `问答系统`

> SWI: Speaking with Intent in Large Language Models

# 摘要

> 意图通常是经过深思熟虑并明确规划的，它为推理和解决问题提供了认知框架。本文在大型语言模型（LLMs）中提出了“带着意图说话”（Speaking with Intent，SWI）的概念。SWI通过显式生成意图，将模型的潜在目标进行封装，并提供高级规划以指导后续分析和交流。通过模拟人类思维中深思熟虑且有目的的思想过程，SWI被认为能够显著提升LLMs的推理能力和生成质量。

在数学推理基准测试中，SWI的表现始终优于传统基线（即无明确意图的生成）。与Chain-of-Thought和Plan-and-Solve等基于触发词的提示方法相比，SWI表现更为出色。同时，在强大的分析-检索-推理（ARR）方法中，SWI也保持了高度竞争力。此外，SWI在推理密集型问答（QA）和文本摘要基准测试中展现了强大的有效性和通用性，显著提升了基线生成的效果。特别是在文本摘要任务中，SWI生成的摘要不仅更加准确、简洁和事实正确，还大幅减少了幻觉现象。

人工评估进一步验证了SWI生成意图的一致性、有效性和可解释性。这项概念验证研究为利用认知概念提升LLMs的推理能力开辟了全新路径，展示了将认知框架引入模型生成过程的巨大潜力。

> Intent, typically clearly formulated and planned, functions as a cognitive framework for reasoning and problem-solving. This paper introduces the concept of Speaking with Intent (SWI) in large language models (LLMs), where the explicitly generated intent encapsulates the model's underlying intention and provides high-level planning to guide subsequent analysis and communication. By emulating deliberate and purposeful thoughts in the human mind, SWI is hypothesized to enhance the reasoning capabilities and generation quality of LLMs. Extensive experiments on mathematical reasoning benchmarks consistently demonstrate the superiority of Speaking with Intent over Baseline (i.e., generation without explicit intent). Moreover, SWI outperforms answer-trigger prompting methods Chain-of-Thought and Plan-and-Solve and maintains competitive performance with the strong method ARR (Analyzing, Retrieving, and Reasoning). Additionally, the effectiveness and generalizability of SWI are solidified on reasoning-intensive question answering (QA) and text summarization benchmarks, where SWI brings consistent improvement to the Baseline generation. In text summarization, SWI-generated summaries exhibit greater accuracy, conciseness, and factual correctness, with fewer hallucinations. Furthermore, human evaluations verify the coherence, effectiveness, and interpretability of the intent produced by SWI. This proof-of-concept study creates a novel avenue for enhancing LLMs' reasoning abilities with cognitive notions.

[Arxiv](https://arxiv.org/abs/2503.21544)