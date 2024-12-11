# 借助大型语言模型迈向自动化跨领域探索性数据分析

发布时间：2024年12月10日

`LLM应用` `数据分析` `数据库`

> Towards Automated Cross-domain Exploratory Data Analysis through Large Language Models

# 摘要

> 探索性数据分析（EDA）与 SQL 相结合，对从事数据探索与分析工作的数据分析师而言极为关键。然而，数据分析师往往面临两大主要挑战：其一，要熟练编写 SQL 查询；其二，要生成合适的可视化类型，以强化对查询结果的解读。鉴于其重要性，大量研究工作致力于探索应对这些挑战的不同方法，包括借助大型语言模型（LLMs）。但现有方法主要因以下原因无法满足现实世界的数据探索需求：一是复杂的数据库模式；二是不清晰的用户意图；三是有限的跨领域泛化能力；四是端到端文本到可视化能力不足。
    本文呈现了 TiInsight，一个基于 SQL 的自动化跨领域探索性数据分析系统。首先，我们提出了分层数据上下文（即 HDC），它借助 LLMs 来总结与数据库模式相关的内容，这对开放世界的 EDA 系统在数据领域实现泛化至关重要。其次，EDA 系统分为四个部分（即阶段）：HDC 生成、问题澄清与分解、文本到 SQL 生成（即 TiSQL）以及数据可视化（即 TiChart）。最后，我们在 PingCAP 的生产环境中构建了一个具备用户友好图形用户界面（GUI）的端到端 EDA 系统。我们还将 TiInsight 的所有 API 开源，以推动 EDA 社区内的研究。通过现实世界用户研究的广泛评估，我们表明 TiInsight 相较于人类专家表现卓越。具体来说，TiSQL 在使用 GPT-4 的 Spider 数据集上达到了 86.3％的执行准确率，在 Bird 数据集上也展现出了顶尖水平的性能。

> Exploratory data analysis (EDA), coupled with SQL, is essential for data analysts involved in data exploration and analysis. However, data analysts often encounter two primary challenges: (1) the need to craft SQL queries skillfully, and (2) the requirement to generate suitable visualization types that enhance the interpretation of query results. Due to its significance, substantial research efforts have been made to explore different approaches to address these challenges, including leveraging large language models (LLMs). However, existing methods fail to meet real-world data exploration requirements primarily due to (1) complex database schema; (2) unclear user intent; (3) limited cross-domain generalization capability; and (4) insufficient end-to-end text-to-visualization capability.
  This paper presents TiInsight, an automated SQL-based cross-domain exploratory data analysis system. First, we propose hierarchical data context (i.e., HDC), which leverages LLMs to summarize the contexts related to the database schema, which is crucial for open-world EDA systems to generalize across data domains. Second, the EDA system is divided into four components (i.e., stages): HDC generation, question clarification and decomposition, text-to-SQL generation (i.e., TiSQL), and data visualization (i.e., TiChart). Finally, we implemented an end-to-end EDA system with a user-friendly GUI interface in the production environment at PingCAP. We have also open-sourced all APIs of TiInsight to facilitate research within the EDA community. Through extensive evaluations by a real-world user study, we demonstrate that TiInsight offers remarkable performance compared to human experts. Specifically, TiSQL achieves an execution accuracy of 86.3% on the Spider dataset using GPT-4. It also demonstrates state-of-the-art performance on the Bird dataset.

[Arxiv](https://arxiv.org/abs/2412.07214)