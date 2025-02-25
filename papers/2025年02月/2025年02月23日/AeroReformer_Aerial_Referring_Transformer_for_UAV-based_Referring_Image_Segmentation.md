# AeroReformer：用于无人机引用图像分割的航空引用变换器

发布时间：2025年02月23日

`LLM应用` `无人机` `计算机视觉`

> AeroReformer: Aerial Referring Transformer for UAV-based Referring Image Segmentation

# 摘要

> 参考分割是一项结合计算机视觉与自然语言处理的新颖任务，能够根据文本描述精准定位并分割目标。尽管自然图像领域的参考图像分割（RIS）已获广泛关注，但针对无人机（UAV）拍摄的航拍图像，相关研究仍显不足。无人机图像的复杂空间尺度、频繁的遮挡问题及多变的目标朝向，使得现有RIS方法难以应对。现有数据集的匮乏更是加剧了这一困境，因为手动标注像素级掩膜并生成文本描述耗时费力。为突破这一瓶颈，我们开发了一个自动标注管道，利用现有无人机分割数据集，并结合多模态大型语言模型（MLLM）生成文本描述。我们还提出了全新框架——空参考变压器（AeroReformer），专为无人机参考图像分割（UAV-RIS）设计。该框架配备视觉语言交叉注意力模块（VLCAM），实现高效的跨模态理解，同时搭载旋转感知多尺度融合（RAMSF）解码器，显著提升航拍场景的分割精度。在两个新开发的数据集上的实验表明，AeroReformer超越现有方法，为UAV-RIS领域树立了新的基准。数据集和代码即将在GitHub上公开：https://github.com/lironui/AeroReformer。

> As a novel and challenging task, referring segmentation combines computer vision and natural language processing to localize and segment objects based on textual descriptions. While referring image segmentation (RIS) has been extensively studied in natural images, little attention has been given to aerial imagery, particularly from unmanned aerial vehicles (UAVs). The unique challenges of UAV imagery, including complex spatial scales, occlusions, and varying object orientations, render existing RIS approaches ineffective. A key limitation has been the lack of UAV-specific datasets, as manually annotating pixel-level masks and generating textual descriptions is labour-intensive and time-consuming. To address this gap, we design an automatic labelling pipeline that leverages pre-existing UAV segmentation datasets and Multimodal Large Language Models (MLLM) for generating textual descriptions. Furthermore, we propose Aerial Referring Transformer (AeroReformer), a novel framework for UAV referring image segmentation (UAV-RIS), featuring a Vision-Language Cross-Attention Module (VLCAM) for effective cross-modal understanding and a Rotation-Aware Multi-Scale Fusion (RAMSF) decoder to enhance segmentation accuracy in aerial scenes. Extensive experiments on two newly developed datasets demonstrate the superiority of AeroReformer over existing methods, establishing a new benchmark for UAV-RIS. The datasets and code will be publicly available at: https://github.com/lironui/AeroReformer.

[Arxiv](https://arxiv.org/abs/2502.16680)