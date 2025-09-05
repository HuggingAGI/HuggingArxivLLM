# PagedEviction：结构化分块KV缓存剪枝助力大型语言模型高效推理

发布时间：2025年09月04日

`LLM应用` `基础理论`

> PagedEviction: Structured Block-wise KV Cache Pruning for Efficient Large Language Model Inference

# 摘要

> KV缓存通过存储已处理标记的注意力状态，显著提升了大型语言模型（LLM）的推理效率，加快了后续标记的生成速度。但随着序列长度增加，KV缓存很快成为主要的内存瓶颈。为此，我们提出PagedEviction——一种新颖的细粒度结构化KV缓存剪枝策略，旨在提升vLLM中PagedAttention的内存效率。与现有依赖注意力标记重要性或跨vLLM页面驱逐标记的方法不同，PagedEviction针对分页内存布局，设计了高效的块级驱逐算法。该方法与PagedAttention无缝集成，无需修改其CUDA注意力内核。在LongBench基准测试集上，我们对Llama-3.1-8B-Instruct、Llama-3.2-1B-Instruct和Llama-3.2-3B-Instruct模型进行了评估，结果显示PagedEviction在长上下文任务中不仅降低了内存占用，准确率也优于基线方法。

> KV caching significantly improves the efficiency of Large Language Model (LLM) inference by storing attention states from previously processed tokens, enabling faster generation of subsequent tokens. However, as sequence length increases, the KV cache quickly becomes a major memory bottleneck. To address this, we propose PagedEviction, a novel fine-grained, structured KV cache pruning strategy that enhances the memory efficiency of vLLM's PagedAttention. Unlike existing approaches that rely on attention-based token importance or evict tokens across different vLLM pages, PagedEviction introduces an efficient block-wise eviction algorithm tailored for paged memory layouts. Our method integrates seamlessly with PagedAttention without requiring any modifications to its CUDA attention kernels. We evaluate PagedEviction across Llama-3.1-8B-Instruct, Llama-3.2-1B-Instruct, and Llama-3.2-3B-Instruct models on the LongBench benchmark suite, demonstrating improved memory usage with better accuracy than baselines on long context tasks.

[Arxiv](https://arxiv.org/abs/2509.04377)