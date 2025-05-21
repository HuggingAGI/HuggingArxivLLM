# # 低成本 FlashAttention：结合指数与乘法硬件操作器的优化方案

发布时间：2025年05月20日

`其他` `人工智能` `机器学习`

> Low-Cost FlashAttention with Fused Exponential and Multiplication Hardware Operators

# 摘要

> # 注意力机制
注意力机制，尤其是 Transformer 架构和大型语言模型（LLMs）中的注意力机制，彻底改变了机器学习和人工智能应用中的序列建模。为处理日益增长的长序列注意力计算需求，研究者提出了专门的硬件加速器，能够在硬件层面直接执行关键注意力步骤。在众多新兴架构中，基于最初为 GPU 设计的 FlashAttention 算法变体的架构脱颖而出，凭借其优化的计算流程、高效的平铺能力和显著降低的内存流量。本研究聚焦于通过融合指数计算与向量乘法（如 e^x 和 V）的新硬件操作，优化基于浮点的 FlashAttention 内核。所提出的 ExpMul 硬件操作大幅降低了 FlashAttention 硬件加速器的面积和功耗。在 28nm ASIC 技术下实现时，相较于采用独立指数和向量乘法硬件操作的现有最优架构，其面积和功耗分别平均降低了 28.8% 和 17.6%。

> Attention mechanisms, particularly within Transformer architectures and large language models (LLMs), have revolutionized sequence modeling in machine learning and artificial intelligence applications. To compute attention for increasingly long sequences, specialized accelerators have been proposed to execute key attention steps directly in hardware. Among the various recently proposed architectures, those based on variants of the FlashAttention algorithm, originally designed for GPUs, stand out due to their optimized computation, tiling capabilities, and reduced memory traffic. In this work, we focus on optimizing the kernel of floating-point-based FlashAttention using new hardware operators that fuse the computation of exponentials and vector multiplications, e.g., e^x, V. The proposed ExpMul hardware operators significantly reduce the area and power costs of FlashAttention-based hardware accelerators. When implemented in a 28nm ASIC technology, they achieve improvements of 28.8% in area and 17.6% in power, on average, compared to state-of-the-art hardware architectures with separate exponentials and vector multiplications hardware operators.

[Arxiv](https://arxiv.org/abs/2505.14314)