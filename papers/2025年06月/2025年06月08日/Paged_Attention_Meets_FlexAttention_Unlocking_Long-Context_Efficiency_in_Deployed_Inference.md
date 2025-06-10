# 分页注意力与FlexAttention携手：为部署推理中的长上下文效率解锁新可能

发布时间：2025年06月08日

`LLM应用` `人工智能` `计算机系统`

> Paged Attention Meets FlexAttention: Unlocking Long-Context Efficiency in Deployed Inference

# 摘要

> 大语言模型（LLMs）在处理长上下文推理时，传统键值（KV）缓存机制导致严重的内存低效问题。本研究提出了一种创新的PagedAttention与PyTorch FlexAttention集成方案，有效解决了整体KV缓存分配的碎片化和低效问题。我们的融合注意力内核在IBM的Foundation Model Stack（FMS）中实现，能够高效聚合分散的KV数据。在NVIDIA L4 GPU（24GB显存）上的基准测试显示，使用全局KV缓存时，推理延迟显著降低，延迟随序列长度从128到2048个token呈线性增长（约2倍），而无缓存情况下延迟呈指数级增长。尽管单步评估的峰值内存使用量基本不变（主要由模型权重和激活占用），但分页注意力机制仅在序列长度超过2048个token时带来轻微内存增量，得益于其基于2的幂次缓存分配策略。我们开源了完整实现，并探讨了其对未来长上下文模型部署的潜在影响。

> Large Language Models (LLMs) encounter severe memory inefficiencies during long-context inference due to conventional handling of key-value (KV) caches. In this work, we introduce a novel integration of PagedAttention with PyTorch's FlexAttention, addressing internal fragmentation and inefficiencies associated with monolithic KV cache allocations. Implemented within IBM's Foundation Model Stack (FMS), our fused attention kernel efficiently gathers scattered KV data. Our benchmarks on an NVIDIA L4 GPU (24GB) demonstrate significantly reduced inference latency, growing only linearly (~2x) with sequence length from 128 to 2048 tokens when utilizing a global KV cache, compared to exponential latency increases without caching. While peak memory usage remains largely unchanged for single-step evaluations (dominated by model weights and activations), paged attention causes minimal incremental memory usage, observable only at sequence lengths exceeding 2048 tokens due to its power-of-two cache allocations. We open-source the full implementation and discuss its implications for future long-context model deployment.

[Arxiv](https://arxiv.org/abs/2506.07311)