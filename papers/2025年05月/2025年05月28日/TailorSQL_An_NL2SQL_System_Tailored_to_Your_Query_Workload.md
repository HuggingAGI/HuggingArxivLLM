# # TailorSQL: 专为您的查询负载设计的 NL2SQL 系统

发布时间：2025年05月28日

`LLM应用` `数据库` `智能数据应用`

> TailorSQL: An NL2SQL System Tailored to Your Query Workload

# 摘要

> 自然语言到SQL（NL2SQL）让结构化数据触手可及，助力智能数据应用，它将自然语言问题转化为SQL查询。先进的NL2SQL技术通常结合数据库模式等信息，调用预训练的大型语言模型（LLM）生成SQL查询。

然而，现有的NL2SQL技术在现实应用中错失了一个重要机会：NL2SQL通常应用于已处理过大量SQL查询的现有数据库中。过去查询负载中隐含的宝贵信息，例如常见的连接路径和晦涩命名的表列语义，对提升NL2SQL翻译的准确性至关重要。我们推出了TailorSQL，它巧妙利用历史查询负载信息，显著提升了自然语言到SQL翻译的准确性和效率。通过专注于特定工作负载，TailorSQL在标准基准测试中的执行准确率实现了高达2倍的提升。


> NL2SQL (natural language to SQL) translates natural language questions into SQL queries, thereby making structured data accessible to non-technical users, serving as the foundation for intelligent data applications. State-of-the-art NL2SQL techniques typically perform translation by retrieving database-specific information, such as the database schema, and invoking a pre-trained large language model (LLM) using the question and retrieved information to generate the SQL query.
  However, existing NL2SQL techniques miss a key opportunity which is present in real-world settings: NL2SQL is typically applied on existing databases which have already served many SQL queries in the past. The past query workload implicitly contains information which is helpful for accurate NL2SQL translation and is not apparent from the database schema alone, such as common join paths and the semantics of obscurely-named tables and columns. We introduce TailorSQL, a NL2SQL system that takes advantage of information in the past query workload to improve both the accuracy and latency of translating natural language questions into SQL. By specializing to a given workload, TailorSQL achieves up to 2$\times$ improvement in execution accuracy on standardized benchmarks.

[Arxiv](https://arxiv.org/abs/2505.23039)