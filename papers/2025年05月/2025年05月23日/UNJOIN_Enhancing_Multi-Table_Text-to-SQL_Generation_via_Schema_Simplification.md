# # UNJOIN：通过简化模式提升多表文本转SQL生成效果

发布时间：2025年05月23日

`LLM应用` `数据库` `SQL生成`

> UNJOIN: Enhancing Multi-Table Text-to-SQL Generation via Schema Simplification

# 摘要

> 大型语言模型 (LLMs) 的发展显著提升了单表查询的 Text-to-SQL 性能。然而，多表数据库的复杂架构和关系运算仍具挑战性。现有方法在检索正确表列、生成准确的 JOIN 和 UNION 以及跨架构泛化方面表现欠佳。为解决这些问题，我们提出 UNJOIN，一个两阶段框架，将架构元素检索与 SQL 逻辑生成分离。第一阶段，我们通过为每个列名添加表名前缀，将数据库所有表的列名合并为单表表示，使模型专注于准确检索。第二阶段，基于简化架构生成 SQL 查询，并通过重建 JOIN、UNION 和关系逻辑映射回原始架构。在 SPIDER 和 BIRD 数据集上的实验表明，UNJOIN 的性能与现有最优基线相当或更优。UNJOIN 仅依赖架构信息，无需数据访问或微调，具备跨数据库的可扩展性和适应性。

> Recent advances in large language models (LLMs) have greatly improved Text-to-SQL performance for single-table queries. But, it remains challenging in multi-table databases due to complex schema and relational operations. Existing methods often struggle with retrieving the right tables and columns, generating accurate JOINs and UNIONs, and generalizing across diverse schemas. To address these issues, we introduce UNJOIN, a two-stage framework that decouples the retrieval of schema elements from SQL logic generation. In the first stage, we merge the column names of all tables in the database into a single-table representation by prefixing each column with its table name. This allows the model to focus purely on accurate retrieval without being distracted by the need to write complex SQL logic. In the second stage, the SQL query is generated on this simplified schema and mapped back to the original schema by reconstructing JOINs, UNIONs, and relational logic. Evaluations on SPIDER and BIRD datasets show that UNJOIN matches or exceeds the state-of-the-art baselines. UNJOIN uses only schema information, which does not require data access or fine-tuning, making it scalable and adaptable across databases.

[Arxiv](https://arxiv.org/abs/2505.18122)