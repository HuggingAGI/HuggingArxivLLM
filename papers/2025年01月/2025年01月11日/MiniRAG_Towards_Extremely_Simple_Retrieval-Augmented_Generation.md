# MiniRAG：极简检索增强生成

发布时间：2025年01月11日

`RAG

理由：这篇论文主要讨论了一种新型的检索增强生成（RAG）系统——MiniRAG，该系统旨在解决现有RAG框架在部署小型语言模型（SLMs）时面临的挑战。论文提出了两项关键技术突破，并展示了MiniRAG在使用SLMs时的性能表现。因此，这篇论文应归类为RAG。` `信息检索`

> MiniRAG: Towards Extremely Simple Retrieval-Augmented Generation

# 摘要

> # 摘要
随着对高效轻量级检索增强生成（RAG）系统的需求日益增长，现有RAG框架在部署小型语言模型（SLMs）时面临重大挑战。由于SLMs在语义理解和文本处理能力上的局限，当前方法性能大幅下降，阻碍了其在资源受限场景中的广泛应用。为此，我们推出了MiniRAG，一种专为极简高效设计的新型RAG系统。MiniRAG带来了两项关键技术突破：（1）语义感知的异构图索引机制，将文本块和命名实体统一整合，降低了对复杂语义理解的依赖；（2）轻量级拓扑增强检索方法，利用图结构实现高效知识发现，无需高级语言能力。实验表明，MiniRAG在使用SLMs时性能媲美基于LLM的方法，且仅需25%的存储空间。我们还提供了一个全面的基准数据集，用于评估复杂查询下的轻量级RAG系统。所有实现和数据集已在https://github.com/HKUDS/MiniRAG开源。

> The growing demand for efficient and lightweight Retrieval-Augmented Generation (RAG) systems has highlighted significant challenges when deploying Small Language Models (SLMs) in existing RAG frameworks. Current approaches face severe performance degradation due to SLMs' limited semantic understanding and text processing capabilities, creating barriers for widespread adoption in resource-constrained scenarios. To address these fundamental limitations, we present MiniRAG, a novel RAG system designed for extreme simplicity and efficiency. MiniRAG introduces two key technical innovations: (1) a semantic-aware heterogeneous graph indexing mechanism that combines text chunks and named entities in a unified structure, reducing reliance on complex semantic understanding, and (2) a lightweight topology-enhanced retrieval approach that leverages graph structures for efficient knowledge discovery without requiring advanced language capabilities. Our extensive experiments demonstrate that MiniRAG achieves comparable performance to LLM-based methods even when using SLMs while requiring only 25\% of the storage space. Additionally, we contribute a comprehensive benchmark dataset for evaluating lightweight RAG systems under realistic on-device scenarios with complex queries. We fully open-source our implementation and datasets at: https://github.com/HKUDS/MiniRAG.

[Arxiv](https://arxiv.org/abs/2501.06713)