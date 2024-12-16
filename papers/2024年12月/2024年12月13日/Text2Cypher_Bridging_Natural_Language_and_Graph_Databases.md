# Text2Cypher：架起自然语言与图形数据库之间的桥梁

发布时间：2024年12月13日

`LLM应用` `知识图谱`

> Text2Cypher: Bridging Natural Language and Graph Databases

# 摘要

> 知识图谱借助节点、关系和属性来呈现任意复杂的数据。当存于图形数据库时，Cypher 查询语言可对知识图谱进行高效建模与查询。不过，使用 Cypher 需具备专业知识，这对非专家用户而言是个难题。我们的工作 Text2Cypher 旨在把自然语言查询转化为 Cypher 查询语言，从而填补这一鸿沟，将知识图谱的用途拓展至非技术专家用户。
    虽说大型语言模型（LLMs）能用于此，但它们常常难以捕捉复杂的细微之处，致使输出不完整或有误。在特定领域的数据集中对 LLMs 进行微调已被证实是更有前景的办法，然而高质量、公开可用的 Text2Cypher 数据集数量有限，这颇具挑战性。在本项工作中，我们展示了如何把几个公开可用的数据集加以整合、清理和组织，形成总计 44,387 个实例，实现有效的微调与评估。在该数据集上微调的模型性能显著提升，在 Google-BLEU 和精确匹配分数上比基线模型更优，凸显了高质量数据集和微调对于提升 Text2Cypher 性能的重要性。

> Knowledge graphs use nodes, relationships, and properties to represent arbitrarily complex data. When stored in a graph database, the Cypher query language enables efficient modeling and querying of knowledge graphs. However, using Cypher requires specialized knowledge, which can present a challenge for non-expert users. Our work Text2Cypher aims to bridge this gap by translating natural language queries into Cypher query language and extending the utility of knowledge graphs to non-technical expert users.
  While large language models (LLMs) can be used for this purpose, they often struggle to capture complex nuances, resulting in incomplete or incorrect outputs. Fine-tuning LLMs on domain-specific datasets has proven to be a more promising approach, but the limited availability of high-quality, publicly available Text2Cypher datasets makes this challenging. In this work, we show how we combined, cleaned and organized several publicly available datasets into a total of 44,387 instances, enabling effective fine-tuning and evaluation. Models fine-tuned on this dataset showed significant performance gains, with improvements in Google-BLEU and Exact Match scores over baseline models, highlighting the importance of high-quality datasets and fine-tuning in improving Text2Cypher performance.

[Arxiv](https://arxiv.org/abs/2412.10064)