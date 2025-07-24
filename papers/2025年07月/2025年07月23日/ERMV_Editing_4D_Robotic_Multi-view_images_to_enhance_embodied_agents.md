# # 标题  
ERMV：优化4D多视角机器人图像，助力提升具身智能体性能

发布时间：2025年07月23日

`Agent` `机器人` `机器学习`

> ERMV: Editing 4D Robotic Multi-view images to enhance embodied agents

# 摘要

> 机器人模仿学习依赖于4D多视图时序图像，但高昂的数据采集成本和高质量数据的匮乏严重制约了其应用。我们提出了一种名为ER MV的新型数据增强框架，通过单帧编辑和机器人状态条件高效编辑多视图序列。这一任务面临三大挑战：保持动态视角和长时间跨度下的几何与外观一致性、以低计算成本扩展工作窗口、确保关键对象的语义完整性。ER MV通过创新的Epipolar运动感知注意力机制、稀疏时空模块和反馈干预机制，有效应对这些挑战。实验表明，ER MV增强的数据显著提升了VLA模型在模拟与真实环境中的表现。

> Robot imitation learning relies on 4D multi-view sequential images. However, the high cost of data collection and the scarcity of high-quality data severely constrain the generalization and application of embodied intelligence policies like Vision-Language-Action (VLA) models. Data augmentation is a powerful strategy to overcome data scarcity, but methods for editing 4D multi-view sequential images for manipulation tasks are currently lacking. Thus, we propose ERMV (Editing Robotic Multi-View 4D data), a novel data augmentation framework that efficiently edits an entire multi-view sequence based on single-frame editing and robot state conditions. This task presents three core challenges: (1) maintaining geometric and appearance consistency across dynamic views and long time horizons; (2) expanding the working window with low computational costs; and (3) ensuring the semantic integrity of critical objects like the robot arm. ERMV addresses these challenges through a series of innovations. First, to ensure spatio-temporal consistency in motion blur, we introduce a novel Epipolar Motion-Aware Attention (EMA-Attn) mechanism that learns pixel shift caused by movement before applying geometric constraints. Second, to maximize the editing working window, ERMV pioneers a Sparse Spatio-Temporal (STT) module, which decouples the temporal and spatial views and remodels a single-frame multi-view problem through sparse sampling of the views to reduce computational demands. Third, to alleviate error accumulation, we incorporate a feedback intervention Mechanism, which uses a Multimodal Large Language Model (MLLM) to check editing inconsistencies and request targeted expert guidance only when necessary. Extensive experiments demonstrate that ERMV-augmented data significantly boosts the robustness and generalization of VLA models in both simulated and real-world environments.

[Arxiv](https://arxiv.org/abs/2507.17462)