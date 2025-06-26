# EQuARX：XLA中的高效量化AllReduce，助力分布式机器学习加速

发布时间：2025年06月21日

`LLM应用

理由：这篇论文探讨了如何优化大型语言模型（LLMs）在分布式计算环境中的性能，特别是通过改进量化和通信方法来提高模型的运行效率。这属于LLM在实际应用中的优化和部署问题，因此归类为LLM应用。` `分布式计算` `计算效率`

> EQuARX: Efficient Quantized AllReduce in XLA for Distributed Machine Learning Acceleration

# 摘要

> 尽管大型语言模型（LLMs）影响力巨大，但其庞大的规模带来了显著的部署挑战。高效运行这些模型通常需要将它们分布在众多加速器设备上，由此带来了设备间通信（collectives）的显著性能开销。尽管模型量化已被广泛应用，用于在对质量影响极小的情况下减少LLM权重和激活的内存及计算需求，但直接将量化应用于AllReduce等collectives本质上非常困难，因为涉及的设备间求和可能导致数值不稳定或显著误差累积。在本研究中，我们提出了XLA编译器中针对TPU的原生动态块级高效量化AllReduce（EQuARX）。通过采用适合TPU的量化方法以及深度流水化通信与计算，EQuARX在int8精度下，在各种网络拓扑中比基线BF16 AllReduce快1.8倍。此外，EQuARX加速了Gemma 3 27B和12B模型的预填阶段，分别提升了1.25倍和1.1倍，同时对质量的影响微乎其微。

> While Large Language Models (LLMs) have become highly influential, their enormous scale presents significant deployment challenges. Efficiently serving these models typically requires distributing them across numerous accelerator devices, which introduces substantial performance overhead from inter-device communication (collectives). While model quantization has been widely adopted to reduce the memory and compute requirements of LLM weights and activations with minimal quality impact, applying quantization directly to collectives like AllReduce is inherently difficult due to the inter-device summation involved, which can lead to numerical instability or significant error accumulation. In this work, we present a native dynamic block-wise efficient quantized AllReduce within the XLA compiler for TPUs (EQuARX). By using TPU-friendly quantization and deep pipelining of communication and compute, EQuARX with int8 precision achieves a 1.8X speedup over baseline BF16 AllReduce across various network topologies. Furthermore, EQuARX accelerates the prefill stage of Gemma 3 27B by 1.25X and Gemma 3 12B by 1.1X, respectively, with small to negligible impact on quality.

[Arxiv](https://arxiv.org/abs/2506.17615)