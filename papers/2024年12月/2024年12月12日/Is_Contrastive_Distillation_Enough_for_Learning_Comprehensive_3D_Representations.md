# 对比蒸馏对于学习全面的 3D 表示是否足够呢？

发布时间：2024年12月12日

`LLM应用` `3D 表征学习` `计算机视觉`

> Is Contrastive Distillation Enough for Learning Comprehensive 3D Representations?

# 摘要

> 跨模态对比蒸馏近来被用于学习有效的 3D 表征。然而，现有的方法在预训练时主要着眼于模态共享特征，却忽略了模态特定特征，致使表征效果欠佳。在本文中，我们从理论层面剖析了当下 3D 表征学习的对比方法存在的局限，并提出了一个新框架——CMCR，以攻克这些短板。我们的方法通过更优地整合模态共享与模态特定特征，对传统方法加以改进。具体而言，我们引入了掩码图像建模和占用率估计任务，引导网络学习更全面的模态特定特征。另外，我们提出了一种新颖的多模态统一码本，用于学习不同模态共享的嵌入空间。再者，我们引入几何增强的掩码图像建模，进一步推动 3D 表征学习。大量实验表明，我们的方法缓解了传统方法所面临的难题，在下游任务中始终优于现有的图像到 LiDAR 对比蒸馏方法。代码可在 https://github.com/Eaphan/CMCR 获取。

> Cross-modal contrastive distillation has recently been explored for learning effective 3D representations. However, existing methods focus primarily on modality-shared features, neglecting the modality-specific features during the pre-training process, which leads to suboptimal representations. In this paper, we theoretically analyze the limitations of current contrastive methods for 3D representation learning and propose a new framework, namely CMCR, to address these shortcomings. Our approach improves upon traditional methods by better integrating both modality-shared and modality-specific features. Specifically, we introduce masked image modeling and occupancy estimation tasks to guide the network in learning more comprehensive modality-specific features. Furthermore, we propose a novel multi-modal unified codebook that learns an embedding space shared across different modalities. Besides, we introduce geometry-enhanced masked image modeling to further boost 3D representation learning. Extensive experiments demonstrate that our method mitigates the challenges faced by traditional approaches and consistently outperforms existing image-to-LiDAR contrastive distillation methods in downstream tasks. Code will be available at https://github.com/Eaphan/CMCR.

[Arxiv](https://arxiv.org/abs/2412.08973)