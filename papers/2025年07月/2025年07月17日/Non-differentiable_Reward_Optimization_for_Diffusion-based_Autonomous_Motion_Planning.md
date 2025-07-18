# 非可微奖励优化在基于扩散模型的自主运动规划中的应用

发布时间：2025年07月17日

`Agent` `机器人` `自主系统`

> Non-differentiable Reward Optimization for Diffusion-based Autonomous Motion Planning

# 摘要

> 安全有效的运动规划对自主机器人至关重要。扩散模型在捕捉复杂智能体交互方面表现出色，这是动态环境中决策的核心要素。近期研究成功将扩散模型应用于运动规划，展示了其在处理复杂场景和准确预测多模态未来轨迹方面的卓越能力。尽管效果显著，扩散模型在训练目标上存在局限性，因为它们近似数据分布，而非明确捕获底层决策动力学。然而，运动规划的核心在于非可微下游目标，如安全（避障）和有效性（目标达成），而传统学习算法无法直接优化这些目标。

本文提出了一种基于强化学习的扩散运动规划模型训练方案，使其能够有效学习显式衡量安全性和有效性的非可微目标。具体而言，我们引入了一种奖励加权动态阈值算法来塑造密集奖励信号，从而实现更有效的训练，并超越基于可微目标训练的模型。与多种基线方法相比，我们在行人数据集（CrowdNav、ETH-UCY）上取得的最新技术水平，证明了我们方法在安全有效运动规划方面的广泛适用性。

> Safe and effective motion planning is crucial for autonomous robots. Diffusion models excel at capturing complex agent interactions, a fundamental aspect of decision-making in dynamic environments. Recent studies have successfully applied diffusion models to motion planning, demonstrating their competence in handling complex scenarios and accurately predicting multi-modal future trajectories. Despite their effectiveness, diffusion models have limitations in training objectives, as they approximate data distributions rather than explicitly capturing the underlying decision-making dynamics. However, the crux of motion planning lies in non-differentiable downstream objectives, such as safety (collision avoidance) and effectiveness (goal-reaching), which conventional learning algorithms cannot directly optimize. In this paper, we propose a reinforcement learning-based training scheme for diffusion motion planning models, enabling them to effectively learn non-differentiable objectives that explicitly measure safety and effectiveness. Specifically, we introduce a reward-weighted dynamic thresholding algorithm to shape a dense reward signal, facilitating more effective training and outperforming models trained with differentiable objectives. State-of-the-art performance on pedestrian datasets (CrowdNav, ETH-UCY) compared to various baselines demonstrates the versatility of our approach for safe and effective motion planning.

[Arxiv](https://arxiv.org/abs/2507.12977)