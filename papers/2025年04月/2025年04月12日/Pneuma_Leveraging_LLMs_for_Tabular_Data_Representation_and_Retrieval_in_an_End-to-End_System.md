# Pneuma：借助 LLMs 打造表格数据表示与检索的端到端系统

发布时间：2025年04月12日

`LLM应用` `数据发现` `大型语言模型`

> Pneuma: Leveraging LLMs for Tabular Data Representation and Retrieval in an End-to-End System

# 摘要

> 在数据库、数据湖和存储库中发现相关表格是挖掘数据价值的第一步。这一任务仍然具有挑战性，因为评估一个表格是否与某个问题相关不仅仅取决于其内容，还取决于上下文，而这种上下文通常是团队或个人掌握的内部知识。尽管数据目录和学术数据发现系统等工具试图解决这一问题，但它们依赖关键词搜索或更复杂的界面，限制了非技术人员查找相关数据的能力。大型语言模型（LLMs）的出现为用户提供了一种直接通过自然语言提问的机会，使数据集的发现更加直观、易用和高效。

> Finding relevant tables among databases, lakes, and repositories is the first step in extracting value from data. Such a task remains difficult because assessing whether a table is relevant to a problem does not always depend only on its content but also on the context, which is usually tribal knowledge known to the individual or team. While tools like data catalogs and academic data discovery systems target this problem, they rely on keyword search or more complex interfaces, limiting non-technical users' ability to find relevant data. The advent of large language models (LLMs) offers a unique opportunity for users to ask questions directly in natural language, making dataset discovery more intuitive, accessible, and efficient.
  In this paper, we introduce Pneuma, a retrieval-augmented generation (RAG) system designed to efficiently and effectively discover tabular data. Pneuma leverages large language models (LLMs) for both table representation and table retrieval. For table representation, Pneuma preserves schema and row-level information to ensure comprehensive data understanding. For table retrieval, Pneuma augments LLMs with traditional information retrieval techniques, such as full-text and vector search, harnessing the strengths of both to improve retrieval performance. To evaluate Pneuma, we generate comprehensive benchmarks that simulate table discovery workload on six real-world datasets including enterprise data, scientific databases, warehousing data, and open data. Our results demonstrate that Pneuma outperforms widely used table search systems (such as full-text search and state-of-the-art RAG systems) in accuracy and resource efficiency.

[Arxiv](https://arxiv.org/abs/2504.09207)