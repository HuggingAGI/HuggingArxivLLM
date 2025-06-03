# 双重稳健对齐：大型语言模型的优化新思路

发布时间：2025年06月01日

`LLM理论` `人工智能` `偏好优化`

> Doubly Robust Alignment for Large Language Models

# 摘要

> 本文研究了用于使大型语言模型与人类偏好对齐的人类反馈强化学习（RLHF）。虽然 RLHF 已经取得了令人鼓舞的成果，但现有算法对偏好模型（如 Bradley-Terry 模型）、参考策略或奖励函数中的误规格化问题高度敏感，常常导致不理想的微调结果。为了解决这一问题，我们提出了一种双重稳健偏好优化算法，该算法在偏好模型或参考策略中任意一个被正确指定时（无需两者同时正确）均能保持一致性。我们的方法在理论与实践中均展现出优于现有最优算法的更优和更稳健的性能。代码已开源，地址为 https://github.com/DRPO4LLM/DRPO4LLM。

> This paper studies reinforcement learning from human feedback (RLHF) for aligning large language models with human preferences. While RLHF has demonstrated promising results, many algorithms are highly sensitive to misspecifications in the underlying preference model (e.g., the Bradley-Terry model), the reference policy, or the reward function, resulting in undesirable fine-tuning. To address model misspecification, we propose a doubly robust preference optimization algorithm that remains consistent when either the preference model or the reference policy is correctly specified (without requiring both). Our proposal demonstrates superior and more robust performance than state-of-the-art algorithms, both in theory and in practice. The code is available at https://github.com/DRPO4LLM/DRPO4LLM

[Arxiv](https://arxiv.org/abs/2506.01183)