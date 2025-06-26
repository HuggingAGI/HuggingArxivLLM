# 解析安全日志的语义感知方法

发布时间：2025年06月20日

`LLM应用` `网络安全` `日志分析`

> Semantic-Aware Parsing for Security Logs

# 摘要

> 安全分析师在处理异构且缺乏结构的现实世界日志时，难以快速高效地查询和关联日志数据。现有AI日志解析器专注于语义日志模板的学习，但缺乏必要的语义解释能力以支持查询操作。直接在原始日志上对大型语言模型进行大规模查询不仅不切实际，还容易遭受提示注入攻击。

本文介绍的Matryoshka是首个利用大型语言模型自动生成语义感知结构化日志解析器的端到端系统。它巧妙结合了采用精确正则表达式的新型语法解析器，以及全新的语义解析层——该层通过对变量进行聚类并映射到可查询且语境有意义的模式中，为分析师提供了语义丰富且易于查询的数据表示，从而实现快速准确的日志查询，无需传统手动解析器的繁琐构建过程。此外，Matryoshka能够将新生成的字段映射到开放网络安全架构框架（OCSF）中的标准属性，确保不同系统间的互操作性。

我们在一个全新整理的现实世界日志基准上对Matryoshka进行了全面评估，引入了创新的评估指标来衡量字段在不同日志中命名和映射的一致性。实验结果表明，Matryoshka的语法解析器性能超越了现有方法，其语义解析层在现实安全查询任务中达到了0.95的F1分数。尽管将字段映射到广泛的OCSF分类法仍具挑战性，但Matryoshka通过自动化提取和组织有价值字段，显著降低了手动工作量，推动了完全自动化的AI驱动日志分析的实现。


> Security analysts struggle to quickly and efficiently query and correlate log data due to the heterogeneity and lack of structure in real-world logs. Existing AI-based parsers focus on learning syntactic log templates but lack the semantic interpretation needed for querying. Directly querying large language models on raw logs is impractical at scale and vulnerable to prompt injection attacks.
  In this paper, we introduce Matryoshka, the first end-to-end system leveraging LLMs to automatically generate semantically-aware structured log parsers. Matryoshka combines a novel syntactic parser-employing precise regular expressions rather than wildcards-with a completely new semantic parsing layer that clusters variables and maps them into a queryable, contextually meaningful schema. This approach provides analysts with queryable and semantically rich data representations, facilitating rapid and precise log querying without the traditional burden of manual parser construction. Additionally, Matryoshka can map the newly created fields to recognized attributes within the Open Cybersecurity Schema Framework (OCSF), enabling interoperability.
  We evaluate Matryoshka on a newly curated real-world log benchmark, introducing novel metrics to assess how consistently fields are named and mapped across logs. Matryoshka's syntactic parser outperforms prior works, and the semantic layer achieves an F1 score of 0.95 on realistic security queries. Although mapping fields to the extensive OCSF taxonomy remains challenging, Matryoshka significantly reduces manual effort by automatically extracting and organizing valuable fields, moving us closer to fully automated, AI-driven log analytics.

[Arxiv](https://arxiv.org/abs/2506.17512)