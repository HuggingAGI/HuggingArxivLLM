# EMS：一种基于全局-局部重要性的针对头向 KV 缓存压缩的自适应驱逐-然后-合并策略

发布时间：2024年12月11日

`LLM应用` `缓存压缩`

> EMS: Adaptive Evict-then-Merge Strategy for Head-wise KV Cache Compression Based on Global-Local Importance

# 摘要

> 随着大型语言模型（LLMs）持续进步，在各类应用中对于更高质量、更快速处理长上下文的需求不断增加。KV 缓存因能存储先前生成的键值令牌，有效减少推理时的冗余计算而被广泛运用。然而，内存开销成为重要问题后，KV 缓存的高效压缩愈发受到关注。现有的多数方法从两个角度进行压缩：识别重要令牌和设计压缩策略。但由于累积注意力分数或位置编码的影响，这些方法常常导致重要令牌分布有偏差。而且，它们忽视了不同头之间的稀疏性和冗余性，致使在头级别保留最有效信息面临困难。为此，我们提出 EMS 来突破这些限制，在极端压缩比下实现更优的 KV 缓存压缩。具体来说，我们引入了一个全局-局部分数，它融合了来自全局和局部 KV 令牌的累积注意力分数，从而更好地判别令牌的重要性。在压缩策略方面，我们设计了一个自适应且统一的驱逐-然后-合并框架，考虑到了不同头之间 KV 令牌的稀疏性和冗余性。另外，我们通过零类机制实现了头级并行压缩以提升效率。大量实验表明，即便在极端压缩比下，我们也拥有 SOTA 性能。EMS 在 256 个缓存预算下，于 LongBench 上的四个 LLMs 中始终达成最低的困惑度，分数提升超过 1.28 分，并且在“大海捞针”任务中，在缓存预算小于上下文长度 2％的情况下，保持 95％的检索准确率。

> As large language models (LLMs) continue to advance, the demand for higher quality and faster processing of long contexts across various applications is growing. KV cache is widely adopted as it stores previously generated key and value tokens, effectively reducing redundant computations during inference. However, as memory overhead becomes a significant concern, efficient compression of KV cache has gained increasing attention. Most existing methods perform compression from two perspectives: identifying important tokens and designing compression strategies. However, these approaches often produce biased distributions of important tokens due to the influence of accumulated attention scores or positional encoding. Furthermore, they overlook the sparsity and redundancy across different heads, which leads to difficulties in preserving the most effective information at the head level. To this end, we propose EMS to overcome these limitations, while achieving better KV cache compression under extreme compression ratios. Specifically, we introduce a Global-Local score that combines accumulated attention scores from both global and local KV tokens to better identify the token importance. For the compression strategy, we design an adaptive and unified Evict-then-Merge framework that accounts for the sparsity and redundancy of KV tokens across different heads. Additionally, we implement the head-wise parallel compression through a zero-class mechanism to enhance efficiency. Extensive experiments demonstrate our SOTA performance even under extreme compression ratios. EMS consistently achieves the lowest perplexity, improves scores by over 1.28 points across four LLMs on LongBench under a 256 cache budget, and preserves 95% retrieval accuracy with a cache budget less than 2% of the context length in the Needle-in-a-Haystack task.

[Arxiv](https://arxiv.org/abs/2412.08521)