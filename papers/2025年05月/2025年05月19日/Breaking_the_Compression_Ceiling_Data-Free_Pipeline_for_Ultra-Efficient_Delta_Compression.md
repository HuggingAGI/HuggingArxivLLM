# 打破压缩极限：无数据的超高效增量压缩流水线

发布时间：2025年05月19日

`其他

理由：这篇论文主要探讨了Delta压缩技术的改进，特别是在模型存储优化方面的应用。虽然它提到了大型语言模型，但其核心贡献在于模型压缩和优化方法，而非直接探讨LLM的应用或理论，因此归类为“其他”。` `模型压缩` `机器学习`

> Breaking the Compression Ceiling: Data-Free Pipeline for Ultra-Efficient Delta Compression

# 摘要

> 随着微调-预训练范式的兴起，为多任务存储众多微调模型会带来显著的存储开销。Delta压缩通过仅存储预训练模型和高度压缩的Delta权重（微调模型与预训练模型权重的差异）来缓解这一问题。然而，现有方法无法同时保持高压缩率和高性能，且通常依赖数据。针对这些挑战，我们提出UltraDelta，这是首个无数据的Delta压缩管道，能够同时实现超高压缩率和强劲性能。UltraDelta通过三个关键组件在跨层、层内和全局维度上最小化冗余、最大化信息并稳定性能：(1) 基于方差的混合稀疏分配根据方差分配稀疏性，为高方差层分配较低的稀疏性以保留跨层信息。 (2) 分布感知压缩应用均匀量化，然后按值分组参数，随后进行组内剪枝，以更好地保留层内分布。 (3) 迹范数引导的重新缩放利用Delta权重的迹范数来估计全局重新缩放因子，在更高压缩率下提升模型稳定性。在大型语言模型（基于LLaMA-2 7B和13B微调）、通用NLP模型（RoBERTa-base，T5-base）、视觉模型（ViT-B/32，ViT-L/14）和多模态模型（BEiT-3）上的广泛实验表明，UltraDelta在高达133倍、800倍、400倍和40倍的压缩比率下，始终优于现有方法，尤其是在超高压缩率下表现尤为突出。

> With the rise of the fine-tuned--pretrained paradigm, storing numerous fine-tuned models for multi-tasking creates significant storage overhead. Delta compression alleviates this by storing only the pretrained model and the highly compressed delta weights (the differences between fine-tuned and pretrained model weights). However, existing methods fail to maintain both high compression and performance, and often rely on data. To address these challenges, we propose UltraDelta, the first data-free delta compression pipeline that achieves both ultra-high compression and strong performance. UltraDelta is designed to minimize redundancy, maximize information, and stabilize performance across inter-layer, intra-layer, and global dimensions, using three key components: (1) Variance-Based Mixed Sparsity Allocation assigns sparsity based on variance, giving lower sparsity to high-variance layers to preserve inter-layer information. (2) Distribution-Aware Compression applies uniform quantization and then groups parameters by value, followed by group-wise pruning, to better preserve intra-layer distribution. (3) Trace-Norm-Guided Rescaling uses the trace norm of delta weights to estimate a global rescaling factor, improving model stability under higher compression. Extensive experiments across (a) large language models (fine-tuned on LLaMA-2 7B and 13B) with up to 133x, (b) general NLP models (RoBERTa-base, T5-base) with up to 800x, (c) vision models (ViT-B/32, ViT-L/14) with up to 400x, and (d) multi-modal models (BEiT-3) with 40x compression ratio, demonstrate that UltraDelta consistently outperforms existing methods, especially under ultra-high compression.

[Arxiv](https://arxiv.org/abs/2505.13563)