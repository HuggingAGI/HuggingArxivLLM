# 面向数据驱动海上导航的目标条件强化学习

发布时间：2025年09月01日

`强化学习` `交通运输`

> Goal-Conditioned Reinforcement Learning for Data-Driven Maritime Navigation

# 摘要

> 在狭窄多变的航道中为船舶规划航线颇具挑战，这源于环境条件的动态变化与操作约束的双重影响。现有船舶航线研究往往难以在多组起讫点间实现泛化，也未能充分利用大规模数据驱动的交通图谱。本文针对海量海事数据提出一种强化学习方案，可在多组起讫点间自主学习规划航线，并能适配不同的六边形网格分辨率。智能体在多离散动作空间内，基于连续观测学习选择航行方向与速度。奖励函数通过融合船舶自动识别系统（AIS）生成的交通图谱与ERA5风场数据，实现对燃油效率、航行耗时、风阻及航线多样性的动态平衡。我们在世界最大河口之一的圣劳伦斯湾对该方法进行了验证，并评估了多种配置方案，包括近端策略优化与循环网络、无效动作掩码及探索策略的组合。实验结果显示，动作掩码可显著提升策略性能，而以正向塑造奖励补充纯惩罚反馈机制，还能带来额外增益。

> Routing vessels through narrow and dynamic waterways is challenging due to changing environmental conditions and operational constraints. Existing vessel-routing studies typically fail to generalize across multiple origin-destination pairs and do not exploit large-scale, data-driven traffic graphs. In this paper, we propose a reinforcement learning solution for big maritime data that can learn to find a route across multiple origin-destination pairs while adapting to different hexagonal grid resolutions. Agents learn to select direction and speed under continuous observations in a multi-discrete action space. A reward function balances fuel efficiency, travel time, wind resistance, and route diversity, using an Automatic Identification System (AIS)-derived traffic graph with ERA5 wind fields. The approach is demonstrated in the Gulf of St. Lawrence, one of the largest estuaries in the world. We evaluate configurations that combine Proximal Policy Optimization with recurrent networks, invalid-action masking, and exploration strategies. Our experiments demonstrate that action masking yields a clear improvement in policy performance and that supplementing penalty-only feedback with positive shaping rewards produces additional gains.

[Arxiv](https://arxiv.org/abs/2509.01838)