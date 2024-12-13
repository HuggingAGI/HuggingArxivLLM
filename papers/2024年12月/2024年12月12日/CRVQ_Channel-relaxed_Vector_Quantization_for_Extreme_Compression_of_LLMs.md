# CRVQ：用于大型语言模型极度压缩的通道松弛式向量量化

发布时间：2024年12月12日

`LLM应用` `计算机硬件` `模型压缩`

> CRVQ: Channel-relaxed Vector Quantization for Extreme Compression of LLMs

# 摘要

> 强大的大型语言模型（LLMs）愈发被期望能以更低的计算成本来部署，从而在资源受限的设备上发挥其能力。训练后量化（PTQ）已成为达成此目标的明星手段，最优方法能将权重平均压缩至不足 2 位。在本文中，我们提出了通道松弛向量量化（CRVQ）这一创新技术，仅以极少的额外比特为代价，大幅提升了 PTQ 基线的性能。这种前沿的极限压缩方法通过两大关键创新达成了成果：（1）精心挑选并重新排列关键权重通道的极小子集；（2）借助多个码本放宽关键通道的约束。凭借我们的方法，相比当前最强的低于 2 位的 PTQ 基线，性能提升了 38.9%，实现了近乎无损的 1 位压缩。此外，我们的方法提供了量化位宽和性能的灵活定制，为各类硬件平台提供了更广泛的部署选择。

> Powerful large language models (LLMs) are increasingly expected to be deployed with lower computational costs, enabling their capabilities on resource-constrained devices. Post-training quantization (PTQ) has emerged as a star approach to achieve this ambition, with best methods compressing weights to less than 2 bit on average. In this paper, we propose Channel-Relaxed Vector Quantization (CRVQ), a novel technique that significantly improves the performance of PTQ baselines at the cost of only minimal additional bits. This state-of-the-art extreme compression method achieves its results through two key innovations: (1) carefully selecting and reordering a very small subset of critical weight channels, and (2) leveraging multiple codebooks to relax the constraint of critical channels. With our method, we demonstrate a 38.9% improvement over the current strongest sub-2-bit PTQ baseline, enabling nearer lossless 1-bit compression. Furthermore, our approach offers flexible customization of quantization bit-width and performance, providing a wider range of deployment options for diverse hardware platforms.

[Arxiv](https://arxiv.org/abs/2412.09282)