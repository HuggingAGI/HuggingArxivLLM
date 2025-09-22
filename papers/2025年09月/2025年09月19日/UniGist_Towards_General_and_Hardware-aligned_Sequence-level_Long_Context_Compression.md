# UniGist：面向通用与硬件对齐的序列级长上下文压缩

发布时间：2025年09月19日

`LLM应用` `基础理论`

> UniGist: Towards General and Hardware-aligned Sequence-level Long Context Compression

# 摘要

> 大型语言模型处理长上下文输入的能力不断提升，但键值（KV）缓存的内存开销仍是其通用部署的主要瓶颈。尽管已有多种压缩策略被探索，但序列级压缩——即丢弃某些标记的完整KV缓存——尤其具有挑战性，因其可能丢失重要的上下文信息。为此，我们提出了UniGist——一种序列级长上下文压缩框架，它通过细粒度地用特殊压缩标记（gist）替换原始标记，高效保留上下文信息。我们采用无分块训练策略，并设计了带有gist移位技巧的高效内核，从而实现了GPU训练的优化。该方案还支持灵活推理，可实际移除压缩标记，进而实现实时内存节省。在多个长上下文任务上的实验显示，UniGist显著提升了压缩质量，尤其在细节回忆任务和长程依赖建模中表现突出。

> Large language models are increasingly capable of handling long-context inputs, but the memory overhead of key-value (KV) cache remains a major bottleneck for general-purpose deployment. While various compression strategies have been explored, sequence-level compression, which drops the full KV caches for certain tokens, is particularly challenging as it can lead to the loss of important contextual information. To address this, we introduce UniGist, a sequence-level long-context compression framework that efficiently preserves context information by replacing raw tokens with special compression tokens (gists) in a fine-grained manner. We adopt a chunk-free training strategy and design an efficient kernel with a gist shift trick, enabling optimized GPU training. Our scheme also supports flexible inference by allowing the actual removal of compressed tokens, resulting in real-time memory savings. Experiments across multiple long-context tasks demonstrate that UniGist significantly improves compression quality, with especially strong performance in detail-recalling tasks and long-range dependency modeling.

[Arxiv](https://arxiv.org/abs/2509.15763)