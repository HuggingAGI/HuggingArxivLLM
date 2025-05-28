# 博弈论视角下LLM对齐的三大基本限制：史密斯一致性与偏好匹配

发布时间：2025年05月26日

`LLM理论` `博弈论` `机器学习`

> Fundamental Limits of Game-Theoretic LLM Alignment: Smith Consistency and Preference Matching

# 摘要

> Nash Learning from Human Feedback 是一种通过将学习建模为两人零和博弈，从而实现大型语言模型 (LLMs) 与人类偏好对齐的博弈论框架。然而，直接将原始偏好作为博弈的收益，严重限制了这一框架的潜力。本文系统性地研究了如何基于成对的人类偏好选择收益函数，以获得理想的对齐特性。我们建立了 Condorcet 一致性、通过混合策略实现的多样性以及 Smith 一致性的必要和充分条件，为博弈论 LLM 对齐的稳健性提供了理论基础。进一步地，我们证明了偏好匹配的不可能性：即使在 Bradley-Terry-Luce 模型等标准假设下，也没有平滑且可学习的成对偏好映射能够保证一个与目标策略匹配的唯一 Nash 均衡。这一结果凸显了博弈论 LLM 对齐的根本局限性。

> Nash Learning from Human Feedback is a game-theoretic framework for aligning large language models (LLMs) with human preferences by modeling learning as a two-player zero-sum game. However, using raw preference as the payoff in the game highly limits the potential of the game-theoretic LLM alignment framework. In this paper, we systematically study using what choices of payoff based on the pairwise human preferences can yield desirable alignment properties. We establish necessary and sufficient conditions for Condorcet consistency, diversity through mixed strategies, and Smith consistency. These results provide a theoretical foundation for the robustness of game-theoretic LLM alignment. Further, we show the impossibility of preference matching -- i.e., no smooth and learnable mappings of pairwise preferences can guarantee a unique Nash equilibrium that matches a target policy, even under standard assumptions like the Bradley-Terry-Luce model. This result highlights the fundamental limitation of game-theoretic LLM alignment.

[Arxiv](https://arxiv.org/abs/2505.20627)