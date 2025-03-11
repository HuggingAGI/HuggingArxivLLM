# OpenRSD：致力于遥感图像目标检测的开放提示

发布时间：2025年03月08日

`其他` `目标检测`

> OpenRSD: Towards Open-prompts for Object Detection in Remote Sensing Images

# 摘要

> 遥感目标检测领域虽已取得显著进展，但现有研究多局限于封闭集检测，导致模型在跨数据集泛化能力上表现不足。开放词汇目标检测（OVD）通过结合文本提示与视觉特征的多模态关联，为这一问题提供了新的解决方案。然而，针对遥感图像（RS）的现有OVD方法仍受制于小规模数据集，并未能有效应对遥感解释中的独特挑战，包括定向目标检测以及在多样化场景中对高精度与实时性能的双重需求。

为解决这些难题，我们提出了OpenRSD——一种通用的开放提示遥感目标检测框架。该框架支持多模态提示，并通过多任务检测头的集成实现了精度与实时性要求的平衡。此外，我们设计了一套多阶段训练pipeline，进一步提升了模型的泛化能力。在七个公开数据集上的实证研究证实，OpenRSD在定向和水平边界框检测方面均表现出色，同时具备实时推理能力，为大规模遥感图像分析提供了有力支持。与YOLO-World相比，OpenRSD不仅将平均精度提升了8.7%，更实现了20.8 FPS的卓越推理速度。相关代码和模型即将开源。

> Remote sensing object detection has made significant progress, but most studies still focus on closed-set detection, limiting generalization across diverse datasets. Open-vocabulary object detection (OVD) provides a solution by leveraging multimodal associations between text prompts and visual features. However, existing OVD methods for remote sensing (RS) images are constrained by small-scale datasets and fail to address the unique challenges of remote sensing interpretation, include oriented object detection and the need for both high precision and real-time performance in diverse scenarios. To tackle these challenges, we propose OpenRSD, a universal open-prompt RS object detection framework. OpenRSD supports multimodal prompts and integrates multi-task detection heads to balance accuracy and real-time requirements. Additionally, we design a multi-stage training pipeline to enhance the generalization of model. Evaluated on seven public datasets, OpenRSD demonstrates superior performance in oriented and horizontal bounding box detection, with real-time inference capabilities suitable for large-scale RS image analysis. Compared to YOLO-World, OpenRSD exhibits an 8.7\% higher average precision and achieves an inference speed of 20.8 FPS. Codes and models will be released.

[Arxiv](https://arxiv.org/abs/2503.06146)