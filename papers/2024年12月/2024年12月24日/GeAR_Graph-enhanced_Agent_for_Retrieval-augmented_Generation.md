# GeAR：用于检索增强式生成的图增强代理

发布时间：2024年12月24日

`RAG`

> GeAR: Graph-enhanced Agent for Retrieval-augmented Generation

# 摘要

> 检索增强生成系统依赖有效的文档检索能力。传统的稀疏或密集检索器在设计上于多跳检索场景中面临难题。本文中，我们推出了 GeAR，它通过两大关键创新提升了 RAG 性能：（一）图扩展，能增强像 BM25 这样的任何传统基础检索器；（二）融入图扩展的代理框架。我们的评估显示，GeAR 在三个多跳问答数据集中展现出卓越的检索性能。另外，我们的系统在颇具挑战的 MuSiQue 数据集上达成了最先进的成果，改进幅度超 10%，且相较于其他多步检索系统，所需的令牌和迭代更少。

> Retrieval-augmented generation systems rely on effective document retrieval capabilities. By design, conventional sparse or dense retrievers face challenges in multi-hop retrieval scenarios. In this paper, we present GeAR, which advances RAG performance through two key innovations: (i) graph expansion, which enhances any conventional base retriever, such as BM25, and (ii) an agent framework that incorporates graph expansion. Our evaluation demonstrates GeAR's superior retrieval performance on three multi-hop question answering datasets. Additionally, our system achieves state-of-the-art results with improvements exceeding 10% on the challenging MuSiQue dataset, while requiring fewer tokens and iterations compared to other multi-step retrieval systems.

[Arxiv](https://arxiv.org/abs/2412.18431)