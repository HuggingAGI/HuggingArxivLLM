# QuIM-RAG: 利用倒置问题匹配优化检索增强生成，提升问答性能

发布时间：2025年01月05日

`RAG

理由：这篇论文主要讨论了一种新颖的检索增强生成（RAG）系统架构，旨在提升问答任务的表现。论文详细描述了如何通过整合在线资源与数据库来增强大型语言模型（LLMs）的能力，并提出了QuIM-RAG这种创新的检索机制。这些内容明显属于RAG（Retrieval-Augmented Generation）领域，因此将其分类为RAG是合适的。` `问答系统` `信息检索`

> QuIM-RAG: Advancing Retrieval-Augmented Generation with Inverted Question Matching for Enhanced QA Performance

# 摘要

> # 摘要
本文提出了一种新颖的检索增强生成（RAG）系统架构，旨在提升目标语料库中的问答（QA）任务表现。大型语言模型（LLMs）在类人文本的分析与生成方面取得了革命性进展，但其依赖预训练数据且缺乏实时更新能力。RAG通过整合在线资源与数据库，生成上下文相关的响应，从而增强了LLMs的能力。然而，传统RAG在处理海量数据时仍面临信息稀释与幻觉等挑战。我们的解决方案是将语料库转化为特定领域数据集，并构建RAG架构以从目标文档生成响应。我们引入了QuIM-RAG（问题到问题倒排索引匹配），这是一种创新的检索机制，通过从文档块生成潜在问题并与用户查询匹配，精准定位最相关的文本块以生成准确答案。我们在Meta Inc.开源的Meta-LLaMA3-8B-instruct模型（Hugging Face平台提供）上实现了这一RAG系统，并构建了一个包含500多页高流量网站内容的自定义语料库，用于回答复杂问题，同时准备了手动标注的真实QA数据用于评估。通过BERT-Score和RAGAS这两种先进的LLM应用评估指标，我们与传统RAG模型进行了对比，结果显示我们的方法在这两项指标上均优于传统RAG架构。

> This work presents a novel architecture for building Retrieval-Augmented Generation (RAG) systems to improve Question Answering (QA) tasks from a target corpus. Large Language Models (LLMs) have revolutionized the analyzing and generation of human-like text. These models rely on pre-trained data and lack real-time updates unless integrated with live data tools. RAG enhances LLMs by integrating online resources and databases to generate contextually appropriate responses. However, traditional RAG still encounters challenges like information dilution and hallucinations when handling vast amounts of data. Our approach addresses these challenges by converting corpora into a domain-specific dataset and RAG architecture is constructed to generate responses from the target document. We introduce QuIM-RAG (Question-to-question Inverted Index Matching), a novel approach for the retrieval mechanism in our system. This strategy generates potential questions from document chunks and matches these with user queries to identify the most relevant text chunks for generating accurate answers. We have implemented our RAG system on top of the open-source Meta-LLaMA3-8B-instruct model by Meta Inc. that is available on Hugging Face. We constructed a custom corpus of 500+ pages from a high-traffic website accessed thousands of times daily for answering complex questions, along with manually prepared ground truth QA for evaluation. We compared our approach with traditional RAG models using BERT-Score and RAGAS, state-of-the-art metrics for evaluating LLM applications. Our evaluation demonstrates that our approach outperforms traditional RAG architectures on both metrics.

[Arxiv](https://arxiv.org/abs/2501.02702)