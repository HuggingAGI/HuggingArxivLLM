# # 无需训练的查询优化：基于LLM的计划相似性方法

发布时间：2025年06月06日

`LLM应用` `数据库` `数据库优化`

> Training-Free Query Optimization via LLM-Based Plan Similarity

# 摘要

> 大型语言模型（LLM）的嵌入为数据库查询优化提供了有前景的新途径。本文探讨了如何利用预训练的执行计划嵌入来指导SQL查询执行，无需额外的模型训练。我们提出了LLM-PM（基于LLM的计划映射）框架，该框架通过将查询的默认执行计划嵌入、在其先前执行的计划中找到k个最近邻，并基于邻居投票推荐数据库提示集。轻量级一致性检查验证所选提示，当需要时，回退机制会在整个提示空间中搜索。在OpenGauss上使用JOB-CEB基准进行评估，LLM-PM实现了平均21%的查询延迟减少。这项工作展示了LLM驱动嵌入在提升查询性能方面的潜力，并为无训练、基于嵌入的优化器指导系统指明了新方向。

> Large language model (LLM) embeddings offer a promising new avenue for database query optimization. In this paper, we explore how pre-trained execution plan embeddings can guide SQL query execution without the need for additional model training. We introduce LLM-PM (LLM-based Plan Mapping), a framework that embeds the default execution plan of a query, finds its k nearest neighbors among previously executed plans, and recommends database hintsets based on neighborhood voting. A lightweight consistency check validates the selected hint, while a fallback mechanism searches the full hint space when needed. Evaluated on the JOB-CEB benchmark using OpenGauss, LLM-PM achieves an average speed-up of 21% query latency reduction. This work highlights the potential of LLM-powered embeddings to deliver practical improvements in query performance and opens new directions for training-free, embedding-based optimizer guidance systems.

[Arxiv](https://arxiv.org/abs/2506.05853)