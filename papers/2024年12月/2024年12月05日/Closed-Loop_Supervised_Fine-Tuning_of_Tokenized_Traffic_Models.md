# 标记化流量模型的闭环监督微调

发布时间：2024年12月05日

`Agent`

> Closed-Loop Supervised Fine-Tuning of Tokenized Traffic Models

# 摘要

> 交通模拟的目标是为交通代理学习一种策略，在闭环展开时能如实还原现实世界中观察到的轨迹联合分布。受大型语言模型启发，标记化多代理策略近来成为交通模拟领域的前沿技术。但这类策略通常通过开环行为克隆训练，在模拟中的闭环执行时会出现协变量偏移问题。在本研究中，我们提出了“Top-K 中的最近者（CAT-K）”展开策略，这是一种简单有效的闭环微调策略，可缓解协变量偏移。CAT-K 微调只需现有轨迹数据，无需强化学习或生成对抗模仿。具体来说，CAT-K 微调让一个 700 万参数的标记化交通模拟策略胜过了同一模型家族中 1.02 亿参数的模型，在提交时登上了 Waymo Sim Agent Challenge 排行榜榜首。相关代码可在 https://github.com/NVlabs/catk 获取。

> Traffic simulation aims to learn a policy for traffic agents that, when unrolled in closed-loop, faithfully recovers the joint distribution of trajectories observed in the real world. Inspired by large language models, tokenized multi-agent policies have recently become the state-of-the-art in traffic simulation. However, they are typically trained through open-loop behavior cloning, and thus suffer from covariate shift when executed in closed-loop during simulation. In this work, we present Closest Among Top-K (CAT-K) rollouts, a simple yet effective closed-loop fine-tuning strategy to mitigate covariate shift. CAT-K fine-tuning only requires existing trajectory data, without reinforcement learning or generative adversarial imitation. Concretely, CAT-K fine-tuning enables a small 7M-parameter tokenized traffic simulation policy to outperform a 102M-parameter model from the same model family, achieving the top spot on the Waymo Sim Agent Challenge leaderboard at the time of submission. The code is available at https://github.com/NVlabs/catk.

[Arxiv](https://arxiv.org/abs/2412.05334)