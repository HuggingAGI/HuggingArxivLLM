# HoloDrive：用于自动驾驶的全方位 2D - 3D 多模态街道场景生成

发布时间：2024年12月03日

`其他` `自动驾驶` `图像生成`

> HoloDrive: Holistic 2D-3D Multi-Modal Street Scene Generation for Autonomous Driving

# 摘要

> 生成式模型极大地提升了自动驾驶中相机图像或激光雷达点云的生成与预测质量。然而，实际的自动驾驶系统会运用多种输入模态，通常为相机和激光雷达，它们包含着互补的生成信息，可现有的生成方法却忽略了这一关键特性，致使生成结果仅涵盖单独的 2D 或 3D 信息。为填补自动驾驶中 2D - 3D 多模态联合生成的空缺，在本文中，我们提出了名为\emph{HoloDrive}的框架，用于共同生成相机图像和激光雷达点云。我们在异构生成模型之间采用了 BEV - to - Camera 和 Camera - to - BEV 转换模块，并在 2D 生成模型中引入深度预测分支，以消除从图像空间到 BEV 空间未投影的歧义，随后通过添加时间结构和精心设计的渐进训练将该方法拓展至预测未来。此外，我们针对单帧生成和世界模型基准开展了实验，且证明我们的方法在生成指标方面较 SOTA 方法有显著的性能提升。

> Generative models have significantly improved the generation and prediction quality on either camera images or LiDAR point clouds for autonomous driving. However, a real-world autonomous driving system uses multiple kinds of input modality, usually cameras and LiDARs, where they contain complementary information for generation, while existing generation methods ignore this crucial feature, resulting in the generated results only covering separate 2D or 3D information. In order to fill the gap in 2D-3D multi-modal joint generation for autonomous driving, in this paper, we propose our framework, \emph{HoloDrive}, to jointly generate the camera images and LiDAR point clouds. We employ BEV-to-Camera and Camera-to-BEV transform modules between heterogeneous generative models, and introduce a depth prediction branch in the 2D generative model to disambiguate the un-projecting from image space to BEV space, then extend the method to predict the future by adding temporal structure and carefully designed progressive training. Further, we conduct experiments on single frame generation and world model benchmarks, and demonstrate our method leads to significant performance gains over SOTA methods in terms of generation metrics.

[Arxiv](https://arxiv.org/abs/2412.01407)