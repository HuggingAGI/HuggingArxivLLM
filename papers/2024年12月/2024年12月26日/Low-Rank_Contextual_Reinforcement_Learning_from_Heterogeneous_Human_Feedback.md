# 基于异构人类反馈的低秩上下文强化学习

发布时间：2024年12月26日

`LLM理论

理由：这篇论文主要讨论了基于人类反馈的强化学习（RLHF）在大型语言模型中的应用，特别是如何通过低秩上下文RLHF（LoCo-RLHF）框架来高效建模异质性反馈。论文还提出了“降维子空间悲观主义”（PRS）策略，并提供了理论证明和实验验证。这些内容主要涉及大型语言模型的理论改进和优化，因此应归类为LLM理论。` `人工智能`

> Low-Rank Contextual Reinforcement Learning from Heterogeneous Human Feedback

# 摘要

> # 摘要
基于人类反馈的强化学习（RLHF）是让大型语言模型与人类偏好对齐的关键。然而，人类反馈的多样性带来了奖励学习的巨大挑战。为此，我们提出了低秩上下文RLHF（LoCo-RLHF）框架，通过整合上下文信息，高效建模异质性反馈。该方法利用用户上下文与查询-回答对交互的低秩结构，降低特征维度。我们还提出了“降维子空间悲观主义”（PRS）策略，应对反馈中的分布偏移问题。理论证明，该策略的次优性差距更小。实验表明，LoCo-RLHF在个性化RLHF中表现优异，且对分布偏移具有鲁棒性。

> Reinforcement learning from human feedback (RLHF) has become a cornerstone for aligning large language models with human preferences. However, the heterogeneity of human feedback, driven by diverse individual contexts and preferences, poses significant challenges for reward learning. To address this, we propose a Low-rank Contextual RLHF (LoCo-RLHF) framework that integrates contextual information to better model heterogeneous feedback while maintaining computational efficiency. Our approach builds on a contextual preference model, leveraging the intrinsic low-rank structure of the interaction between user contexts and query-answer pairs to mitigate the high dimensionality of feature representations. Furthermore, we address the challenge of distributional shifts in feedback through our Pessimism in Reduced Subspace (PRS) policy, inspired by pessimistic offline reinforcement learning techniques. We theoretically demonstrate that our policy achieves a tighter sub-optimality gap compared to existing methods. Extensive experiments validate the effectiveness of LoCo-RLHF, showcasing its superior performance in personalized RLHF settings and its robustness to distribution shifts.

[Arxiv](https://arxiv.org/abs/2412.19436)