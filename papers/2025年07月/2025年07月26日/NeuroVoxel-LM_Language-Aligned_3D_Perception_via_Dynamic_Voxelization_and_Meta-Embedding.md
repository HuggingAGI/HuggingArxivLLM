# NeuroVoxel-LM：基于动态体素化和元嵌入的三维语言对齐感知

发布时间：2025年07月26日

`LLM应用` `计算机视觉`

> NeuroVoxel-LM: Language-Aligned 3D Perception via Dynamic Voxelization and Meta-Embedding

# 摘要

> 视觉语言模型（VLMs）和多模态大语言模型（MLLMs）的近期突破显著推动了基于语言驱动的3D场景感知能力。然而，现有3D语言模型在处理大规模稀疏点云时面临特征提取速度慢和表征精度有限的挑战。为解决这些问题，我们提出NeuroVoxel-LM，一个将NeRF（神经辐射场）与动态分辨率体素化和轻量级元嵌入相结合的新框架。具体而言，我们引入了动态分辨率多尺度体素化（DR-MSV）技术，该技术能够根据几何和结构复杂度自适应调整体素粒度，在保持重建保真度的同时显著降低计算成本。此外，我们提出了基于注意力加权和残差融合的轻量级元嵌入自适应池化机制（TAP-LME），以增强语义表征能力。实验结果表明，DR-MSV显著提升了点云特征提取的效率和精度，而TAP-LME在从NeRF权重中捕获细粒度语义方面优于传统的最大池化方法。

> Recent breakthroughs in Visual Language Models (VLMs) and Multimodal Large Language Models (MLLMs) have significantly advanced 3D scene perception towards language-driven cognition. However, existing 3D language models struggle with sparse, large-scale point clouds due to slow feature extraction and limited representation accuracy. To address these challenges, we propose NeuroVoxel-LM, a novel framework that integrates Neural Radiance Fields (NeRF) with dynamic resolution voxelization and lightweight meta-embedding. Specifically, we introduce a Dynamic Resolution Multiscale Voxelization (DR-MSV) technique that adaptively adjusts voxel granularity based on geometric and structural complexity, reducing computational cost while preserving reconstruction fidelity. In addition, we propose the Token-level Adaptive Pooling for Lightweight Meta-Embedding (TAP-LME) mechanism, which enhances semantic representation through attention-based weighting and residual fusion. Experimental results demonstrate that DR-MSV significantly improves point cloud feature extraction efficiency and accuracy, while TAP-LME outperforms conventional max-pooling in capturing fine-grained semantics from NeRF weights.

[Arxiv](https://arxiv.org/abs/2507.20110)