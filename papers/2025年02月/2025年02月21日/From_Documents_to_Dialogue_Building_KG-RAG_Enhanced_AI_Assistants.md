# 从文档到对话：打造KG-RAG赋能的智能助手

发布时间：2025年02月21日

`RAG

摘要中提到的论文主要探讨了通过基于知识图谱的检索增强生成（RAG）框架来解决大型语言模型在处理内部文档时的限制。论文详细介绍了构建高质量知识图谱的方法及其在提升回答准确性中的应用，因此归类为RAG。` `企业应用` `问答系统`

> From Documents to Dialogue: Building KG-RAG Enhanced AI Assistants

# 摘要

> Adobe Experience Platform AI Assistant 是一款对话工具，通过聊天机器人让企业无缝访问内部数据。然而，受限于访问权限，大型语言模型（LLMs）无法调用这些内部文档，导致零-shot 回答准确性受限。为突破这一限制，我们引入了基于知识图谱（KG）的检索增强生成（RAG）框架，从外部知识库中提取信息，助力 LLMs 处理私有或未见过的文档。本文提出了一种构建高质量、低噪声知识图谱的创新方法。我们采用多种技术，包括基于种子概念的增量实体识别、相似性过滤去重、实体关系对置信度评分筛选，以及事实与源文档的可追溯链接。我们的 KG-RAG 系统通过检索相关元组并将其加入用户提示上下文，显著提升了回答的相关性。评估结果显示，与现有系统相比，KG-RAG 系统使无关回答减少超 50%，完全相关回答增加 88%。

> The Adobe Experience Platform AI Assistant is a conversational tool that enables organizations to interact seamlessly with proprietary enterprise data through a chatbot. However, due to access restrictions, Large Language Models (LLMs) cannot retrieve these internal documents, limiting their ability to generate accurate zero-shot responses. To overcome this limitation, we use a Retrieval-Augmented Generation (RAG) framework powered by a Knowledge Graph (KG) to retrieve relevant information from external knowledge sources, enabling LLMs to answer questions over private or previously unseen document collections. In this paper, we propose a novel approach for building a high-quality, low-noise KG. We apply several techniques, including incremental entity resolution using seed concepts, similarity-based filtering to deduplicate entries, assigning confidence scores to entity-relation pairs to filter for high-confidence pairs, and linking facts to source documents for provenance. Our KG-RAG system retrieves relevant tuples, which are added to the user prompts context before being sent to the LLM generating the response. Our evaluation demonstrates that this approach significantly enhances response relevance, reducing irrelevant answers by over 50% and increasing fully relevant answers by 88% compared to the existing production system.

[Arxiv](https://arxiv.org/abs/2502.15237)