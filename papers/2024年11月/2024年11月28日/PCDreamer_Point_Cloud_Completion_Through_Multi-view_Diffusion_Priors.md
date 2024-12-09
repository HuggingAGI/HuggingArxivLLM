# PCDreamer：借助多视图扩散先验实现点云的完成

发布时间：2024年11月28日

`其他` `计算机视觉` `点云处理`

> PCDreamer: Point Cloud Completion Through Multi-view Diffusion Priors

# 摘要

> 这篇论文呈现了 PCDreamer，一种全新的点云补全之法。传统手段通常从局部点云提取特征以预测缺失区域，然而庞大的解空间常常致使结果不尽人意。较新的方法已开始将图像用作额外引导，切实提升了性能，可在实际中获取图像与局部点云的配对数据颇具难度。为突破这些局限，我们借助大型模型中相对视图一致的多视图扩散先验，生成所需形状的新视图。由此得到的图像集编码了全局和局部的形状线索，这对形状补全极为有利。为充分利用先验，我们设计了一个形状融合模块，用于从多模态输入（比如图像和点云）生成初始完整形状，还有一个后续的形状整合模块，通过舍弃由扩散先验的不一致引入的不可靠点，从而得到最终的完整形状。大量实验结果表明，我们的性能出色，尤其在恢复精细细节方面。

> This paper presents PCDreamer, a novel method for point cloud completion. Traditional methods typically extract features from partial point clouds to predict missing regions, but the large solution space often leads to unsatisfactory results. More recent approaches have started to use images as extra guidance, effectively improving performance, but obtaining paired data of images and partial point clouds is challenging in practice. To overcome these limitations, we harness the relatively view-consistent multi-view diffusion priors within large models, to generate novel views of the desired shape. The resulting image set encodes both global and local shape cues, which is especially beneficial for shape completion. To fully exploit the priors, we have designed a shape fusion module for producing an initial complete shape from multi-modality input (\ie, images and point clouds), and a follow-up shape consolidation module to obtain the final complete shape by discarding unreliable points introduced by the inconsistency from diffusion priors. Extensive experimental results demonstrate our superior performance, especially in recovering fine details.

[Arxiv](https://arxiv.org/abs/2411.19036)