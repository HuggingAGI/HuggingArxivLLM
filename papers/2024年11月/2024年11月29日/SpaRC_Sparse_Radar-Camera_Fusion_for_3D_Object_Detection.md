# SpaRC：用于 3D 物体检测的稀疏雷达与相机融合

发布时间：2024年11月29日

`其他` `自动驾驶` `计算机视觉`

> SpaRC: Sparse Radar-Camera Fusion for 3D Object Detection

# 摘要

> 在这项工作中，我们推出了 SpaRC，这是一款用于 3D 感知的新型稀疏融合变压器，它融合了多视图图像语义以及雷达和相机的点特征。雷达与相机模式的融合已成为自动驾驶系统的高效感知范式。传统方法借助密集的基于鸟瞰图（BEV）的架构来进行深度估计，而当代基于查询的变压器通过以对象为中心的方法在仅相机检测中表现出色。不过，由于隐式深度建模，这些基于查询的方法在误报检测和定位精度上存在局限。我们通过三项关键贡献来应对这些挑战：（1）用于跨模态特征对齐的稀疏截锥体融合（SFF）；（2）用于精确对象定位的距离自适应雷达聚合（RAR）；（3）用于聚焦查询聚合的局部自注意力（LSA）。与需要高强度计算的 BEV 网格渲染的现有方法不同，SpaRC 直接基于编码的点特征运行，在效率和准确性上有显著提升。在 nuScenes 和 TruckScenes 基准上的实证评估显示，SpaRC 大幅超越现有的基于密集 BEV 和基于稀疏查询的探测器。我们的方法达成了 67.1 NDS 和 63.1 AMOTA 的前沿性能指标。代码和预训练模型可在 https://github.com/phi-wol/sparc 获取。

> In this work, we present SpaRC, a novel Sparse fusion transformer for 3D perception that integrates multi-view image semantics with Radar and Camera point features. The fusion of radar and camera modalities has emerged as an efficient perception paradigm for autonomous driving systems. While conventional approaches utilize dense Bird's Eye View (BEV)-based architectures for depth estimation, contemporary query-based transformers excel in camera-only detection through object-centric methodology. However, these query-based approaches exhibit limitations in false positive detections and localization precision due to implicit depth modeling. We address these challenges through three key contributions: (1) sparse frustum fusion (SFF) for cross-modal feature alignment, (2) range-adaptive radar aggregation (RAR) for precise object localization, and (3) local self-attention (LSA) for focused query aggregation. In contrast to existing methods requiring computationally intensive BEV-grid rendering, SpaRC operates directly on encoded point features, yielding substantial improvements in efficiency and accuracy. Empirical evaluations on the nuScenes and TruckScenes benchmarks demonstrate that SpaRC significantly outperforms existing dense BEV-based and sparse query-based detectors. Our method achieves state-of-the-art performance metrics of 67.1 NDS and 63.1 AMOTA. The code and pretrained models are available at https://github.com/phi-wol/sparc.

[Arxiv](https://arxiv.org/abs/2411.19860)