# 基于图检索增强的大型语言模型在对话推荐系统中的应用

发布时间：2025年03月08日

`LLM应用` `推荐系统` `图计算`

> Graph Retrieval-Augmented LLM for Conversational Recommendation Systems

# 摘要

> 对话推荐系统 (CRSs) 通过自然语言对话为用户提供个性化推荐，是一种变革性的范式。然而，用户通常提供简短、不完整的偏好陈述，导致知识稀疏性问题。尽管最近的方法整合了外部知识来源来缓解这一问题，但在语义理解和复杂偏好推理方面仍存在困难。最近的大型语言模型 (LLMs) 在自然语言理解和推理方面展现出巨大潜力，但现有基于 LLM 的 CRSs 由于缺乏领域知识，要么生成幻觉推荐，要么需要昂贵的领域特定训练，极大地限制了其适用性。本研究提出了一种无需训练的新型框架 G-CRS，结合图检索增强生成和上下文学习，以增强 LLMs 的推荐能力。G-CRS 采用两阶段的检索与推荐架构：首先，基于 GNN 的图推理器识别候选项目；然后，通过个性化 PageRank 探索共同发现潜在项目和相似用户交互。检索到的上下文被转换为结构化提示供 LLM 推理，实现基于上下文的推荐，而无需特定任务的训练。实验结果表明，G-CRS 在无需特定任务训练的情况下，优于现有方法的推荐性能。

> Conversational Recommender Systems (CRSs) have emerged as a transformative paradigm for offering personalized recommendations through natural language dialogue. However, they face challenges with knowledge sparsity, as users often provide brief, incomplete preference statements. While recent methods have integrated external knowledge sources to mitigate this, they still struggle with semantic understanding and complex preference reasoning. Recent Large Language Models (LLMs) demonstrate promising capabilities in natural language understanding and reasoning, showing significant potential for CRSs. Nevertheless, due to the lack of domain knowledge, existing LLM-based CRSs either produce hallucinated recommendations or demand expensive domain-specific training, which largely limits their applicability. In this work, we present G-CRS (Graph Retrieval-Augmented Large Language Model for Conversational Recommender Systems), a novel training-free framework that combines graph retrieval-augmented generation and in-context learning to enhance LLMs' recommendation capabilities. Specifically, G-CRS employs a two-stage retrieve-and-recommend architecture, where a GNN-based graph reasoner first identifies candidate items, followed by Personalized PageRank exploration to jointly discover potential items and similar user interactions. These retrieved contexts are then transformed into structured prompts for LLM reasoning, enabling contextually grounded recommendations without task-specific training. Extensive experiments on two public datasets show that G-CRS achieves superior recommendation performance compared to existing methods without requiring task-specific training.

[Arxiv](https://arxiv.org/abs/2503.06430)