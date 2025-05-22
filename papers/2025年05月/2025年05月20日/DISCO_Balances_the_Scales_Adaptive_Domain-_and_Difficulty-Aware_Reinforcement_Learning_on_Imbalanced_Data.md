# DISCO 平衡数据分布：自适应领域和难度感知的强化学习方法

发布时间：2025年05月20日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLMs）在强化学习框架下与人类偏好对齐的问题，特别是针对基于组的相对策略优化（GRPO）方法的局限性。论文提出了一种新的领域感知自洽策略优化（DISCO）方法，旨在解决多领域和数据不平衡场景下的优化问题。该研究属于对大型语言模型训练和优化方法的理论探讨，因此归类于LLM理论。` `策略优化`

> DISCO Balances the Scales: Adaptive Domain- and Difficulty-Aware Reinforcement Learning on Imbalanced Data

# 摘要

> 大型语言模型（LLMs）正通过强化学习从人类反馈（RLHF）日益与人类偏好保持一致。在RLHF方法中，基于组的相对策略优化（GRPO）因其简洁性和强大的性能而备受关注，特别是它无需学习价值函数。然而，GRPO隐含地假设了平衡的领域分布和组间一致的语义对齐——这些假设在现实数据集中很少成立。当应用于多领域且数据不平衡的场景时，GRPO会过度优化主导领域，忽视代表性不足的领域，导致泛化能力和公平性较差。我们提出了领域感知自洽策略优化（DISCO），这是对GRPO的一个原理性扩展，通过两项关键创新解决了组间不平衡问题。领域感知奖励缩放通过重新加权优化来抵消频率偏差，基于领域流行度进行调整。难度感知奖励缩放则利用提示级别的自洽性来识别和优先处理具有更大学习价值的不确定提示。这些策略共同促进了跨领域更加公平和有效的策略学习。在多个LLMs和偏态训练分布上的广泛实验表明，DISCO提升了泛化能力，在Qwen3模型上比现有GRPO变体高出5%的性能，并在多领域对齐基准上达到了新的最先进水平。

> Large Language Models (LLMs) are increasingly aligned with human preferences through Reinforcement Learning from Human Feedback (RLHF). Among RLHF methods, Group Relative Policy Optimization (GRPO) has gained attention for its simplicity and strong performance, notably eliminating the need for a learned value function. However, GRPO implicitly assumes a balanced domain distribution and uniform semantic alignment across groups - assumptions that rarely hold in real-world datasets. When applied to multi-domain, imbalanced data, GRPO disproportionately optimizes for dominant domains, neglecting underrepresented ones and resulting in poor generalization and fairness. We propose Domain-Informed Self-Consistency Policy Optimization (DISCO), a principled extension to GRPO that addresses inter-group imbalance with two key innovations. Domain-aware reward scaling counteracts frequency bias by reweighting optimization based on domain prevalence. Difficulty-aware reward scaling leverages prompt-level self-consistency to identify and prioritize uncertain prompts that offer greater learning value. Together, these strategies promote more equitable and effective policy learning across domains. Extensive experiments across multiple LLMs and skewed training distributions show that DISCO improves generalization, outperforms existing GRPO variants by 5% on Qwen3 models, and sets new state-of-the-art results on multi-domain alignment benchmarks.

[Arxiv](https://arxiv.org/abs/2505.15074)