# PreQRAG -- 分类与重写，提升RAG性能

发布时间：2025年06月20日

`RAG` `信息检索` `问答系统`

> PreQRAG -- Classify and Rewrite for Enhanced RAG

# 摘要

> 本文介绍了UDInfo团队在SIGIR 2025 LiveRAG挑战中的提交内容。我们提出了PreQRAG，一种通过有针对性的问题预处理来提升检索和生成质量的检索增强生成（RAG）架构。PreQRAG采用了一个流水线，首先将每个输入问题分类为单文档或多文档类型。对于单文档问题，我们采用问题改写技术来提高检索精确度和生成相关性。对于多文档问题，我们将复杂查询分解为更聚焦的子问题，以便下游组件能更有效地处理。这种分类和改写策略显著提升了RAG的整体表现。实验结果证明，我们的基于问题类型的架构设计非常有效，PreQRAG在LiveRAG挑战的第二阶段取得了初步第二名的成绩。

> This paper presents the submission of the UDInfo team to the SIGIR 2025 LiveRAG Challenge. We introduce PreQRAG, a Retrieval Augmented Generation (RAG) architecture designed to improve retrieval and generation quality through targeted question preprocessing. PreQRAG incorporates a pipeline that first classifies each input question as either single-document or multi-document type. For single-document questions, we employ question rewriting techniques to improve retrieval precision and generation relevance. For multi-document questions, we decompose complex queries into focused sub-questions that can be processed more effectively by downstream components. This classification and rewriting strategy improves the RAG performance. Experimental evaluation of the LiveRAG Challenge dataset demonstrates the effectiveness of our question-type-aware architecture, with PreQRAG achieving the preliminary second place in Session 2 of the LiveRAG challenge.

[Arxiv](https://arxiv.org/abs/2506.17493)