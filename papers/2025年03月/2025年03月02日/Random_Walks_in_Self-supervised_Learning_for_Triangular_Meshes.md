# 随机游走自监督学习在三角网格中的应用

发布时间：2025年03月02日

`其他` `计算机图形学` `计算机视觉`

> Random Walks in Self-supervised Learning for Triangular Meshes

# 摘要

> 本研究聚焦于3D网格分析中的自监督学习难题，提出了一种创新方法。该方法通过随机游走实现数据增强，生成多样化的网格表面表示。结合对比损失和聚类损失，构建了完整的学习框架。其中，对比学习通过最大化同一网格的增强实例相似性，同时最小化不同网格间的相似性。我们进一步引入聚类损失，在训练周期中增强类别区分度并降低训练方差。实验中，我们采用基于提取特征的监督SVM线性分类器和平均平均精度（mAP）分数进行评估，结果表明该方法在物体分类和形状检索等下游任务中具有显著潜力。

> This study addresses the challenge of self-supervised learning for 3D mesh analysis. It presents an new approach that uses random walks as a form of data augmentation to generate diverse representations of mesh surfaces. Furthermore, it employs a combination of contrastive and clustering losses. The contrastive learning framework maximizes similarity between augmented instances of the same mesh while minimizing similarity between different meshes. We integrate this with a clustering loss, enhancing class distinction across training epochs and mitigating training variance. Our model's effectiveness is evaluated using mean Average Precision (mAP) scores and a supervised SVM linear classifier on extracted features, demonstrating its potential for various downstream tasks such as object classification and shape retrieval.

[Arxiv](https://arxiv.org/abs/2503.00816)