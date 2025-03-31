# 熵引导的序列加权方法，实现基于强化学习的大型语言模型微调中的高效探索

发布时间：2025年03月28日

`其他` `人工智能`

> Entropy-guided sequence weighting for efficient exploration in RL-based LLM fine-tuning

# 摘要

> 我们提出了一种创新方法——熵引导序列加权（EGSW），该方法通过动态分配权重来优化探索与利用的平衡，特别适用于基于强化学习的大型语言模型微调。EGSW结合熵正则化与基于优势的加权，平衡策略更新，实现在高维状态空间中的高效探索。采用温度缩放的Softmax加权方式，EGSW优先考虑高奖励、高不确定性步骤，同时保持训练稳定。尽管EGSW最初旨在提升大型语言模型（LLM）微调中的Group Relative Policy Optimization（GRPO）效果，但其具有广泛的适用性，可应用于其他强化学习（RL）算法，并支持步级和轨迹级设置。实证结果表明，EGSW显著提升了GRPO的推理能力，提高了样本效率。未来研究将探索EGSW在先进强化学习方法中的应用潜力。

> We introduce Entropy-Guided Sequence Weighting (EGSW), a novel approach that enhances the exploration-exploitation tradeoff by dynamically assigning weights to generated outputs based on their advantage and entropy for Reinforcement Learning-based Large Language Model fine-tuning. EGSW integrates entropy regularization with advantage-based weighting to balance policy updates, enabling efficient exploration in high-dimensional state spaces. By employing temperature-scaled softmax weighting over sequences, EGSW prioritizing high-reward, high-uncertainty steps while maintaining training stability. Although originally developed to improve Group Relative Policy Optimization (GRPO) during large language model (LLM) fine-tuning, EGSW is generalizable to other reinforcement learning (RL) algorithms and can be implemented in both step-wise and trajectory-wise settings. Empirical evaluations demonstrate that EGSW enhances GRPO reasoning ability, yielding improvements in sample efficiency. Future work will explore the application of EGSW to advanced RL methodologies.

[Arxiv](https://arxiv.org/abs/2503.22456)