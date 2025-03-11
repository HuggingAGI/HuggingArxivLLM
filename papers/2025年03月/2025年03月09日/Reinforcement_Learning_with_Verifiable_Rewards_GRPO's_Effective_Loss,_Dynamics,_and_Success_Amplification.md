# 强化学习的可验证奖励机制：GRPO的有效损失、动态特性与成功放大

发布时间：2025年03月09日

`Agent` `人工智能` `机器学习`

> Reinforcement Learning with Verifiable Rewards: GRPO's Effective Loss, Dynamics, and Success Amplification

# 摘要

> 组相对策略优化（GRPO）成功应用于DeepSeek R1模型的训练，旨在通过可验证或二元奖励提升大型语言模型（LLMs）的推理能力。本文研究表明，GRPO结合可验证奖励可表达为一种Kullback Leibler（$\mathsf{KL}$）正则化对比损失，其中对比样本来自旧策略的合成数据。最优策略$π_{n}$可显式表示为二元奖励，以及旧策略（$π_{n-1}$）和参考策略$π_0$的一阶和二阶统计量的函数。通过迭代此方案，我们获得了一系列策略$π_{n}$，并能量化各策略的成功概率$p_n$。研究表明，策略的成功概率满足一个递推关系，该关系收敛于一个依赖初始成功概率$p_0$和$\mathsf{KL}$正则化器参数$β$的函数的固定点$p^*$。我们证明$p^*$必然大于$p_0$，从而证实GRPO能够有效提升策略的成功概率。

> Group Relative Policy Optimization (GRPO) was introduced and used successfully to train DeepSeek R1 models for promoting reasoning capabilities of LLMs using verifiable or binary rewards. We show in this paper that GRPO with verifiable rewards can be written as a Kullback Leibler ($\mathsf{KL}$) regularized contrastive loss, where the contrastive samples are synthetic data sampled from the old policy. The optimal GRPO policy $π_{n}$ can be expressed explicitly in terms of the binary reward, as well as the first and second order statistics of the old policy ($π_{n-1}$) and the reference policy $π_0$. Iterating this scheme, we obtain a sequence of policies $π_{n}$ for which we can quantify the probability of success $p_n$. We show that the probability of success of the policy satisfies a recurrence that converges to a fixed point of a function that depends on the initial probability of success $p_0$ and the regularization parameter $β$ of the $\mathsf{KL}$ regularizer. We show that the fixed point $p^*$ is guaranteed to be larger than $p_0$, thereby demonstrating that GRPO effectively amplifies the probability of success of the policy.

[Arxiv](https://arxiv.org/abs/2503.06639)