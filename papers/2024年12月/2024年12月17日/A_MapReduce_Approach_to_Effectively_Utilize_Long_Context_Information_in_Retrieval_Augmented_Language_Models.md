# 一种 MapReduce 方法，旨在检索增强语言模型中有效利用长上下文信息

发布时间：2024年12月17日

`RAG` `语言模型`

> A MapReduce Approach to Effectively Utilize Long Context Information in Retrieval Augmented Language Models

# 摘要

> 尽管大型语言模型（LLMs）在改进和助力医疗保健方面潜力巨大，但因知识陈旧或产生幻觉，它们难以针对不断变化的主题给出最新回应。检索增强生成（RAG）是一项重要创新，它将LLMs与搜索引擎及外部知识源相融合，提升了LLM回应的准确性和相关性。然而，RAG回应的质量在很大程度上会受检索结果中关键信息的排序和密度影响，比如“中间丢失”问题。在本项工作中，我们致力于提升医疗领域RAG工作流程的稳健性和可靠性。具体而言，我们提出了一种映射-归约策略——BriefContext，在不改动模型权重的情况下解决“中间丢失”问题。我们在多种LLM骨干和多个问答数据集上展示了该工作流程的优势。此方法有望增强部署在医疗保健领域的LLM的安全性和可靠性。

> While holding great promise for improving and facilitating healthcare, large language models (LLMs) struggle to produce up-to-date responses on evolving topics due to outdated knowledge or hallucination. Retrieval-augmented generation (RAG) is a pivotal innovation that improves the accuracy and relevance of LLM responses by integrating LLMs with a search engine and external sources of knowledge. However, the quality of RAG responses can be largely impacted by the rank and density of key information in the retrieval results, such as the "lost-in-the-middle" problem. In this work, we aim to improve the robustness and reliability of the RAG workflow in the medical domain. Specifically, we propose a map-reduce strategy, BriefContext, to combat the "lost-in-the-middle" issue without modifying the model weights. We demonstrated the advantage of the workflow with various LLM backbones and on multiple QA datasets. This method promises to improve the safety and reliability of LLMs deployed in healthcare domains.

[Arxiv](https://arxiv.org/abs/2412.15271)