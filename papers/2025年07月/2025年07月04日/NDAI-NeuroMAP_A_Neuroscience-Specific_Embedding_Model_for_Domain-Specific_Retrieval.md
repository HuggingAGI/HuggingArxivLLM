# # NDAI-NeuroMAP：专为神经科学领域设计的嵌入模型，用于领域特定的检索

发布时间：2025年07月04日

`LLM应用

理由：这篇论文专注于将大型语言模型应用于神经科学领域的信息检索任务，通过构建特定领域的嵌入模型来优化性能，属于LLM的应用层面。` `神经科学` `临床自然语言处理`

> NDAI-NeuroMAP: A Neuroscience-Specific Embedding Model for Domain-Specific Retrieval

# 摘要

> 我们推出 NDAI-NeuroMAP，这是首个专为神经科学领域设计的高精度信息检索任务而打造的密集向量嵌入模型。我们的方法涵盖了一个庞大的训练语料库，包含 500,000 个精心构造的三元组，并补充了 250,000 个神经科学专用定义条目和 250,000 个结构化知识图谱三元组。我们基于 FremyCompany/BioLORD-2023 模型，采用结合对比学习与三元组度量学习的多目标优化框架进行微调。在包含约 24,000 个神经科学专用查询的测试集上，我们的模型显著优于现有通用和生物医学嵌入模型。这表明，领域特定的嵌入架构对神经科学导向的 RAG 系统及相关临床自然语言处理应用至关重要。

> We present NDAI-NeuroMAP, the first neuroscience-domain-specific dense vector embedding model engineered for high-precision information retrieval tasks. Our methodology encompasses the curation of an extensive domain-specific training corpus comprising 500,000 carefully constructed triplets (query-positive-negative configurations), augmented with 250,000 neuroscience-specific definitional entries and 250,000 structured knowledge-graph triplets derived from authoritative neurological ontologies. We employ a sophisticated fine-tuning approach utilizing the FremyCompany/BioLORD-2023 foundation model, implementing a multi-objective optimization framework combining contrastive learning with triplet-based metric learning paradigms. Comprehensive evaluation on a held-out test dataset comprising approximately 24,000 neuroscience-specific queries demonstrates substantial performance improvements over state-of-the-art general-purpose and biomedical embedding models. These empirical findings underscore the critical importance of domain-specific embedding architectures for neuroscience-oriented RAG systems and related clinical natural language processing applications.

[Arxiv](https://arxiv.org/abs/2507.03329)