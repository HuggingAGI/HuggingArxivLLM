# InReAcTable：LLM驱动的基于表格数据的交互式可视化数据故事构建

发布时间：2025年08月25日

`RAG` `基础理论`

> InReAcTable: LLM-Powered Interactive Visual Data Story Construction from Tabular Data

# 摘要

> 表格数据中的洞察蕴含着有价值的模式，能帮助分析师把握关键信息。将相关洞察组织成可视化数据故事，是深入分析的关键。然而，构建这类故事颇具挑战——提取的洞察之间存在复杂的内在关联。用户往往需要从海量离散洞察中筛选，再整合成符合分析目标的统一叙事，这一过程困难重重。现有方法要么过度依赖用户专业知识，导致效率低下；要么采用自动化手段，却难以完全捕捉用户动态变化的目标。为此，本文提出InReAcTable框架，通过构建数据洞察间的结构与语义双重关联，助力可视化数据故事的构建。用户每一次交互都会触发Acting模块：该模块利用洞察图进行结构过滤以缩小搜索范围，随后Reasoning模块借助基于大型语言模型的检索增强生成技术完成语义过滤，最终推荐出与用户分析意图匹配的洞察。基于InReAcTable框架，我们开发了交互式原型系统，可引导用户构建贴合其分析需求的可视化数据故事。我们通过案例研究与用户实验，验证了InReAcTable框架及原型系统在交互式构建可视化数据故事时的实用性与有效性。

> Insights in tabular data capture valuable patterns that help analysts understand critical information. Organizing related insights into visual data stories is crucial for in-depth analysis. However, constructing such stories is challenging because of the complexity of the inherent relations between extracted insights. Users face difficulty sifting through a vast number of discrete insights to integrate specific ones into a unified narrative that meets their analytical goals. Existing methods either heavily rely on user expertise, making the process inefficient, or employ automated approaches that cannot fully capture their evolving goals. In this paper, we introduce InReAcTable, a framework that enhances visual data story construction by establishing both structural and semantic connections between data insights. Each user interaction triggers the Acting module, which utilizes an insight graph for structural filtering to narrow the search space, followed by the Reasoning module using the retrieval-augmented generation method based on large language models for semantic filtering, ultimately providing insight recommendations aligned with the user's analytical intent. Based on the InReAcTable framework, we develop an interactive prototype system that guides users to construct visual data stories aligned with their analytical requirements. We conducted a case study and a user experiment to demonstrate the utility and effectiveness of the InReAcTable framework and the prototype system for interactively building visual data stories.

[Arxiv](https://arxiv.org/abs/2508.18174)