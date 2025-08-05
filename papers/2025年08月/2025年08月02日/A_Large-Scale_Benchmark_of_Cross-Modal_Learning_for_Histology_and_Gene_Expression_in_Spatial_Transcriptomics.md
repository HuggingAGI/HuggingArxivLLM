# # 大规模跨模态学习基准测试：组织学与基因表达的空间转录组学研究

发布时间：2025年08月02日

`其他` `生物医学` `数据科学`

> A Large-Scale Benchmark of Cross-Modal Learning for Histology and Gene Expression in Spatial Transcriptomics

# 摘要

> 空间转录组学能够同时测量基因表达和组织形态，为细胞组织和疾病机制提供了前所未有的见解。然而，该领域缺乏全面的基准来评估结合组织学图像和基因表达数据的多模式学习方法。本文介绍了HESCAPE，这是一个基于经过整理的泛器官数据集的空间转录组学跨模式对比预训练大规模基准，涵盖了6个不同的基因组和54个供体。我们系统评估了最先进的图像和基因表达编码器在多种预训练策略下的表现，并评估了它们在两个下游任务中的有效性：基因突变分类和基因表达预测。我们的基准测试表明，基因表达编码器是强表示对齐的主要决定因素，而预先在空间转录组学数据上训练的基因模型的表现优于未使用空间数据训练的模型以及简单的基线方法。然而，下游任务评估揭示了一个显著的矛盾：尽管对比预训练一致提高了基因突变分类性能，但它却降低了直接基因表达预测的表现，与没有跨模式目标的基线编码器相比。我们发现批次效应是影响跨模式对齐的关键因素。我们的研究结果强调了在空间转录组学中需要稳健批次的多模式学习方法。为了加速这一方向的进步，我们发布了HESCAPE，为社区提供了标准化的数据集、评估协议和基准工具。

> Spatial transcriptomics enables simultaneous measurement of gene expression and tissue morphology, offering unprecedented insights into cellular organization and disease mechanisms. However, the field lacks comprehensive benchmarks for evaluating multimodal learning methods that leverage both histology images and gene expression data. Here, we present HESCAPE, a large-scale benchmark for cross-modal contrastive pretraining in spatial transcriptomics, built on a curated pan-organ dataset spanning 6 different gene panels and 54 donors. We systematically evaluated state-of-the-art image and gene expression encoders across multiple pretraining strategies and assessed their effectiveness on two downstream tasks: gene mutation classification and gene expression prediction. Our benchmark demonstrates that gene expression encoders are the primary determinant of strong representational alignment, and that gene models pretrained on spatial transcriptomics data outperform both those trained without spatial data and simple baseline approaches. However, downstream task evaluation reveals a striking contradiction: while contrastive pretraining consistently improves gene mutation classification performance, it degrades direct gene expression prediction compared to baseline encoders trained without cross-modal objectives. We identify batch effects as a key factor that interferes with effective cross-modal alignment. Our findings highlight the critical need for batch-robust multimodal learning approaches in spatial transcriptomics. To accelerate progress in this direction, we release HESCAPE, providing standardized datasets, evaluation protocols, and benchmarking tools for the community

[Arxiv](https://arxiv.org/abs/2508.01490)