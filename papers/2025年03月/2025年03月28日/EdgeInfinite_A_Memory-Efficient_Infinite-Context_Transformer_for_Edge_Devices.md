# EdgeInfinite：专为边缘设备设计的内存高效无限上下文Transformer模型

发布时间：2025年03月28日

`LLM理论

摘要讨论了大型语言模型（LLMs）在处理长序列时的挑战，并提出了一种新的内存高效解决方案，EdgeInfinite。这属于对模型内部机制的优化和理论分析，因此归类为LLM理论。` `计算机科学`

> EdgeInfinite: A Memory-Efficient Infinite-Context Transformer for Edge Devices

# 摘要

> 基于Transformer的大型语言模型（LLMs）在处理长序列时面临挑战，原因在于注意力机制的二次复杂度和不断增长的Key-Value (KV)缓存内存需求。现有的KV缓存优化方法在长输出任务中难以避免不可逆的令牌驱逐问题，而替代的序列建模架构在现有的Transformer基础设施中采用成本高昂。我们提出EdgeInfinite，一种针对无限上下文的内存高效解决方案，通过可训练的内存门控模块将压缩内存集成到基于Transformer的LLMs中。这种方法与标准Transformer架构完全兼容，仅需微调一小部分参数，并支持选择性激活内存门控模块以实现长短期上下文任务路由。实验结果表明，EdgeInfinite在长上下文基准测试中与基于Transformer的LLMs基线模型性能相当，同时优化了内存消耗和首令牌生成时间。

> Transformer-based large language models (LLMs) encounter challenges in processing long sequences on edge devices due to the quadratic complexity of attention mechanisms and growing memory demands from Key-Value (KV) cache. Existing KV cache optimizations struggle with irreversible token eviction in long-output tasks, while alternative sequence modeling architectures prove costly to adopt within established Transformer infrastructure. We present EdgeInfinite, a memory-efficient solution for infinite contexts that integrates compressed memory into Transformer-based LLMs through a trainable memory-gating module. This approach maintains full compatibility with standard Transformer architectures, requiring fine-tuning only a small part of parameters, and enables selective activation of the memory-gating module for long and short context task routing. The experimental result shows that EdgeInfinite achieves comparable performance to baseline Transformer-based LLM on long context benchmarks while optimizing memory consumption and time to first token.

[Arxiv](https://arxiv.org/abs/2503.22196)