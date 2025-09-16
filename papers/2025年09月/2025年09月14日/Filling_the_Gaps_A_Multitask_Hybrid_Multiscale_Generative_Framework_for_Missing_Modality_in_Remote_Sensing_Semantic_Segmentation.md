# 填补空白：面向遥感语义分割中缺失模态的多任务混合多尺度生成框架

发布时间：2025年09月14日

`其他` `能源与环保`

> Filling the Gaps: A Multitask Hybrid Multiscale Generative Framework for Missing Modality in Remote Sensing Semantic Segmentation

# 摘要

> 与传统单模态模型相比，多模态学习在多个领域均表现出显著的性能优势。然而，在实际应用中，多模态信号常因传感器故障或恶劣天气而缺失，导致模型运行和性能大幅下降。生成模型（如自编码器（AE）和生成对抗网络（GAN））是直观的解决方案，旨在通过可用模态重建缺失模态，但其在遥感语义分割任务中的效能尚未得到深入研究。本文首先分析了现有生成方法在应对多模态遥感数据异质性时的局限性：这些方法难以充分捕捉复杂场景中的语义上下文——此类场景通常存在类内差异大而类间差异小的问题；此外，传统生成模型往往过度依赖主导模态，由此产生的偏差会影响缺失模态情况下的模型鲁棒性。为解决上述问题，我们提出一种全新的生成增强多模态学习网络（GEMMNet），其核心包含三个关键组件：（1）混合特征提取器（HyFEx）：用于高效学习模态特异性表示；（2）多尺度感知混合融合模块（HyFMA）：用于跨尺度捕捉模态协同的语义上下文；（3）互补损失（CoLoss）机制：通过增强模态与任务间的一致性以减轻固有偏差。实验结果表明，在两个极具挑战性的遥感语义分割数据集（Vaihingen和Potsdam）上，我们的GEMMNet不仅优于AE、条件GAN（cGAN）等生成模型基线，还超越了mmformer和shaspec等当前最先进的非生成方法。本文源代码已公开。

> Multimodal learning has shown significant performance boost compared to ordinary unimodal models across various domains. However, in real-world scenarios, multimodal signals are susceptible to missing because of sensor failures and adverse weather conditions, which drastically deteriorates models' operation and performance. Generative models such as AutoEncoder (AE) and Generative Adversarial Network (GAN) are intuitive solutions aiming to reconstruct missing modality from available ones. Yet, their efficacy in remote sensing semantic segmentation remains underexplored. In this paper, we first examine the limitations of existing generative approaches in handling the heterogeneity of multimodal remote sensing data. They inadequately capture semantic context in complex scenes with large intra-class and small inter-class variation. In addition, traditional generative models are susceptible to heavy dependence on the dominant modality, introducing bias that affects model robustness under missing modality conditions. To tackle these limitations, we propose a novel Generative-Enhanced MultiModal learning Network (GEMMNet) with three key components: (1) Hybrid Feature Extractor (HyFEx) to effectively learn modality-specific representations, (2) Hybrid Fusion with Multiscale Awareness (HyFMA) to capture modality-synergistic semantic context across scales and (3) Complementary Loss (CoLoss) scheme to alleviate the inherent bias by encouraging consistency across modalities and tasks. Our method, GEMMNet, outperforms both generative baselines AE, cGAN (conditional GAN), and state-of-the-art non-generative approaches - mmformer and shaspec - on two challenging semantic segmentation remote sensing datasets (Vaihingen and Potsdam). Source code is made available.

[Arxiv](https://arxiv.org/abs/2509.11102)