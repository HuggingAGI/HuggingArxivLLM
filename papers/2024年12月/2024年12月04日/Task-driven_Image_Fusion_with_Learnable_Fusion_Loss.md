# 任务驱动的带有可学习融合损失的图像融合

发布时间：2024年12月04日

`其他` `图像融合` `计算机视觉`

> Task-driven Image Fusion with Learnable Fusion Loss

# 摘要

> 多模态图像融合整合了多个传感器源的信息，其视觉质量和感知特性优于任何单一来源，通常能强化下游任务。然而，当下用于下游任务的融合方法仍采用可能与下游任务不匹配的预定义融合目标，限制了自适应引导，降低了模型灵活性。为此，我们提出了任务驱动图像融合（TDFusion），这是一个融合框架，融入了由任务损失引导的可学习融合损失。具体而言，我们的融合损失包含由一个名为损失生成模块的神经网络建模的可学习参数。该模块以元学习的方式接受下游任务损失的监督。在融合模块通过融合损失优化后，学习目标是将融合图像的任务损失最小化。融合模块与损失模块之间的迭代更新确保融合网络朝着最小化任务损失的方向演进，引导融合过程趋向任务目标。TDFusion 的训练仅依赖下游任务的损失，使其能适应任何特定任务，可应用于任何融合和任务网络架构。实验展示了 TDFusion 在融合及相关任务应用中的表现，涵盖四个公共融合数据集、语义分割和对象检测。代码将会公布。

> Multi-modal image fusion aggregates information from multiple sensor sources, achieving superior visual quality and perceptual characteristics compared to any single source, often enhancing downstream tasks. However, current fusion methods for downstream tasks still use predefined fusion objectives that potentially mismatch the downstream tasks, limiting adaptive guidance and reducing model flexibility. To address this, we propose Task-driven Image Fusion (TDFusion), a fusion framework incorporating a learnable fusion loss guided by task loss. Specifically, our fusion loss includes learnable parameters modeled by a neural network called the loss generation module. This module is supervised by the loss of downstream tasks in a meta-learning manner. The learning objective is to minimize the task loss of the fused images, once the fusion module has been optimized by the fusion loss. Iterative updates between the fusion module and the loss module ensure that the fusion network evolves toward minimizing task loss, guiding the fusion process toward the task objectives. TDFusion's training relies solely on the loss of downstream tasks, making it adaptable to any specific task. It can be applied to any architecture of fusion and task networks. Experiments demonstrate TDFusion's performance in both fusion and task-related applications, including four public fusion datasets, semantic segmentation, and object detection. The code will be released.

[Arxiv](https://arxiv.org/abs/2412.03240)