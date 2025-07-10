# 纺锤KV：一种兼顾浅层与深层的创新KV缓存缩减方法

发布时间：2025年07月08日

`LLM应用

论文摘要：近年来，大型语言模型（LLMs）取得了令人瞩目的成就。然而，KV缓存不断增长的内存占用给推理系统带来了重大挑战。我们发现，KV缓存中存在大量冗余，特别是在深层模型中具有显著的压缩潜力，但浅层模型的压缩效果却不尽如人意。基于这一观察，我们提出了一种名为SpindleKV的新型KV缓存压缩方法，该方法在浅层和深层模型之间实现了良好的平衡。对于深层模型，我们采用基于注意力权重的缓存淘汰策略；而对于浅层模型，我们则采用基于代码本的替换方法，这种方法通过相似性和合并策略进行学习。此外，SpindleKV还解决了其他基于注意力的缓存淘汰方法所面临的Grouped-Query Attention（GQA）难题。在两个常见基准测试中，使用三种不同LLMs的实验结果表明，与基线方法相比，SpindleKV在保持相似甚至更优模型性能的同时，取得了更好的KV缓存压缩效果。

LLM应用` `计算机科学` `人工智能`

> SpindleKV: A Novel KV Cache Reduction Method Balancing Both Shallow and Deep Layers

# 摘要

> 近年来，大型语言模型（LLMs）取得了令人瞩目的成就。然而，KV缓存不断增长的内存占用给推理系统带来了重大挑战。我们发现，KV缓存中存在大量冗余，特别是在深层模型中具有显著的压缩潜力，但浅层模型的压缩效果却不尽如人意。基于这一观察，我们提出了一种名为SpindleKV的新型KV缓存压缩方法，该方法在浅层和深层模型之间实现了良好的平衡。对于深层模型，我们采用基于注意力权重的缓存淘汰策略；而对于浅层模型，我们则采用基于代码本的替换方法，这种方法通过相似性和合并策略进行学习。此外，SpindleKV还解决了其他基于注意力的缓存淘汰方法所面临的Grouped-Query Attention（GQA）难题。在两个常见基准测试中，使用三种不同LLMs的实验结果表明，与基线方法相比，SpindleKV在保持相似甚至更优模型性能的同时，取得了更好的KV缓存压缩效果。

> Large Language Models (LLMs) have achieved impressive accomplishments in recent years. However, the increasing memory consumption of KV cache has possessed a significant challenge to the inference system. Eviction methods have revealed the inherent redundancy within the KV cache, demonstrating its potential for reduction, particularly in deeper layers. However, KV cache reduction for shallower layers has been found to be insufficient. Based on our observation that, the KV cache exhibits a high degree of similarity. Based on this observation, we proposed a novel KV cache reduction method, SpindleKV, which balances both shallow and deep layers. For deep layers, we employ an attention weight based eviction method, while for shallow layers, we apply a codebook based replacement approach which is learnt by similarity and merging policy. Moreover, SpindleKV addressed the Grouped-Query Attention (GQA) dilemma faced by other attention based eviction methods. Experiments on two common benchmarks with three different LLMs shown that SpindleKV obtained better KV cache reduction effect compared to baseline methods, while preserving similar or even better model performance.

[Arxiv](https://arxiv.org/abs/2507.06517)