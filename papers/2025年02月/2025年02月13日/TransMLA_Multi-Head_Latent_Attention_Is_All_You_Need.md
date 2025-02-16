# TransMLA：多头潜在注意力机制，一切你所需

发布时间：2025年02月13日

`LLM应用` `人工智能` `计算机科学`

> TransMLA: Multi-Head Latent Attention Is All You Need

# 摘要

> 现代大型语言模型（LLMs）在当前硬件上常面临通信瓶颈，而非单纯计算限制。多头潜在注意力（MLA）通过在键值（KV）层使用低秩矩阵，允许压缩后的潜在KV状态缓存，从而显著减少KV缓存大小，提升推理速度。此外，MLA借助上投影矩阵增强表达能力，以额外计算换取更低通信开销。尽管MLA在Deepseek V2/V3/R1中已展现高效与有效，但多数模型提供商仍依赖组查询注意力（GQA），尚未计划采用MLA。本文证明GQA可始终用MLA表示，保持相同KV缓存开销，反之则不然。为推广MLA应用，我们推出TransMLA——一种后训练方法，可将基于GQA的主流预训练模型（如LLaMA、Qwen、Mixtral）转换为MLA模型。转换后，模型可通过额外训练提升表达能力，而不增加KV缓存大小。此外，我们计划开发MLA专用推理加速技术，保持转换模型的低延迟，从而实现更高效的Deepseek R1蒸馏。

> Modern large language models (LLMs) often encounter communication bottlenecks on current hardware, rather than purely computational constraints. Multi-head Latent Attention (MLA) tackles this challenge by using low-rank matrices in the key-value (KV) layers, thereby allowing compressed latent KV states to be cached. This approach significantly reduces the KV cache size relative to traditional multi-head attention, leading to faster inference. Moreover, MLA employs an up-projection matrix to increase expressiveness, trading additional computation for reduced communication overhead. Although MLA has demonstrated efficiency and effectiveness in Deepseek V2/V3/R1, many major model providers still rely on Group Query Attention (GQA) and have not announced any plans to adopt MLA. In this paper, we show that GQA can always be represented by MLA while maintaining the same KV cache overhead, but the converse does not hold. To encourage broader use of MLA, we introduce TransMLA, a post-training method that converts widely used GQA-based pre-trained models (e.g., LLaMA, Qwen, Mixtral) into MLA-based models. After conversion, the model can undergo additional training to boost expressiveness without increasing the KV cache size. Furthermore, we plan to develop MLA-specific inference acceleration techniques to preserve low latency in transformed models, thus enabling more efficient distillation of Deepseek R1.

[Arxiv](https://arxiv.org/abs/2502.07864)