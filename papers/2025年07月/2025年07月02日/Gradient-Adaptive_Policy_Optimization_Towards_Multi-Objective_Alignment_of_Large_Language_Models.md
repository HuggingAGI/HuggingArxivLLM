# 基于梯度自适应的策略优化：探索大规模语言模型的多目标对齐之路

发布时间：2025年07月02日

`LLM理论

理由：这篇论文探讨了如何通过强化学习和多目标优化来对齐大型语言模型（LLMs）与人类偏好，特别是在存在冲突的情况下。它引入了新的理论方法（GAPO和P-GAPO），分析了这些方法的收敛性，并在理论上进行了验证。这些内容属于LLM的理论层面，因此归类为LLM理论。` `人工智能` `伦理学`

> Gradient-Adaptive Policy Optimization: Towards Multi-Objective Alignment of Large Language Models

# 摘要

> 从人类反馈中进行的强化学习 (RLHF) 已经成为将大型语言模型 (LLMs) 与人类偏好对齐的强大技术。然而，有效对齐 LLMs 与多样化的个人偏好仍是一项重大挑战，尤其是在这些偏好存在冲突的情况下。为了解决这一问题，我们将人类价值对齐建模为一个多目标优化问题，旨在最大化一组可能相互冲突的目标。我们引入了梯度自适应策略优化 (GAPO)，这是一种采用多梯度下降来对齐 LLMs 与多样化偏好分布的新颖微调范式。GAPO 能够自适应地调整每个目标的梯度尺度，从而确定一个在目标间最优平衡权衡的更新方向。此外，我们还引入了 P-GAPO，它能够整合用户在不同目标上的偏好，并实现更贴近用户特定需求的帕累托解。我们的理论分析表明，GAPO 能够收敛到多目标的帕累托最优解。在 Mistral-7B 上的实证结果表明，GAPO 在帮助性和无害性方面均超越了当前最先进的方法，展现出更优越的性能表现。

> Reinforcement Learning from Human Feedback (RLHF) has emerged as a powerful technique for aligning large language models (LLMs) with human preferences. However, effectively aligning LLMs with diverse human preferences remains a significant challenge, particularly when they are conflict. To address this issue, we frame human value alignment as a multi-objective optimization problem, aiming to maximize a set of potentially conflicting objectives. We introduce Gradient-Adaptive Policy Optimization (GAPO), a novel fine-tuning paradigm that employs multiple-gradient descent to align LLMs with diverse preference distributions. GAPO adaptively rescales the gradients for each objective to determine an update direction that optimally balances the trade-offs between objectives. Additionally, we introduce P-GAPO, which incorporates user preferences across different objectives and achieves Pareto solutions that better align with the user's specific needs. Our theoretical analysis demonstrates that GAPO converges towards a Pareto optimal solution for multiple objectives. Empirical results on Mistral-7B show that GAPO outperforms current state-of-the-art methods, achieving superior performance in both helpfulness and harmlessness.

[Arxiv](https://arxiv.org/abs/2507.01915)