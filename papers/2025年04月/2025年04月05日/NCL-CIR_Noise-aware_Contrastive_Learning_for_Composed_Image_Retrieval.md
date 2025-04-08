# NCL-CIR: 噪声感知对比学习针对组合图像检索

发布时间：2025年04月05日

`其他` `图像检索` `多模态技术`

> NCL-CIR: Noise-aware Contrastive Learning for Composed Image Retrieval

# 摘要

> 组合图像检索（CIR）致力于通过结合图像与修改文本的多模态查询，精准定位目标图像。尽管近期的CIR方法展现出潜力，但它们主要集中在通过数据增强或模型设计探索查询对（图像与文本）之间的关系。这些方法通常假设查询与目标图像之间存在完美的对齐，而这在实际中几乎难以实现。现实中，由于修改文本不准确、目标图像质量低或标注错误等原因，查询对往往出现部分或完全的不匹配。忽视这些不匹配会导致数据集中出现大量噪声配对样本，使模型过拟合，最终影响性能。为解决这一问题，我们提出了面向CIR的噪声感知对比学习（NCL-CIR），包含两个关键组件：权重补偿块（WCB）和噪声配对过滤块（NFB）。WCB结合多样化的权重图，确保多模态查询与目标图像的令牌表示更加稳定。同时，NFB借助高斯混合模型（GMM）通过评估损失分布预测噪声配对，并相应生成软标签，从而设计基于软标签的噪声对比估计（NCE）损失函数。因此，整体架构有助于缓解不匹配和部分匹配样本的影响，实验结果表明NCL-CIR在基准数据集上取得了优异的性能。

> Composed Image Retrieval (CIR) seeks to find a target image using a multi-modal query, which combines an image with modification text to pinpoint the target. While recent CIR methods have shown promise, they mainly focus on exploring relationships between the query pairs (image and text) through data augmentation or model design. These methods often assume perfect alignment between queries and target images, an idealized scenario rarely encountered in practice. In reality, pairs are often partially or completely mismatched due to issues like inaccurate modification texts, low-quality target images, and annotation errors. Ignoring these mismatches leads to numerous False Positive Pair (FFPs) denoted as noise pairs in the dataset, causing the model to overfit and ultimately reducing its performance. To address this problem, we propose the Noise-aware Contrastive Learning for CIR (NCL-CIR), comprising two key components: the Weight Compensation Block (WCB) and the Noise-pair Filter Block (NFB). The WCB coupled with diverse weight maps can ensure more stable token representations of multi-modal queries and target images. Meanwhile, the NFB, in conjunction with the Gaussian Mixture Model (GMM) predicts noise pairs by evaluating loss distributions, and generates soft labels correspondingly, allowing for the design of the soft-label based Noise Contrastive Estimation (NCE) loss function. Consequently, the overall architecture helps to mitigate the influence of mismatched and partially matched samples, with experimental results demonstrating that NCL-CIR achieves exceptional performance on the benchmark datasets.

[Arxiv](https://arxiv.org/abs/2504.04339)