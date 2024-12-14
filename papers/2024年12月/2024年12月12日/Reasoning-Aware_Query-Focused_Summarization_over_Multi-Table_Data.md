# 关于多表数据的推理感知型、面向查询的摘要

发布时间：2024年12月12日

`LLM应用` `数据处理` `查询优化`

> Reasoning-Aware Query-Focused Summarization over Multi-Table Data

# 摘要

> 查询聚焦的多表数据摘要提取是一项既具挑战性又关键的任务，旨在从结构化数据中获取精准且相关的信息。现有的方法往往依赖复杂的预处理步骤，难以在不同领域通用，也难以应对多表查询所需的逻辑推理。本文中，我们提出了 QueryTableSummarizer++，这是一个端到端的生成框架，借助具有表感知预训练、查询对齐微调以及带反馈的强化学习增强的大型语言模型（LLMs）。我们的方法无需中间序列化步骤，可直接生成与查询相关的摘要。在基准数据集上的实验显示，QueryTableSummarizer++在 BLEU、ROUGE 和 F1 分数方面大幅优于最先进的基线。进一步的分析凸显了其可扩展性、跨领域通用性以及对复杂查询的稳健处理能力。人工评估进一步证实了生成摘要的卓越品质和实际适用性，使 QueryTableSummarizer++成为多表摘要任务的高效解决方案。

> Query-focused summarization over multi-table data is a challenging yet critical task for extracting precise and relevant information from structured data. Existing methods often rely on complex preprocessing steps and struggle to generalize across domains or handle the logical reasoning required for multi-table queries. In this paper, we propose QueryTableSummarizer++, an end-to-end generative framework leveraging large language models (LLMs) enhanced with table-aware pre-training, query-aligned fine-tuning, and reinforcement learning with feedback. Our method eliminates the need for intermediate serialization steps and directly generates query-relevant summaries. Experiments on a benchmark dataset demonstrate that QueryTableSummarizer++ significantly outperforms state-of-the-art baselines in terms of BLEU, ROUGE, and F1-score. Additional analyses highlight its scalability, generalization across domains, and robust handling of complex queries. Human evaluation further validates the superior quality and practical applicability of the generated summaries, establishing QueryTableSummarizer++ as a highly effective solution for multi-table summarization tasks.

[Arxiv](https://arxiv.org/abs/2412.08970)