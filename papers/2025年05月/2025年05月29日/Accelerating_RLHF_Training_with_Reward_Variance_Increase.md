# 通过增加奖励方差，加速 RLHF 训练

发布时间：2025年05月29日

`LLM理论` `人工智能`

> Accelerating RLHF Training with Reward Variance Increase

# 摘要

> 人类反馈强化学习（RLHF）是确保大型语言模型（LLMs）在后训练阶段与人类价值观和偏好对齐的关键技术。作为一种有效的RLHF方法，组相对策略优化（GRPO）已在许多基于LLMs的应用中取得成功。然而，高效的基于GRPO的RLHF训练仍然是一个挑战。最近研究表明，初始策略模型的更高奖励方差可以加快RLHF训练速度。受此启发，我们提出了一种实用的奖励调整模型，通过可证明增加奖励方差并保持相对偏好和奖励期望，从而加速RLHF训练。我们的奖励调整方法本质上提出了一个非凸优化问题，这在一般情况下是NP难的。为了解决计算上的挑战，我们设计了一种新型的$O(n \log n)$算法，通过显式表征可行集的极值点，找到非凸奖励调整模型的全局解。作为一个重要应用，我们将这种奖励调整模型自然地集成到GRPO算法中，从而得到一个更高效的奖励方差增加的GRPO（GRPOVI）算法，用于RLHF训练。作为一个有趣的副产品，我们为DeepSeek-R1中基于规则奖励的GRPO在RLHF训练中的实证有效性提供了间接解释。实验结果表明，与原始的GRPO算法相比，GRPOVI算法可以显著提高RLHF训练效率。

> Reinforcement learning from human feedback (RLHF) is an essential technique for ensuring that large language models (LLMs) are aligned with human values and preferences during the post-training phase. As an effective RLHF approach, group relative policy optimization (GRPO) has demonstrated success in many LLM-based applications. However, efficient GRPO-based RLHF training remains a challenge. Recent studies reveal that a higher reward variance of the initial policy model leads to faster RLHF training. Inspired by this finding, we propose a practical reward adjustment model to accelerate RLHF training by provably increasing the reward variance and preserving the relative preferences and reward expectation. Our reward adjustment method inherently poses a nonconvex optimization problem, which is NP-hard to solve in general. To overcome the computational challenges, we design a novel $O(n \log n)$ algorithm to find a global solution of the nonconvex reward adjustment model by explicitly characterizing the extreme points of the feasible set. As an important application, we naturally integrate this reward adjustment model into the GRPO algorithm, leading to a more efficient GRPO with reward variance increase (GRPOVI) algorithm for RLHF training. As an interesting byproduct, we provide an indirect explanation for the empirical effectiveness of GRPO with rule-based reward for RLHF training, as demonstrated in DeepSeek-R1. Experiment results demonstrate that the GRPOVI algorithm can significantly improve the RLHF training efficiency compared to the original GRPO algorithm.

[Arxiv](https://arxiv.org/abs/2505.23247)