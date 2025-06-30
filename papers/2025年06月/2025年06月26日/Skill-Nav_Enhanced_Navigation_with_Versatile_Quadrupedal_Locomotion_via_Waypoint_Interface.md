# Skill-Nav: 借助航点界面实现增强导航与多用途四足运动能力

发布时间：2025年06月26日

`Agent` `机器人` `导航系统`

> Skill-Nav: Enhanced Navigation with Versatile Quadrupedal Locomotion via Waypoint Interface

# 摘要

> 四足机器人借助强化学习（RL）展现出了令人惊叹的运动能力，甚至能够完成极限跑酷动作。然而，如何将这些运动技能与导航能力相结合，仍然是一个未被充分探索的领域，这为提升四足机器人长距离运动能力提供了巨大潜力。在本文中，我们提出了Skill-Nav方法，该方法通过将四足机器人的运动技能整合到一个基于路标的分层导航框架中，实现了更高效的运动控制。具体来说，我们利用深度强化学习训练了一个基于路标的运动策略，使机器人能够自主调整其运动方式，精准到达目标位置的同时避开障碍物。与传统的直接速度控制相比，基于路标的导航方式不仅更加简单，而且提供了更大的灵活性，能够更好地协调高层规划与底层控制。通过将路标作为接口，我们能够充分利用各种通用规划工具，如大型语言模型（LLMs）和路径规划算法，来引导机器人的运动策略，使其能够顺利穿越各种复杂地形。我们在模拟环境和真实场景中进行了大量实验，结果表明Skill-Nav能够有效应对复杂地形挑战，成功完成各种高难度导航任务。

> Quadrupedal robots have demonstrated exceptional locomotion capabilities through Reinforcement Learning (RL), including extreme parkour maneuvers. However, integrating locomotion skills with navigation in quadrupedal robots has not been fully investigated, which holds promise for enhancing long-distance movement capabilities. In this paper, we propose Skill-Nav, a method that incorporates quadrupedal locomotion skills into a hierarchical navigation framework using waypoints as an interface. Specifically, we train a waypoint-guided locomotion policy using deep RL, enabling the robot to autonomously adjust its locomotion skills to reach targeted positions while avoiding obstacles. Compared with direct velocity commands, waypoints offer a simpler yet more flexible interface for high-level planning and low-level control. Utilizing waypoints as the interface allows for the application of various general planning tools, such as large language models (LLMs) and path planning algorithms, to guide our locomotion policy in traversing terrains with diverse obstacles. Extensive experiments conducted in both simulated and real-world scenarios demonstrate that Skill-Nav can effectively traverse complex terrains and complete challenging navigation tasks.

[Arxiv](https://arxiv.org/abs/2506.21853)