# 开放词汇遥感图像语义分割的探索

发布时间：2024年12月27日

`其他

**理由**：这篇论文主要讨论的是遥感图像分割领域的新方法，特别是开放词汇遥感图像语义分割（OVRSISS）。虽然论文中提到了深度学习方法和视觉语言模型，但其核心内容并不直接涉及大型语言模型（LLM）、检索增强生成（RAG）或智能体（Agent）等主题。因此，将其归类为“其他”更为合适。` `图像分割`

> Towards Open-Vocabulary Remote Sensing Image Semantic Segmentation

# 摘要

> # 摘要
近年来，基于深度学习的方法在遥感图像分割领域取得了革命性进展。然而，这些方法通常依赖于预定义的语义类别集，导致在适应新类别时需要额外的图像标注和模型训练，且无法分割任意语义类别。为此，我们提出了开放词汇遥感图像语义分割（OVRSISS），旨在实现对遥感图像中任意语义类别的分割。为解决OVRSISS数据集的不足，我们构建了LandDiscover50K，一个包含51,846张图像的综合数据集，涵盖40个多样化的语义类别。此外，我们提出了GSNet框架，该框架结合了特殊遥感模型的领域先验和通用视觉语言模型的多功能特性。GSNet由双流图像编码器（DSIE）、查询引导特征融合（QGFF）和残差信息保留解码器（RIPD）组成。DSIE首先从特殊模型和通用模型的双流中提取全面特征；QGFF在可变词汇的引导下，整合专家和通用特征，实现互补；RIPD则用于聚合多源特征，生成更精确的掩码预测。实验表明，我们的方法显著优于其他方法，且LandDiscover50K有效提升了OVRSISS方法的性能。数据集和代码将在https://github.com/yecy749/GSNet公开。

> Recently, deep learning based methods have revolutionized remote sensing image segmentation. However, these methods usually rely on a pre-defined semantic class set, thus needing additional image annotation and model training when adapting to new classes. More importantly, they are unable to segment arbitrary semantic classes. In this work, we introduce Open-Vocabulary Remote Sensing Image Semantic Segmentation (OVRSISS), which aims to segment arbitrary semantic classes in remote sensing images. To address the lack of OVRSISS datasets, we develop LandDiscover50K, a comprehensive dataset of 51,846 images covering 40 diverse semantic classes. In addition, we propose a novel framework named GSNet that integrates domain priors from special remote sensing models and versatile capabilities of general vision-language models. Technically, GSNet consists of a Dual-Stream Image Encoder (DSIE), a Query-Guided Feature Fusion (QGFF), and a Residual Information Preservation Decoder (RIPD). DSIE first captures comprehensive features from both special models and general models in dual streams. Then, with the guidance of variable vocabularies, QGFF integrates specialist and generalist features, enabling them to complement each other. Finally, RIPD is proposed to aggregate multi-source features for more accurate mask predictions. Experiments show that our method outperforms other methods by a large margin, and our proposed LandDiscover50K improves the performance of OVRSISS methods. The proposed dataset and method will be made publicly available at https://github.com/yecy749/GSNet.

[Arxiv](https://arxiv.org/abs/2412.19492)