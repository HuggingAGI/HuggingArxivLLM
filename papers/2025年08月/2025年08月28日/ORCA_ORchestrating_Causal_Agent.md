# ORCA：编排因果智能体

发布时间：2025年08月28日

`Agent` `零售与电商`

> ORCA: ORchestrating Causal Agent

# 摘要

> 因果推断是决策科学的核心，但在复杂业务场景中，随着数据规模扩大，从数据整理到因果分析的全流程复杂度显著上升。非专业人员在关系型数据库中操作时，常因重复性瓶颈难以获取及时、可靠的业务洞见。为此，我们提出ORCA（编排因果智能体）——一款基于大型语言模型的智能体系统，可自动处理关系型数据库管理系统（RDBMS）中的常规流程，同时通过人机交互确保专家监督。ORCA能统筹完整的数据分析链路：解析自然语言查询、定位数据库表、生成合规SQL代码、预处理数据，以及调用因果推断库配置建模流程。领域专家仍能通过与ORCA的迭代交互掌控自动化过程，无需深厚的统计计算技术背景即可实现稳健的数据驱动决策。在基准数据集和合成电商数据集上的实证评估显示，ORCA在表理解、查询生成和因果效应估计方面性能优异——与GPT-4o mini相比，其平均处理效应估计精度提升超过【数学公式】。

> Causal inference is essential for decision-making science while the complexity of the data analysis workflow, ranging from data wrangling to causal analysis, increases substantially as the scale of data grows in complicated business environments. Especially, the execution of the workflow in relational databases by non-experts can result in repetitive bottlenecks which impede timely and responsible business insights. To address this challenge, we propose ORCA (Orchestrating Causal Agent), an LLM agentic system that can automate routine workflows in RDBMS while preserving expert oversight via human-AI interactions. ORCA orchestrates the full data analysis pipeline: interpreting natural language queries, navigating tables from DB servers, generating proper SQL codes, preprocessing data, and configuring modeling processes using causal inference libraries. Domain experts still can control the automation through iterative interactions with ORCA, enabling robust data-driven decision making with less technical expertise in statistical computing. Empirical evaluations on benchmark and synthetic e-commerce datasets demonstrate competitive performance of ORCA in table understanding, query generation, and cause-effect estimation -- achieving over $7\times$ improvement in estimating average treatment compared to GPT-4o mini.

[Arxiv](https://arxiv.org/abs/2508.21304)