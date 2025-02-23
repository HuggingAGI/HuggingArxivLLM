# # 大型语言模型的逐层稀疏性分析：从理论视角探讨
从理论视角分析大型语言模型的逐层稀疏性

发布时间：2025年02月20日

`LLM理论` `视觉处理`

> Determining Layer-wise Sparsity for Large Language Models Through a Theoretical Perspective

# 摘要

> 本文从理论视角探讨了大型语言模型 (LLMs) 分层稀疏率的确定问题。我们发现现有稀疏化方法存在“$	extbf{重构误差爆炸}$”的关键问题，即稀疏化过程中各层重构误差逐渐累积，早期层的误差在后续层中传播并放大，导致整体误差显著增加，模型性能大幅下降。通过理论分析，我们提出了一种简单而有效的分层稀疏率分配方法，采用单调递增的等差数列，将多层稀疏率的确定简化为单个公差超参数的确定。这一方法仅需少量尝试即可找到最优稀疏率。理论分析和实验结果均表明，该稀疏率分配方案接近最优。实验表明，我们的方法显著提升了各类架构下稀疏 LLMs 的性能，超越了现有分层稀疏方法。此外，该方法改进了多种压缩技术的性能，并可应用于视觉和多模态模型。特别地，通过 Wanda 实现的 70% 稀疏 LLaMA2-7B 模型，我们的方法将困惑度降低了 52.10，提升了 10.50% 的平均零样本准确率，并在 CPU 和 GPU 上分别实现了 2.63 倍和 2.23 倍的加速效果。

> In this paper, we address the challenge of determining the layer-wise sparsity rates of large language models (LLMs) through a theoretical perspective. Specifically, we identify a critical issue of ''$\textbf{reconstruction error explosion}$'' in existing LLMs sparsification methods. This refers to the cumulative effect of reconstruction errors throughout the sparsification process, where errors from earlier layers propagate and amplify in subsequent layers. As a result, the overall reconstruction error increases significantly, leading to a substantial degradation in model performance. Through theoretical analysis, we derive a simple yet effective approach to layer-wise sparsity allocation that mitigates this issue. Our method uses a monotonically increasing arithmetic progression, reducing the process of determining sparsity rates for multiple layers to the determination of a single common difference hyperparameter. Remarkably, this allows for the optimal layer-wise sparsity rates to be identified with just a few trials. Both our theoretical analysis and experimental results demonstrate that this sparsity allocation scheme is near optimal. Extensive experiments show that our method significantly improves the performance of sparse LLMs across various architectures, outperforming existing layer-wise sparsity methods. Furthermore, it enhances the performance of various compression techniques and is applicable to vision and multimodal models. Notably, our method achieves a reduction of 52.10 in perplexity for the 70$\%$ sparse LLaMA2-7B model obtained via Wanda, improves average zero-shot accuracy by 10.50$\%$, and delivers speedups of 2.63$\times$ and 2.23$\times$ on CPU and GPU, respectively.

[Arxiv](https://arxiv.org/abs/2502.14770)