# Glinthawk：高吞吐量LLM推理的双层架构

发布时间：2025年01月20日

`LLM应用

理由：这篇论文主要讨论了如何通过改进架构设计（Glinthawk）来优化大型语言模型（LLM）的推理过程，特别是通过解耦注意力机制与Transformer模型的其余部分，以提高吞吐量和降低成本。这属于对LLM在实际应用中的性能优化，因此归类为“LLM应用”。` `高性能计算`

> Glinthawk: A Two-Tiered Architecture for High-Throughput LLM Inference

# 摘要

> 大型语言模型（LLM）在自然语言处理领域掀起了一场革命，但其推理过程对资源需求巨大，且未能充分利用GPU等高端加速器。注意力机制成为主要瓶颈，它需要存储大量键值缓存，导致最大吞吐量远低于可用计算资源。现有方法通过内存高效的注意力和分页机制试图缓解这一问题，但仍受限于所有操作必须在高端加速器上执行的假设。
    为此，我们提出了Glinthawk，一种两层架构，将注意力机制与Transformer模型的其余部分解耦。这一设计使得注意力的内存需求可以独立扩展，从而支持更大的批量处理，并更高效地利用高端加速器。我们以NVIDIA T4 GPU和标准CPU虚拟机分别作为两层，构建了Glinthawk原型。相比传统单层架构，Glinthawk将吞吐量提升了$5.9	imes$，生成成本降低了$2.8	imes$。对于长序列任务，吞吐量提升高达$16.3	imes$，成本降低$2.4	imes$。评估显示，该架构能够容忍适度网络延迟，性能损失极小，非常适合批处理等对延迟不敏感、注重吞吐量的应用场景。我们已在url{https://github.com/microsoft/glinthawk}公开分享这一原型。

> Large Language Models (LLM) have revolutionized natural language processing, but their inference demands substantial resources, while under-utilizing high-end accelerators like GPUs. A major bottleneck arises from the attention mechanism, which requires storing large key-value caches, limiting the maximum achievable throughput way below the available computing resources. Current approaches attempt to mitigate this issue through memory-efficient attention and paging mechanisms, but remained constrained by the assumption that all operations must be performed on high-end accelerators.
  In this work, we propose Glinthawk, a two-tiered architecture that decouples the attention mechanism from the rest of the Transformer model. This approach allows the memory requirements for attention to scale independently, enabling larger batch sizes and more efficient use of the high-end accelerators. We prototype Glinthawk with NVIDIA T4 GPUs as one tier and standard CPU VMs as the other. Compared to a traditional single-tier setup, it improves throughput by $5.9\times$ and reduces cost of generation by $2.8\times$. For longer sequence lengths, it achieves $16.3\times$ throughput improvement at $2.4\times$ less cost. Our evaluation shows that this architecture can tolerate moderate network latency with minimal performance degradation, making it highly effective for latency-tolerant, throughput-oriented applications such as batch processing. We shared our prototype publicly at \url{https://github.com/microsoft/glinthawk}.

[Arxiv](https://arxiv.org/abs/2501.11779)