# 探索缩小直接对齐算法中奖励生成差距的方法

发布时间：2025年06月11日

`LLM理论` `人工智能` `机器学习`

> Towards Bridging the Reward-Generation Gap in Direct Alignment Algorithms

# 摘要

> 直接对齐算法（DAAs）如DPO和SimPO，作为强化学习从人类反馈（RLHF）的替代方案，在将大型语言模型（LLMs）与人类偏好对齐方面表现出色。然而，这些算法存在一个关键问题——“奖励生成差距”，即训练目标与实际生成性能之间的不一致。本文发现，这一差距源于LLM生成过程中前缀标记的重要性与DAAs隐含奖励函数中该重要性的体现之间的不匹配。为解决这一问题，我们提出了一种名为前缀导向等长训练（POET）的简单而有效的方法，该方法通过将优选和非优选响应截断至相同长度，使DAAs在所有位置上优化目标时更加关注前缀标记。实验结果表明，POET相较于标准DAAs在AlpacaEval 2中提升了高达15.6分，并在下游任务中整体有所改善。这凸显了在DAAs中解决奖励优化与生成性能不一致问题的重要性。

> Direct Alignment Algorithms (DAAs), such as Direct Preference Optimization (DPO) and Simple Preference Optimization (SimPO), have emerged as efficient alternatives to Reinforcement Learning from Human Feedback (RLHF) algorithms for aligning large language models (LLMs) with human preferences. However, DAAs suffer from a fundamental limitation we identify as the "reward-generation gap" -- a misalignment between optimization objectives during training and actual generation performance during inference. In this paper, we find a contributor to the reward-generation gap is the mismatch between the inherent importance of prefix tokens during the LLM generation process and how this importance is reflected in the implicit reward functions of DAAs. To bridge the gap, we introduce a simple yet effective approach called Prefix-Oriented Equal-length Training (POET), which truncates both preferred and dispreferred responses to match the shorter one's length. Training with POET, where both responses in each sample are truncated to equal length, resulting in diverse truncated lengths across samples, the optimization of DAAs objective is implicitly constrained to converge across all positions, thus paying more attention to prefix tokens than the standard DAAs. We conduct experiments with DPO and SimPO, two representative DAAs, demonstrating that POET improves over their standard implementations, achieving up to 15.6 points in AlpacaEval 2 and overall improvements across downstream tasks. Our results highlight the importance of addressing the misalignment between reward optimization and generation performance in DAAs.

[Arxiv](https://arxiv.org/abs/2506.09457)