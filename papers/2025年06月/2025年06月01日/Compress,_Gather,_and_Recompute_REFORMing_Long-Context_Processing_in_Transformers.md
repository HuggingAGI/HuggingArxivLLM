# 压缩、收集与重组：Transformer长上下文处理的REFORM方法

发布时间：2025年06月01日

`LLM应用

理由：这篇论文主要探讨了如何优化大型语言模型在处理超长上下文时的效率和性能，提出了一种新的推理框架REFORM。它属于LLM的应用层面，专注于解决实际应用中的具体问题，如处理长上下文的挑战，并通过实验验证了其优越性。因此，它被归类为LLM应用。`

> Compress, Gather, and Recompute: REFORMing Long-Context Processing in Transformers

# 摘要

> 大型语言模型在实际应用中的 popularity 日益攀升，但处理超长上下文（常超出模型预训练时的上下文限制）已成为一大挑战。现有高效长上下文处理方法虽有潜力，但基于循环压缩的方法在信息保留上力有未逮，而随机访问方法则需耗费大量内存资源。为此，我们提出了REFORM——一个新颖的两阶段推理框架，旨在高效处理长上下文。首先，REFORM逐步处理输入块，同时维护压缩的 KV 缓存，构建跨层上下文嵌入，并通过提前退出策略提升效率。其次，它利用相似性匹配识别和收集关键令牌，并选择性地重新计算 KV 缓存。在1M上下文长度下，REFORM较基线方法分别在RULER和BABILong上实现了50%和27%以上的性能提升。它还在Infinite-Bench和MM-NIAH上表现优异，凸显了在不同任务和领域的灵活性。此外，REFORM将推理时间缩短30%，峰值内存使用减少5%，在高效性和优越性能间实现了完美平衡。

> As large language models increasingly gain popularity in real-world applications, processing extremely long contexts, often exceeding the model's pre-trained context limits, has emerged as a critical challenge. While existing approaches to efficient long-context processing show promise, recurrent compression-based methods struggle with information preservation, whereas random access approaches require substantial memory resources. We introduce REFORM, a novel inference framework that efficiently handles long contexts through a two-phase approach. First, it incrementally processes input chunks while maintaining a compressed KV cache, constructs cross-layer context embeddings, and utilizes early exit strategy for improved efficiency. Second, it identifies and gathers essential tokens via similarity matching and selectively recomputes the KV cache. Compared to baselines, REFORM achieves over 50% and 27% performance gains on RULER and BABILong respectively at 1M context length. It also outperforms baselines on Infinite-Bench and MM-NIAH, demonstrating flexibility across diverse tasks and domains. Additionally, REFORM reduces inference time by 30% and peak memory usage by 5%, achieving both efficiency and superior performance.

[Arxiv](https://arxiv.org/abs/2506.01215)