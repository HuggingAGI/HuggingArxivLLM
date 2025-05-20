# FreeKV：优化键值缓存，实现更高效的大语言模型推理

发布时间：2025年05月19日

`LLM应用` `计算机系统`

> FreeKV: Boosting KV Cache Retrieval for Efficient LLM Inference

# 摘要

> 大型语言模型（LLMs）正通过快速扩展上下文窗口广泛应用于各种复杂场景。然而，长上下文的部署面临重大挑战，核心问题在于KV缓存的尺寸随上下文长度线性增长。虽然KV缓存压缩方法被提出以应对这一挑战，但KV丢弃方法会导致显著的准确性损失，而KV检索方法则面临严重的效率瓶颈。为此，我们提出FreeKV，一个算法-系统协同优化框架，旨在提升KV检索效率的同时保持准确性。在算法层面，FreeKV通过引入推测式检索，将KV选择和召回过程移出关键路径，并结合细粒度校正确保准确性。在系统层面，FreeKV采用混合KV布局，消除碎片化数据传输，同时利用双缓冲流式召回进一步提升效率。实验结果显示，FreeKV在各种场景和模型中实现了近乎无损的准确性，与最先进（SOTA）的KV检索方法相比，速度提升了高达13倍。

> Large language models (LLMs) have been widely deployed with rapidly expanding context windows to support increasingly demanding applications. However, long contexts pose significant deployment challenges, primarily due to the KV cache whose size grows proportionally with context length. While KV cache compression methods are proposed to address this issue, KV dropping methods incur considerable accuracy loss, and KV retrieval methods suffer from significant efficiency bottlenecks. We propose FreeKV, an algorithm-system co-optimization framework to enhance KV retrieval efficiency while preserving accuracy. On the algorithm side, FreeKV introduces speculative retrieval to shift the KV selection and recall processes out of the critical path, combined with fine-grained correction to ensure accuracy. On the system side, FreeKV employs hybrid KV layouts across CPU and GPU memory to eliminate fragmented data transfers, and leverages double-buffered streamed recall to further improve efficiency. Experiments demonstrate that FreeKV achieves near-lossless accuracy across various scenarios and models, delivering up to 13$\times$ speedup compared to SOTA KV retrieval methods.

[Arxiv](https://arxiv.org/abs/2505.13109)