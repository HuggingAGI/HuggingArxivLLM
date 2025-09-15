# DGFusion：深度引导的传感器融合实现鲁棒语义感知

发布时间：2025年09月11日

`其他` `交通运输`

> DGFusion: Depth-Guided Sensor Fusion for Robust Semantic Perception

# 摘要

> 自动驾驶车辆要实现鲁棒的语义感知，需有效融合多个优势互补的传感器。然而，当前主流的语义感知传感器融合方法往往在输入的整个空间范围内统一处理数据，这在复杂环境下会严重制约性能。为此，我们提出一种新颖的深度引导多模态融合方法，通过融入深度信息来改进条件感知融合机制。我们的网络DGFusion将多模态分割转化为多任务学习问题：利用户外传感器套件中常见的激光雷达数据——既将其作为模型输入，又作为深度学习的真值。我们设计了辅助深度头来提取深度感知特征，这些特征被编码为空间动态变化的局部深度令牌，用于调节注意力跨模态融合过程。这些局部令牌与全局条件令牌协同工作，能动态调整传感器融合策略，以适应场景中各传感器随空间变化的可靠性（这种可靠性很大程度上由深度决定）。此外，我们还为深度学习设计了鲁棒损失函数，这对于从激光雷达输入中学习至关重要——在恶劣条件下，激光雷达数据往往稀疏且噪声较大。在具有挑战性的MUSES和DELIVER数据集上，我们的方法实现了全景分割和语义分割的最先进性能。相关代码和模型将开源于https://github.com/timbroed/DGFusion。

> Robust semantic perception for autonomous vehicles relies on effectively combining multiple sensors with complementary strengths and weaknesses. State-of-the-art sensor fusion approaches to semantic perception often treat sensor data uniformly across the spatial extent of the input, which hinders performance when faced with challenging conditions. By contrast, we propose a novel depth-guided multimodal fusion method that upgrades condition-aware fusion by integrating depth information. Our network, DGFusion, poses multimodal segmentation as a multi-task problem, utilizing the lidar measurements, which are typically available in outdoor sensor suites, both as one of the model's inputs and as ground truth for learning depth. Our corresponding auxiliary depth head helps to learn depth-aware features, which are encoded into spatially varying local depth tokens that condition our attentive cross-modal fusion. Together with a global condition token, these local depth tokens dynamically adapt sensor fusion to the spatially varying reliability of each sensor across the scene, which largely depends on depth. In addition, we propose a robust loss for our depth, which is essential for learning from lidar inputs that are typically sparse and noisy in adverse conditions. Our method achieves state-of-the-art panoptic and semantic segmentation performance on the challenging MUSES and DELIVER datasets. Code and models will be available at https://github.com/timbroed/DGFusion

[Arxiv](https://arxiv.org/abs/2509.09828)