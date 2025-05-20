# 在LLM强化学习中，切勿让低概率标记占据主导地位

发布时间：2025年05月19日

`LLM应用` `人工智能` `机器学习`

> Do Not Let Low-Probability Tokens Over-Dominate in RL for LLMs

# 摘要

> 强化学习（RL）已成为提升大型语言模型（LLMs）推理能力的基石，最近的创新如组相对策略优化（GRPO）展示了其卓越的有效性。在这项研究中，我们发现了一个关键但尚未被充分探索的 RL 训练问题：低概率令牌因梯度幅度大而对模型更新产生不成比例的影响，阻碍了高概率令牌的有效学习。为了解决这一问题，我们提出了两种创新方法：优势重加权和低概率令牌隔离（Lopti），它们能有效减弱低概率令牌的梯度，同时强调高概率令牌驱动的参数更新。我们的方法促进了不同概率令牌之间的平衡更新，显著提升了 RL 训练效率。实验结果表明，在 K&K 逻辑推理任务中，这些方法使 GRPO 训练的 LLMs 性能提升了高达 46.2%。我们的实现代码可在 https://github.com/zhyang2226/AR-Lopti 获取。

> Reinforcement learning (RL) has become a cornerstone for enhancing the reasoning capabilities of large language models (LLMs), with recent innovations such as Group Relative Policy Optimization (GRPO) demonstrating exceptional effectiveness. In this study, we identify a critical yet underexplored issue in RL training: low-probability tokens disproportionately influence model updates due to their large gradient magnitudes. This dominance hinders the effective learning of high-probability tokens, whose gradients are essential for LLMs' performance but are substantially suppressed. To mitigate this interference, we propose two novel methods: Advantage Reweighting and Low-Probability Token Isolation (Lopti), both of which effectively attenuate gradients from low-probability tokens while emphasizing parameter updates driven by high-probability tokens. Our approaches promote balanced updates across tokens with varying probabilities, thereby enhancing the efficiency of RL training. Experimental results demonstrate that they substantially improve the performance of GRPO-trained LLMs, achieving up to a 46.2% improvement in K&K Logic Puzzle reasoning tasks. Our implementation is available at https://github.com/zhyang2226/AR-Lopti.

[Arxiv](https://arxiv.org/abs/2505.12929)