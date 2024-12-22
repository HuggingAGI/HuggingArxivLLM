# 用于跨视图地理定位的具有一致性和不变性学习的多级别嵌入和对齐网络

发布时间：2024年12月19日

`其他` `地理定位` `无人机`

> Multi-Level Embedding and Alignment Network with Consistency and Invariance Learning for Cross-View Geo-Localization

# 摘要

> 跨视图地理定位（CVGL）旨在通过检索最相似的带有 GPS 标签的卫星图像来确定无人机图像的位置。然而，平台间存在较大的成像差距，视角变化也颇为显著，这限制了现有方法有效关联跨视图特征以及提取一致且不变特征的能力。此外，现有方法在提升模型性能时，常常忽视计算和存储需求增加的问题。为解决这些限制，我们提出了一种名为多级嵌入与对齐网络（MEAN）的轻量级增强对齐网络。MEAN 网络运用渐进式多级增强策略、全局到局部关联以及跨域对齐，实现了跨层级的特征交流。这使得 MEAN 能够有效地连接不同层级的特征，并学习到强大的跨视图一致映射和模态不变特征。而且，MEAN 采用浅骨干网络与轻量级分支设计相结合，有效减少了参数数量和计算复杂度。在 University-1652 和 SUES-200 数据集上的实验结果显示，与最先进的模型相比，MEAN 的参数数量减少了 62.17%，计算复杂度降低了 70.99%，同时保持了具有竞争力甚至更出色的性能。代码即将发布。

> Cross-View Geo-Localization (CVGL) involves determining the localization of drone images by retrieving the most similar GPS-tagged satellite images. However, the imaging gaps between platforms are often significant and the variations in viewpoints are substantial, which limits the ability of existing methods to effectively associate cross-view features and extract consistent and invariant characteristics. Moreover, existing methods often overlook the problem of increased computational and storage requirements when improving model performance. To handle these limitations, we propose a lightweight enhanced alignment network, called the Multi-Level Embedding and Alignment Network (MEAN). The MEAN network uses a progressive multi-level enhancement strategy, global-to-local associations, and cross-domain alignment, enabling feature communication across levels. This allows MEAN to effectively connect features at different levels and learn robust cross-view consistent mappings and modality-invariant features. Moreover, MEAN adopts a shallow backbone network combined with a lightweight branch design, effectively reducing parameter count and computational complexity. Experimental results on the University-1652 and SUES-200 datasets demonstrate that MEAN reduces parameter count by 62.17% and computational complexity by 70.99% compared to state-of-the-art models, while maintaining competitive or even superior performance. The codes will be released soon.

[Arxiv](https://arxiv.org/abs/2412.14819)