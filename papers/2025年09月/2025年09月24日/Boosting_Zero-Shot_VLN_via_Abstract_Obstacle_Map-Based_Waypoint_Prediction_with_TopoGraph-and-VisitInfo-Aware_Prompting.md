# 借助基于抽象障碍物地图的路径点预测与拓扑图-访问信息感知提示提升零样本视觉语言导航

发布时间：2025年09月24日

`Agent` `交通运输`

> Boosting Zero-Shot VLN via Abstract Obstacle Map-Based Waypoint Prediction with TopoGraph-and-VisitInfo-Aware Prompting

# 摘要

> 随着基础模型与机器人技术的飞速发展，视觉-语言导航（VLN）已成为具身智能体的核心任务，拥有广阔的实际应用前景。我们聚焦连续环境下的VLN任务——这一场景极具挑战性，智能体需同时解读自然语言指令、感知周围环境并规划底层动作。为此，我们提出一种零样本框架，将简化而高效的航点预测器与多模态大型语言模型（MLLM）相融合。该预测器基于抽象障碍物地图工作，生成线性可达航点，并将其整合到带有明确访问记录的动态更新拓扑图中。我们将拓扑图与访问信息编码到提示词中，让MLLM能同时对空间结构和探索历史进行推理，从而促进探索过程，并赋予其用于纠错的局部路径规划能力。

> With the rapid progress of foundation models and robotics, vision-language navigation (VLN) has emerged as a key task for embodied agents with broad practical applications. We address VLN in continuous environments, a particularly challenging setting where an agent must jointly interpret natural language instructions, perceive its surroundings, and plan low-level actions. We propose a zero-shot framework that integrates a simplified yet effective waypoint predictor with a multimodal large language model (MLLM). The predictor operates on an abstract obstacle map, producing linearly reachable waypoints, which are incorporated into a dynamically updated topological graph with explicit visitation records. The graph and visitation information are encoded into the prompt, enabling reasoning over both spatial structure and exploration history to encourage exploration and equip MLLM with local path planning for error correction. Extensive experiments on R2R-CE and RxR-CE show that our method achieves state-of-the-art zero-shot performance, with success rates of 41% and 36%, respectively, outperforming prior state-of-the-art methods.

[Arxiv](https://arxiv.org/abs/2509.20499)