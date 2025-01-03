# 大型空间模型：端到端无姿态图像到语义3D的转换

发布时间：2024年10月24日

`其他

理由：这篇论文主要讨论的是从少量图像中重建和理解3D结构的问题，提出了大型空间模型（LSM）来处理未定位的RGB图像并生成语义辐射场。虽然论文中提到了Transformer架构和语言交互生成标签图，但其核心内容集中在计算机视觉领域的3D重建和语义理解，并不直接涉及Agent、RAG、LLM应用或LLM理论。因此，将其分类为“其他”更为合适。` `计算机视觉` `3D重建`

> Large Spatial Model: End-to-end Unposed Images to Semantic 3D

# 摘要

> # 摘要
从少量图像中重建和理解3D结构是计算机视觉领域的经典问题。传统方法通常将其分解为多个子任务，涉及复杂的数据表示转换。例如，通过运动结构（SfM）进行密集重建需要将图像转换为关键点、优化相机参数并估计结构，随后进行稀疏重建以支持密集建模，最终输入到特定任务的神经网络中。这一多步骤过程不仅耗时，还增加了工程复杂度。
本文提出的大型空间模型（LSM）直接将未定位的RGB图像处理成语义辐射场。LSM在一次前馈操作中同时估计几何、外观和语义，并能在新视角下与语言交互生成多功能标签图。基于Transformer架构，LSM通过像素对齐的点图整合全局几何信息。为了提升空间属性回归的精度，我们引入了局部上下文聚合与多尺度融合，显著改善了局部细节的准确性。针对标记3D语义数据稀缺的问题，我们将预训练的2D语言分割模型集成到3D一致的语义特征场中，并通过高效的解码器参数化语义各向异性高斯，实现了端到端的监督学习。大量实验表明，LSM直接从未定位图像中统一了多个3D视觉任务，首次实现了实时的语义3D重建。

> Reconstructing and understanding 3D structures from a limited number of images is a well-established problem in computer vision. Traditional methods usually break this task into multiple subtasks, each requiring complex transformations between different data representations. For instance, dense reconstruction through Structure-from-Motion (SfM) involves converting images into key points, optimizing camera parameters, and estimating structures. Afterward, accurate sparse reconstructions are required for further dense modeling, which is subsequently fed into task-specific neural networks. This multi-step process results in considerable processing time and increased engineering complexity.
  In this work, we present the Large Spatial Model (LSM), which processes unposed RGB images directly into semantic radiance fields. LSM simultaneously estimates geometry, appearance, and semantics in a single feed-forward operation, and it can generate versatile label maps by interacting with language at novel viewpoints. Leveraging a Transformer-based architecture, LSM integrates global geometry through pixel-aligned point maps. To enhance spatial attribute regression, we incorporate local context aggregation with multi-scale fusion, improving the accuracy of fine local details. To tackle the scarcity of labeled 3D semantic data and enable natural language-driven scene manipulation, we incorporate a pre-trained 2D language-based segmentation model into a 3D-consistent semantic feature field. An efficient decoder then parameterizes a set of semantic anisotropic Gaussians, facilitating supervised end-to-end learning. Extensive experiments across various tasks show that LSM unifies multiple 3D vision tasks directly from unposed images, achieving real-time semantic 3D reconstruction for the first time.

[Arxiv](https://arxiv.org/abs/2410.18956)