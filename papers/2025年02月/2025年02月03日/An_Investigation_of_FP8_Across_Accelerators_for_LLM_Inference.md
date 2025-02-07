# FP8加速器在LLM推理中的应用研究

发布时间：2025年02月03日

`LLM应用

理由：这篇论文主要讨论了8位浮点（FP8）计算单元在LLM推理中的应用，特别是其在AI加速器上的性能表现。虽然涉及硬件和计算效率的讨论，但其核心关注点是如何通过FP8优化LLM推理的性能和效率，因此属于LLM应用的范畴。` `人工智能` `数据中心`

> An Investigation of FP8 Across Accelerators for LLM Inference

# 摘要

> 现代AI加速器引入的8位浮点（FP8）计算单元，激发了人们对基于FP8的LLM推理的浓厚兴趣。与16位浮点不同，FP8在深度学习中需要一个共享的缩放因子。尽管E4M3和E5M2在单个值级别上定义明确，但它们的缩放和累加方法尚未标准化，且因硬件和软件实现而异。因此，FP8更像是一种量化格式，而非标准数值表示。本研究首次对NVIDIA H100和Intel Gaudi 2两种AI加速器上的FP8计算与加速进行了全面分析。结果表明，Gaudi 2通过FP8在LLM推理中实现了更高的吞吐量与功率效率，为数据中心级LLM服务中FP8的应用提供了重要参考。

> The introduction of 8-bit floating-point (FP8) computation units in modern AI accelerators has generated significant interest in FP8-based large language model (LLM) inference. Unlike 16-bit floating-point formats, FP8 in deep learning requires a shared scaling factor. Additionally, while E4M3 and E5M2 are well-defined at the individual value level, their scaling and accumulation methods remain unspecified and vary across hardware and software implementations. As a result, FP8 behaves more like a quantization format than a standard numeric representation. In this work, we provide the first comprehensive analysis of FP8 computation and acceleration on two AI accelerators: the NVIDIA H100 and Intel Gaudi 2. Our findings highlight that the Gaudi 2, by leveraging FP8, achieves higher throughput-to-power efficiency during LLM inference, offering valuable insights into the practical implications of FP8 adoption for datacenter-scale LLM serving.

[Arxiv](https://arxiv.org/abs/2502.01070)