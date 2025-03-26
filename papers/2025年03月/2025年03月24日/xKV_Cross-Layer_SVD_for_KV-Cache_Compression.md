# xKV：跨层奇异值分解实现 KV-Cache 压缩

发布时间：2025年03月24日

`LLM应用

理由：这篇论文专注于优化大型语言模型（LLM）的内存使用，特别是KV-Cache的压缩。通过提出xKV方法，作者解决了长上下文窗口推理中的内存瓶颈，属于模型优化和实际应用中的技术改进，因此归类为LLM应用。` `人工智能`

> xKV: Cross-Layer SVD for KV-Cache Compression

# 摘要

> 长上下文窗口的大型语言模型（LLMs）功能强大，但 KV-Cache 的内存占用问题也随之而来。现有研究尝试跨层压缩 KV-Cache，但要么成本过高，要么依赖不切实际的假设。我们发现多层 KV-Cache 的主特征向量高度一致，基于此提出了xKV方法。xKV通过奇异值分解（SVD）将多层 KV-Cache整合到共享子空间，大幅降低内存需求。在Llama-3.1和Qwen2.5等主流模型上测试，xKV的压缩率比现有方法提升6.8倍，准确率提升2.7%。此外，xKV与DeepSeek-Coder-V2等多头潜在注意力模型兼容，在编码任务上实现3倍压缩，性能无损。这一成果展示了xKV在解决长上下文推理内存瓶颈方面的卓越性能。代码已开源：https://github.com/abdelfattah-lab/xKV。

> Large Language Models (LLMs) with long context windows enable powerful applications but come at the cost of high memory consumption to store the Key and Value states (KV-Cache). Recent studies attempted to merge KV-cache from multiple layers into shared representations, yet these approaches either require expensive pretraining or rely on assumptions of high per-token cosine similarity across layers which generally does not hold in practice. We find that the dominant singular vectors are remarkably well-aligned across multiple layers of the KV-Cache. Exploiting this insight, we propose xKV, a simple post-training method that applies Singular Value Decomposition (SVD) on the KV-Cache of grouped layers. xKV consolidates the KV-Cache of multiple layers into a shared low-rank subspace, significantly reducing KV-Cache sizes. Through extensive evaluations on the RULER long-context benchmark with widely-used LLMs (e.g., Llama-3.1 and Qwen2.5), xKV achieves up to 6.8x higher compression rates than state-of-the-art inter-layer technique while improving accuracy by 2.7%. Moreover, xKV is compatible with the emerging Multi-Head Latent Attention (MLA) (e.g., DeepSeek-Coder-V2), yielding a notable 3x compression rates on coding tasks without performance degradation. These results highlight xKV's strong capability and versatility in addressing memory bottlenecks for long-context LLM inference. Our code is publicly available at: https://github.com/abdelfattah-lab/xKV.

[Arxiv](https://arxiv.org/abs/2503.18893)