# # InvisibleInk: 低成本高实用的差分隐私文本生成

发布时间：2025年06月30日

`RAG` `数据隐私`

> InvisibleInk: High-Utility and Low-Cost Text Generation with Differential Privacy

# 摘要

> 基于 LLM 的长文本生成技术的突破推动了检索增强生成（RAG）和推理时扩展等范式的实现。然而，如何安全地将私密信息融入生成过程仍是一个关键的开放问题。我们提出了 InvisibleInk，这是一个满足严格差分隐私保证的高度可扩展长文本生成框架。该框架通过在 LLM 的对数上使用指数机制来解释从 LLM 的下一个词分布中采样的过程，并引入了两项创新。首先，我们通过仅隔离和剪切模型中相对于公共对数的敏感信息来降低隐私成本。其次，我们通过从一个较小的超集的前 $k$ 私密词元中采样来提升文本质量。实证评估显示，在相同隐私级别的长文本生成中，与现有最佳基线相比，计算成本降低了 8 倍。总而言之，InvisibleInk 生成私密长文本的计算成本不到非私密生成的 10 倍，展现了其高效性与实用性。

> As major progress in LLM-based long-form text generation enables paradigms such as retrieval-augmented generation (RAG) and inference-time scaling, safely incorporating private information into the generation remains a critical open question. We present InvisibleInk, a highly scalable long-form text generation framework satisfying rigorous differential privacy guarantees with respect to the sensitive references. It interprets sampling from the LLM's next-token-distribution as the exponential mechanism over the LLM logits with two innovations. First, we reduce the privacy cost by isolating and clipping only the sensitive information in the model logits (relative to the public logits). Second, we improve text quality by sampling from a small superset of the top-$k$ private tokens. Empirical evaluations demonstrate a consistent $8\times$ reduction in computation cost over state-of-the-art baselines to generate long-form private text of the same utility across privacy levels. In summary, InvisibleInk is able to generate private long-form text at less than $10\times$ the computation cost of non-private generation.

[Arxiv](https://arxiv.org/abs/2507.02974)