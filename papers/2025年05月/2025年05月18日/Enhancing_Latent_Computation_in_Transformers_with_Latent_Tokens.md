# # 摘要
潜在令牌增强Transformer潜在计算能力

发布时间：2025年05月18日

`LLM理论` `大型语言模型` `模型优化`

> Enhancing Latent Computation in Transformers with Latent Tokens

# 摘要

> 在大型语言模型中引入辅助标记已成为提升模型性能的有力策略。本文提出了一种轻量级方法，即潜在标记；这些标记本身可能无法用自然语言解释，但它们通过自注意力机制引导基于Transformer的LLM进行自回归解码过程。所提出的潜在标记可以与预训练的Transformer无缝集成，采用参数高效的训练方式，并在推理时灵活应用，同时仅给标准Transformer的现有架构带来极小的复杂度开销。我们对潜在标记的作用机制提出了一些假设，并设计了相应的合成任务来验证这些假设。数值结果证实，该方法显著优于基线模型，尤其在分布外泛化场景中表现突出，凸显了其在提升LLMs适应性方面的潜力。

> Augmenting large language models (LLMs) with auxiliary tokens has emerged as a promising strategy for enhancing model performance. In this work, we introduce a lightweight method termed latent tokens; these are dummy tokens that may be non-interpretable in natural language but steer the autoregressive decoding process of a Transformer-based LLM via the attention mechanism. The proposed latent tokens can be seamlessly integrated with a pre-trained Transformer, trained in a parameter-efficient manner, and applied flexibly at inference time, while adding minimal complexity overhead to the existing infrastructure of standard Transformers. We propose several hypotheses about the underlying mechanisms of latent tokens and design synthetic tasks accordingly to verify them. Numerical results confirm that the proposed method noticeably outperforms the baselines, particularly in the out-of-distribution generalization scenarios, highlighting its potential in improving the adaptability of LLMs.

[Arxiv](https://arxiv.org/abs/2505.12629)