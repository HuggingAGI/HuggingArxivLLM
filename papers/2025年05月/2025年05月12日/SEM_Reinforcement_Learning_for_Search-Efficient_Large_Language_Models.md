# 提升搜索效率的大型语言模型强化学习方法——SEM

发布时间：2025年05月12日

`LLM应用` `搜索引擎` `人工智能`

> SEM: Reinforcement Learning for Search-Efficient Large Language Models

# 摘要

> 大型语言模型（LLMs）不仅在推理能力上表现出色，更在调用外部工具，尤其是搜索引擎方面展现出了显著优势。然而，如何训练模型准确判断何时需要调用搜索，何时可以依赖自身知识库，仍然是一个亟待解决的难题。现有强化学习方法往往导致冗余搜索行为，造成效率低下和成本过高。本文提出了一种全新的后训练强化学习框架——SEM，旨在显式地训练LLMs以优化搜索使用。通过整合MuSiQue和MMLU构建平衡数据集，我们为模型创造了一系列必须学会区分的场景：哪些问题可以直接回答，哪些问题需要外部检索。我们设计了结构化推理模板，并采用组相对策略优化（GRPO）对模型的搜索行为进行后训练。我们的奖励函数鼓励在无需搜索时准确回答，同时在需要检索时有效执行。实验结果表明，我们的方法显著减少了冗余搜索操作，同时在多个具有挑战性的基准测试中保持或提升了回答的准确性。这一框架不仅提升了模型的推理效率，还扩展了其合理利用外部知识的能力。

> Recent advancements in Large Language Models(LLMs) have demonstrated their capabilities not only in reasoning but also in invoking external tools, particularly search engines. However, teaching models to discern when to invoke search and when to rely on their internal knowledge remains a significant challenge. Existing reinforcement learning approaches often lead to redundant search behaviors, resulting in inefficiencies and over-cost. In this paper, we propose SEM, a novel post-training reinforcement learning framework that explicitly trains LLMs to optimize search usage. By constructing a balanced dataset combining MuSiQue and MMLU, we create scenarios where the model must learn to distinguish between questions it can answer directly and those requiring external retrieval. We design a structured reasoning template and employ Group Relative Policy Optimization(GRPO) to post-train the model's search behaviors. Our reward function encourages accurate answering without unnecessary search while promoting effective retrieval when needed. Experimental results demonstrate that our method significantly reduces redundant search operations while maintaining or improving answer accuracy across multiple challenging benchmarks. This framework advances the model's reasoning efficiency and extends its capability to judiciously leverage external knowledge.

[Arxiv](https://arxiv.org/abs/2505.07903)