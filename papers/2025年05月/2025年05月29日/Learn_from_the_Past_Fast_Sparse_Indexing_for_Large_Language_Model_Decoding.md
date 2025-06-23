# 以史为鉴：大型语言模型解码的高效稀疏索引方法

发布时间：2025年05月29日

`LLM应用

理由：这篇论文专注于优化大语言模型（LLM）在长上下文中的解码过程，特别是通过提出一种名为LFPS的方法来提高解码效率和减少内存需求。这属于LLM的应用层面，因为它直接针对LLM在实际应用中的性能优化，而不是理论上的模型改进或与其他领域（如RAG或Agent）的结合。` `计算优化`

> Learn from the Past: Fast Sparse Indexing for Large Language Model Decoding

# 摘要

> 大语言模型 (LLMs) 对长上下文的支持日益增强，但解码过程中键值 (KV) 缓存的内存需求激增，成为 GPU 内存容量和 PCIe 带宽的瓶颈。稀疏注意力机制通过仅计算部分键值对的注意力权重来缓解这一问题，但其索引计算通常需要遍历所有键向量，导致显著的计算和数据传输开销。现有方法往往将每个解码步骤视为独立过程，忽视了历史解码信息中的时间相关性。为此，我们提出了 LFPS（从过去学习稀疏索引），这是一种基于历史注意力模式动态构建稀疏索引候选的加速方法。LFPS 捕捉了解码器注意力中的两种常见趋势——垂直模式（关注固定位置）和斜线模式（关注相对位置），并结合位置扩展策略，有效预测当前步骤的 Top-k 索引。我们在 LongBench-RULER 等具有挑战性的长上下文基准测试中验证了 LFPS，以 Llama-3.1-8B-Instruct 作为基线模型。实验结果表明，在 RTX 4090 GPU 和 Xeon Gold 6430 的单个 CPU 核心上，LFPS 分别实现了相对于全注意力 22.8 倍和相对于精确 Top-k 检索 9.6 倍的加速，同时保持生成准确性。这表明 LFPS 为长上下文 LLM 推理中的解码优化提供了一种实用且高效的解决方案。

> As large language models (LLMs) continue to support increasingly longer contexts, the memory demand for key-value (KV) caches during decoding grows rapidly, becoming a critical bottleneck in both GPU memory capacity and PCIe bandwidth. Sparse attention mechanisms alleviate this issue by computing attention weights only for selected key-value pairs. However, their indexing computation typically requires traversing all key vectors, resulting in significant computational and data transfer overhead. To reduce the cost of index retrieval, existing methods often treat each decoding step as an independent process, failing to exploit the temporal correlations embedded in historical decoding information. To this end, we propose LFPS(Learn From the Past for Sparse Indexing), an acceleration method that dynamically constructs sparse indexing candidates based on historical attention patterns. LFPS captures two prevalent trends in decoder attention -vertical patterns (attending to fixed positions) and slash patterns (attending to relative positions) -and incorporates a positional expansion strategy to effectively predict the Top-k indices for the current step. We validate LFPS on challenging long-context benchmarks such as LongBench-RULER, using Llama-3.1-8B-Instruct as the base model. Experimental results show that LFPS achieves up to 22.8$\times$ speedup over full attention and 9.6$\times$ speedup over exact Top-k retrieval on an RTX 4090 GPU and a single CPU core of a Xeon Gold 6430, respectively, while preserving generation accuracy. These results demonstrate that LFPS offers a practical and efficient solution for decoding optimization in long-context LLM inference.

[Arxiv](https://arxiv.org/abs/2506.15704)