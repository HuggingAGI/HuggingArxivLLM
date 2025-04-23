# WindVE：CPU 与 NPU 协同的向量嵌入

发布时间：2025年04月22日

`RAG` `工业界` `推理服务`

> WindVE: Collaborative CPU-NPU Vector Embedding

# 摘要

> 检索增强生成技术通过整合信息检索提升大型语言模型性能。在工业界，基于LLMs的推理服务对成本性能比极为敏感，亟需提升硬件资源利用率。具体而言，向量嵌入和检索过程占据了总延迟的20%。因此，优化向量嵌入中的计算资源利用率对提升推理过程的成本性能比至关重要，进而增强产品竞争力。本文分析了向量嵌入技术在推理服务中的部署成本，提出了一个理论公式，并通过数学表达式确定，提升并发查询处理能力是降低向量嵌入部署成本的关键。因此，本文专注于提升产品处理并发查询的能力。为了在不牺牲性能的前提下优化并发处理，我们设计了一个队列管理器，能够有效卸载CPU的峰值查询。该管理器采用线性回归模型确定最优队列深度，这一关键参数对系统效能有显著影响。我们进一步开发了一个名为WindVE的系统，利用CPU-NPU异构架构卸载峰值并发查询，该系统通过利用两种处理器的性能差异，有效管理流量高峰。实验结果表明，WindVE与最先进的向量嵌入框架FlagEmbedding相比，实现了比未卸载方案高出22.3%的并发水平。

> Retrieval-Augmented Generation is a technology that enhances large language models by integrating information retrieval. In the industry, inference services based on LLMs are highly sensitive to cost-performance ratio, prompting the need for improving hardware resource utilization in the inference service. Specifically, vector embedding and retrieval processes take up to 20% of the total latency. Therefore, optimizing the utilization of computational resources in vector embeddings is crucial for enhancing the cost-performance ratio of inference processes, which in turn boosts their product competitiveness.In this paper, we analyze the deployment costs of vector embedding technology in inference services, propose a theoretical formula, and determine through the mathematical expression that increasing the capacity to process concurrent queries is the key to reducing the deployment costs of vector embeddings. Therefore, in this paper, we focus on improving the product's capability to process concurrent queries. To optimize concurrency without sacrificing performance, we have designed a queue manager that adeptly offloads CPU peak queries. This manager utilizes a linear regression model to ascertain the optimal queue depths, a critical parameter that significantly influences the efficacy of the system. We further develop a system named WindVE that uses a CPU-NPU heterogeneous architecture to offload peak concurrent queries, which leverages the performance differences between the two processors to effectively manage traffic surges. Through experiments, we compare WindVE to the state-of-the-art vector embedding framework FlagEmbedding, and achieve a concurrency level up to 22.3% higher than the scheme without offloading.

[Arxiv](https://arxiv.org/abs/2504.14941)