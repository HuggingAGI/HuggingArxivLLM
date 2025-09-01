# Long-VLA：赋能视觉语言动作模型，解锁机器人操作的长程能力

发布时间：2025年08月28日

`Agent` `工业与制造`

> Long-VLA: Unleashing Long-Horizon Capability of Vision Language Action Model for Robot Manipulation

# 摘要

> 视觉-语言-动作（VLA）模型已成为机器人策略学习的核心，它借助大规模多模态数据实现了鲁棒且可扩展的控制。然而，现有VLA框架主要面向短视域任务，在长视域、多步骤机器人操作中效果有限，这主要受限于技能链衔接和子任务依赖的难题。为此，我们提出Long-VLA——首个专为长视域机器人任务设计的端到端VLA模型。我们的方法核心在于一种新颖的相位感知输入掩码策略：它能自适应地将每个子任务划分为移动阶段与交互阶段，使模型聚焦于相位相关的感官线索，同时提升子任务间的兼容性。这种统一策略既保留了VLA训练的可扩展性与数据效率，我们提出的架构无关模块还能无缝集成至现有VLA模型中。我们还构建了L-CALVIN基准，用于系统评估长视域操作任务。在模拟与真实场景任务中的大量实验表明，Long-VLA显著优于现有最优方法，为长视域机器人控制树立了新基准。

> Vision-Language-Action (VLA) models have become a cornerstone in robotic policy learning, leveraging large-scale multimodal data for robust and scalable control. However, existing VLA frameworks primarily address short-horizon tasks, and their effectiveness on long-horizon, multi-step robotic manipulation remains limited due to challenges in skill chaining and subtask dependencies. In this work, we introduce Long-VLA, the first end-to-end VLA model specifically designed for long-horizon robotic tasks. Our approach features a novel phase-aware input masking strategy that adaptively segments each subtask into moving and interaction phases, enabling the model to focus on phase-relevant sensory cues and enhancing subtask compatibility. This unified strategy preserves the scalability and data efficiency of VLA training, and our architecture-agnostic module can be seamlessly integrated into existing VLA models. We further propose the L-CALVIN benchmark to systematically evaluate long-horizon manipulation. Extensive experiments on both simulated and real-world tasks demonstrate that Long-VLA significantly outperforms prior state-of-the-art methods, establishing a new baseline for long-horizon robotic control.

[Arxiv](https://arxiv.org/abs/2508.19958)