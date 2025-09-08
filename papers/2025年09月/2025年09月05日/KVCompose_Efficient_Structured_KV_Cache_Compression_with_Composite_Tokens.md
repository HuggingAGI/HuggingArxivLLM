# KVCompose：基于复合令牌的高效结构化KV缓存压缩

发布时间：2025年09月05日

`LLM理论` `基础理论`

> KVCompose: Efficient Structured KV Cache Compression with Composite Tokens

# 摘要

> 大型语言模型（LLMs）借助键值（KV）缓存实现高效的自回归解码；但缓存大小会随上下文长度和模型深度线性增长，这已成为长上下文推理的主要瓶颈。现有的KV缓存压缩方法要么依赖僵化的启发式规则，要么因注意力头的个体差异破坏张量布局，要么需要专用计算内核。
  为此，我们提出一种简单却高效的KV缓存压缩框架——基于注意力引导的层自适应复合令牌。该方法通过聚合注意力分数来评估令牌重要性，独立筛选各注意力头的特定令牌，并将其对齐为复合令牌，从而保持现有推理引擎所需的统一缓存结构。全局分配机制会进一步调整各层的保留预算，为包含高信息量令牌的层分配更多存储空间。这种方法在保证精度的同时大幅降低内存占用，性能持续优于现有的结构化和半结构化方法。关键的是，该方法与标准推理流程完全兼容，为高效部署长上下文LLM提供了实用且可扩展的解决方案。

> Large language models (LLMs) rely on key-value (KV) caches for efficient autoregressive decoding; however, cache size grows linearly with context length and model depth, becoming a major bottleneck in long-context inference. Prior KV cache compression methods either enforce rigid heuristics, disrupt tensor layouts with per-attention-head variability, or require specialized compute kernels.
  We propose a simple, yet effective, KV cache compression framework based on attention-guided, layer-adaptive composite tokens. Our method aggregates attention scores to estimate token importance, selects head-specific tokens independently, and aligns them into composite tokens that respect the uniform cache structure required by existing inference engines. A global allocation mechanism further adapts retention budgets across layers, assigning more capacity to layers with informative tokens. This approach achieves significant memory reduction while preserving accuracy, consistently outperforming prior structured and semi-structured methods. Crucially, our approach remains fully compatible with standard inference pipelines, offering a practical and scalable solution for efficient long-context LLM deployment.

[Arxiv](https://arxiv.org/abs/2509.05165)