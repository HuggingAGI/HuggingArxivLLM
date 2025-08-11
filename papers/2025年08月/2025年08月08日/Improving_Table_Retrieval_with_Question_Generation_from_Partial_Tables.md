# 基于部分表格生成问题以优化表格检索

发布时间：2025年08月08日

`RAG` `问答系统` `信息检索`

> Improving Table Retrieval with Question Generation from Partial Tables

# 摘要

> 近期，基于检索器-读者架构的大型语言模型（LLMs）在开放领域表格问答任务中得到了广泛应用。先前研究有效利用LLMs应对读者组件中的复杂推理需求，如文本到文本、文本到SQL以及多跳推理等。然而，检索器组件主要集中在优化查询表示，训练检索器根据问题检索相关表格，或从问题中选择关键词以匹配表格段落。但对如何提升表格本身在嵌入空间中的表示以更好地与问题对齐的关注较少。为解决这一问题，我们提出了QGpT（基于部分表格的问题生成），这是一种简单而有效的方法。该方法利用LLM根据表格的小部分生成合成问题，模拟用户如何查询当前考虑的表格内容。生成的问题与用于生成的部分表格段落共同嵌入，从而增强与用户查询的语义对齐。无需嵌入整个表格，我们的方法显著提升了多个基准测试中密集和晚期交互检索器的检索性能。

> Recent advances in open-domain question answering over tables have widely adopted large language models (LLMs) under the Retriever-Reader architecture. Prior works have effectively leveraged LLMs to tackle the complex reasoning demands of the Reader component, such as text-to-text, text-to-SQL, and multi hop reasoning. In contrast, the Retriever component has primarily focused on optimizing the query representation-training retrievers to retrieve relevant tables based on questions, or to select keywords from questions for matching table segments. However, little attention has been given to enhancing how tables themselves are represented in embedding space to better align with questions. To address this, we propose QGpT (Question Generation from Partial Tables), a simple yet effective method that uses an LLM to generate synthetic questions based on small portions of a table. These questions are generated to simulate how a user might query the content of the table currently under consideration. The generated questions are then jointly embedded with the partial table segments used for generation, enhancing semantic alignment with user queries. Without the need to embed entire tables, our method significantly improves retrieval performance across multiple benchmarks for both dense and late-interaction retrievers.

[Arxiv](https://arxiv.org/abs/2508.06168)