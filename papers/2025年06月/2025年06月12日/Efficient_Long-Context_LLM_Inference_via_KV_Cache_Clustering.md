# 基于 KV 缓存聚类的高效长上下文 LLM 推理

发布时间：2025年06月12日

`LLM应用

摘要分析：这篇论文专注于优化大型语言模型（LLM）在处理长上下文时的内存使用和计算效率。通过提出Chelsea框架，作者优化了KV缓存的管理，显著减少了内存使用并提高了计算速度。这属于模型应用层面的优化，因此归类为LLM应用。` `人工智能` `计算机系统`

> Efficient Long-Context LLM Inference via KV Cache Clustering

# 摘要

> 扩展上下文窗口的大型语言模型（LLMs）在复杂任务中应用日益广泛。然而，长上下文LLMs所需的大量键值（KV）缓存带来了显著的部署挑战。现有方法要么丢弃未来生成所需的关键信息，要么因计算开销过高而导致效率提升有限。本文中，我们介绍了Chelsea——一个简单而有效的在线KV缓存聚类框架。基于观察到键状态在序列维度上具有高度相似性的发现，我们提出了一种高效的聚类方法：将序列划分为块，并采用块软匹配策略，通过块内的交替分区和相似性识别实现聚类。随后，Chelsea将每个聚类中的KV缓存合并为一个质心。此外，我们对计算复杂度和块内分区策略的最优性进行了理论分析。在各种模型和长上下文基准上的广泛实验表明，Chelsea在保持模型性能的同时，将KV缓存内存使用量减少高达80%。此外，Chelsea仅需极低的计算开销，即可将推理解码阶段加速最多3.19倍，并将端到端延迟减少最多2.72倍。

> Large language models (LLMs) with extended context windows have become increasingly prevalent for tackling complex tasks. However, the substantial Key-Value (KV) cache required for long-context LLMs poses significant deployment challenges. Existing approaches either discard potentially critical information needed for future generations or offer limited efficiency gains due to high computational overhead. In this paper, we introduce Chelsea, a simple yet effective framework for online KV cache clustering. Our approach is based on the observation that key states exhibit high similarity along the sequence dimension. To enable efficient clustering, we divide the sequence into chunks and propose Chunked Soft Matching, which employs an alternating partition strategy within each chunk and identifies clusters based on similarity. Chelsea then merges the KV cache within each cluster into a single centroid. Additionally, we provide a theoretical analysis of the computational complexity and the optimality of the intra-chunk partitioning strategy. Extensive experiments across various models and long-context benchmarks demonstrate that Chelsea achieves up to 80% reduction in KV cache memory usage while maintaining comparable model performance. Moreover, with minimal computational overhead, Chelsea accelerates the decoding stage of inference by up to 3.19$\times$ and reduces end-to-end latency by up to 2.72$\times$.

[Arxiv](https://arxiv.org/abs/2506.11418)