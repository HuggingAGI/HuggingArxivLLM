# SimGRAG：借助相似子图实现知识图谱驱动的检索增强式生成

发布时间：2024年12月17日

`RAG` `知识图谱` `问答系统`

> SimGRAG: Leveraging Similar Subgraphs for Knowledge Graphs Driven Retrieval-Augmented Generation

# 摘要

> 近期，大型语言模型（LLMs）的发展在各类任务中展现出令人瞩目的多面性。为消除其产生的幻觉，检索增强生成（RAG）应运而生，成为一种强有力的手段，借助知识图谱（KGs）等外部知识源。在本文中，我们对KG驱动的RAG任务展开研究，并提出一种全新的相似图增强检索增强生成（SimGRAG）方法。该方法通过两个阶段有效解决了查询文本与KG结构的对齐难题：（1）查询转模式，利用LLM将查询转化为期望的图模式；（2）模式转子图，运用图语义距离（GSD）指标来量化模式与候选子图之间的对齐情况。我们还研发了一种优化的检索算法，能在1000万规模的KG上于1秒延迟内高效识别出前k个子图。大量实验表明，SimGRAG在问答和事实核验方面均超越了最先进的KG驱动的RAG方法，具备卓越的即插即用可用性和可扩展性。

> Recent advancements in large language models (LLMs) have shown impressive versatility across various tasks. To eliminate its hallucinations, retrieval-augmented generation (RAG) has emerged as a powerful approach, leveraging external knowledge sources like knowledge graphs (KGs). In this paper, we study the task of KG-driven RAG and propose a novel Similar Graph Enhanced Retrieval-Augmented Generation (SimGRAG) method. It effectively addresses the challenge of aligning query texts and KG structures through a two-stage process: (1) query-to-pattern, which uses an LLM to transform queries into a desired graph pattern, and (2) pattern-to-subgraph, which quantifies the alignment between the pattern and candidate subgraphs using a graph semantic distance (GSD) metric. We also develop an optimized retrieval algorithm that efficiently identifies the top-$k$ subgraphs within 1-second latency on a 10-million-scale KG. Extensive experiments show that SimGRAG outperforms state-of-the-art KG-driven RAG methods in both question answering and fact verification, offering superior plug-and-play usability and scalability.

[Arxiv](https://arxiv.org/abs/2412.15272)