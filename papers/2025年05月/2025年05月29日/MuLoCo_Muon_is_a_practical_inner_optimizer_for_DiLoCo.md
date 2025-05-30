# **MuLoCo**: Muon 作为 DiLoCo 的实用内部优化器，展现了其实际应用价值。

发布时间：2025年05月29日

`LLM应用

摘要讨论了DiLoCo框架在训练大型语言模型中的应用，特别是优化通信效率和压缩技术。这些优化属于模型训练的应用层面，因此归类为LLM应用。` `人工智能` `分布式计算`

> MuLoCo: Muon is a practical inner optimizer for DiLoCo

# 摘要

> DiLoCo 是一个强大的框架，专为在有网络限制的情况下训练大型语言模型 (LLMs) 而设计，它在数据中心环境中能显著提升并行性和加速器的利用率。尽管 DiLoCo 已大幅减少通信频率，但其通信步骤仍需对模型参数进行全量同步。尽管已有研究探索了减少 DiLoCo 通信的方法，但错误反馈累加器的作用以及内部优化器对压缩性的影响仍有待深入研究。本研究中，我们评估了标准压缩方法（包括 Top-k 稀疏化和量化）在与 AdamW 和 Muon 两个本地优化器配合使用时，能否有效降低 DiLoCo 的通信开销。我们的实验通过预训练解码器-only transformer 语言模型 (LMs) 发现，将 Muon 作为 DiLoCo 的内部优化器，并结合错误反馈累加器，能够将通信增量数据压缩至 2 位，同时几乎不影响模型性能。尤为关键的是，MuLoCo（Muon 内部优化器的 DiLoCo）在通信量仅为原方案 1/8 的情况下，性能表现远超 DiLoCo，同时保持相同的内存复杂度。

> DiLoCo is a powerful framework for training large language models (LLMs) under networking constraints with advantages for increasing parallelism and accelerator utilization in data center settings. Despite significantly reducing communication frequency, however, DiLoCo's communication steps still involve all-reducing a complete copy of the model's parameters. While existing works have explored ways to reduce communication in DiLoCo, the role of error feedback accumulators and the effect of the inner-optimizer on compressibility remain under-explored. In this work, we investigate the effectiveness of standard compression methods including Top-k sparsification and quantization for reducing the communication overhead of DiLoCo when paired with two local optimizers (AdamW and Muon). Our experiments pre-training decoder-only transformer language models (LMs) reveal that leveraging Muon as the inner optimizer for DiLoCo along with an error-feedback accumulator allows to aggressively compress the communicated delta to 2-bits with next to no performance degradation. Crucially, MuLoCo (Muon inner optimizer DiLoCo) significantly outperforms DiLoCo while communicating 8X less and having identical memory complexity.

[Arxiv](https://arxiv.org/abs/2505.23725)