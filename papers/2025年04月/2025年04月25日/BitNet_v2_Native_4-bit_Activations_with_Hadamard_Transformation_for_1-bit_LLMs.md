# BitNet v2：通过Hadamard变换实现支持1-bit大语言模型的原生4位激活

发布时间：2025年04月25日

`LLM理论` `计算机科学` `模型优化`

> BitNet v2: Native 4-bit Activations with Hadamard Transformation for 1-bit LLMs

# 摘要

> 1-bit大规模语言模型（LLMs）的高效部署面临激活异常值带来的挑战。为解决这一问题，我们提出了BitNet v2，一个支持1-bit LLMs原生4-bit激活量化的全新框架。针对注意力机制和前馈网络中的激活异常值，我们设计了H-BitLinear模块，通过在线Hadamard变换优化激活分布，使其更接近高斯形式，从而提升低比特表示效果。实验结果表明，BitNet v2在8-bit激活训练下性能与BitNet b1.58相当；而在4-bit激活原生训练下，性能仅轻微下降，同时显著降低了批量推理的内存占用和计算成本。

> Efficient deployment of 1-bit Large Language Models (LLMs) is hindered by activation outliers, which complicate quantization to low bit-widths. We introduce BitNet v2, a novel framework enabling native 4-bit activation quantization for 1-bit LLMs. To tackle outliers in attention and feed-forward network activations, we propose H-BitLinear, a module applying an online Hadamard transformation prior to activation quantization. This transformation smooths sharp activation distributions into more Gaussian-like forms, suitable for low-bit representation. Experiments show BitNet v2 trained from scratch with 8-bit activations matches BitNet b1.58 performance. Crucially, BitNet v2 achieves minimal performance degradation when trained with native 4-bit activations, significantly reducing memory footprint and computational cost for batched inference.

[Arxiv](https://arxiv.org/abs/2504.18415)