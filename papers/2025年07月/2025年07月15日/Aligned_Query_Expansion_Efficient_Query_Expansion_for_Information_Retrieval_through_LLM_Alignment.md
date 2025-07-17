# 对齐驱动的查询扩展：通过大语言模型对齐提升信息检索效率

发布时间：2025年07月15日

`LLM应用` `信息检索` `问答系统`

> Aligned Query Expansion: Efficient Query Expansion for Information Retrieval through LLM Alignment

# 摘要

> 大型语言模型（LLMs）的突破推动了信息检索领域一项新技术的普及：通过扩展文档和查询与相关术语的查询生成技术。这项技术通过解决词汇不匹配问题，显著提升了传统基于词汇的检索方法的效果。然而，近期研究发现，采用贪心解码策略生成查询可能会产生次优结果，包括幻觉现象，因此建议在扩展前进行过滤。这种“先生成再过滤”的方法不仅成本高昂——需要生成多个查询并为所有查询应用相关性模型——还未能有效指导LLM识别哪些查询更适合作为扩展基础。为突破这些限制，我们提出了一种名为对齐查询扩展（AQE）的创新方法，专注于提升开放领域问答中段落检索的查询扩展效果。AQE巧妙运用了LLM对齐领域的最新技术，通过微调模型生成直接优化检索任务效果的查询扩展，从而省去了额外的过滤步骤。这种对齐策略不仅确保了查询的相关性，还显著降低了计算成本并提升了检索效果。实证评估表明，AQE在域内和域外设置下均超越了现有基线模型的查询扩展性能，实现了检索效果的显著提升。

> With the breakthroughs in large language models (LLMs), query generation techniques that expand documents and queries with related terms are becoming increasingly popular in the information retrieval field. Such techniques have been shown to improve the effectiveness of traditional lexical retrieval methods by dealing with the vocabulary mismatch problem. Recent work has found that generating queries with a greedy decoding strategy can produce sub-optimal queries, including hallucinations, and proposed to filter out queries before expansion. This `generate-then-filter' approach is costly, as it requires generating multiple queries and applying a relevance model to all of them and does not teach the LLM which of the generated queries is more effective for expansion. To overcome such limitations, we propose Aligned Query Expansion (AQE), a novel approach to enhance query expansion for passage retrieval in open-domain question answering. AQE leverages recent techniques in LLM alignment to fine-tune models for generating query expansions that directly optimize the effectiveness of the retrieval task, eliminating the need for additional filtering steps. This alignment ensures that queries are more relevant, reducing computational costs while improving retrieval effectiveness. Empirical evaluations show that AQE outperforms baseline models for query expansion in both in-domain and out-of-domain settings, demonstrating significant improvements in retrieval effectiveness.

[Arxiv](https://arxiv.org/abs/2507.11042)