# AttentionPredictor: 时间模式是高效LLM推理的关键

发布时间：2025年02月06日

`LLM理论

理由：这篇论文主要关注的是大型语言模型（LLMs）的推理效率问题，特别是通过键值（KV）缓存压缩来提高推理效率。论文提出了一种新的方法（AttentionPredictor）来识别关键令牌，并设计了跨令牌的关键缓存预取框架。这些工作属于对LLM内部机制和性能优化的理论研究，因此应归类为“LLM理论”。` `机器学习`

> AttentionPredictor: Temporal Pattern Matters for Efficient LLM Inference

# 摘要

> 随着大型语言模型（LLMs）的发展，通过键值（KV）缓存压缩实现高效推理备受关注，尤其是在长上下文生成场景中。现有方法通常利用注意力分数进行启发式排序来识别关键KV令牌，但由于忽略了注意力分数中的	extit{时间模式}，往往难以准确定位关键令牌，导致LLM性能显著下降。为此，我们提出了AttentionPredictor，这是首个基于学习的关键令牌识别方法。AttentionPredictor通过轻量级卷积模型捕捉时空模式，预测下一个令牌的注意力分数，同时几乎不占用内存。此外，我们还设计了跨令牌的关键缓存预取框架，有效隐藏令牌估计的时间开销，加速解码过程。实验表明，AttentionPredictor在实现16$	imes$ KV缓存压缩的同时，保持了与现有技术相当的LLM性能，显著优于当前最优方法。

> With the development of large language models (LLMs), efficient inference through Key-Value (KV) cache compression has attracted considerable attention, especially for long-context generation. To compress the KV cache, recent methods identify critical KV tokens through heuristic ranking with attention scores. However, these methods often struggle to accurately determine critical tokens as they neglect the \textit{temporal patterns} in attention scores, resulting in a noticeable degradation in LLM performance. To address this challenge, we propose AttentionPredictor, which is the first learning-based critical token identification approach. Specifically, AttentionPredictor learns a lightweight convolution model to capture spatiotemporal patterns and predict the next-token attention score. An appealing feature of AttentionPredictor is that it accurately predicts the attention score while consuming negligible memory. Moreover, we propose a cross-token critical cache prefetching framework that hides the token estimation time overhead to accelerate the decoding stage. By retaining most of the attention information, AttentionPredictor achieves 16$\times$ KV cache compression with comparable LLM performance, significantly outperforming the state-of-the-art.

[Arxiv](https://arxiv.org/abs/2502.04077)