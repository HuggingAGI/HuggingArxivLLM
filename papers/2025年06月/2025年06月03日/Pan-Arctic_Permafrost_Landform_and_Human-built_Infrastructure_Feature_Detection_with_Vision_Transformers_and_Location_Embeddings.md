# 泛北极永久冻土地貌与人类建造基础设施特征检测：基于视觉变压器与位置嵌入

发布时间：2025年06月03日

`其他` `地理空间分析`

> Pan-Arctic Permafrost Landform and Human-built Infrastructure Feature Detection with Vision Transformers and Location Embeddings

# 摘要

> 利用亚米级卫星图像在泛北极范围内对永久冻土地貌、融化扰动和人类基础设施进行准确制图日益重要。处理PB级图像数据需要高性能计算和强大的特征检测模型。尽管基于卷积神经网络（CNN）的深度学习方法在遥感领域广泛应用，但视觉变压器（ViTs）通过注意力机制在捕获长距离依赖和全局上下文方面展现出优势。ViTs支持通过自监督学习进行预训练，解决了北极特征检测中标注数据不足的问题，并在基准数据集上超越了CNN。然而，北极地区的模型泛化面临挑战，尤其是同一语义类别的特征可能具有多样化的光谱特性。为了解决这些问题，我们整合了地理空间位置嵌入到ViTs中，以提升模型的跨区域适应能力。本研究探讨了两个关键问题：（1）预训练ViTs作为高分辨率北极遥感任务特征提取器的适用性；（2）结合图像和位置嵌入的优势。我们使用已发表的北极特征检测数据集，评估了模型在冰楔多边形（IWP）、退化融化滑塌（RTS）和人类基础设施检测三个任务上的表现。通过实证探索多种配置，我们实现了图像嵌入与位置嵌入的高效融合。结果显示，集成位置嵌入的ViTs在RTS检测等任务中表现优于传统CNN模型，F1分数从0.84提升至0.92。这证明了具有空间感知能力的基于变压器模型在北极遥感应用中的巨大潜力。

> Accurate mapping of permafrost landforms, thaw disturbances, and human-built infrastructure at pan-Arctic scale using sub-meter satellite imagery is increasingly critical. Handling petabyte-scale image data requires high-performance computing and robust feature detection models. While convolutional neural network (CNN)-based deep learning approaches are widely used for remote sensing (RS),similar to the success in transformer based large language models, Vision Transformers (ViTs) offer advantages in capturing long-range dependencies and global context via attention mechanisms. ViTs support pretraining via self-supervised learning-addressing the common limitation of labeled data in Arctic feature detection and outperform CNNs on benchmark datasets. Arctic also poses challenges for model generalization, especially when features with the same semantic class exhibit diverse spectral characteristics. To address these issues for Arctic feature detection, we integrate geospatial location embeddings into ViTs to improve adaptation across regions. This work investigates: (1) the suitability of pre-trained ViTs as feature extractors for high-resolution Arctic remote sensing tasks, and (2) the benefit of combining image and location embeddings. Using previously published datasets for Arctic feature detection, we evaluate our models on three tasks-detecting ice-wedge polygons (IWP), retrogressive thaw slumps (RTS), and human-built infrastructure. We empirically explore multiple configurations to fuse image embeddings and location embeddings. Results show that ViTs with location embeddings outperform prior CNN-based models on two of the three tasks including F1 score increase from 0.84 to 0.92 for RTS detection, demonstrating the potential of transformer-based models with spatial awareness for Arctic RS applications.

[Arxiv](https://arxiv.org/abs/2506.02868)