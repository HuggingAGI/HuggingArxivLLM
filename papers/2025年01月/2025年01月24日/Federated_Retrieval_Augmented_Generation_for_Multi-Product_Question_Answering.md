# 多产品问答的联邦检索增强生成

发布时间：2025年01月24日

`RAG

理由：这篇论文主要讨论了在多产品问答场景中，如何通过检索增强生成技术（RAG）来提升问答系统的表现。论文提出了一种新的多产品知识增强问答框架（MKP-QA），并强调了其在跨领域搜索中的优势。因此，这篇论文的核心内容与RAG技术密切相关，应归类为RAG。` `企业服务` `问答系统`

> Federated Retrieval Augmented Generation for Multi-Product Question Answering

# 摘要

> # 摘要
近期，大型语言模型和检索增强生成技术的突破，点燃了企业产品领域特定问答的热情。然而，AI助手在多产品问答场景中常遇挑战，需跨领域提供精准答案。现有多领域RAG-QA方法要么盲目查询所有领域，徒增计算成本与LLM幻觉，要么依赖僵化资源选择，限制搜索结果。我们推出MKP-QA，一种创新的多产品知识增强问答框架，具备跨领域及相关知识的概率联合搜索能力。该方法通过整合查询-领域与查询-段落概率相关性，显著提升多领域搜索质量。针对多产品问答基准缺失问题，我们还推出了聚焦Adobe Experience Platform、Target及Customer Journey Analytics三大产品的新数据集。实验证明，MKP-QA在检索精度与响应质量上，大幅提升了多产品RAG-QA的表现。

> Recent advancements in Large Language Models and Retrieval-Augmented Generation have boosted interest in domain-specific question-answering for enterprise products. However, AI Assistants often face challenges in multi-product QA settings, requiring accurate responses across diverse domains. Existing multi-domain RAG-QA approaches either query all domains indiscriminately, increasing computational costs and LLM hallucinations, or rely on rigid resource selection, which can limit search results. We introduce MKP-QA, a novel multi-product knowledge-augmented QA framework with probabilistic federated search across domains and relevant knowledge. This method enhances multi-domain search quality by aggregating query-domain and query-passage probabilistic relevance. To address the lack of suitable benchmarks for multi-product QAs, we also present new datasets focused on three Adobe products: Adobe Experience Platform, Target, and Customer Journey Analytics. Our experiments show that MKP-QA significantly boosts multi-product RAG-QA performance in terms of both retrieval accuracy and response quality.

[Arxiv](https://arxiv.org/abs/2501.14998)