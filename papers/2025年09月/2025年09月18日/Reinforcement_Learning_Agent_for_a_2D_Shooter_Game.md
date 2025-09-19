# 2D射击游戏的强化学习智能体

发布时间：2025年09月18日

`强化学习` `媒体与娱乐`

> Reinforcement Learning Agent for a 2D Shooter Game

# 摘要

> 在复杂游戏环境中，强化学习智能体常面临稀疏奖励、训练不稳定和样本效率低下的问题。本文针对2D射击游戏智能体，提出了一种混合训练方法，将离线模仿学习与在线强化学习相结合。我们设计了一个多头神经网络，该网络具有行为克隆和Q学习的独立输出，并通过带注意力机制的共享特征提取层实现统一。初始使用纯深度Q网络的实验显示出明显的不稳定性，智能体尽管偶尔表现良好，却频繁退回到低效策略。为解决这一问题，我们提出了一种混合方法：首先基于规则智能体的演示数据进行行为克隆，再过渡到强化学习阶段。我们的混合方法在对抗基于规则的对手时，胜率稳定保持在70%以上，明显优于纯强化学习方法——后者不仅方差大，性能还频繁下降。多头架构在保持训练稳定性的同时，实现了学习模式间的高效知识迁移。结果表明，将基于演示的初始化与强化学习优化相结合，为在复杂多智能体环境中开发游戏AI智能体提供了稳健方案，尤其适用于纯探索难以奏效的场景。

> Reinforcement learning agents in complex game environments often suffer from sparse rewards, training instability, and poor sample efficiency. This paper presents a hybrid training approach that combines offline imitation learning with online reinforcement learning for a 2D shooter game agent. We implement a multi-head neural network with separate outputs for behavioral cloning and Q-learning, unified by shared feature extraction layers with attention mechanisms. Initial experiments using pure deep Q-Networks exhibited significant instability, with agents frequently reverting to poor policies despite occasional good performance. To address this, we developed a hybrid methodology that begins with behavioral cloning on demonstration data from rule-based agents, then transitions to reinforcement learning. Our hybrid approach achieves consistently above 70% win rate against rule-based opponents, substantially outperforming pure reinforcement learning methods which showed high variance and frequent performance degradation. The multi-head architecture enables effective knowledge transfer between learning modes while maintaining training stability. Results demonstrate that combining demonstration-based initialization with reinforcement learning optimization provides a robust solution for developing game AI agents in complex multi-agent environments where pure exploration proves insufficient.

[Arxiv](https://arxiv.org/abs/2509.15042)