# PRESERVE: 分布式LLM服务中的模型权重与KV缓存预取

发布时间：2025年01月14日

`LLM应用

**理由**：这篇论文主要讨论了如何通过优化硬件和通信操作来提升大型语言模型（LLM）的推理性能，属于LLM在实际应用中的性能优化问题，因此归类为LLM应用。` `人工智能` `硬件优化`

> PRESERVE: Prefetching Model Weights and KV-Cache in Distributed LLM Serving

# 摘要

> 大型语言模型（LLMs）广泛应用于多个领域，但其庞大的计算需求带来了显著挑战，尤其是HBM带宽瓶颈和设备间通信开销。本文提出PRESERVE，一种创新的预取框架，通过将模型权重和KV缓存的读取与集体通信操作重叠，优化LLM推理。在商用AI加速器上的大量实验表明，PRESERVE在最先进的开源LLM上实现了高达1.6倍的端到端加速。此外，通过设计空间探索，我们确定了最佳硬件配置，选择最优L2缓存大小后，每成本性能提升1.25倍。PRESERVE有望缓解内存瓶颈和通信开销，为提升LLM推理系统的性能和可扩展性提供解决方案。

> Large language models (LLMs) are widely used across various applications, but their substantial computational requirements pose significant challenges, particularly in terms of HBM bandwidth bottlenecks and inter-device communication overhead. In this paper, we present PRESERVE, a novel prefetching framework designed to optimize LLM inference by overlapping memory reads for model weights and KV-cache with collective communication operations. Through extensive experiments conducted on commercial AI accelerators, we demonstrate up to 1.6x end-to-end speedup on state-of-the-art, open-source LLMs. Additionally, we perform a design space exploration that identifies the optimal hardware configuration for the proposed method, showing a further 1.25x improvement in performance per cost by selecting the optimal L2 cache size. Our results show that PRESERVE has the potential to mitigate the memory bottlenecks and communication overheads, offering a solution to improve the performance and scalability of the LLM inference systems.

[Arxiv](https://arxiv.org/abs/2501.08192)