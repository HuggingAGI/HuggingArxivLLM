# # 摘要
从关系型数据库中生成基于检索增强的本体

发布时间：2025年06月01日

`RAG` `知识图谱` `数据库`

> Retrieval-Augmented Generation of Ontologies from Relational Databases

# 摘要

> 将关系型数据库转化为知识图谱，搭配丰富的本体，不仅能提升语义互操作性，还能释放基于图的高级学习与推理潜力。然而，传统方法要么需要大量手动工作从数据库模式中提取本体，要么只能生成基础本体。我们推出RIGOR（基于检索增强的迭代生成关系数据库本体方法），这是一种LLM驱动的解决方案，能够以极小的人工干预将关系模式转化为丰富的OWL本体。RIGOR借助RAG技术，整合数据库模式及其文档、领域本体存储库和不断扩展的核心本体，驱动生成式LLM持续产出带有来源标记的增量本体片段。每个片段在被核心本体吸收前都会经过评判LLM的优化，并遵循外键约束逐表处理，直至全面覆盖。在真实世界数据库中的应用表明，RIGOR生成的本体在准确性、完整性、简洁性、适应性、清晰度和一致性等关键质量指标上表现优异，同时大幅降低了人工工作量。

> Transforming relational databases into knowledge graphs with enriched ontologies enhances semantic interoperability and unlocks advanced graph-based learning and reasoning over data. However, previous approaches either demand significant manual effort to derive an ontology from a database schema or produce only a basic ontology. We present RIGOR, Retrieval-augmented Iterative Generation of RDB Ontologies, an LLM-driven approach that turns relational schemas into rich OWL ontologies with minimal human effort. RIGOR combines three sources via RAG, the database schema and its documentation, a repository of domain ontologies, and a growing core ontology, to prompt a generative LLM for producing successive, provenance-tagged delta ontology fragments. Each fragment is refined by a judge-LLM before being merged into the core ontology, and the process iterates table-by-table following foreign key constraints until coverage is complete. Applied to real-world databases, our approach outputs ontologies that score highly on standard quality dimensions such as accuracy, completeness, conciseness, adaptability, clarity, and consistency, while substantially reducing manual effort.

[Arxiv](https://arxiv.org/abs/2506.01232)