# REAL-MM-RAG：面向真实世界的多模态检索基准测试

发布时间：2025年02月17日

`RAG` `信息检索`

> REAL-MM-RAG: A Real-World Multi-Modal Retrieval Benchmark

# 摘要

> 多模态文档检索的准确性对检索增强生成（RAG）至关重要，但现有基准测试未能完全涵盖现实世界中的挑战。为此，我们推出了REAL-MM-RAG，一个自动化的基准测试，专注于解决现实世界检索中的四大关键特性：多模态文档、增强难度、现实RAG查询以及精准标注。此外，我们提出了一种基于查询改写的多难度等级方案，旨在评估模型在语义理解上的能力，而不仅仅是简单的关键词匹配。通过REAL-MM-RAG基准测试，我们发现现有模型在处理表格密集型文档以及应对查询改写时存在明显不足。为了解决这些问题，我们整理了一个改写过的训练集，并引入了一个全新的以金融为核心、表格密集型的数据集。在这些数据集上进行微调后，模型在REAL-MM-RAG基准测试中实现了最先进的检索性能。我们的研究不仅为多模态RAG系统中的检索评估和改进提供了新思路，还提供了针对性的训练数据和模型，有效应对当前的技术限制。

> Accurate multi-modal document retrieval is crucial for Retrieval-Augmented Generation (RAG), yet existing benchmarks do not fully capture real-world challenges with their current design. We introduce REAL-MM-RAG, an automatically generated benchmark designed to address four key properties essential for real-world retrieval: (i) multi-modal documents, (ii) enhanced difficulty, (iii) Realistic-RAG queries and (iv) accurate labeling. Additionally, we propose a multi-difficulty-level scheme based on query rephrasing to evaluate models' semantic understanding beyond keyword matching. Our benchmark reveals significant model weaknesses, particularly in handling table-heavy documents and robustness to query rephrasing. To mitigate these shortcomings, we curate a rephrased training set and introduce a new finance-focused, table-heavy dataset. Fine-tuning on these datasets enables models to achieve state-of-the-art retrieval performance on REAL-MM-RAG benchmark. Our work offers a better way to evaluate and improve retrieval in multi-modal RAG systems while also providing training data and models that address current limitations.

[Arxiv](https://arxiv.org/abs/2502.12342)