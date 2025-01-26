# 基于大语言模型与数据库关键词搜索的文本转SQL

发布时间：2025年01月23日

`LLM应用

理由：这篇论文讨论了如何利用大型语言模型（LLMs）来改进Text-to-SQL的提示策略，特别是在实际数据库应用中的表现。论文提出了一种新的策略，结合了动态少样本示例和数据库关键词搜索（KwS）平台服务，以提升NL问题到SQL查询的编译效果。这属于LLM在实际应用中的优化和改进，因此归类为“LLM应用”。` `数据库`

> Text-to-SQL based on Large Language Models and Database Keyword Search

# 摘要

> 基于LLMs的Text-to-SQL提示策略在基准测试中表现出色，但在实际数据库应用中，尤其是处理复杂NL问题时，表现却不尽如人意。本文提出了一种新策略，通过动态少样本示例和数据库关键词搜索（KwS）平台服务，将NL问题编译为SQL查询。文章详细阐述了如何利用示例和KwS平台的关键词匹配服务提升模式链接的精度和召回率，并展示了如何通过KwS平台合成视图简化SQL查询编译。实验结果表明，该策略在实际数据库中的表现超越了现有方法。文章最后对实验结果进行了讨论。

> Text-to-SQL prompt strategies based on Large Language Models (LLMs) achieve remarkable performance on well-known benchmarks. However, when applied to real-world databases, their performance is significantly less than for these benchmarks, especially for Natural Language (NL) questions requiring complex filters and joins to be processed. This paper then proposes a strategy to compile NL questions into SQL queries that incorporates a dynamic few-shot examples strategy and leverages the services provided by a database keyword search (KwS) platform. The paper details how the precision and recall of the schema-linking process are improved with the help of the examples provided and the keyword-matching service that the KwS platform offers. Then, it shows how the KwS platform can be used to synthesize a view that captures the joins required to process an input NL question and thereby simplify the SQL query compilation step. The paper includes experiments with a real-world relational database to assess the performance of the proposed strategy. The experiments suggest that the strategy achieves an accuracy on the real-world relational database that surpasses state-of-the-art approaches. The paper concludes by discussing the results obtained.

[Arxiv](https://arxiv.org/abs/2501.13594)