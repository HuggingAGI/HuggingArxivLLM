# LServe：高效长序列大语言模型服务，基于统一稀疏注意力机制

发布时间：2025年02月20日

`LLM应用` `云计算`

> LServe: Efficient Long-sequence LLM Serving with Unified Sparse Attention

# 摘要

> 大型语言模型（LLMs）在处理长序列方面展现了巨大潜力，但高效运行这些长上下文模型仍具挑战性。这主要是因为预填充阶段注意力机制的二次计算复杂度，以及解码阶段 KV 缓存带来的大内存占用。为了解决这些问题，我们提出了 LServe，一个通过混合稀疏注意力加速长序列 LLM 服务的高效系统。该方法将不同硬件友好的、结构化的稀疏模式统一到一个框架中，用于预填充和解码注意力，其中对不重要令牌的计算以块为单位跳过。LServe 展示了长上下文 LLM 注意力中静态和动态稀疏性的兼容性。这种设计通过结合这些优化实现了倍增加速。具体来说，我们将一半的注意力头转换为几乎免费的流式头，在预填充和解码阶段均实现。此外，我们发现仅需固定数量的 KV 页面即可保持长上下文能力，无论上下文长度如何。然后，我们设计了一个基于查询中心相似性的分层 KV 页面选择策略，动态剪枝 KV 页面。平均而言，与 vLLM 相比，LServe 将 LLM 预填充加速 2.9 倍，解码加速 1.3-2.1 倍，同时保持长上下文准确性。代码已发布在 https://github.com/mit-han-lab/omniserve。


> Large language models (LLMs) have shown remarkable potential in processing long sequences, yet efficiently serving these long-context models remains challenging due to the quadratic computational complexity of attention in the prefilling stage and the large memory footprint of the KV cache in the decoding stage. To address these issues, we introduce LServe, an efficient system that accelerates long-sequence LLM serving via hybrid sparse attention. This method unifies different hardware-friendly, structured sparsity patterns for both prefilling and decoding attention into a single framework, where computations on less important tokens are skipped block-wise. LServe demonstrates the compatibility of static and dynamic sparsity in long-context LLM attention. This design enables multiplicative speedups by combining these optimizations. Specifically, we convert half of the attention heads to nearly free streaming heads in both the prefilling and decoding stages. Additionally, we find that only a constant number of KV pages is required to preserve long-context capabilities, irrespective of context length. We then design a hierarchical KV page selection policy that dynamically prunes KV pages based on query-centric similarity. On average, LServe accelerates LLM prefilling by up to 2.9x and decoding by 1.3-2.1x over vLLM, maintaining long-context accuracy. Code is released at https://github.com/mit-han-lab/omniserve.

[Arxiv](https://arxiv.org/abs/2502.14866)