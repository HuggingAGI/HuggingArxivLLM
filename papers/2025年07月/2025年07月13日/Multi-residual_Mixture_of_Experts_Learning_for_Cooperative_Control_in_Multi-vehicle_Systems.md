# 多残差专家混合学习在多车辆系统中的协作控制研究

发布时间：2025年07月13日

`Agent` `自动驾驶` `智能交通`

> Multi-residual Mixture of Experts Learning for Cooperative Control in Multi-vehicle Systems

# 摘要

> 自动驾驶汽车（AVs）正日益受到关注，其应用已不仅限于一种交通工具，而是演变为能够控制交通流动态的移动执行器。这与传统的固定位置执行器（如交通信号灯）形成鲜明对比，被称为Lagrangian交通控制。然而，为自动驾驶汽车设计一种能在不同交通场景中通用的有效Lagrangian交通控制策略，面临着巨大挑战。现实世界的交通环境极其多样，要在如此多样的交通场景中开发出稳健表现的策略极具难度。这一挑战还因交通系统的多智能体特性、参与者动机的多样性以及在严格物理和外部约束下相互冲突的优化目标而变得更加复杂。为应对这些挑战，我们引入了Multi-Residual Mixture of Expert Learning（MRMEL），这是一个用于Lagrangian交通控制的全新框架。它通过学习残差修正来增强给定的次优基础策略，同时明确考虑交通场景空间的结构。特别地，受残差强化学习的启发，MRMEL通过学习残差修正来增强次优的基础自动驾驶控制策略，同时根据交通场景动态选择最合适的候选策略，这些候选策略被建模为专家混合模型。我们在亚特兰大、达拉斯沃思堡和盐湖城的有信号灯交叉口的协同生态驾驶案例研究中验证了MRMEL，采用了基于现实世界数据的交通场景。结果表明，与每种设置下的最强基线相比，MRMEL始终表现出更优性能，实现额外4%-9%的总体车辆排放减少。

> Autonomous vehicles (AVs) are becoming increasingly popular, with their applications now extending beyond just a mode of transportation to serving as mobile actuators of a traffic flow to control flow dynamics. This contrasts with traditional fixed-location actuators, such as traffic signals, and is referred to as Lagrangian traffic control. However, designing effective Lagrangian traffic control policies for AVs that generalize across traffic scenarios introduces a major challenge. Real-world traffic environments are highly diverse, and developing policies that perform robustly across such diverse traffic scenarios is challenging. It is further compounded by the joint complexity of the multi-agent nature of traffic systems, mixed motives among participants, and conflicting optimization objectives subject to strict physical and external constraints. To address these challenges, we introduce Multi-Residual Mixture of Expert Learning (MRMEL), a novel framework for Lagrangian traffic control that augments a given suboptimal nominal policy with a learned residual while explicitly accounting for the structure of the traffic scenario space. In particular, taking inspiration from residual reinforcement learning, MRMEL augments a suboptimal nominal AV control policy by learning a residual correction, but at the same time dynamically selects the most suitable nominal policy from a pool of nominal policies conditioned on the traffic scenarios and modeled as a mixture of experts. We validate MRMEL using a case study in cooperative eco-driving at signalized intersections in Atlanta, Dallas Fort Worth, and Salt Lake City, with real-world data-driven traffic scenarios. The results show that MRMEL consistently yields superior performance-achieving an additional 4%-9% reduction in aggregate vehicle emissions relative to the strongest baseline in each setting.

[Arxiv](https://arxiv.org/abs/2507.09836)