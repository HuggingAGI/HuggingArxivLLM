# TURBOATTENTION：用于高吞吐量大型语言模型的高效注意力近似方法

发布时间：2024年12月11日

`LLM应用` `计算机` `人工智能`

> TURBOATTENTION: Efficient Attention Approximation For High Throughputs LLMs

# 摘要

> 大型语言模型（LLM）进行推理时，在关键的注意力机制方面，需要大量的计算和内存。虽然像量化和诸如 FlashAttention 这样的加速算法等技术提升了整体推理效率，但它们解决的是不同方面的问题：量化主要针对权重激活操作，而 FlashAttention 改进了执行，却需要高精度格式。近期的键值（KV）缓存量化降低了内存带宽，不过注意力操作仍需浮点反量化。
  我们推出了 TurboAttention，这是一种能实现注意力量化执行的综合办法，能同时解决内存和计算效率的问题。我们的方案引入了两项关键创新：FlashQ，一种按头注意力量化技术，既能压缩 KV 缓存，又能实现激活-激活乘法的量化执行；基于稀疏性的 Softmax 近似（SAS），它消除了在注意力中的指数运算时对 FP32 进行反量化的需求。实验结果显示，TurboAttention 在注意力方面实现了 1.2 - 1.8 倍的提速，将 KV 缓存大小减少了 4.4 倍以上，在超过 FP16 基线的情况下，实现了高达 2.37 倍的最大吞吐量，并且在各种数据集和模型中，表现优于现有的量化和压缩技术。

> Large language model (LLM) inference demands significant amount of computation and memory, especially in the key attention mechanism. While techniques, such as quantization and acceleration algorithms, like FlashAttention, have improved efficiency of the overall inference, they address different aspects of the problem: quantization focuses on weight-activation operations, while FlashAttention improves execution but requires high-precision formats. Recent Key-value (KV) cache quantization reduces memory bandwidth but still needs floating-point dequantization for attention operation.
  We present TurboAttention, a comprehensive approach to enable quantized execution of attention that simultaneously addresses both memory and computational efficiency. Our solution introduces two key innovations: FlashQ, a headwise attention quantization technique that enables both compression of KV cache and quantized execution of activation-activation multiplication, and Sparsity-based Softmax Approximation (SAS), which eliminates the need for dequantization to FP32 during exponentiation operation in attention. Experimental results demonstrate that TurboAttention achieves 1.2-1.8x speedup in attention, reduces the KV cache size by over 4.4x, and enables up to 2.37x maximum throughput over the FP16 baseline while outperforming state-of-the-art quantization and compression techniques across various datasets and models.

[Arxiv](https://arxiv.org/abs/2412.08585)