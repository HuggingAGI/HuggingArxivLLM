# Gen2Real：借助生成视频迈向无需演示的灵巧操作

发布时间：2025年09月16日

`强化学习` `工业与制造`

> \textsc{Gen2Real}: Towards Demo-Free Dexterous Manipulation by Harnessing Generated Video

# 摘要

> 灵巧操作一直是机器人领域的棘手难题，主要瓶颈在于收集大量学习所需的人类演示数据成本高昂。为此，本文提出	extsc{Gen2Real}系统——它仅用一段生成视频就能替代昂贵的人类演示，进而驱动机器人掌握技能。该系统融合三大核心模块：演示生成模块通过视频生成技术融合姿态与深度估计，生成手-物体交互轨迹；轨迹优化模块借助物理感知交互优化模型（PIOM）保证物理一致性；演示学习模块将人类动作迁移至机器人手，并利用基于锚点的残差近端策略优化（PPO）策略实现稳定控制。仅凭生成视频，所学策略在仿真抓取任务中成功率达77.3%，在真实机器人上也能实现连贯操作。我们还通过消融实验验证了各组件的作用，并实现了自然语言直接指定任务的功能，充分彰显	extsc{Gen2Real}能将想象视频中的抓取技能迁移至现实执行的灵活性与鲁棒性。

> Dexterous manipulation remains a challenging robotics problem, largely due to the difficulty of collecting extensive human demonstrations for learning. In this paper, we introduce \textsc{Gen2Real}, which replaces costly human demos with one generated video and drives robot skill from it: it combines demonstration generation that leverages video generation with pose and depth estimation to yield hand-object trajectories, trajectory optimization that uses Physics-aware Interaction Optimization Model (PIOM) to impose physics consistency, and demonstration learning that retargets human motions to a robot hand and stabilizes control with an anchor-based residual Proximal Policy Optimization (PPO) policy. Using only generated videos, the learned policy achieves a 77.3\% success rate on grasping tasks in simulation and demonstrates coherent executions on a real robot. We also conduct ablation studies to validate the contribution of each component and demonstrate the ability to directly specify tasks using natural language, highlighting the flexibility and robustness of \textsc{Gen2Real} in generalizing grasping skills from imagined videos to real-world execution.

[Arxiv](https://arxiv.org/abs/2509.14178)