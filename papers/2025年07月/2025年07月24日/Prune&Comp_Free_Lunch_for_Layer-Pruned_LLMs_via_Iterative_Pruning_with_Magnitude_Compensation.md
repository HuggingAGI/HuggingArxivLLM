# Prune&Comp：层剪枝大型语言模型的零成本优化——迭代剪枝结合幅度补偿

发布时间：2025年07月24日

`LLM应用

摘要中提到的层剪裁技术、Prune&Comp方案以及在LLM上的实验结果，都属于对大型语言模型的应用优化，因此归类为LLM应用。` `人工智能`

> Prune&Comp: Free Lunch for Layer-Pruned LLMs via Iterative Pruning with Magnitude Compensation

# 摘要

> 层剪裁技术在压缩大型语言模型（LLMs）的同时实现了与剪裁比例成正比的加速效果，展现出巨大潜力。然而，我们发现移除任何一层都会导致隐藏状态间出现显著的幅度差异，进而引发性能大幅下降。为解决这一问题，我们提出了Prune&Comp——一种创新的即插即用层剪裁方案。该方案通过幅度补偿在无需训练的情况下有效缓解此类差异。具体而言，我们首先估算层移除所导致的幅度差异，随后通过离线重缩放剩余权重消除这一差异，且无需承担任何运行时开销。通过迭代剪裁策略，我们进一步展示了Prune&Comp的优势。当将其与迭代剪裁-补偿循环相结合时，Prune&Comp能够持续提升现有层剪裁指标。例如，当使用流行的块影响力指标对LLaMA-3-8B的5层进行剪裁时，Prune&Comp使困惑度近乎减半，并保留了原始模型93.19%的问题回答性能，较基线提升了4.01%。

> Layer pruning has emerged as a promising technique for compressing large language models (LLMs) while achieving acceleration proportional to the pruning ratio. In this work, we identify that removing any layer induces a significant magnitude gap in hidden states, resulting in substantial performance degradation. To address this issue, we propose Prune&Comp, a novel plug-and-play layer pruning scheme that leverages magnitude compensation to mitigate such gaps in a training-free manner. Specifically, we first estimate the magnitude gap caused by layer removal and then eliminate this gap by rescaling the remaining weights offline, with zero runtime overhead incurred. We further demonstrate the advantages of Prune&Comp through an iterative pruning strategy. When integrated with an iterative prune-and-compensate loop, Prune&Comp consistently enhances existing layer pruning metrics. For instance, when 5 layers of LLaMA-3-8B are pruned using the prevalent block influence metric, Prune&Comp nearly halves the perplexity and retains 93.19\% of the original model's question-answering performance, outperforming the baseline by 4.01%.

[Arxiv](https://arxiv.org/abs/2507.18212)