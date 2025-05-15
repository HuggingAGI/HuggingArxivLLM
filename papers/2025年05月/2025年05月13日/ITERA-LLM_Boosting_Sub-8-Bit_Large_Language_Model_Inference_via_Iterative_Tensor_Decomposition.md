# ITERA-LLM：通过迭代张量分解优化低于8位的大型语言模型推理性能

发布时间：2025年05月13日

`LLM应用` `模型压缩` `硬件协同设计`

> ITERA-LLM: Boosting Sub-8-Bit Large Language Model Inference via Iterative Tensor Decomposition

# 摘要

> 随着大型语言模型（LLMs）的规模扩展到数十亿参数，其展现出令人瞩目的能力。然而，在资源受限的平台上部署这些大规模模型面临巨大挑战，通常采用后训练定点量化作为压缩手段。然而，仅使用量化方法在精度低于8位时会导致LLMs出现显著的准确性下降。本文提出了一种名为ITERA-LLM的软件-硬件协同设计框架，通过将低于8位的量化与基于奇异值分解的迭代低秩张量分解相结合，有效补偿量化误差，从而实现更高的压缩率和更低的计算复杂度。该框架还引入了硬件感知的设计空间探索（DSE）过程，全面优化准确性、延迟和资源利用率，为特定目标LLM量身定制配置。实验结果表明，与仅量化方法相比，ITERA-LLM在保持相似模型准确性的同时，实现了线性层延迟降低高达41.1%。

> Recent advancements in Large Language Models (LLMs) have demonstrated impressive capabilities as their scale expands to billions of parameters. Deploying these large-scale models on resource-constrained platforms presents significant challenges, with post-training fixed-point quantization often used as a model compression technique. However, quantization-only methods typically lead to significant accuracy degradation in LLMs when precision falls below 8 bits. This paper addresses this challenge through a software-hardware co-design framework, ITERA-LLM, which integrates sub-8-bit quantization with SVD-based iterative low-rank tensor decomposition for error compensation, leading to higher compression ratios and reduced computational complexity. The proposed approach is complemented by a hardware-aware Design Space Exploration (DSE) process that optimizes accuracy, latency, and resource utilization, tailoring the configuration to the specific requirements of the targeted LLM. Our results show that ITERA-LLM achieves linear layer latency reduction of up to 41.1%, compared to quantization-only baseline approach while maintaining similar model accuracy.

[Arxiv](https://arxiv.org/abs/2505.08981)