# Ross3D: 融合三维感知的重构视觉指令调优

发布时间：2025年04月02日

`其他` `计算机视觉` `3D视觉`

> Ross3D: Reconstructive Visual Instruction Tuning with 3D-Awareness

# 摘要

> 大型多模态模型（LMMs）在2D图像和视频领域的快速发展激发了将其应用于3D场景解析的热情。然而，大规模3D视觉-语言数据集的缺失成为了主要障碍。为解决这一问题，传统方法主要通过设计3D输入级别的场景表示，将3D感知能力注入到2D LMMs中。本研究提供了一个全新视角：我们引入了具有3D感知能力的重构视觉指令调优方法（Ross3D），将3D感知的视觉监督整合到训练过程中。具体而言，它包含了跨视图和全局视图重构。跨视图重构要求通过聚合其他视图的重叠信息来重构被遮挡的视图；全局视图重构旨在从所有可用视图中聚合信息以恢复鸟瞰图图像，从而为整个场景提供全面概览。实证结果显示，Ross3D在各种3D场景理解基准测试中达到了当前最优水平。更重要的是，我们的半监督实验表明，利用大量未标注的3D视觉数据具有巨大潜力。

> The rapid development of Large Multimodal Models (LMMs) for 2D images and videos has spurred efforts to adapt these models for interpreting 3D scenes. However, the absence of large-scale 3D vision-language datasets has posed a significant obstacle. To address this issue, typical approaches focus on injecting 3D awareness into 2D LMMs by designing 3D input-level scene representations. This work provides a new perspective. We introduce reconstructive visual instruction tuning with 3D-awareness (Ross3D), which integrates 3D-aware visual supervision into the training procedure. Specifically, it incorporates cross-view and global-view reconstruction. The former requires reconstructing masked views by aggregating overlapping information from other views. The latter aims to aggregate information from all available views to recover Bird's-Eye-View images, contributing to a comprehensive overview of the entire scene. Empirically, Ross3D achieves state-of-the-art performance across various 3D scene understanding benchmarks. More importantly, our semi-supervised experiments demonstrate significant potential in leveraging large amounts of unlabeled 3D vision-only data.

[Arxiv](https://arxiv.org/abs/2504.01901)