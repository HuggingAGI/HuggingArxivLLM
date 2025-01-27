# CAPRAG：利用向量和图检索增强生成的大型语言模型，打造客户服务与自动报告解决方案

发布时间：2025年01月23日

`Agent

理由：这篇论文描述了一个由大型语言模型（LLMs）驱动的AI代理，旨在为客户提供银行服务和年度报告的相关信息。论文中提到的“AI代理”和“混合客户分析管道检索增强生成（CAPRAG）”表明这是一个具体的应用系统，属于Agent类别。虽然论文中提到了检索增强生成（RAG）技术，但整体内容更侧重于描述一个具体的AI代理系统，而不是单纯讨论RAG技术或LLM的理论或应用。因此，将其分类为Agent更为合适。` `银行业` `金融科技`

> CAPRAG: A Large Language Model Solution for Customer Service and Automatic Reporting using Vector and Graph Retrieval-Augmented Generation

# 摘要

> 银行业中新功能和新服务的引入常常让客户感到应接不暇，这为银行提供了一个通过由大型语言模型（LLMs）驱动的金融聊天机器人来提升用户体验的机会。我们开发了一个AI代理，旨在为客户提供银行服务和年度报告的相关信息。我们提出了一种混合客户分析管道检索增强生成（CAPRAG），有效解决了基于关系和上下文查询的问题，从而提升了数字银行环境中的客户参与度。为此，我们开发了一个处理管道来优化文本数据，并将其应用于两个主要框架：向量RAG和图RAG。这种双重方法使我们能够将处理后的数据填充到向量和图数据库中，以实现高效检索。Cypher查询组件用于有效查询图数据库。当用户提交查询时，首先通过查询扩展模块进行扩展，然后路由到混合知识库（KB）以构建最终查询。这个最终查询随后被发送到开源LLM以生成响应。总体而言，我们为国际银行设计的创新服务在日益复杂的数字环境中为银行客户提供服务，增强了信息的清晰度和可访问性。

> The introduction of new features and services in the banking sector often overwhelms customers, creating an opportunity for banks to enhance user experience through financial chatbots powered by large language models (LLMs). We initiated an AI agent designed to provide customers with relevant information about banking services and insights from annual reports. We proposed a hybrid Customer Analysis Pipeline Retrieval-Augmented Generation (CAPRAG) that effectively addresses both relationship-based and contextual queries, thereby improving customer engagement in the digital banking landscape. To implement this, we developed a processing pipeline to refine text data, which we utilized in two main frameworks: Vector RAG and Graph RAG. This dual approach enables us to populate both vector and graph databases with processed data for efficient retrieval. The Cypher query component is employed to effectively query the graph database. When a user submits a query, it is first expanded by a query expansion module before being routed to construct a final query from the hybrid Knowledge Base (KB). This final query is then sent to an open-source LLM for response generation. Overall, our innovative, designed to international banks, serves bank's customers in an increasingly complex digital environment, enhancing clarity and accessibility of information.

[Arxiv](https://arxiv.org/abs/2501.13993)