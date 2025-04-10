# ER-RAG：利用基于ER的统一建模增强异构数据源的RAG方法

发布时间：2025年03月02日

`RAG` `问答系统` `知识图谱`

> ER-RAG: Enhance RAG with ER-Based Unified Modeling of Heterogeneous Data Sources

# 摘要

> 大型语言模型（LLMs）在问答（QA）任务中表现出色，而检索增强生成（RAG）通过整合来自网页、数据库和知识图谱等多样化外部来源的证据，进一步提升了其精确性。然而，当前的RAG方法依赖于针对特定数据源的个体策略，这在资源有限或黑箱环境下带来了挑战，并且当证据分散于多个来源时，操作也会变得复杂。为了解决这些限制，我们提出了ER-RAG框架，它利用实体-关系（ER）模型实现了跨异构数据源的证据整合统一。ER-RAG通过基于ER模型的API，采用GET和JOIN操作，实现了实体检索和关系查询的标准规范化。它采用两阶段生成过程：首先，一个偏好优化模块选择最优来源；其次，另一个模块根据源模式构建API链。这种统一方法实现了高效微调和跨多样化数据源的无缝集成。ER-RAG在2024年KDDCup CRAG挑战赛中赢得了所有三个赛道，使用8B LLM backbone达到了与商用RAG流水线相当的性能，同时在LLM评分上比混合竞争对手高出3.1%，并将检索速度提升了5.5倍。

> Large language models (LLMs) excel in question-answering (QA) tasks, and retrieval-augmented generation (RAG) enhances their precision by incorporating external evidence from diverse sources like web pages, databases, and knowledge graphs. However, current RAG methods rely on agent-specific strategies for individual data sources, posing challenges low-resource or black-box environments and complicates operations when evidence is fragmented across sources. To address these limitations, we propose ER-RAG, a framework that unifies evidence integration across heterogeneous data sources using the Entity-Relationship (ER) model. ER-RAG standardizes entity retrieval and relationship querying through ER-based APIs with GET and JOIN operations. It employs a two-stage generation process: first, a preference optimization module selects optimal sources; second, another module constructs API chains based on source schemas. This unified approach allows efficient fine-tuning and seamless integration across diverse data sources. ER-RAG demonstrated its effectiveness by winning all three tracks of the 2024 KDDCup CRAG Challenge, achieving performance on par with commercial RAG pipelines using an 8B LLM backbone. It outperformed hybrid competitors by 3.1% in LLM score and accelerated retrieval by 5.5X.

[Arxiv](https://arxiv.org/abs/2504.06271)