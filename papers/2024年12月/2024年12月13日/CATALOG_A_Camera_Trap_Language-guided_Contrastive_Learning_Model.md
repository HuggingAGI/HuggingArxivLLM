# 目录：相机陷阱语言引导的对比学习模型

发布时间：2024年12月13日

`LLM应用

**理由：**
这篇论文主要讨论了如何利用基础模型（FMs）和多模态融合技术来解决相机陷阱图像识别中的领域转移问题。虽然论文中提到了基础模型（FMs），但重点在于如何将这些模型应用于特定的计算机视觉任务（相机陷阱图像识别），并通过对比学习等方法提升模型性能。因此，这篇论文更符合“LLM应用”这一分类，因为它展示了如何将基础模型应用于具体的实际问题中。` `野生动物监测` `计算机视觉`

> CATALOG: A Camera Trap Language-guided Contrastive Learning Model

# 摘要

> # 摘要
基础模型（FMs）在图像分类、目标检测和图像分割等计算机视觉任务中表现出色。然而，当这些模型在分布与训练数据集不同的数据集上测试时，领域转移问题使得这些任务依然充满挑战。这在识别相机陷阱图像中的动物物种时尤为突出，因为光照、伪装和遮挡等因素的变异性增加了难度。本文提出了一种名为相机陷阱语言引导对比学习（CATALOG）的模型，通过结合多个FMs提取相机陷阱数据的视觉和文本特征，并利用对比损失函数进行训练。我们在两个基准数据集上评估了CATALOG，结果显示其在相机陷阱图像识别中超越了现有最先进方法，尤其是在训练和测试数据涉及不同动物物种或来自不同地理区域时。该方法展示了多模态融合与对比学习结合FMs在解决相机陷阱图像识别领域转移问题上的潜力。CATALOG的代码已开源，详见https://github.com/Julian075/CATALOG。

> Foundation Models (FMs) have been successful in various computer vision tasks like image classification, object detection and image segmentation. However, these tasks remain challenging when these models are tested on datasets with different distributions from the training dataset, a problem known as domain shift. This is especially problematic for recognizing animal species in camera-trap images where we have variability in factors like lighting, camouflage and occlusions. In this paper, we propose the Camera Trap Language-guided Contrastive Learning (CATALOG) model to address these issues. Our approach combines multiple FMs to extract visual and textual features from camera-trap data and uses a contrastive loss function to train the model. We evaluate CATALOG on two benchmark datasets and show that it outperforms previous state-of-the-art methods in camera-trap image recognition, especially when the training and testing data have different animal species or come from different geographical areas. Our approach demonstrates the potential of using FMs in combination with multi-modal fusion and contrastive learning for addressing domain shifts in camera-trap image recognition. The code of CATALOG is publicly available at https://github.com/Julian075/CATALOG.

[Arxiv](https://arxiv.org/abs/2412.10624)