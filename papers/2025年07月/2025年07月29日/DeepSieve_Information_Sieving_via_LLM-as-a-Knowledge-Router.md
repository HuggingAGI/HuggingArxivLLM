# 深度筛选：LLM 驱动的智能信息筛选机制

发布时间：2025年07月29日

`RAG` `问答系统`

> DeepSieve: Information Sieving via LLM-as-a-Knowledge-Router

# 摘要

> 大型语言模型 (LLMs) 善于处理多种推理任务，但在涉及知识密集型查询时表现欠佳，原因在于它们无法动态获取最新或特定领域的信息。检索增强生成 (RAG) 应运而生，为这一问题提供了一种有前景的解决方案，使 LLMs 能够将回答基于外部来源。然而，现有的 RAG 方法在查询和来源两侧缺乏精细的控制，常常导致检索噪声和推理肤浅。我们提出了 DeepSieve，一个基于 LLM 作为知识路由器的智能 RAG 框架。DeepSieve 将复杂查询分解为结构化的子问题，并递归地将每个子问题路由到最合适的知识来源，通过多阶段蒸馏过程过滤掉不相关信息。我们的设计强调模块化、透明度和适应性，充分利用了智能体系统设计的最新进展。在跨异质来源的多跳问答任务上的实验表明，与传统的 RAG 方法相比，DeepSieve 在推理深度、检索精度和可解释性方面都有显著提升。

> Large Language Models (LLMs) excel at many reasoning tasks but struggle with knowledge-intensive queries due to their inability to dynamically access up-to-date or domain-specific information. Retrieval-Augmented Generation (RAG) has emerged as a promising solution, enabling LLMs to ground their responses in external sources. However, existing RAG methods lack fine-grained control over both the query and source sides, often resulting in noisy retrieval and shallow reasoning. In this work, we introduce DeepSieve, an agentic RAG framework that incorporates information sieving via LLM-as-a-knowledge-router. DeepSieve decomposes complex queries into structured sub-questions and recursively routes each to the most suitable knowledge source, filtering irrelevant information through a multi-stage distillation process. Our design emphasizes modularity, transparency, and adaptability, leveraging recent advances in agentic system design. Experiments on multi-hop QA tasks across heterogeneous sources demonstrate improved reasoning depth, retrieval precision, and interpretability over conventional RAG approaches.

[Arxiv](https://arxiv.org/abs/2507.22050)