# # 小编码器在检测 groundedness 方面的能力可与大解码器相媲美

发布时间：2025年06月26日

`LLM应用` `信息检索` `问答系统`

> Small Encoders Can Rival Large Decoders in Detecting Groundedness

# 摘要

> 通过增强外部上下文，大型语言模型（LLMs）在自然语言处理（NLP）任务中的表现得到了显著提升。然而，当提供的上下文信息不足时，LLMs 在回答查询时常常无法可靠地生成答案，往往只能依赖于无根据的推测或内部知识。'基于上下文生成严格支持的响应'（即'groundedness'）对于确保回答的事实准确性和可信度至关重要。本研究旨在在 LLMs 生成昂贵答案之前，检测给定查询是否基于提供的上下文文档。这种检测机制能够显著减少推理时间和资源消耗。我们发现，经过精心策划的数据集微调的轻量级、特定任务的编码器模型（如 RoBERTa 和 NomicBERT），在 groundedness 检测方面能够达到与最先进的 LLMs（如 Llama3 8B 和 GPT4o）相当的准确率，同时将推理延迟降低了几个数量级。代码可在此获得：https://github.com/chandarlab/Hallucinate-less

> Augmenting large language models (LLMs) with external context significantly improves their performance in natural language processing (NLP) tasks. However, LLMs struggle to answer queries reliably when the provided context lacks information, often resorting to ungrounded speculation or internal knowledge. Groundedness - generating responses strictly supported by the context - is essential for ensuring factual consistency and trustworthiness. This study focuses on detecting whether a given query is grounded in a document provided in context before the costly answer generation by LLMs. Such a detection mechanism can significantly reduce both inference time and resource consumption. We show that lightweight, task specific encoder models such as RoBERTa and NomicBERT, fine-tuned on curated datasets, can achieve accuracy comparable to state-of-the-art LLMs, such as Llama3 8B and GPT4o, in groundedness detection while reducing inference latency by orders of magnitude. The code is available at : https://github.com/chandarlab/Hallucinate-less

[Arxiv](https://arxiv.org/abs/2506.21288)