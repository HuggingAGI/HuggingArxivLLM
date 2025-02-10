# nvAgent: 基于协作代理工作流的自然语言数据可视化自动化

发布时间：2025年02月07日

`Agent

理由：这篇论文介绍了一个名为nvAgent的协作代理工作流，专为自然语言到可视化（NL2Vis）任务设计。nvAgent由多个代理组成，每个代理负责不同的任务（如数据库处理、可视化生成、代码翻译和输出验证），这些代理协同工作以完成复杂的NL2Vis任务。因此，这篇论文的核心内容是关于多代理系统的设计和应用，属于Agent分类。` `数据可视化`

> nvAgent: Automated Data Visualization from Natural Language via Collaborative Agent Workflow

# 摘要

> # 自然语言到可视化（NL2Vis）
NL2Vis致力于将自然语言描述转化为表格的可视化呈现，帮助用户从海量数据中挖掘洞见。随着大型语言模型（LLMs）的飞速发展，自动化代码生成将表格数据转化为可视化图表成为可能。然而，面对需要跨表推理的复杂查询，现有方法往往力不从心。为此，我们提出了一个名为nvAgent的协作代理工作流，专为NL2Vis设计。nvAgent由三个代理组成：处理器代理负责数据库处理和上下文过滤，作曲代理规划可视化生成，验证代理则负责代码翻译和输出验证。在VisEval新基准上的全面评估显示，nvAgent在单表和多表场景中分别实现了7.88%和9.23%的性能提升，显著超越了现有技术。定性分析进一步表明，nvAgent在处理复杂、异构数据源时，性能优势接近20%，充分展现了其生成高质量可视化图表的能力。

> Natural Language to Visualization (NL2Vis) seeks to convert natural-language descriptions into visual representations of given tables, empowering users to derive insights from large-scale data. Recent advancements in Large Language Models (LLMs) show promise in automating code generation to transform tabular data into accessible visualizations. However, they often struggle with complex queries that require reasoning across multiple tables. To address this limitation, we propose a collaborative agent workflow, termed nvAgent, for NL2Vis. Specifically, nvAgent comprises three agents: a processor agent for database processing and context filtering, a composer agent for planning visualization generation, and a validator agent for code translation and output verification. Comprehensive evaluations on the new VisEval benchmark demonstrate that nvAgent consistently surpasses state-of-the-art baselines, achieving a 7.88% improvement in single-table and a 9.23% improvement in multi-table scenarios. Qualitative analyses further highlight that nvAgent maintains nearly a 20% performance margin over previous models, underscoring its capacity to produce high-quality visual representations from complex, heterogeneous data sources.

[Arxiv](https://arxiv.org/abs/2502.05036)