# # 高效且有效的多布尔架构LLMs

发布时间：2025年05月28日

`LLM理论`

> Highly Efficient and Effective LLMs with Multi-Boolean Architectures

# 摘要

> 权重二值化作为一种极具潜力的策略，能够大幅降低大型语言模型（LLMs）的复杂度。它主要分为两类方法：后训练二值化和结合训练感知二值化方法的微调。第一种方法虽然复杂度较低，但会导致原始LLMs信息的重大损失，从而引发性能表现不佳的问题。相比之下，第二种方法严重依赖全精度潜在权重来近似二值权重的梯度，这不仅效果仍不尽如人意，还带来了显著的复杂度。本文中，我们提出了一种全新的框架，首次成功将LLMs转化为多核布尔参数，并直接在布尔域内进行微调，从而避免了昂贵的潜在权重需求。这在微调和推理阶段均大幅降低了复杂度。通过在多种LLMs上进行广泛且深入的实验，我们证明了本方法在性能上超越了近期的超低比特量化和二值化方法。

> Weight binarization has emerged as a promising strategy to drastically reduce the complexity of large language models (LLMs). It is mainly classified into two approaches: post-training binarization and finetuning with training-aware binarization methods. The first approach, while having low complexity, leads to significant loss of information from the original LLMs, resulting in poor performance. The second approach, on the other hand, relies heavily on full-precision latent weights for gradient approximation of binary weights, which not only remains suboptimal but also introduces substantial complexity. In this paper, we introduce a novel framework that effectively transforms LLMs into multi-kernel Boolean parameters, for the first time, finetunes them directly in the Boolean domain, eliminating the need for expensive latent weights. This significantly reduces complexity during both finetuning and inference. Through extensive and insightful experiments across a wide range of LLMs, we demonstrate that our method outperforms recent ultra low-bit quantization and binarization methods.

[Arxiv](https://arxiv.org/abs/2505.22811)