# 打造高保真复杂测试数据，赋能实际场景下的SQL代码生成服务

发布时间：2025年04月23日

`LLM应用

摘要讨论了大型语言模型（LLMs）在生成测试数据中的应用，特别是在SQL代码生成服务中的实际效用，属于LLM的实际应用。` `数据库`

> High-Fidelity And Complex Test Data Generation For Real-World SQL Code Generation Services

# 摘要

> 在工业环境中，高保真测试数据的需求至关重要，因为生产数据的访问受到严格限制。传统数据生成方法在生成低保真数据时显得力不从心，尤其难以建模复杂的数据结构和语义关系，这对于测试像自然语言到SQL（NL2SQL）这样复杂的SQL代码生成服务尤为重要。本文聚焦于包含嵌套结构列的复杂模式，这种模式在Google SQL代码生成任务中频繁出现，重点解决生成语法正确且语义“有意义”模拟数据的迫切需求。我们揭示了现有生产环境中方法的局限性，特别是它们在处理大规模和复杂模式方面的不足，以及缺乏语义连贯的测试数据导致的有限测试覆盖率。我们证明，通过利用大型语言模型（LLMs）并结合策略性的预处理和后处理步骤，我们可以生成符合复杂结构约束、保持语义完整性的高保真测试数据，这些数据与测试目标（SQL查询/函数）高度一致。这种方法支持对涉及连接、聚合甚至深度嵌套子查询的复杂SQL查询进行全方位测试，从而确保对SQL代码生成服务（如NL2SQL和SQL代码助手服务）进行稳健评估。我们的结果展示了基于现成大型语言模型（	extit{gemini}）的测试数据生成方案在工业SQL代码生成服务中的实际效用，特别是在生产数据集经常不可用的情况下，生成真实测试数据至关重要。

> The demand for high-fidelity test data is paramount in industrial settings where access to production data is largely restricted. Traditional data generation methods often fall short, struggling with low-fidelity and the ability to model complex data structures and semantic relationships that are critical for testing complex SQL code generation services like Natural Language to SQL (NL2SQL). In this paper, we address the critical need for generating syntactically correct and semantically ``meaningful'' mock data for complex schema that includes columns with nested structures that we frequently encounter in Google SQL code generation workloads. We highlight the limitations of existing approaches used in production, particularly their inability to handle large and complex schema, as well as the lack of semantically coherent test data that lead to limited test coverage. We demonstrate that by leveraging Large Language Models (LLMs) and incorporating strategic pre- and post-processing steps, we can generate realistic high-fidelity test data that adheres to complex structural constraints and maintains semantic integrity to the test targets (SQL queries/functions). This approach supports comprehensive testing of complex SQL queries involving joins, aggregations, and even deeply nested subqueries, ensuring robust evaluation of SQL code generation services, like NL2SQL and SQL Code Assistant services. Our results demonstrate the practical utility of an out-of-the-box LLM (\textit{gemini}) based test data generation for industrial SQL code generation services where generating realistic test data is essential due to the frequent unavailability of production datasets.

[Arxiv](https://arxiv.org/abs/2504.17203)