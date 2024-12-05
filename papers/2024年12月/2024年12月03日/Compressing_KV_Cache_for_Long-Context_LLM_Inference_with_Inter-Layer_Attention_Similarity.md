# 利用层间注意力相似性压缩用于长上下文 LLM 推理的 KV 缓存

发布时间：2024年12月03日

`LLM应用` `大型语言模型`

> Compressing KV Cache for Long-Context LLM Inference with Inter-Layer Attention Similarity

# 摘要

> 在诸如 GPT 和 LLaMA 系列等大型语言模型（LLMs）中，不断增大的上下文窗口尺寸提升了其处理复杂长文本任务的能力，然而这是以牺牲推理效率为代价的，尤其是在内存和计算复杂度方面。现有的一些方法，像选择性令牌保留和基于窗口的注意力机制，虽提高了效率，却有丢弃未来文本生成所需重要令牌的风险。在本文中，我们提出了一种不会造成令牌丢失且能提升 LLM 效率的方法，即降低不太重要令牌的内存和计算负载。我们应对了两个挑战：其一，探究上下文中重要令牌的分布情况，发现近期令牌在上下文中比远距离令牌更重要；其二，通过跨层共享注意力分数来优化远距离令牌的资源。实验表明，我们的方法在不损害性能的前提下节省了 35％的 KV 缓存。

> The increasing context window size in Large Language Models (LLMs), such as the GPT and LLaMA series, has improved their ability to tackle complex, long-text tasks, but at the cost of inference efficiency, particularly regarding memory and computational complexity. Existing methods, including selective token retention and window-based attention, improve efficiency but risk discarding important tokens needed for future text generation. In this paper, we propose an approach that enhances LLM efficiency without token loss by reducing the memory and computational load of less important tokens, rather than discarding them.We address two challenges: 1) investigating the distribution of important tokens in the context, discovering recent tokens are more important than distant tokens in context, and 2) optimizing resources for distant tokens by sharing attention scores across layers. The experiments show that our method saves $35\%$ KV cache without compromising the performance.

[Arxiv](https://arxiv.org/abs/2412.02252)