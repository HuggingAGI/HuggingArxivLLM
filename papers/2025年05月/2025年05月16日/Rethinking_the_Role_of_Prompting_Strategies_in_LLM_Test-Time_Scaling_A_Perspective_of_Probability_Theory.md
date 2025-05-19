# 从概率论的角度重新审视提示策略在LLM测试时扩展中的作用

发布时间：2025年05月16日

`LLM理论

理由：这篇论文主要研究了大规模语言模型在推理时间计算扩展方面的表现，深入分析了不同提示策略的性能，并提出了理论方法来优化推理过程。这属于对LLM本身的理论研究，而非具体应用。` `大规模语言模型` `推理优化`

> Rethinking the Role of Prompting Strategies in LLM Test-Time Scaling: A Perspective of Probability Theory

# 摘要

> 最近，关于大规模语言模型 (LLM) 推理时间计算扩展的研究引发了广泛关注。然而，目前对各种推理提示策略在扩展过程中表现的研究仍然有限。本文聚焦于一个标准且现实的扩展场景：多数投票机制。我们系统性地在 6 种 LLM $	imes$ 8 种提示策略 $	imes$ 6 个基准测试上开展实验。实验结果一致表明，随着采样时间和计算开销的增加，那些初始性能优越的复杂提示策略逐渐落后于简单的链式思维（Chain-of-Thought）。我们深入分析了这一现象并提供了理论证明。此外，我们提出了一种基于概率论的方法，可以在不进行额外资源密集型推理的情况下，快速准确地预测大规模采样情况下的扩展性能并选择最优策略。这一方法可作为多数投票机制的推理时间扩展定律。进一步地，我们根据理论分析提出了两种显著提升扩展性能的方法。我们希望这项研究能够重新审视复杂提示策略的作用，释放简单提示策略的潜力，并为提升推理时间扩展性能提供新的见解。

> Recently, scaling test-time compute on Large Language Models (LLM) has garnered wide attention. However, there has been limited investigation of how various reasoning prompting strategies perform as scaling. In this paper, we focus on a standard and realistic scaling setting: majority voting. We systematically conduct experiments on 6 LLMs $\times$ 8 prompting strategies $\times$ 6 benchmarks. Experiment results consistently show that as the sampling time and computational overhead increase, complicated prompting strategies with superior initial performance gradually fall behind simple Chain-of-Thought. We analyze this phenomenon and provide theoretical proofs. Additionally, we propose a method according to probability theory to quickly and accurately predict the scaling performance and select the best strategy under large sampling times without extra resource-intensive inference in practice. It can serve as the test-time scaling law for majority voting. Furthermore, we introduce two ways derived from our theoretical analysis to significantly improve the scaling performance. We hope that our research can promote to re-examine the role of complicated prompting, unleash the potential of simple prompting strategies, and provide new insights for enhancing test-time scaling performance.

[Arxiv](https://arxiv.org/abs/2505.10981)