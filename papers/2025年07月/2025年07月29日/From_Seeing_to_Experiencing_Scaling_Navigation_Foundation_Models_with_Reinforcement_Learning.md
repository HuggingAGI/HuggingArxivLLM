# 从看见到感知：强化学习助力导航基础模型的扩展

发布时间：2025年07月29日

`Agent` `智能体导航`

> From Seeing to Experiencing: Scaling Navigation Foundation Models with Reinforcement Learning

# 摘要

> 导航基础模型通过海量网络数据的训练，使智能体能跨不同环境和具身化实现泛化。然而，仅基于离线数据训练的模型，往往缺乏对行动后果的推理能力或通过反事实理解进行适应的能力。这使得它们在现实世界的城市导航中面临重大挑战，尤其是在需要交互式和安全行为（如避开障碍物和行人）的关键场景中。

为应对这些挑战，我们提出了 Seeing-to-Experiencing（S2E）框架，通过强化学习扩展导航基础模型的能力。S2E 结合了视频预训练和强化学习的优势，既保留了大规模真实世界视频带来的泛化能力，又通过仿真环境中的强化学习增强了交互性。

具体而言，我们引入了两项创新：
1. 基于锚点的分布匹配策略（Anchor-Guided Distribution Matching），通过基于锚点的监督学习稳定训练并建模多样化运动模式。
2. 残差注意力模块（Residual-Attention Module），从仿真环境中获取反应性行为，同时保留预训练知识。

此外，我们建立了 NavBench-GS，一个基于现实场景高保真 3D 重建的全面端到端评估基准，结合了物理交互，可系统评估导航模型的泛化和安全性。

大量实验表明，S2E 减轻了仅依赖离线数据扩展时的收益递减现象。我们还全面分析了强化学习与监督微调在机器人学习后训练中的优势。研究发现强调了将交互式在线体验整合到机器人基础模型扩展中的关键作用。


> Navigation foundation models trained on massive webscale data enable agents to generalize across diverse environments and embodiments. However, these models trained solely on offline data, often lack the capacity to reason about the consequences of their actions or adapt through counterfactual understanding. They thus face significant limitations in the real-world urban navigation where interactive and safe behaviors, such as avoiding obstacles and moving pedestrians, are critical. To tackle these challenges, we introduce the Seeing-to-Experiencing framework to scale the capability of navigation foundation models with reinforcement learning. S2E combines the strengths of pre-training on videos and post-training through RL. It maintains the generalizability acquired from large-scale real-world videos while enhancing its interactivity through RL in simulation environments. Specifically, we introduce two innovations: an Anchor-Guided Distribution Matching strategy, which stabilizes learning and models diverse motion patterns through anchor-based supervision; and a Residual-Attention Module, which obtains reactive behaviors from simulation environments without erasing the model's pretrained knowledge. Moreover, we establish a comprehensive end-to-end evaluation benchmark, NavBench-GS, built on photorealistic 3DGS reconstructions of real-world scenes that incorporate physical interactions. It can systematically assess the generalizability and safety of navigation foundation models. Extensive experiments show that S2E mitigates the diminishing returns often seen when scaling with offline data alone. We perform a thorough analysis of the benefits of Reinforcement Learning compared to Supervised Fine-Tuning in the context of post-training for robot learning. Our findings emphasize the crucial role of integrating interactive online experiences to effectively scale foundation models in Robotics.

[Arxiv](https://arxiv.org/abs/2507.22028)