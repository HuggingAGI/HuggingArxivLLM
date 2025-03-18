# DAgent：基于关系型数据库驱动的数据分析报告生成器

发布时间：2025年03月17日

`Agent`

> DAgent: A Relational Database-Driven Data Analysis Report Generation Agent

# 摘要

> 基于关系型数据库的数据分析报告生成（RDB-DA）在金融和医疗等领域得到了广泛应用。然而，这类任务通常由数据科学家手动完成，耗时且亟需自动化。现有方法（如表格问答或文本到SQL）虽减少了人工依赖，但无法处理复杂的分析任务。为解决这一问题，本文提出了一种名为DAgent的LLM代理系统，并构建了一个包含新数据集DA-Dataset和评估指标的基准。DAgent通过规划、工具和记忆模块，将自然语言问题分解为独立的子查询，准确检索数据库信息，并通过多步推理和数据整合生成高质量的分析报告。实验结果表明，DAgent在检索性能和报告质量上表现优异，展现出在复杂数据库分析任务中的巨大潜力。

> Relational database-driven data analysis (RDB-DA) report generation, which aims to generate data analysis reports after querying relational databases, has been widely applied in fields such as finance and healthcare. Typically, these tasks are manually completed by data scientists, making the process very labor-intensive and showing a clear need for automation. Although existing methods (e.g., Table QA or Text-to-SQL) have been proposed to reduce human dependency, they cannot handle complex analytical tasks that require multi-step reasoning, cross-table associations, and synthesizing insights into reports. Moreover, there is no dataset available for developing automatic RDB-DA report generation. To fill this gap, this paper proposes an LLM agent system for RDB-DA report generation tasks, dubbed DAgent; moreover, we construct a benchmark for automatic data analysis report generation, which includes a new dataset DA-Dataset and evaluation metrics. DAgent integrates planning, tools, and memory modules to decompose natural language questions into logically independent sub-queries, accurately retrieve key information from relational databases, and generate analytical reports that meet the requirements of completeness, correctness, and conciseness through multi-step reasoning and effective data integration. Experimental analysis on the DA-Dataset demonstrates that DAgent's superiority in retrieval performance and analysis report generation quality, showcasing its strong potential for tackling complex database analysis report generation tasks.

[Arxiv](https://arxiv.org/abs/2503.13269)