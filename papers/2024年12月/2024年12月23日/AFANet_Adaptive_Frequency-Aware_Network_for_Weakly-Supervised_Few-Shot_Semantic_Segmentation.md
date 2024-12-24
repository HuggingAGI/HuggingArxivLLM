# AFANet：适用于弱监督少样本语义分割的自适应频率感知网络

发布时间：2024年12月23日

`LLM应用` `计算机视觉` `少样本学习`

> AFANet: Adaptive Frequency-Aware Network for Weakly-Supervised Few-Shot Semantic Segmentation

# 摘要

> 少样本学习旨在借助从少量样本获取的先验知识来识别新的概念。然而，像少样本语义分割这类视觉密集型任务，像素级标注既费时又费钱。所以，在本文中，我们采用更具挑战性的图像级标注，并提出用于弱监督少样本语义分割（WFSS）的自适应频率感知网络（AFANet）。具体而言，我们先是提出了一个跨粒度频率感知模块（CFM），它将RGB图像分解为高频和低频分布，并通过重新调整进一步优化语义结构信息。和大多数现有的以离线学习方式使用来自多模态语言视觉模型（如CLIP）的文本信息的WFSS方法不同，我们进一步提出了一个CLIP引导的空间适配器模块（CSM），它通过在线学习对文本信息进行空间域自适应转换，从而为CFM提供丰富的跨模态语义信息。在Pascal-5^{i}和COCO-20^{i}数据集上开展的大量实验表明，AFANet已取得了最先进的性能。代码可在https://github.com/jarch-ma/AFANet获取。

> Few-shot learning aims to recognize novel concepts by leveraging prior knowledge learned from a few samples. However, for visually intensive tasks such as few-shot semantic segmentation, pixel-level annotations are time-consuming and costly. Therefore, in this paper, we utilize the more challenging image-level annotations and propose an adaptive frequency-aware network (AFANet) for weakly-supervised few-shot semantic segmentation (WFSS). Specifically, we first propose a cross-granularity frequency-aware module (CFM) that decouples RGB images into high-frequency and low-frequency distributions and further optimizes semantic structural information by realigning them. Unlike most existing WFSS methods using the textual information from the multi-modal language-vision model, e.g., CLIP, in an offline learning manner, we further propose a CLIP-guided spatial-adapter module (CSM), which performs spatial domain adaptive transformation on textual information through online learning, thus providing enriched cross-modal semantic information for CFM. Extensive experiments on the Pascal-5\textsuperscript{i} and COCO-20\textsuperscript{i} datasets demonstrate that AFANet has achieved state-of-the-art performance. The code is available at https://github.com/jarch-ma/AFANet.

[Arxiv](https://arxiv.org/abs/2412.17601)