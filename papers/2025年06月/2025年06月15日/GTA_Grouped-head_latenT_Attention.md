# GTA: 分组潜在注意力

发布时间：2025年06月15日

`LLM应用` `模型优化`

> GTA: Grouped-head latenT Attention

# 摘要

> 注意力机制是大型语言模型 (LLMs) 的成功基石，但其巨大的计算和内存开销对优化效率和性能提出了挑战。随着文本长度的增加，KV 缓存和注意力计算的规模迅速扩大，这成为了一个关键瓶颈，使得在计算和内存资源有限的硬件上部署变得困难。我们发现，注意力机制中存在大量冗余，因为 KV 缓存可以显著压缩，而不同头之间的注意力图显示出高度相似性，这表明许多计算和存储都是不必要的。基于这些发现，我们提出了 	extbf{G}rouped-Head Laten	extbf{T} 	extbf{A}ttention (GTA)，这是一种新型注意力机制，在减少内存使用和计算复杂度的同时保持性能。GTA 包括两个组成部分：(1) 一种共享注意力图机制，可以在多个头之间复用注意力分数，从而减少键缓存的大小；(2) 一种非线性值解码器，通过学习投影将值缓存压缩到潜在空间，进一步降低内存需求。与 Grouped-Query Attention 相比，GTA 将注意力计算的 FLOPs 减少了高达 \emph{62.5\%}，并将 KV 缓存的大小缩减了高达 \emph{70\%}，同时避免了 Multi-Head Latent Attention 的额外开销，从而提高了 LLM 的部署效率。因此，采用 GTA 的模型实现了端到端推理速度的 \emph{2x} 提升，其中预填充得益于计算成本的降低，解码则得益于更小的缓存占用。

> Attention mechanisms underpin the success of large language models (LLMs), yet their substantial computational and memory overhead poses challenges for optimizing efficiency and performance. A critical bottleneck arises as KV cache and attention computations scale rapidly with text length, challenging deployment on hardware with limited computational and memory resources. We observe that attention mechanisms exhibit substantial redundancy, since the KV cache can be significantly compressed and attention maps across heads display high similarity, revealing that much of the computation and storage is unnecessary. Leveraging these insights, we propose \textbf{G}rouped-Head Laten\textbf{T} \textbf{A}ttention (GTA), a novel attention mechanism that reduces memory usage and computational complexity while maintaining performance. GTA comprises two components: (1) a shared attention map mechanism that reuses attention scores across multiple heads, decreasing the key cache size; and (2) a nonlinear value decoder with learned projections that compresses the value cache into a latent space, further cutting memory needs. GTA cuts attention computation FLOPs by up to \emph{62.5\%} versus Grouped-Query Attention and shrink the KV cache by up to \emph{70\%}, all while avoiding the extra overhead of Multi-Head Latent Attention to improve LLM deployment efficiency. Consequently, GTA models achieve a \emph{2x} increase in end-to-end inference speed, with prefill benefiting from reduced computational cost and decoding benefiting from the smaller cache footprint.

[Arxiv](https://arxiv.org/abs/2506.17286)