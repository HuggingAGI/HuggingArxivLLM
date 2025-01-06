# PG-SAG: 基于语义感知分组的并行高斯泼溅技术，助力细粒度大规模城市建筑重建

发布时间：2025年01月03日

`其他

理由：这篇论文主要讨论的是3D高斯泼溅（3DGS）技术及其在大规模城市区域建筑表面重建中的应用。虽然论文中提到了使用跨模态模型Language Segment Anything进行建筑掩码分割，但整体内容主要集中在计算机视觉和3D重建领域，与Agent、RAG、LLM应用、LLM理论等分类关系不大。因此，将其分类为“其他”更为合适。` `计算机视觉` `城市重建`

> PG-SAG: Parallel Gaussian Splatting for Fine-Grained Large-Scale Urban Buildings Reconstruction via Semantic-Aware Grouping

# 摘要

> # 3D 高斯泼溅 (3DGS) 已成为实时新视图合成领域的革命性方法。基于 3DGS，最新进展通过空间分区策略应对大规模场景，显著降低了显存和优化时间成本。本文提出了一种并行高斯泼溅方法 PG-SAG，充分利用语义线索进行分区和高斯核优化，实现了大规模城市区域的细粒度建筑表面重建，且无需降低原始图像分辨率。首先，利用跨模态模型 Language Segment Anything 分割建筑掩码。然后，根据注册图像中的可见性检查，将分割的建筑区域分组为子区域，并并行优化这些子区域的高斯核。此外，针对掩码边缘重新设计了法线损失，以减轻边缘法线向量的模糊性。最后，为优化 3D 高斯，我们引入了梯度约束的负载均衡损失，该损失考虑了场景复杂性，有效减少了像素并行渲染阶段的线程等待时间和重建损失。我们在多个城市数据集上进行了广泛实验，结果表明，与多种最先进的基于 3DGS 的方法相比，PG-SAG 在建筑表面重建方面表现卓越。项目网址：https://github.com/TFWang-9527/PG-SAG。

> 3D Gaussian Splatting (3DGS) has emerged as a transformative method in the field of real-time novel synthesis. Based on 3DGS, recent advancements cope with large-scale scenes via spatial-based partition strategy to reduce video memory and optimization time costs. In this work, we introduce a parallel Gaussian splatting method, termed PG-SAG, which fully exploits semantic cues for both partitioning and Gaussian kernel optimization, enabling fine-grained building surface reconstruction of large-scale urban areas without downsampling the original image resolution. First, the Cross-modal model - Language Segment Anything is leveraged to segment building masks. Then, the segmented building regions is grouped into sub-regions according to the visibility check across registered images. The Gaussian kernels for these sub-regions are optimized in parallel with masked pixels. In addition, the normal loss is re-formulated for the detected edges of masks to alleviate the ambiguities in normal vectors on edges. Finally, to improve the optimization of 3D Gaussians, we introduce a gradient-constrained balance-load loss that accounts for the complexity of the corresponding scenes, effectively minimizing the thread waiting time in the pixel-parallel rendering stage as well as the reconstruction lost. Extensive experiments are tested on various urban datasets, the results demonstrated the superior performance of our PG-SAG on building surface reconstruction, compared to several state-of-the-art 3DGS-based methods. Project Web:https://github.com/TFWang-9527/PG-SAG.

[Arxiv](https://arxiv.org/abs/2501.01677)