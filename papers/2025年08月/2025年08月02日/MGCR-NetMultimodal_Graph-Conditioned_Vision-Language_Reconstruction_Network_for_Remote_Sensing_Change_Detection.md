# MGCR-Net:面向遥感变化检测的多模态图引导视觉语言重建网络

发布时间：2025年08月02日

`LLM应用` `计算机视觉`

> MGCR-Net:Multimodal Graph-Conditioned Vision-Language Reconstruction Network for Remote Sensing Change Detection

# 摘要

> 随着遥感卫星技术的进步和深度学习的快速发展，遥感变化检测（RSCD）已成为区域监测的重要技术手段。传统变化检测（CD）方法和基于深度学习的方法在变化分析与检测方面做出了巨大贡献，然而在多模态数据的探索与应用方面仍存在局限。为此，我们提出了一种多模态图条件视觉语言重构网络（MGCR-Net），以进一步挖掘多模态数据的语义交互潜力。多模态大型语言模型（MLLM）凭借其在计算机视觉领域的卓越表现，尤其是强大的视觉语言理解和对话交互能力，受到了广泛关注。具体来说，我们设计了一种基于MLLM的优化策略，从原始CD图像中生成多模态文本数据，作为MGCR的文本输入。通过双编码器框架提取视觉和文本特征。在RSCD任务中首次引入了多模态图条件视觉语言重构机制，并结合图注意力构建了语义图条件重构模块（SGCM），该模块通过基于图的条件生成视觉语言（VL）令牌，并通过多头注意力实现视觉和文本特征之间的跨维交互。最后，通过语言视觉变压器（LViT）对重构的VL特征进行深度融合，实现细粒度特征对齐和高层次语义交互。在四个公共数据集上的实验结果表明，MGCR在性能上优于主流的CD方法。我们的代码可在https://github.com/cn-xvkong/MGCR获取

> With the advancement of remote sensing satellite technology and the rapid progress of deep learning, remote sensing change detection (RSCD) has become a key technique for regional monitoring. Traditional change detection (CD) methods and deep learning-based approaches have made significant contributions to change analysis and detection, however, many outstanding methods still face limitations in the exploration and application of multimodal data. To address this, we propose the multimodal graph-conditioned vision-language reconstruction network (MGCR-Net) to further explore the semantic interaction capabilities of multimodal data. Multimodal large language models (MLLM) have attracted widespread attention for their outstanding performance in computer vision, particularly due to their powerful visual-language understanding and dialogic interaction capabilities. Specifically, we design a MLLM-based optimization strategy to generate multimodal textual data from the original CD images, which serve as textual input to MGCR. Visual and textual features are extracted through a dual encoder framework. For the first time in the RSCD task, we introduce a multimodal graph-conditioned vision-language reconstruction mechanism, which is integrated with graph attention to construct a semantic graph-conditioned reconstruction module (SGCM), this module generates vision-language (VL) tokens through graph-based conditions and enables cross-dimensional interaction between visual and textual features via multihead attention. The reconstructed VL features are then deeply fused using the language vision transformer (LViT), achieving fine-grained feature alignment and high-level semantic interaction. Experimental results on four public datasets demonstrate that MGCR achieves superior performance compared to mainstream CD methods. Our code is available on https://github.com/cn-xvkong/MGCR

[Arxiv](https://arxiv.org/abs/2508.01555)