# SeqAffordSplat：基于3D高斯散射的场景级顺序可及性推理方法

发布时间：2025年07月31日

`Agent` `机器人` `3D技术`

> SeqAffordSplat: Scene-level Sequential Affordance Reasoning on 3D Gaussian Splatting

# 摘要

> 3D仿体推理，即将人类指令与3D物体的功能区域相关联的任务，是具身智能体的关键能力。现有的基于3D高斯散射（3DGS）的方法在本质上只能处理单对象、单步骤的交互，这种局限性难以应对复杂现实应用中所需的长时序、多对象任务。为了解决这一问题，我们提出了全新的序列3D高斯仿体推理任务，并构建了SeqAffordSplat这一大规模基准数据集，包含1800+个场景，以支持复杂3DGS环境中长时序仿体理解的研究。随后，我们提出了SeqSplatNet，这是一个端到端的框架，能够直接将指令映射为3D仿体遮罩序列。SeqSplatNet采用一个大语言模型，该模型自回归生成文本，其中穿插着特殊的分割标记，从而引导条件解码器生成对应的三维遮罩。为了处理复杂的场景几何结构，我们引入了一种预训练策略，即条件几何重建，其中模型学习从已知的几何观测中重建完整的仿体区域遮罩，从而构建出强大的几何先验。此外，为了消解语义歧义，我们设计了一种特征注入机制，该机制将来自二维视觉基础模型（VFM）的丰富语义特征提升，并在多个尺度上融合到三维解码器中。大量实验表明，我们的方法在具有挑战性的基准测试中取得了新的最先进水平，有效地推动了仿体推理从单步骤交互迈向场景级别的复杂序列任务。

> 3D affordance reasoning, the task of associating human instructions with the functional regions of 3D objects, is a critical capability for embodied agents. Current methods based on 3D Gaussian Splatting (3DGS) are fundamentally limited to single-object, single-step interactions, a paradigm that falls short of addressing the long-horizon, multi-object tasks required for complex real-world applications. To bridge this gap, we introduce the novel task of Sequential 3D Gaussian Affordance Reasoning and establish SeqAffordSplat, a large-scale benchmark featuring 1800+ scenes to support research on long-horizon affordance understanding in complex 3DGS environments. We then propose SeqSplatNet, an end-to-end framework that directly maps an instruction to a sequence of 3D affordance masks. SeqSplatNet employs a large language model that autoregressively generates text interleaved with special segmentation tokens, guiding a conditional decoder to produce the corresponding 3D mask. To handle complex scene geometry, we introduce a pre-training strategy, Conditional Geometric Reconstruction, where the model learns to reconstruct complete affordance region masks from known geometric observations, thereby building a robust geometric prior. Furthermore, to resolve semantic ambiguities, we design a feature injection mechanism that lifts rich semantic features from 2D Vision Foundation Models (VFM) and fuses them into the 3D decoder at multiple scales. Extensive experiments demonstrate that our method sets a new state-of-the-art on our challenging benchmark, effectively advancing affordance reasoning from single-step interactions to complex, sequential tasks at the scene level.

[Arxiv](https://arxiv.org/abs/2507.23772)