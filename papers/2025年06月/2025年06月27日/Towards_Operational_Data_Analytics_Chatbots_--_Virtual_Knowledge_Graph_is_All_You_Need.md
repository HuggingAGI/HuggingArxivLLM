# 迈向业务数据分析聊天机器人——虚拟知识图谱，一切所需

发布时间：2025年06月27日

`LLM应用` `科学计算` `数据中心`

> Towards Operational Data Analytics Chatbots -- Virtual Knowledge Graph is All You Need

# 摘要

> 生成式人工智能对科学计算的挑战，使得数据中心在规模和数据量上都经历了前所未有的增长。因此，计算效率变得比以往任何时候都更加重要。运营数据分析（ODA）通过收集数据中心的遥测数据来提升效率，但目前主要集中在实时数据可视化和事后分析上。然而，随着NoSQL数据库成为支持扩展性的默认存储后端，由于其无模式特性，查询这些数据颇具挑战性，因为需要领域知识来遍历数据源之间的关系。本体和知识图谱（KGs）可以捕捉这些关系，但传统KGs的扩展成本高昂，且尚未广泛应用于多变量时间序列。虚拟知识图谱（VKGs）通过在运行时生成特定查询图，提供了一种轻量级的替代方案。

在这项工作中，我们提出了一种完整的端到端ODA聊天机器人系统，该系统使用大型语言模型（LLM）生成SPARQL查询，并利用VKG进行数据检索。与直接使用NoSQL查询相比，这种方法实现了92.5%的准确率，而直接查询的准确率为25%。所提出的 methodology 优化了VKG构建和LLM推理，将之前工作的平均查询延迟降低了85%（从20.36秒降至3.03秒），并将VKG大小控制在179 MiB以内。这种性能使该工具适合部署，并能够实时与ODA最终用户进行交互。

> With generative artificial intelligence challenging computational scientific computing, data centers are experiencing unprecedented growth in both scale and volume. As a result, computing efficiency has become more critical than ever. Operational Data Analytics (ODA) relies on the collection of data center telemetry to improve efficiency, but so far has been focusing on real-time telemetry data visualization and post-mortem analysis. However, with NoSQL databases now serving as the default storage backend to support scalability, querying this data is challenging due to its schema-less nature, which requires domain knowledge to traverse relationships between data sources. Ontologies and Knowledge Graphs (KGs) can capture these relationships, but traditional KGs are costly to scale and have not been widely applied to multivariate timeseries. Virtual Knowledge Graphs (VKGs) offer a lightweight alternative by generating query-specific graphs at runtime. In this work, we present a full end-to-end ODA chatbot system that uses a Large Language Model (LLM) to generate SPARQL queries, utilizing VKG for data retrieval. This approach achieves 92.5% accuracy compared to 25% with direct NoSQL queries. The proposed methodology optimizes VKG construction and LLM inference, cutting previous work average query latency by 85% (from 20.36s to 3.03s) and keeping VKG sizes under 179 MiB. This performance makes the tool suitable for deployment and real-time interaction with ODA end-users.

[Arxiv](https://arxiv.org/abs/2506.22267)