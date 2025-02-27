# 以代理为中心的信息访问

发布时间：2025年02月26日

`Agent` `人工智能` `信息检索`

> Agent-centric Information Access

# 摘要

> 随着大型语言模型（LLMs）的专业化发展，我们展望未来将有数百万个专家型LLMs，每个都基于专有数据训练，在特定领域表现出色。在这一系统中，回答查询需高效筛选相关模型，整合它们的回答。本文提出了一种以智能体为中心的信息访问框架，LLMs作为知识智能体，根据其专业知识动态排名和查询。与传统文档检索不同，此方法需实时推断专业知识，而非依赖静态元数据或预先定义的描述。这种转变带来了高效专业选择、成本效益查询、跨模型回答整合及抵御对抗性操纵等挑战。为应对这些挑战，我们提出了一种可扩展的评估框架，利用检索增强生成和聚类技术，构建并评估数千个专业模型，未来有望扩展至数百万个模型。

> As large language models (LLMs) become more specialized, we envision a future where millions of expert LLMs exist, each trained on proprietary data and excelling in specific domains. In such a system, answering a query requires selecting a small subset of relevant models, querying them efficiently, and synthesizing their responses. This paper introduces a framework for agent-centric information access, where LLMs function as knowledge agents that are dynamically ranked and queried based on their demonstrated expertise. Unlike traditional document retrieval, this approach requires inferring expertise on the fly, rather than relying on static metadata or predefined model descriptions. This shift introduces several challenges, including efficient expert selection, cost-effective querying, response aggregation across multiple models, and robustness against adversarial manipulation. To address these issues, we propose a scalable evaluation framework that leverages retrieval-augmented generation and clustering techniques to construct and assess thousands of specialized models, with the potential to scale toward millions.

[Arxiv](https://arxiv.org/abs/2502.19298)