# 预分类与改写，提升 RAG 效果

发布时间：2025年06月20日

`RAG` `信息检索`

> PreQRAG -- Classify and Rewrite for Enhanced RAG

# 摘要

> 本文展示了UDInfo团队在SIGIR 2025 LiveRAG挑战中的提交。我们提出了一种名为PreQRAG的检索增强生成（RAG）架构，通过针对性的问题预处理来提升检索和生成质量。PreQRAG采用了一种流水线方法，首先将输入问题分类为单文档或多文档类型。对于单文档问题，我们采用问题重写技术以提高检索精度和生成相关性。对于多文档问题，我们将复杂查询分解为更专注的子问题，以便下游组件能更高效地处理。这种分类和重写策略显著提升了RAG的性能。在LiveRAG挑战数据集上的实验评估表明，我们基于问题类型的感知架构效果显著，PreQRAG在LiveRAG挑战的第二阶段中取得了初步第二名的成绩。

> This paper presents the submission of the UDInfo team to the SIGIR 2025 LiveRAG Challenge. We introduce PreQRAG, a Retrieval Augmented Generation (RAG) architecture designed to improve retrieval and generation quality through targeted question preprocessing. PreQRAG incorporates a pipeline that first classifies each input question as either single-document or multi-document type. For single-document questions, we employ question rewriting techniques to improve retrieval precision and generation relevance. For multi-document questions, we decompose complex queries into focused sub-questions that can be processed more effectively by downstream components. This classification and rewriting strategy improves the RAG performance. Experimental evaluation of the LiveRAG Challenge dataset demonstrates the effectiveness of our question-type-aware architecture, with PreQRAG achieving the preliminary second place in Session 2 of the LiveRAG challenge.

[Arxiv](https://arxiv.org/abs/2506.17493)