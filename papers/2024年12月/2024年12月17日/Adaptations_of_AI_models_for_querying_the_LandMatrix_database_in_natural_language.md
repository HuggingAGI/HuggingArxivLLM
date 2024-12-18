# 用于以自然语言查询 LandMatrix 数据库的 AI 模型的改编

发布时间：2024年12月17日

`LLM应用` `公共政策`

> Adaptations of AI models for querying the LandMatrix database in natural language

# 摘要

> 土地矩阵倡议（https://landmatrix.org）及其全球观测站致力于为中低收入国家的农业、采掘或能源等领域提供大规模土地收购的可靠数据，以推动相关的讨论和行动。然而，尽管这些数据在学术界获得认可，但在公共政策中却未被充分利用，主要归因于获取和使用的复杂性，这需要技术专长以及对数据库架构的深入理解。
    此项工作的目标在于简化从不同数据库系统获取数据的流程。本文所提出的方法通过土地矩阵的数据进行评估。本工作对大型语言模型（LLMs）进行了各种比较，还展示了 LLM 适配（提示工程、RAG、代理）的组合，用于查询不同的数据库系统（GraphQL 和 REST 查询）。实验具有可重复性，在线演示可在以下网址获取：https://github.com/tetis-nlp/landmatrix-graphql-python。

> The Land Matrix initiative (https://landmatrix.org) and its global observatory aim to provide reliable data on large-scale land acquisitions to inform debates and actions in sectors such as agriculture, extraction, or energy in low- and middle-income countries. Although these data are recognized in the academic world, they remain underutilized in public policy, mainly due to the complexity of access and exploitation, which requires technical expertise and a good understanding of the database schema.
  The objective of this work is to simplify access to data from different database systems. The methods proposed in this article are evaluated using data from the Land Matrix. This work presents various comparisons of Large Language Models (LLMs) as well as combinations of LLM adaptations (Prompt Engineering, RAG, Agents) to query different database systems (GraphQL and REST queries). The experiments are reproducible, and a demonstration is available online: https://github.com/tetis-nlp/landmatrix-graphql-python.

[Arxiv](https://arxiv.org/abs/2412.12961)