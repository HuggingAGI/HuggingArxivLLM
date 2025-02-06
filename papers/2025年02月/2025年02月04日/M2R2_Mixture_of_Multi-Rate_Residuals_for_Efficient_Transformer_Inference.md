# M2R2: 多速率残差混合助力Transformer高效推理

发布时间：2025年02月04日

`LLM理论

理由：这篇论文主要讨论了如何通过改进残差变换来提升大型语言模型（LLMs）的推理效率和生成质量。具体来说，它提出了一个名为多速率残差混合（M2R2）的框架，旨在动态调节残差速度，从而在推理任务中实现更好的生成质量和加速效果。这些内容涉及LLM的内部机制和优化方法，属于对LLM理论的研究和改进。` `机器学习`

> M2R2: Mixture of Multi-Rate Residuals for Efficient Transformer Inference

# 摘要

> 残差变换提升了大型语言模型（LLMs）的表示深度和表达能力。然而，在自回归生成中对所有标记应用静态残差变换会导致推理效率和生成保真度之间的权衡不佳。现有方法如早期退出、跳过解码和深度混合通过基于标记复杂性调节残差变换来解决这一问题，但它们主要关注标记通过模型层的距离，忽略了残差演化的速度。我们提出了多速率残差混合（M2R2），这是一个动态调节残差速度的框架，旨在提高早期对齐并增强推理效率。在Koala、Self-Instruct、WizardLM和MT-Bench等推理任务上的评估表明，M2R2在生成质量和加速之间取得了更好的平衡，超越了基于距离的最先进策略。在自推测解码设置中，M2R2在MT-Bench上实现了高达2.8倍的加速，表现优于2模型推测解码、Medusa、LookAhead解码和DEED等方法。在专家混合（MoE）架构中，M2R2通过将早期残差对齐与提前加载专家到高带宽内存（HBM）相结合，加速了解码，减少了专家切换瓶颈，并实现了2.9倍的加速，使其在资源受限的环境中表现出色。

> Residual transformations enhance the representational depth and expressive power of large language models (LLMs). However, applying static residual transformations across all tokens in auto-regressive generation leads to a suboptimal trade-off between inference efficiency and generation fidelity. Existing methods, including Early Exiting, Skip Decoding, and Mixture-of-Depth address this by modulating the residual transformation based on token-level complexity. Nevertheless, these approaches predominantly consider the distance traversed by tokens through the model layers, neglecting the underlying velocity of residual evolution. We introduce Mixture of Multi-rate Residuals (M2R2), a framework that dynamically modulates residual velocity to improve early alignment, enhancing inference efficiency. Evaluations on reasoning oriented tasks such as Koala, Self-Instruct, WizardLM, and MT-Bench show M2R2 surpasses state-of-the-art distance-based strategies, balancing generation quality and speedup. In self-speculative decoding setup, M2R2 achieves up to 2.8x speedups on MT-Bench, outperforming methods like 2-model speculative decoding, Medusa, LookAhead Decoding, and DEED. In Mixture-of-Experts (MoE) architectures, integrating early residual alignment with ahead-of-time expert loading into high-bandwidth memory (HBM) accelerates decoding, reduces expert-switching bottlenecks, and achieves a 2.9x speedup, making it highly effective in resource-constrained environments.

[Arxiv](https://arxiv.org/abs/2502.02040)