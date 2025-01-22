# Dialect2SQL: 一个专注于摩洛哥达里贾方言的阿拉伯方言文本到SQL新数据集

发布时间：2025年01月20日

`LLM应用

解释：这篇论文主要讨论了将自然语言问题（NLQs）转换为可执行SQL查询的任务，即文本到SQL（text-to-SQL）。虽然论文中提到了数据集和基准测试，但其核心关注点是如何利用自然语言处理技术（特别是文本到SQL的转换）来让非技术用户与关系数据库互动。这属于LLM（大型语言模型）在实际应用中的使用，因此分类为“LLM应用”。` `数据库`

> Dialect2SQL: A Novel Text-to-SQL Dataset for Arabic Dialects with a Focus on Moroccan Darija

# 摘要

> 将自然语言问题（NLQs）转换为可执行SQL查询的任务，即文本到SQL（text-to-SQL），近年来备受关注，因为它让非技术用户也能轻松与关系数据库互动。像SPIDER和WikiSQL这样的基准测试，为新模型的开发和性能评估提供了重要支持。此外，SEDE和BIRD等数据集引入了更多挑战和复杂性，以更好地模拟现实场景。然而，这些数据集主要针对高资源语言，如英语和中文。在本研究中，我们推出了Dialect2SQL，这是首个大规模的跨领域阿拉伯方言文本到SQL数据集，包含9,428个NLQ-SQL对，覆盖69个不同领域的数据库。除了SQL相关的挑战，如长模式、脏值和复杂查询外，我们的数据集还融入了摩洛哥方言的复杂性，该方言以其多样的源语言、大量借词和独特表达而著称。这表明，我们的数据集将为文本到SQL社区以及低资源语言资源的开发带来重要贡献。

> The task of converting natural language questions (NLQs) into executable SQL queries, known as text-to-SQL, has gained significant interest in recent years, as it enables non-technical users to interact with relational databases. Many benchmarks, such as SPIDER and WikiSQL, have contributed to the development of new models and the evaluation of their performance. In addition, other datasets, like SEDE and BIRD, have introduced more challenges and complexities to better map real-world scenarios. However, these datasets primarily focus on high-resource languages such as English and Chinese. In this work, we introduce Dialect2SQL, the first large-scale, cross-domain text-to-SQL dataset in an Arabic dialect. It consists of 9,428 NLQ-SQL pairs across 69 databases in various domains. Along with SQL-related challenges such as long schemas, dirty values, and complex queries, our dataset also incorporates the complexities of the Moroccan dialect, which is known for its diverse source languages, numerous borrowed words, and unique expressions. This demonstrates that our dataset will be a valuable contribution to both the text-to-SQL community and the development of resources for low-resource languages.

[Arxiv](https://arxiv.org/abs/2501.11498)