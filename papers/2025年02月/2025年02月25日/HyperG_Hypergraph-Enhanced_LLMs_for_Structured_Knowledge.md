# # HyperG：超图增强的大型语言模型，助力结构化知识处理

发布时间：2025年02月25日

`LLM应用

摘要讨论了如何改进大型语言模型处理结构化数据的能力，并提出了一种新的框架HyperG，用于提升LLMs在结构化数据上的应用效果。尽管涉及模型改进，但主要关注点在于应用层面的提升，因此归类为LLM应用。` `结构化数据处理` `知识图谱`

> HyperG: Hypergraph-Enhanced LLMs for Structured Knowledge

# 摘要

> 由于大量专业知识以结构化格式存储（如通过HTML组织的网页数据），大型语言模型（LLMs）需要充分理解这些结构化信息，以拓展其在现实世界任务中的应用。目前，将LLMs应用于结构化数据的方法主要分为两类：基于序列化和基于操作的方法。然而，无论是通过序列化还是使用类似SQL的操作作为中介，这两种方法在捕获结构关系和处理稀疏数据方面都存在局限性。针对结构化数据的独特特性，我们提出了一种基于超图的生成框架HyperG，旨在提升LLMs处理结构化知识的能力。具体来说，HyperG首先通过上下文信息丰富稀疏数据，充分发挥LLMs的生成能力，并引入提示注意力超图学习（PHL）网络，以编码增强的信息及数据中的复杂结构关系。为验证HyperG的有效性和通用性，我们在需要结构化知识的两个不同下游任务中进行了广泛实验。

> Given that substantial amounts of domain-specific knowledge are stored in structured formats, such as web data organized through HTML, Large Language Models (LLMs) are expected to fully comprehend this structured information to broaden their applications in various real-world downstream tasks. Current approaches for applying LLMs to structured data fall into two main categories: serialization-based and operation-based methods. Both approaches, whether relying on serialization or using SQL-like operations as an intermediary, encounter difficulties in fully capturing structural relationships and effectively handling sparse data. To address these unique characteristics of structured data, we propose HyperG, a hypergraph-based generation framework aimed at enhancing LLMs' ability to process structured knowledge. Specifically, HyperG first augment sparse data with contextual information, leveraging the generative power of LLMs, and incorporate a prompt-attentive hypergraph learning (PHL) network to encode both the augmented information and the intricate structural relationships within the data. To validate the effectiveness and generalization of HyperG, we conduct extensive experiments across two different downstream tasks requiring structured knowledge.

[Arxiv](https://arxiv.org/abs/2502.18125)