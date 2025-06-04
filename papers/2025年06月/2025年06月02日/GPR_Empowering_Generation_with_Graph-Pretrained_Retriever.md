# GPR：赋能生成任务的图预训练检索器

发布时间：2025年06月02日

`RAG` `知识图谱` `图检索`

> GPR: Empowering Generation with Graph-Pretrained Retriever

# 摘要

> 图检索增强生成（GRAG）对图特定的检索器提出了较高要求。然而，现有检索器通常依赖基于纯文本预训练的语言模型，由于领域不匹配和结构忽视，限制了它们的实际效果。针对这些挑战，我们提出了GPR，这是一种直接在知识图谱上预训练的图基检索器。通过LLM引导的图增强，GPR能够将自然语言问题与相关子图精准对齐，并借助结构感知目标学习细粒度的检索策略。实验结果表明，GPR在两个数据集、三个LLM主干模型及五个基线上的表现均优于传统方法，显著提升了检索质量和下游生成效果，证实了其作为GRAG强大检索方案的有效性。

> Graph retrieval-augmented generation (GRAG) places high demands on graph-specific retrievers. However, existing retrievers often rely on language models pretrained on plain text, limiting their effectiveness due to domain misalignment and structure ignorance. To address these challenges, we propose GPR, a graph-based retriever pretrained directly on knowledge graphs. GPR aligns natural language questions with relevant subgraphs through LLM-guided graph augmentation and employs a structure-aware objective to learn fine-grained retrieval strategies. Experiments on two datasets, three LLM backbones, and five baselines show that GPR consistently improves both retrieval quality and downstream generation, demonstrating its effectiveness as a robust retrieval solution for GRAG.

[Arxiv](https://arxiv.org/abs/2506.00261)