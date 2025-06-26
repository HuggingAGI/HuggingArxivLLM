# HI-SQL：通过整合动态提示机制优化文本转SQL系统性能

发布时间：2025年06月11日

`LLM应用` `数据库`

> HI-SQL: Optimizing Text-to-SQL Systems through Dynamic Hint Integration

# 摘要

> 文本到SQL生成架起了自然语言与数据库之间的桥梁，让用户无需掌握SQL技能即可轻松查询数据。虽然大型语言模型（LLMs）在这一领域取得了长足的进步，但在处理涉及多表连接、嵌套条件和复杂操作的复杂查询时，仍存在诸多挑战。现有方法通常采用多步骤管道，不仅计算成本高昂、延迟增加，还容易导致错误积累。为了解决这些问题，我们提出了HI-SQL，一种创新的管道，它利用历史查询日志生成上下文提示，以指导SQL生成过程。通过分析以往的查询记录，我们的方法能够生成针对性的提示，特别关注多表和嵌套操作中的复杂性。这些提示被无缝融入SQL生成流程，不仅避免了繁琐的多步骤方法，还大幅降低了对人工编写提示的依赖。实验结果表明，我们的方法在多个基准数据集上显著提升了LLM生成查询的准确性，同时在LLM调用次数和响应延迟方面保持了高效的性能，为优化Text-to-SQL系统提供了一个强大且实用的解决方案。

> Text-to-SQL generation bridges the gap between natural language and databases, enabling users to query data without requiring SQL expertise. While large language models (LLMs) have significantly advanced the field, challenges remain in handling complex queries that involve multi-table joins, nested conditions, and intricate operations. Existing methods often rely on multi-step pipelines that incur high computational costs, increase latency, and are prone to error propagation. To address these limitations, we propose HI-SQL, a pipeline that incorporates a novel hint generation mechanism utilizing historical query logs to guide SQL generation. By analyzing prior queries, our method generates contextual hints that focus on handling the complexities of multi-table and nested operations. These hints are seamlessly integrated into the SQL generation process, eliminating the need for costly multi-step approaches and reducing reliance on human-crafted prompts. Experimental evaluations on multiple benchmark datasets demonstrate that our approach significantly improves query accuracy of LLM-generated queries while ensuring efficiency in terms of LLM calls and latency, offering a robust and practical solution for enhancing Text-to-SQL systems.

[Arxiv](https://arxiv.org/abs/2506.18916)