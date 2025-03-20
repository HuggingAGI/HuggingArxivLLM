# 连续多模态对比学习

发布时间：2025年03月19日

`其他` `多模态学习` `持续学习`

> Continual Multimodal Contrastive Learning

# 摘要

> 多模态对比学习（MCL）在对齐不同模态和生成多模态表示方面取得了显著进展。通过跨模态对比学习，大规模多模态数据提升了表示质量。然而，一个关键但常被忽视的挑战依然存在：多模态数据很少是在一个过程中收集的，从头开始训练计算成本高昂。相反，新兴的多模态数据可以用来逐步优化现有模型，即模型是基于一系列模态对数据进行训练的。我们将此问题定义为持续多模态对比学习（CMCL），这是一个尚未充分探索但在多模态学习和持续学习交叉领域中至关重要的研究方向。本文通过稳定性和可塑性两个专门原则来定义CMCL。我们从理论上推导出一种基于优化的新方法，该方法将更新后的梯度从两侧投影到子空间中，以防止任何梯度干扰已学知识。两个上界为我们的解决方案在稳定性和可塑性方面提供了理论见解。除了理论贡献，我们还在多个数据集上通过与先进持续学习基线的比较进行了实验。实证结果进一步支持了我们的主张，并展示了我们方法的有效性。代码将公开发布。

> Multimodal contrastive learning (MCL) advances in aligning different modalities and generating multimodal representations in a joint space. By leveraging contrastive learning across diverse modalities, large-scale multimodal data enhances representational quality. However, a critical yet often overlooked challenge remains: multimodal data is rarely collected in a single process, and training from scratch is computationally expensive. Instead, emergent multimodal data can be used to optimize existing models gradually, \textit{i.e.}, models are trained on a sequence of modality pair data. We define this problem as Continual Multimodal Contrastive Learning (CMCL), an underexplored yet crucial research direction at the intersection of multimodal and continual learning. In this paper, we formulate CMCL through two specialized principles of stability and plasticity. We theoretically derive a novel optimization-based method, which projects updated gradients from dual sides onto subspaces where any gradient is prevented from interfering with the previously learned knowledge. Two upper bounds provide theoretical insights on both stability and plasticity in our solution. Beyond our theoretical contributions, we conduct experiments on multiple datasets by comparing our method against advanced continual learning baselines. The empirical results further support our claims and demonstrate the efficacy of our method. The code will be publicly available.

[Arxiv](https://arxiv.org/abs/2503.14963)