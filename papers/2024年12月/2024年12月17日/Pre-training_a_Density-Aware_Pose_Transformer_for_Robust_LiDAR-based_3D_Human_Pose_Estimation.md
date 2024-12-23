# 预训练一个用于基于稳健激光雷达的 3D 人体姿态估计的密度感知姿态变换模型

发布时间：2024年12月17日

`其他` `自动驾驶` `人体姿态估计`

> Pre-training a Density-Aware Pose Transformer for Robust LiDAR-based 3D Human Pose Estimation

# 摘要

> 随着自动驾驶的迅猛发展，基于激光雷达的 3D 人体姿态估计（3D HPE）逐渐成为研究热点。然而，鉴于激光雷达采集的点云存在噪声和稀疏性，稳健的人体姿态估计仍颇具挑战。现有的多数方法借助时间信息、多模态融合或 SMPL 优化来校正有偏差的结果。在本研究中，我们尝试仅通过对低质量点云的内在特性建模来为 3D HPE 获取充足信息。于是，提出了一种简洁且强大的方法，为点云的建模和增强提供了思路。具体而言，我们先是提出了一个简洁有效的密度感知姿态转换器（DAPT），以获取稳定的关键点表征。通过运用一组关节锚点和精心设计的交换模块，从不同密度的点云中提取有效信息。接着利用 1D 热图来呈现关键点的精确位置。其次，提出了一种全面的激光雷达人体合成与增强方法来预训练模型，使其能够获得更优的人体先验。我们通过随机采样人体位置和方向，并通过添加激光级掩码模拟遮挡来增加点云的多样性。在多个数据集上开展了广泛的实验，包括 IMU 标注的 LidarHuman26M、SLOPER4D 以及手动标注的 Waymo Open Dataset v2.0（Waymo）、HumanM3。我们的方法在所有场景中均展现出了 SOTA 性能。特别地，与 Waymo 上的 LPFormer 相比，我们将平均 MPJPE 降低了 10.0 毫米。与 SLOPER4D 上的 PRN 相比，我们显著将平均 MPJPE 降低了 20.7 毫米。

> With the rapid development of autonomous driving, LiDAR-based 3D Human Pose Estimation (3D HPE) is becoming a research focus. However, due to the noise and sparsity of LiDAR-captured point clouds, robust human pose estimation remains challenging. Most of the existing methods use temporal information, multi-modal fusion, or SMPL optimization to correct biased results. In this work, we try to obtain sufficient information for 3D HPE only by modeling the intrinsic properties of low-quality point clouds. Hence, a simple yet powerful method is proposed, which provides insights both on modeling and augmentation of point clouds. Specifically, we first propose a concise and effective density-aware pose transformer (DAPT) to get stable keypoint representations. By using a set of joint anchors and a carefully designed exchange module, valid information is extracted from point clouds with different densities. Then 1D heatmaps are utilized to represent the precise locations of the keypoints. Secondly, a comprehensive LiDAR human synthesis and augmentation method is proposed to pre-train the model, enabling it to acquire a better human body prior. We increase the diversity of point clouds by randomly sampling human positions and orientations and by simulating occlusions through the addition of laser-level masks. Extensive experiments have been conducted on multiple datasets, including IMU-annotated LidarHuman26M, SLOPER4D, and manually annotated Waymo Open Dataset v2.0 (Waymo), HumanM3. Our method demonstrates SOTA performance in all scenarios. In particular, compared with LPFormer on Waymo, we reduce the average MPJPE by $10.0mm$. Compared with PRN on SLOPER4D, we notably reduce the average MPJPE by $20.7mm$.

[Arxiv](https://arxiv.org/abs/2412.13454)