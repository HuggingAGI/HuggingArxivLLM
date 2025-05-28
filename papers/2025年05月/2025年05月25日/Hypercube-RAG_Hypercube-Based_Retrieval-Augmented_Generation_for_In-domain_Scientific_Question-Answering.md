# Hypercube-RAG：基于超立方体的检索增强生成方法在领域科学问答中的应用

发布时间：2025年05月25日

`RAG` `科学问答`

> Hypercube-RAG: Hypercube-Based Retrieval-Augmented Generation for In-domain Scientific Question-Answering

# 摘要

> 大型语言模型（LLMs）在解决特定主题问题时，通常需要整合外部知识。检索增强生成（RAG）通过利用外部数据和知识，显著提升了LLMs的响应质量，展现出巨大潜力。然而，传统基于语义相似性的RAG在处理科学问答（QA）等需要专业知识的领域任务时，往往难以返回既简洁又高度相关的信息。我们提出了一种基于多维结构Hypercube的全新RAG框架——Hypercube-RAG，旨在实现精准高效的知识检索。Hypercube能够在应用驱动、人类定义的多维空间中对文档进行索引。对于给定查询，Hypercube-RAG首先根据其实体和主题进行分解，然后通过将这些分解后的组件与超立方体维度对齐，从各个维度中检索相关文档。实验结果表明，在三个科学QA数据集上，与最强的RAG基线相比，我们的方法在准确性上提升了3.7%，检索效率提高了81.2%（以相对增益衡量）。更重要的是，Hypercube-RAG通过揭示用于检索的预定义超立方体维度，天然具备可解释性。代码和数据集可在GitHub上获取：https://github.com/JimengShi/Hypercube-RAG。


> Large language models (LLMs) often need to incorporate external knowledge to solve theme-specific problems. Retrieval-augmented generation (RAG), which empowers LLMs to generate more qualified responses with retrieved external data and knowledge, has shown its high promise. However, traditional semantic similarity-based RAGs struggle to return concise yet highly relevant information for domain knowledge-intensive tasks, such as scientific question-answering (QA). Built on a multi-dimensional (cube) structure called Hypercube, which can index documents in an application-driven, human-defined, multi-dimensional space, we introduce the Hypercube-RAG, a novel RAG framework for precise and efficient retrieval. Given a query, Hypercube-RAG first decomposes it based on its entities and topics and then retrieves relevant documents from cubes by aligning these decomposed components with hypercube dimensions. Experiments on three in-domain scientific QA datasets demonstrate that our method improves accuracy by 3.7% and boosts retrieval efficiency by 81.2%, measured as relative gains over the strongest RAG baseline. More importantly, our Hypercube-RAG inherently offers explainability by revealing the underlying predefined hypercube dimensions used for retrieval. The code and data sets are available at https://github.com/JimengShi/Hypercube-RAG.

[Arxiv](https://arxiv.org/abs/2505.19288)