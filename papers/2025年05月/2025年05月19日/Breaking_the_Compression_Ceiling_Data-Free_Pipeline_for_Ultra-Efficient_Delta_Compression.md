# 突破压缩极限：无数据管道实现超高效增量压缩

发布时间：2025年05月19日

`其他` `计算机视觉`

> Breaking the Compression Ceiling: Data-Free Pipeline for Ultra-Efficient Delta Compression

# 摘要

> 微调-预训练范式的兴起带来了多任务场景下存储大量微调模型的存储开销问题。增量压缩通过仅存储预训练模型和高度压缩的增量权重来缓解这一问题，但现有方法往往顾此失彼，难以兼顾高压缩率和高性能，且通常依赖数据。为了解决这些挑战，我们提出了UltraDelta——首个无数据依赖的增量压缩 pipeline，实现了超高压缩率的同时保持了强大的性能。

UltraDelta 通过三个关键组件设计，旨在最小化冗余、最大化信息，并在跨层、层内和全局维度上稳定性能：(1) 基于方差的混合稀疏度分配根据方差分配稀疏度，为高方差层分配较低的稀疏度以保留跨层信息。 (2) 分布感知压缩首先应用均匀量化，然后按值分组参数，接着进行组内剪枝，以更好地保留层内分布。 (3) 迹范数引导的缩放利用增量权重的迹范数来估计全局缩放因子，在更高压缩率下提升模型稳定性。

通过在 (a) 大型语言模型（基于 LLaMA-2 7B 和 13B 微调）的 133 倍压缩，(b) 通用 NLP 模型（RoBERTa-base，T5-base）的 800 倍压缩，(c) 视觉模型（ViT-B/32，ViT-L/14）的 400 倍压缩，以及 (d) 多模态模型（BEiT-3）的 40 倍压缩比上的广泛实验，结果表明 UltraDelta 一致优于现有方法，尤其是在超高压缩率下表现尤为突出。

> With the rise of the fine-tuned--pretrained paradigm, storing numerous fine-tuned models for multi-tasking creates significant storage overhead. Delta compression alleviates this by storing only the pretrained model and the highly compressed delta weights (the differences between fine-tuned and pretrained model weights). However, existing methods fail to maintain both high compression and performance, and often rely on data. To address these challenges, we propose UltraDelta, the first data-free delta compression pipeline that achieves both ultra-high compression and strong performance. UltraDelta is designed to minimize redundancy, maximize information, and stabilize performance across inter-layer, intra-layer, and global dimensions, using three key components: (1) Variance-Based Mixed Sparsity Allocation assigns sparsity based on variance, giving lower sparsity to high-variance layers to preserve inter-layer information. (2) Distribution-Aware Compression applies uniform quantization and then groups parameters by value, followed by group-wise pruning, to better preserve intra-layer distribution. (3) Trace-Norm-Guided Rescaling uses the trace norm of delta weights to estimate a global rescaling factor, improving model stability under higher compression. Extensive experiments across (a) large language models (fine-tuned on LLaMA-2 7B and 13B) with up to 133x, (b) general NLP models (RoBERTa-base, T5-base) with up to 800x, (c) vision models (ViT-B/32, ViT-L/14) with up to 400x, and (d) multi-modal models (BEiT-3) with 40x compression ratio, demonstrate that UltraDelta consistently outperforms existing methods, especially under ultra-high compression.

[Arxiv](https://arxiv.org/abs/2505.13563)