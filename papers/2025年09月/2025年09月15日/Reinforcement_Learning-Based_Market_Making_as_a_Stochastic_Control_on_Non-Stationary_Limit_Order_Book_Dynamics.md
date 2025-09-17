# 基于强化学习的做市：非平稳限价订单簿动态的随机控制

发布时间：2025年09月15日

`强化学习` `金融科技`

> Reinforcement Learning-Based Market Making as a Stochastic Control on Non-Stationary Limit Order Book Dynamics

# 摘要

> 强化学习已成为一种极具潜力的框架，能助力开发自适应、数据驱动的策略，让做市商通过与限价订单簿环境的交互优化决策策略。本文探讨了强化学习智能体在做市场景中的整合应用，其中明确建模了底层市场动态，以捕捉真实市场的典型特征——包括订单到达时间聚类、非平稳价差与收益漂移、随机订单量及价格波动性。这些机制不仅提升了控制智能体的稳定性，还将特定领域知识融入智能体的策略学习过程。本文的贡献包括：基于近端策略优化（PPO）算法实现了实用的做市智能体，并通过模拟器环境对智能体在不同市场条件下的性能进行了对比评估。与闭式最优解的财务回报及风险指标对比分析显示，强化学习智能体在非平稳市场中仍能有效运作，且所提模拟器环境可作为做市场景下强化学习智能体训练与预训练的重要工具。

> Reinforcement Learning has emerged as a promising framework for developing adaptive and data-driven strategies, enabling market makers to optimize decision-making policies based on interactions with the limit order book environment. This paper explores the integration of a reinforcement learning agent in a market-making context, where the underlying market dynamics have been explicitly modeled to capture observed stylized facts of real markets, including clustered order arrival times, non-stationary spreads and return drifts, stochastic order quantities and price volatility. These mechanisms aim to enhance stability of the resulting control agent, and serve to incorporate domain-specific knowledge into the agent policy learning process. Our contributions include a practical implementation of a market making agent based on the Proximal-Policy Optimization (PPO) algorithm, alongside a comparative evaluation of the agent's performance under varying market conditions via a simulator-based environment. As evidenced by our analysis of the financial return and risk metrics when compared to a closed-form optimal solution, our results suggest that the reinforcement learning agent can effectively be used under non-stationary market conditions, and that the proposed simulator-based environment can serve as a valuable tool for training and pre-training reinforcement learning agents in market-making scenarios.

[Arxiv](https://arxiv.org/abs/2509.12456)