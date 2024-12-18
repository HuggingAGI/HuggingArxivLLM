# CATSplat：带有空间引导的上下文感知 Transformer ，用于从单视图图像实现通用的 3D 高斯 Splatting

发布时间：2024年12月17日

`其他` `3D 场景重建` `计算机视觉`

> CATSplat: Context-Aware Transformer with Spatial Guidance for Generalizable 3D Gaussian Splatting from A Single-View Image

# 摘要

> 最近，基于 3D 高斯喷溅的可泛化前馈方法因具备用有限资源重建 3D 场景的潜力而备受瞩目。这些方法仅通过一次前向传递中的少量图像，就能创建出由每个像素的 3D 高斯基元参数化的 3D 辐射场。然而，与得益于跨视图对应关系的多视图方法不同，利用单视图图像进行 3D 场景重建仍是一个有待深入探索的领域。在本研究中，我们推出了 CATSplat，这是一个新颖的基于可泛化变压器的框架，旨在打破单目设置中的固有局限。首先，我们建议借助来自视觉语言模型的文本引导，来弥补单张图像信息的不足。通过交叉注意力将来自文本嵌入的特定场景上下文细节融入其中，为不单纯依赖视觉线索的上下文感知 3D 场景重建开辟了道路。此外，我们提倡在单视图环境下利用来自 3D 点特征的空间引导，以达成全面的几何理解。凭借 3D 先验，图像特征能够捕捉丰富的结构洞察，在无需多视图技术的情况下预测 3D 高斯。在大规模数据集上开展的大量实验表明，CATSplat 在单视图 3D 场景重建及高质量新视图合成方面表现出了最先进的性能。

> Recently, generalizable feed-forward methods based on 3D Gaussian Splatting have gained significant attention for their potential to reconstruct 3D scenes using finite resources. These approaches create a 3D radiance field, parameterized by per-pixel 3D Gaussian primitives, from just a few images in a single forward pass. However, unlike multi-view methods that benefit from cross-view correspondences, 3D scene reconstruction with a single-view image remains an underexplored area. In this work, we introduce CATSplat, a novel generalizable transformer-based framework designed to break through the inherent constraints in monocular settings. First, we propose leveraging textual guidance from a visual-language model to complement insufficient information from a single image. By incorporating scene-specific contextual details from text embeddings through cross-attention, we pave the way for context-aware 3D scene reconstruction beyond relying solely on visual cues. Moreover, we advocate utilizing spatial guidance from 3D point features toward comprehensive geometric understanding under single-view settings. With 3D priors, image features can capture rich structural insights for predicting 3D Gaussians without multi-view techniques. Extensive experiments on large-scale datasets demonstrate the state-of-the-art performance of CATSplat in single-view 3D scene reconstruction with high-quality novel view synthesis.

[Arxiv](https://arxiv.org/abs/2412.12906)