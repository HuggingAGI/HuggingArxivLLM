# 加速检索增强生成

发布时间：2024年12月14日

`RAG

理由：这篇论文主要讨论了检索增强生成（RAG）技术，特别是如何通过精确最近邻搜索来加速RAG的执行管道。论文还介绍了一种新型的硬件架构（IKS）来优化RAG的性能。因此，这篇论文的核心内容与RAG技术密切相关，应归类为RAG。` `信息检索` `内存计算`

> Accelerating Retrieval-Augmented Generation

# 摘要

> # 摘要
检索增强生成（RAG）是一种不断发展的解决方案，旨在解决大型语言模型（LLMs）中的幻觉问题并提升准确性。RAG通过从外部知识源（如网络）检索信息来增强LLMs。本文深入剖析了几种RAG执行管道，揭示了其检索与生成阶段之间复杂的相互作用。我们发现，尽管精确检索方案成本较高，但与近似检索相比，它能显著减少推理时间，因为精确检索模型可以向生成模型提供更小但更准确的文档列表，同时保持相同的端到端准确性。这一发现推动了RAG中精确最近邻搜索的加速。
在本研究中，我们设计了智能知识存储（IKS），这是一种类型2的CXL设备，采用扩展的近内存加速架构，并引入了主机CPU与近内存加速器之间的新型缓存一致性接口。与在Intel Sapphire Rapids CPU上执行搜索相比，IKS在512GB向量数据库上的精确最近邻搜索速度快了13.4-27.9倍。这种高效的搜索性能使得代表性RAG应用程序的端到端推理时间减少了1.7-26.3倍。IKS本质上是一个内存扩展器，其内部DRAM可以解耦并用于服务器上的其他应用程序，从而避免当今服务器中最昂贵的组件——DRAM被闲置。

> An evolving solution to address hallucination and enhance accuracy in large language models (LLMs) is Retrieval-Augmented Generation (RAG), which involves augmenting LLMs with information retrieved from an external knowledge source, such as the web. This paper profiles several RAG execution pipelines and demystifies the complex interplay between their retrieval and generation phases. We demonstrate that while exact retrieval schemes are expensive, they can reduce inference time compared to approximate retrieval variants because an exact retrieval model can send a smaller but more accurate list of documents to the generative model while maintaining the same end-to-end accuracy. This observation motivates the acceleration of the exact nearest neighbor search for RAG.
  In this work, we design Intelligent Knowledge Store (IKS), a type-2 CXL device that implements a scale-out near-memory acceleration architecture with a novel cache-coherent interface between the host CPU and near-memory accelerators. IKS offers 13.4-27.9x faster exact nearest neighbor search over a 512GB vector database compared with executing the search on Intel Sapphire Rapids CPUs. This higher search performance translates to 1.7-26.3x lower end-to-end inference time for representative RAG applications. IKS is inherently a memory expander; its internal DRAM can be disaggregated and used for other applications running on the server to prevent DRAM, which is the most expensive component in today's servers, from being stranded.

[Arxiv](https://arxiv.org/abs/2412.15246)