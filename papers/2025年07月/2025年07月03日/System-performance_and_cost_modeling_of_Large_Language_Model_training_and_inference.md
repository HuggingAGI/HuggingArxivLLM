# # 大型语言模型训练与推理的系统性能及成本建模

发布时间：2025年07月03日

`LLM应用` `计算系统` `计算机体系结构`

> System-performance and cost modeling of Large Language Model training and inference

# 摘要

> 基于Transformer架构的大型语言模型（LLMs）凭借其卓越的扩展性和适应性，彻底改变了人工智能、科学和工程领域的众多方面。然而，LLM规模和复杂性的指数级增长远远超过了计算能力、内存带宽、网络性能和成本效率的进步，这给其在分布式系统中的扩展性带来了重大挑战。为了解决这些限制，文献中提出了替代模型架构、优化策略、通信感知网络拓扑以及新颖的系统设计方法。本文提出了一种集成了最新计算技术、内存优化和最新通信技术的LLM训练与推理性能-成本建模方法。基于分析性能模型，我们的方法整合了近期创新，如闪存注意力技术与专家混合模型，以解决内存带宽和计算瓶颈。同时，该方法还考虑了不同网络拓扑及其特定通信算法在5D并行中的影响，并集成了小芯片成本模型。所提出的建模方法为未来计算系统设计提供了宝贵的见解，促进了软硬件协同开发，特别是因为它能够分析各种系统架构配置的性能-成本权衡。

> Large language models (LLMs), based on transformer architectures, have revolutionized numerous domains within artificial intelligence, science, and engineering due to their exceptional scalability and adaptability. However, the exponential growth in LLM size and complexity has outpaced advancements in compute capacity, memory bandwidth, network performance, and cost efficiency, posing significant challenges to their scalability on distributed systems. To address these limitations, alternative model architectures, optimization strategies, communication-aware network topologies, and novel system design approaches have been proposed in literature. This paper introduces a performance-cost modeling methodology for LLM training and inference that integrates state-of-the-art compute techniques with memory optimizations, and latest communication techniques. Building on an analytical performance model, our approach incorporates recent innovations such as the flash attention technique and mixture of experts models to address the memory bandwidth and compute bottlenecks. It also considers the impact of different network topologies and topology-specific communication algorithms with 5D parallellism. The framework also integrates a chiplet cost model. The proposed modeling methodology provides valuable insights to guide future compute system design and facilitates hardware-software co-development, in particular due to its ability to analyze performance-cost trade-offs for various system architectural configurations.

[Arxiv](https://arxiv.org/abs/2507.02456)