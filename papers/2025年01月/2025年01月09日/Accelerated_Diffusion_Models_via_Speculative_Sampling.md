# 基于推测性采样的扩散模型加速方法

发布时间：2025年01月09日

`LLM理论

理由：该论文主要讨论了推测采样技术在大型语言模型（LLM）推理中的应用，特别是将其扩展到扩散模型以加速生成过程。虽然论文涉及了LLM的应用场景，但其核心贡献在于理论上的扩展和创新，即如何通过推测采样技术优化LLM的推理过程。因此，将其归类为“LLM理论”更为合适。` `人工智能` `机器学习`

> Accelerated Diffusion Models via Speculative Sampling

# 摘要

> 推测采样是一种加速大型语言模型推理的流行技术，它通过快速草稿模型生成候选标记，并根据目标模型的分布决定是否接受这些标记。尽管此前推测采样仅适用于离散序列，但我们将其扩展到了扩散模型，这类模型通过连续的向量值马尔可夫链生成样本。目标模型在此情境下是一个高质量但计算昂贵的扩散模型。我们提出了多种草稿策略，其中一种简单有效的方法无需训练草稿模型，可直接应用于任何扩散模型。实验结果显示，该方法在各种扩散模型上显著提升了生成速度，函数评估次数减半，同时仍能生成目标模型的精确样本。

> Speculative sampling is a popular technique for accelerating inference in Large Language Models by generating candidate tokens using a fast draft model and accepting or rejecting them based on the target model's distribution. While speculative sampling was previously limited to discrete sequences, we extend it to diffusion models, which generate samples via continuous, vector-valued Markov chains. In this context, the target model is a high-quality but computationally expensive diffusion model. We propose various drafting strategies, including a simple and effective approach that does not require training a draft model and is applicable out of the box to any diffusion model. Our experiments demonstrate significant generation speedup on various diffusion models, halving the number of function evaluations, while generating exact samples from the target model.

[Arxiv](https://arxiv.org/abs/2501.05370)