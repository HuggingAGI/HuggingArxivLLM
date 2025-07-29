# DOA: 基于深度强化学习的退化优化智能体，具备自适应姿态补偿能力

发布时间：2025年07月25日

`Agent

理由：这篇论文专注于使用强化学习（PPO）训练自适应退化优化代理（DOA），以解决SLAM中的退化问题。它探讨了智能体在复杂环境中的适应能力和优化策略，属于智能体（Agent）研究领域。` `室内定位` `机器人导航`

> DOA: A Degeneracy Optimization Agent with Adaptive Pose Compensation Capability based on Deep Reinforcement Learning

# 摘要

> 基于粒子滤波的2D-SLAM在室内定位领域备受青睐，但长直走廊等环境会导致严重退化问题。我们提出了一种创新性解决方案：利用近端策略优化（PPO）训练自适应退化优化代理（DOA）。该方法针对传统监督学习框架中的三大核心挑战进行了系统性改进：突破退化数据集的采集瓶颈、提升训练样本质量、明确标注协议设计。通过精心设计的奖励函数，我们引导代理在退化环境中发展出独特的感知能力。代理能够根据退化因子动态调整传感器贡献，并通过线性插值公式实现观测分布向运动模型分布的平滑过渡。为提升跨环境适应性，我们引入了迁移学习模块，有效解决了退化环境下的训练效率问题。通过消融实验，我们验证了模型设计的合理性及迁移学习的关键作用。实验结果表明，与现有最优方法相比，我们的DOA在各类环境中的退化解析与优化能力均表现优异。

> Particle filter-based 2D-SLAM is widely used in indoor localization tasks due to its efficiency. However, indoor environments such as long straight corridors can cause severe degeneracy problems in SLAM. In this paper, we use Proximal Policy Optimization (PPO) to train an adaptive degeneracy optimization agent (DOA) to address degeneracy problem. We propose a systematic methodology to address three critical challenges in traditional supervised learning frameworks: (1) data acquisition bottlenecks in degenerate dataset, (2) inherent quality deterioration of training samples, and (3) ambiguity in annotation protocol design. We design a specialized reward function to guide the agent in developing perception capabilities for degenerate environments. Using the output degeneracy factor as a reference weight, the agent can dynamically adjust the contribution of different sensors to pose optimization. Specifically, the observation distribution is shifted towards the motion model distribution, with the step size determined by a linear interpolation formula related to the degeneracy factor. In addition, we employ a transfer learning module to endow the agent with generalization capabilities across different environments and address the inefficiency of training in degenerate environments. Finally, we conduct ablation studies to demonstrate the rationality of our model design and the role of transfer learning. We also compare the proposed DOA with SOTA methods to prove its superior degeneracy detection and optimization capabilities across various environments.

[Arxiv](https://arxiv.org/abs/2507.19742)