# StreamLink：基于大型语言模型的分布式数据工程系统

发布时间：2025年05月27日

`LLM应用

摘要中提到的StreamLink系统将大型语言模型应用于数据工程任务，展示了LLM在实际中的应用，因此归类为LLM应用。` `数据工程` `大数据`

> StreamLink: Large-Language-Model Driven Distributed Data Engineering System

# 摘要

> 大型语言模型（LLMs）在自然语言理解（NLU）方面表现卓越，为创新应用打开了大门。我们推出StreamLink——一个基于LLM的分布式数据系统，旨在提升数据工程任务的效率和可访问性。StreamLink建立在Apache Spark和Hadoop等分布式框架之上，能够处理海量数据。StreamLink的重要设计理念是尊重用户数据隐私，通过使用本地微调的LLM而非像ChatGPT这样的公共AI服务来实现。借助领域适配的LLM，我们能够提升系统对用户在各种场景下提出的自然语言查询的理解能力，并简化生成结构化查询语言（SQL）等数据库查询的过程，从而提高信息处理效率。我们还集成了基于LLM的语法和安全检查器，以确保每个生成的查询既可靠又安全。StreamLink展示了将生成式LLM与分布式数据处理相结合的巨大潜力，为用户中心的数据工程提供了全面支持。通过这种架构，用户可以以友好且安全的方式与不同规模的复杂数据库系统进行交互。与基线方法相比，SQL生成的执行准确率提高了10%，并且用户可以通过自然语言在几秒内从数亿条数据中找到最关注的内容。

> Large Language Models (LLMs) have shown remarkable proficiency in natural language understanding (NLU), opening doors for innovative applications. We introduce StreamLink - an LLM-driven distributed data system designed to improve the efficiency and accessibility of data engineering tasks. We build StreamLink on top of distributed frameworks such as Apache Spark and Hadoop to handle large data at scale. One of the important design philosophies of StreamLink is to respect user data privacy by utilizing local fine-tuned LLMs instead of a public AI service like ChatGPT. With help from domain-adapted LLMs, we can improve our system's understanding of natural language queries from users in various scenarios and simplify the procedure of generating database queries like the Structured Query Language (SQL) for information processing. We also incorporate LLM-based syntax and security checkers to guarantee the reliability and safety of each generated query. StreamLink illustrates the potential of merging generative LLMs with distributed data processing for comprehensive and user-centric data engineering. With this architecture, we allow users to interact with complex database systems at different scales in a user-friendly and security-ensured manner, where the SQL generation reaches over 10\% of execution accuracy compared to baseline methods, and allow users to find the most concerned item from hundreds of millions of items within a few seconds using natural language.

[Arxiv](https://arxiv.org/abs/2505.21575)