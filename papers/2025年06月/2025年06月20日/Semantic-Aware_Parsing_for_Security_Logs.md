# 面向安全日志的语义感知解析

发布时间：2025年06月20日

`LLM应用` `安全分析` `日志管理`

> Semantic-Aware Parsing for Security Logs

# 摘要

> 安全分析师在处理现实世界日志数据时常常面临挑战：数据的异构性和缺乏结构使得快速高效地查询和关联变得困难。现有的AI解析器虽然专注于学习语义日志模板，但缺乏必要的语义解释能力。直接在原始日志上使用大型语言模型进行查询不仅在大规模应用中不切实际，还容易遭受提示注入攻击。

在这篇论文中，我们首次提出了Matryoshka——一个端到端系统，利用LLM自动生成语义感知的结构化日志解析器。该系统创新性地结合了采用精确正则表达式而非通配符的语义解析器，以及全新的语义解析层。这一层能够对变量进行聚类并将其映射到可查询且语义丰富的模式中。这种设计为分析师提供了高效的数据表示，使他们能够快速准确地进行日志查询，而无需传统手动构建解析器的负担。此外，Matryoshka支持将新创建的字段映射到开放网络安全架构框架（OCSF）中的已识别属性，从而实现跨系统的互操作性。

我们在一个新整理的现实世界日志基准上对Matryoshka进行了全面评估，并引入了新的评估指标来衡量字段在不同日志中的命名和映射一致性。结果显示，Matryoshka的语义解析器在性能上超越了现有的解决方案，其语义层在现实安全查询中达到了0.95的F1分数。尽管将字段映射到广泛的OCSF分类仍具挑战性，但Matryoshka通过自动提取和组织有价值的字段，显著减少了手动工作量，推动了AI驱动日志分析的自动化进程。


> Security analysts struggle to quickly and efficiently query and correlate log data due to the heterogeneity and lack of structure in real-world logs. Existing AI-based parsers focus on learning syntactic log templates but lack the semantic interpretation needed for querying. Directly querying large language models on raw logs is impractical at scale and vulnerable to prompt injection attacks.
  In this paper, we introduce Matryoshka, the first end-to-end system leveraging LLMs to automatically generate semantically-aware structured log parsers. Matryoshka combines a novel syntactic parser-employing precise regular expressions rather than wildcards-with a completely new semantic parsing layer that clusters variables and maps them into a queryable, contextually meaningful schema. This approach provides analysts with queryable and semantically rich data representations, facilitating rapid and precise log querying without the traditional burden of manual parser construction. Additionally, Matryoshka can map the newly created fields to recognized attributes within the Open Cybersecurity Schema Framework (OCSF), enabling interoperability.
  We evaluate Matryoshka on a newly curated real-world log benchmark, introducing novel metrics to assess how consistently fields are named and mapped across logs. Matryoshka's syntactic parser outperforms prior works, and the semantic layer achieves an F1 score of 0.95 on realistic security queries. Although mapping fields to the extensive OCSF taxonomy remains challenging, Matryoshka significantly reduces manual effort by automatically extracting and organizing valuable fields, moving us closer to fully automated, AI-driven log analytics.

[Arxiv](https://arxiv.org/abs/2506.17512)