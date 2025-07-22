# 受益于参考：检索增强的跨模态点云补全

发布时间：2025年07月19日

`其他` `计算机视觉` `3D建模`

> Benefit from Reference: Retrieval-Augmented Cross-modal Point Cloud Completion

# 摘要

> 基于不完整点云完成3D结构是一项极具挑战性的任务，尤其是当剩余点云缺乏典型结构特征时。近年来，基于跨模态学习的方法尝试引入实例图像来辅助结构特征学习，但这些方法仍局限于特定输入类别，限制了其生成能力。在本研究中，我们提出了一种新型检索增强点云完成框架。该框架的核心思想是通过跨模态检索从相似参考样本中学习结构先验信息。具体来说，我们设计了一种结构共享特征编码器（SSFE），用于联合提取跨模态特征并重建参考特征作为先验。得益于编码器中双通道控制门的机制，参考样本中的相关结构特征得到增强，而无关信息干扰被抑制。此外，我们提出了一种渐进式检索增强生成器（PRAG），采用层次化特征融合机制，从全局到局部将参考先验信息与输入特征相结合。通过在多个数据集和真实场景中的广泛评估，我们的方法在生成精细点云方面表现出色，并在处理稀疏数据和未见类别方面展现了良好的泛化能力。

> Completing the whole 3D structure based on an incomplete point cloud is a challenging task, particularly when the residual point cloud lacks typical structural characteristics. Recent methods based on cross-modal learning attempt to introduce instance images to aid the structure feature learning. However, they still focus on each particular input class, limiting their generation abilities. In this work, we propose a novel retrieval-augmented point cloud completion framework. The core idea is to incorporate cross-modal retrieval into completion task to learn structural prior information from similar reference samples. Specifically, we design a Structural Shared Feature Encoder (SSFE) to jointly extract cross-modal features and reconstruct reference features as priors. Benefiting from a dual-channel control gate in the encoder, relevant structural features in the reference sample are enhanced and irrelevant information interference is suppressed. In addition, we propose a Progressive Retrieval-Augmented Generator (PRAG) that employs a hierarchical feature fusion mechanism to integrate reference prior information with input features from global to local. Through extensive evaluations on multiple datasets and real-world scenes, our method shows its effectiveness in generating fine-grained point clouds, as well as its generalization capability in handling sparse data and unseen categories.

[Arxiv](https://arxiv.org/abs/2507.14485)