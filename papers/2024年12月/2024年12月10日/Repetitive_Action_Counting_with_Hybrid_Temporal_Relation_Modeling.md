# 基于混合时间关系建模的重复性动作计数

发布时间：2024年12月10日

`其他` `视频处理` `动作计数`

> Repetitive Action Counting with Hybrid Temporal Relation Modeling

# 摘要

> 重复性动作计数（RAC）的目标是统计视频中出现的重复性动作的数量。在现实世界里，重复性动作极具多样性，带来了诸多挑战（比如视角变化、周期不均匀以及动作中断）。现有的基于时间自相似矩阵（TSSM）的 RAC 方法在用于复杂的日常视频时，面临着对动作周期捕捉不足的瓶颈。为解决此问题，我们提出了一种名为混合时间关系建模网络（HTRM-Net）的新方法，为 RAC 构建多样的 TSSM。HTRM-Net 主要包含三个关键部分：双模态时间自相似矩阵建模、随机矩阵丢弃和局部时间上下文建模。具体而言，我们通过双模态（自注意力和双 softmax）操作构建时间自相似矩阵，从行和列相关性的组合中获取多样的矩阵表示。为进一步强化矩阵表示，我们提议引入随机矩阵丢弃模块，以明确引导矩阵的通道学习。接着，将视频帧的局部时间上下文和学习到的矩阵注入时间相关性建模中，这能让模型足够强健，以应对诸如动作中断之类的易出错情况。最后，设计了一个多尺度矩阵融合模块，用于在多尺度矩阵中自适应聚合时间相关性。大量跨数据集的实验表明，所提出的方法不仅优于当前的先进方法，而且在准确计算未见过的动作类别中的重复性动作方面展现出强大的能力。值得注意的是，我们的方法在 MAE 中比经典的 TransRAC 方法高出 20.04％，在 OBO 中高出 22.76％。

> Repetitive Action Counting (RAC) aims to count the number of repetitive actions occurring in videos. In the real world, repetitive actions have great diversity and bring numerous challenges (e.g., viewpoint changes, non-uniform periods, and action interruptions). Existing methods based on the temporal self-similarity matrix (TSSM) for RAC are trapped in the bottleneck of insufficient capturing action periods when applied to complicated daily videos. To tackle this issue, we propose a novel method named Hybrid Temporal Relation Modeling Network (HTRM-Net) to build diverse TSSM for RAC. The HTRM-Net mainly consists of three key components: bi-modal temporal self-similarity matrix modeling, random matrix dropping, and local temporal context modeling. Specifically, we construct temporal self-similarity matrices by bi-modal (self-attention and dual-softmax) operations, yielding diverse matrix representations from the combination of row-wise and column-wise correlations. To further enhance matrix representations, we propose incorporating a random matrix dropping module to guide channel-wise learning of the matrix explicitly. After that, we inject the local temporal context of video frames and the learned matrix into temporal correlation modeling, which can make the model robust enough to cope with error-prone situations, such as action interruption. Finally, a multi-scale matrix fusion module is designed to aggregate temporal correlations adaptively in multi-scale matrices. Extensive experiments across intra- and cross-datasets demonstrate that the proposed method not only outperforms current state-of-the-art methods but also exhibits robust capabilities in accurately counting repetitive actions in unseen action categories. Notably, our method surpasses the classical TransRAC method by 20.04\% in MAE and 22.76\% in OBO.

[Arxiv](https://arxiv.org/abs/2412.07233)