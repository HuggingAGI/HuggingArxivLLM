# mmRAG：面向文本、表格与知识图谱的检索增强生成模块化基准

发布时间：2025年05月16日

`RAG` `问答系统` `知识图谱`

> mmRAG: A Modular Benchmark for Retrieval-Augmented Generation over Text, Tables, and Knowledge Graphs

# 摘要

> 检索增强生成（RAG）已成为提升大型语言模型能力的强效范式。然而，现有的RAG评估主要聚焦于文本检索，并依赖不透明的端到端生成输出评估。为了解决这些局限，我们推出了mmRAG——一个专为多模态RAG系统设计的模块化基准测试。我们的基准整合了来自六个跨文本、表格及知识图谱的问答数据集的查询，并将它们统一转换为可检索文档。为了能够直接、细致地评估RAG组件（如检索准确性、查询路由等），而不仅仅是端到端生成质量，我们遵循标准的信息检索程序来标注文档相关性并推导数据集相关性。通过在mmRAG上评估多种RAG实现，我们建立了基线性能。

> Retrieval-Augmented Generation (RAG) has emerged as a powerful paradigm for enhancing the capabilities of large language models. However, existing RAG evaluation predominantly focuses on text retrieval and relies on opaque, end-to-end assessments of generated outputs. To address these limitations, we introduce mmRAG, a modular benchmark designed for evaluating multi-modal RAG systems. Our benchmark integrates queries from six diverse question-answering datasets spanning text, tables, and knowledge graphs, which we uniformly convert into retrievable documents. To enable direct, granular evaluation of individual RAG components -- such as the accuracy of retrieval and query routing -- beyond end-to-end generation quality, we follow standard information retrieval procedures to annotate document relevance and derive dataset relevance. We establish baseline performance by evaluating a wide range of RAG implementations on mmRAG.

[Arxiv](https://arxiv.org/abs/2505.11180)