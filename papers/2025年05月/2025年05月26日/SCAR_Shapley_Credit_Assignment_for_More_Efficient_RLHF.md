# SCAR：通过夏普利值提升强化学习中人类反馈的效率

发布时间：2025年05月26日

`LLM理论`

> SCAR: Shapley Credit Assignment for More Efficient RLHF

# 摘要

> 从人类反馈中强化学习（RLHF）是将大型语言模型（LLMs）与人类偏好对齐的常用技术，但其稀疏奖励信号常导致信用分配难题。传统方法中，奖励模型仅对完整生成序列给出单一分数，难以揭示具体决策的影响。为此，我们提出Shapley信用分配奖励（SCAR），一种基于合作博弈论中Shapley值的创新方法。SCAR根据各令牌或文本片段的边际贡献，将整体奖励分配至具体部分，从而生成密集奖励信号。与以往方法不同，SCAR无需额外训练模型或人工标注，即可实现公平信用分配。理论分析表明，SCAR保留了原始最优策略；实验结果则显示，在情感控制、文本摘要等任务中，SCAR较标准RLHF和注意力基线方法更快收敛且效果更优。这表明，SCAR为RLHF中的信用分配提供了一种更高效、理论扎实的解决方案，助力LLMs更高效对齐人类偏好。

> Reinforcement Learning from Human Feedback (RLHF) is a widely used technique for aligning Large Language Models (LLMs) with human preferences, yet it often suffers from sparse reward signals, making effective credit assignment challenging. In typical setups, the reward model provides a single scalar score for an entire generated sequence, offering little insight into which token or span-level decisions were responsible for the outcome. To address this, we propose Shapley Credit Assignment Rewards (SCAR), a novel method that leverages Shapley values in cooperative game theory. SCAR distributes the total sequence-level reward among constituent tokens or text spans based on their principled marginal contributions. This creates dense reward signals, crucially, without necessitating the training of auxiliary critique models or recourse to fine-grained human annotations at intermediate generation stages. Unlike prior dense reward methods, SCAR offers a game-theoretic foundation for fair credit attribution. Theoretically, we demonstrate that SCAR preserves the original optimal policy, and empirically, across diverse tasks including sentiment control, text summarization, and instruction tuning, we show that SCAR converges significantly faster and achieves higher final reward scores compared to standard RLHF and attention-based dense reward baselines. Our findings suggest that SCAR provides a more effective and theoretically sound method for credit assignment in RLHF, leading to more efficient alignment of LLMs.

[Arxiv](https://arxiv.org/abs/2505.20417)