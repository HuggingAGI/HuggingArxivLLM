# 利用 RAG 与 LLMs 探索政治事件

发布时间：2025年01月06日

`RAG` `政治信息抽取` `媒体内容分析`

> Political Events using RAG with LLMs

# 摘要

> 在当今数字环境中，媒体内容是政治新闻分析的重要基础，为政治信息抽取提供了来自新闻、社交媒体、演讲和报告等多渠道的宝贵见解。自然语言处理（NLP）彻底改变了政治信息抽取，实现了从多样化媒体来源中自动提取事件信息。传统NLP方法通常需要专业知识来构建基于规则的系统或使用特定领域数据集训练机器学习模型，而由生成式人工智能驱动的大型语言模型（LLMs）则提供了一种更高效的选择。这些模型降低了从头构建模型的门槛，并减少了对大量训练数据的依赖，从而促进了快速实施。然而，在处理特定领域任务时仍存在挑战，因此我们开发了检索增强生成（RAG）框架。通过整合外部数据检索，RAG增强了大型语言模型的上下文理解能力，扩展了其知识库，超越了预训练数据的限制。为了展示RAG的实际效果，我们开发了一个专门用于从新闻文章中提取政治事件信息的政治事件抽取系统。理解这些政治见解对于掌握最新的政治动态至关重要，无论是在国家层面还是全球层面。

> In the contemporary digital landscape, media content stands as the foundation for political news analysis, offering invaluable insights sourced from various channels like news articles, social media updates, speeches, and reports. Natural Language Processing (NLP) has revolutionized Political Information Extraction (IE), automating tasks such as Event Extraction (EE) from these diverse media outlets. While traditional NLP methods often necessitate specialized expertise to build rule-based systems or train machine learning models with domain-specific datasets, the emergence of Large Language Models (LLMs) driven by Generative Artificial Intelligence (GenAI) presents a promising alternative. These models offer accessibility, alleviating challenges associated with model construction from scratch and reducing the dependency on extensive datasets during the training phase, thus facilitating rapid implementation. However, challenges persist in handling domain-specific tasks, leading to the development of the Retrieval-Augmented Generation (RAG) framework. RAG enhances LLMs by integrating external data retrieval, enriching their contextual understanding, and expanding their knowledge base beyond pre-existing training data. To illustrate RAG's efficacy, we introduce the Political EE system, specifically tailored to extract political event information from news articles. Understanding these political insights is essential for remaining informed about the latest political advancements, whether on a national or global scale.

[Arxiv](https://arxiv.org/abs/2502.15701)