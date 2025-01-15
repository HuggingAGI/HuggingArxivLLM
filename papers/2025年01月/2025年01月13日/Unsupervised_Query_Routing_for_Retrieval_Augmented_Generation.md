# 无监督查询路由助力检索增强生成

发布时间：2025年01月13日

`RAG

理由：这篇论文主要讨论了检索增强生成（RAG）中的查询路由问题，提出了一种无监督方法来选择最佳搜索引擎。这属于RAG领域的研究，因为它涉及到如何通过检索增强来优化生成过程。` `信息检索` `搜索引擎`

> Unsupervised Query Routing for Retrieval Augmented Generation

# 摘要

> 检索增强生成的查询路由旨在为输入查询匹配最合适的搜索引擎。现有方法过度依赖需要大量人工标注的监督数据集，导致成本高、可扩展性差，且对分布外场景的泛化能力不足。为解决这些问题，我们提出了一种创新的无监督方法，通过构建“上限”响应来评估检索增强响应的质量，从而为查询选择最佳搜索引擎。该方法无需人工标注，能够自动处理大规模真实用户查询并生成训练数据。我们在五个数据集上的实验表明，该方法显著提升了系统的可扩展性和泛化能力。

> Query routing for retrieval-augmented generation aims to assign an input query to the most suitable search engine. Existing works rely heavily on supervised datasets that require extensive manual annotation, resulting in high costs and limited scalability, as well as poor generalization to out-of-distribution scenarios. To address these challenges, we introduce a novel unsupervised method that constructs the "upper-bound" response to evaluate the quality of retrieval-augmented responses. This evaluation enables the decision of the most suitable search engine for a given query. By eliminating manual annotations, our approach can automatically process large-scale real user queries and create training data. We conduct extensive experiments across five datasets, demonstrating that our method significantly enhances scalability and generalization capabilities.

[Arxiv](https://arxiv.org/abs/2501.07793)