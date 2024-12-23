# C-FedRAG：一种机密的联邦检索增强型生成系统

发布时间：2024年12月18日

`RAG` `组织管理` `数据处理`

> C-FedRAG: A Confidential Federated Retrieval-Augmented Generation System

# 摘要

> 当组织试图运用大型语言模型（LLMs）来进行知识查询与分析时，常常会在维持针对特定、最新信息微调的LLM方面遭遇难题，以保证答案的相关性和可靠性。检索增强生成（RAG）很快成为那些想要克服维护专有模型挑战的组织的可行之选，也有助于减少其查询回应中的LLM幻觉。然而，RAG在跨分层访问和不同数据源扩展数据管道时存在自身的问题。在很多情形下，有必要查询单个数据孤岛之外的内容，为LLM提供更丰富、更相关的上下文。在组织信任边界内和跨边界分析数据源通常受复杂的数据共享政策所限，这些政策禁止集中式数据存储，从而阻碍了RAG解决方案的快速有效搭建和扩展。在本文中，我们引入机密计算（CC）技术作为安全的联邦检索增强生成（FedRAG）的解决方案。我们提出的机密FedRAG系统（C-FedRAG）通过确保上下文的保密性，在分散的数据提供者网络中实现RAG工作流的安全连接和扩展。我们还展示了如何使用NVIDIA FLARE SDK来实现C-FedRAG系统，并使用MedRAG工具包和MIRAGE基准数据集来评估其性能。

> Organizations seeking to utilize Large Language Models (LLMs) for knowledge querying and analysis often encounter challenges in maintaining an LLM fine-tuned on targeted, up-to-date information that keeps answers relevant and grounded. Retrieval Augmented Generation (RAG) has quickly become a feasible solution for organizations looking to overcome the challenges of maintaining proprietary models and to help reduce LLM hallucinations in their query responses. However, RAG comes with its own issues regarding scaling data pipelines across tiered-access and disparate data sources. In many scenarios, it is necessary to query beyond a single data silo to provide richer and more relevant context for an LLM. Analyzing data sources within and across organizational trust boundaries is often limited by complex data-sharing policies that prohibit centralized data storage, therefore, inhibit the fast and effective setup and scaling of RAG solutions. In this paper, we introduce Confidential Computing (CC) techniques as a solution for secure Federated Retrieval Augmented Generation (FedRAG). Our proposed Confidential FedRAG system (C-FedRAG) enables secure connection and scaling of a RAG workflows across a decentralized network of data providers by ensuring context confidentiality. We also demonstrate how to implement a C-FedRAG system using the NVIDIA FLARE SDK and assess its performance using the MedRAG toolkit and MIRAGE benchmarking dataset.

[Arxiv](https://arxiv.org/abs/2412.13163)