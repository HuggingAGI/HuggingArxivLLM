# 基于多模态变压器的低光图像增强模型：ModalFormer

发布时间：2025年07月27日

`其他` `图像处理` `计算机视觉`

> ModalFormer: Multimodal Transformer for Low-Light Image Enhancement

# 摘要

> # 摘要  
低光图像增强（LLIE）是一项基础且具挑战性的任务，因低光照条件下拍摄的图像常伴有噪声、细节缺失及对比度不足等问题。现有方法多仅依赖RGB图像的像素级变换，忽视了多视觉模态的丰富上下文信息。本文提出ModalFormer，首个大规模多模态低光图像增强框架，通过充分利用九种辅助模态实现当前最优性能。  
我们的模型包含两大核心组件：跨模态变压器（CM-T），专为修复受损图像并无缝整合多模态信息设计；以及多个辅助子网络，专注于多模态特征重构。CM-T的核心创新在于跨模态多头自注意力机制（CM-MSA），该机制能够高效融合RGB数据与特定模态特征（包括深度特征嵌入、分割信息、几何线索及颜色信息），生成信息丰富的混合注意力图。  
在多个基准数据集上的大量实验验证了ModalFormer在低光图像增强任务中的卓越性能。预训练模型及实验结果已开源，可在https://github.com/albrateanu/ModalFormer获取。

> Low-light image enhancement (LLIE) is a fundamental yet challenging task due to the presence of noise, loss of detail, and poor contrast in images captured under insufficient lighting conditions. Recent methods often rely solely on pixel-level transformations of RGB images, neglecting the rich contextual information available from multiple visual modalities. In this paper, we present ModalFormer, the first large-scale multimodal framework for LLIE that fully exploits nine auxiliary modalities to achieve state-of-the-art performance. Our model comprises two main components: a Cross-modal Transformer (CM-T) designed to restore corrupted images while seamlessly integrating multimodal information, and multiple auxiliary subnetworks dedicated to multimodal feature reconstruction. Central to the CM-T is our novel Cross-modal Multi-headed Self-Attention mechanism (CM-MSA), which effectively fuses RGB data with modality-specific features--including deep feature embeddings, segmentation information, geometric cues, and color information--to generate information-rich hybrid attention maps. Extensive experiments on multiple benchmark datasets demonstrate ModalFormer's state-of-the-art performance in LLIE. Pre-trained models and results are made available at https://github.com/albrateanu/ModalFormer.

[Arxiv](https://arxiv.org/abs/2507.20388)