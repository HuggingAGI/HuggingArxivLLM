# SwiftSpec：通过扩展异步推测解码实现LLM的超低延迟解码

发布时间：2025年06月12日

`LLM应用

论文摘要：大型语言模型 (LLMs) 的低延迟解码对于聊天机器人和代码助手等应用至关重要，但在单查询设置下生成长输出仍然面临速度瓶颈。先前的研究分别通过推测解码（结合小型草稿模型与大型目标模型）和张量并行技术加速了解码过程。然而，传统方法受限于草稿模型与目标模型之间的计算需求不平衡、KV缓存不一致以及小批量张量并行下的通信开销，难以同时应用这两种技术。本文提出 SwiftSpec，一个针对 LLM 解码实现超低延迟的系统。SwiftSpec 以异步和分散的方式重新设计了推测解码管道，使每个组件能够灵活扩展，并从关键路径中移除草稿开销。为了实现这一设计，SwiftSpec 提出了并行树生成、树感知的 KV 缓存管理以及融合的、延迟优化的内核，以克服上述挑战。在 5 个模型家族和 6 个数据集上，SwiftSpec 较现有的最优推测解码系统平均提升了 1.75 倍的速度。特别地，在 8 块 Nvidia Hopper GPU 上，SwiftSpec 以 348 tokens/s 的速度实现了对 Llama3-70B 的服务，成为目前在该规模下已知的低延迟 LLM 服务最快系统。

LLM应用` `人工智能`

> SwiftSpec: Ultra-Low Latency LLM Decoding by Scaling Asynchronous Speculative Decoding

# 摘要

> 大型语言模型 (LLMs) 的低延迟解码对于聊天机器人和代码助手等应用至关重要，但在单查询设置下生成长输出仍然面临速度瓶颈。先前的研究分别通过推测解码（结合小型草稿模型与大型目标模型）和张量并行技术加速了解码过程。然而，传统方法受限于草稿模型与目标模型之间的计算需求不平衡、KV缓存不一致以及小批量张量并行下的通信开销，难以同时应用这两种技术。本文提出 SwiftSpec，一个针对 LLM 解码实现超低延迟的系统。SwiftSpec 以异步和分散的方式重新设计了推测解码管道，使每个组件能够灵活扩展，并从关键路径中移除草稿开销。为了实现这一设计，SwiftSpec 提出了并行树生成、树感知的 KV 缓存管理以及融合的、延迟优化的内核，以克服上述挑战。在 5 个模型家族和 6 个数据集上，SwiftSpec 较现有的最优推测解码系统平均提升了 1.75 倍的速度。特别地，在 8 块 Nvidia Hopper GPU 上，SwiftSpec 以 348 tokens/s 的速度实现了对 Llama3-70B 的服务，成为目前在该规模下已知的低延迟 LLM 服务最快系统。

> Low-latency decoding for large language models (LLMs) is crucial for applications like chatbots and code assistants, yet generating long outputs remains slow in single-query settings. Prior work on speculative decoding (which combines a small draft model with a larger target model) and tensor parallelism has each accelerated decoding. However, conventional approaches fail to apply both simultaneously due to imbalanced compute requirements (between draft and target models), KV-cache inconsistencies, and communication overheads under small-batch tensor-parallelism. This paper introduces SwiftSpec, a system that targets ultra-low latency for LLM decoding. SwiftSpec redesigns the speculative decoding pipeline in an asynchronous and disaggregated manner, so that each component can be scaled flexibly and remove draft overhead from the critical path. To realize this design, SwiftSpec proposes parallel tree generation, tree-aware KV cache management, and fused, latency-optimized kernels to overcome the challenges listed above. Across 5 model families and 6 datasets, SwiftSpec achieves an average of 1.75x speedup over state-of-the-art speculative decoding systems and, as a highlight, serves Llama3-70B at 348 tokens/s on 8 Nvidia Hopper GPUs, making it the fastest known system for low-latency LLM serving at this scale.

[Arxiv](https://arxiv.org/abs/2506.11309)