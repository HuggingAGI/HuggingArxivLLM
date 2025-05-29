# # 流形引导：缓解大型推理模型中的过度思考

发布时间：2025年05月28日

`LLM理论` `数学推理`

> Mitigating Overthinking in Large Reasoning Models via Manifold Steering

# 摘要

> 近期，大型推理模型（LRMs）在解决数学和编程等复杂任务中展现出令人瞩目的能力。然而，这些模型在推理过程中经常出现一种被称为“过思考”的现象，表现为过多的验证循环和冗余的思考过程，导致显著的计算开销。本文旨在从机制可解释性的角度探究过思考现象的根本原因，从而缓解这一问题。我们首先证明，过思考的倾向可以在模型的激活空间中通过单一方向进行有效捕捉，且通过沿此方向干预激活可以缓解问题。然而，这种干预的效果很快达到瓶颈，甚至随着干预强度的增加而恶化。因此，我们系统性地探索了激活空间，发现过思考现象实际上与一个低维流形相关联，这意味着效果有限的原因在于高维调控方向引入的噪声。基于这一洞察，我们提出了一种名为流形调控（Manifold Steering）的新方法，该方法通过理论近似干扰噪声，将调控方向优雅地投影到低维激活流形上。在DeepSeek-R1蒸馏模型上的大量实验验证了我们的方法在多个数学基准测试中将输出标记减少高达71%的同时，甚至提高了准确性。此外，我们的方法在代码生成和基于知识的问答任务中也展现出强大的跨领域迁移能力，保持了稳定的标记减少效果。代码可在以下链接获取：https://github.com/Aries-iai/Manifold_Steering。

> Recent advances in Large Reasoning Models (LRMs) have demonstrated remarkable capabilities in solving complex tasks such as mathematics and coding. However, these models frequently exhibit a phenomenon known as overthinking during inference, characterized by excessive validation loops and redundant deliberation, leading to substantial computational overheads. In this paper, we aim to mitigate overthinking by investigating the underlying mechanisms from the perspective of mechanistic interpretability. We first showcase that the tendency of overthinking can be effectively captured by a single direction in the model's activation space and the issue can be eased by intervening the activations along this direction. However, this efficacy soon reaches a plateau and even deteriorates as the intervention strength increases. We therefore systematically explore the activation space and find that the overthinking phenomenon is actually tied to a low-dimensional manifold, which indicates that the limited effect stems from the noises introduced by the high-dimensional steering direction. Based on this insight, we propose Manifold Steering, a novel approach that elegantly projects the steering direction onto the low-dimensional activation manifold given the theoretical approximation of the interference noise. Extensive experiments on DeepSeek-R1 distilled models validate that our method reduces output tokens by up to 71% while maintaining and even improving the accuracy on several mathematical benchmarks. Our method also exhibits robust cross-domain transferability, delivering consistent token reduction performance in code generation and knowledge-based QA tasks. Code is available at: https://github.com/Aries-iai/Manifold_Steering.

[Arxiv](https://arxiv.org/abs/2505.22411)