# Apt-Serve：一种基于混合缓存的自适应请求调度方法，用于实现大规模LLM推理服务

发布时间：2025年04月10日

`LLM应用` `人工智能` `云计算`

> Apt-Serve: Adaptive Request Scheduling on Hybrid Cache for Scalable LLM Inference Serving

# 摘要

> 大型语言模型（LLM）推理服务系统对众多基于LLM的应用至关重要。随着对LLM服务需求的持续增长，如何将这些系统扩展以处理高请求率并满足延迟服务级别目标（SLO），即有效吞吐量，变得至关重要。然而，现有系统往往难以提升有效吞吐量，主要原因在于首次生成令牌时间（TTFT）SLO的显著下降。我们识别出导致这一瓶颈的两个主要原因：(1) 内存密集型的KV缓存限制了GPU内存约束下批处理规模的扩展，(2) 默认的先到先得调度策略强加的 rigid batch 组成。本文中，我们引入了Apt-Serve，一个旨在提升LLM推理服务有效吞吐量的可扩展框架。Apt-Serve采用了一种新的混合缓存方案，将KV缓存与内存高效的隐藏缓存相结合，用于存储可重用的输入隐藏状态向量，从而支持更大批处理规模并提升请求并发能力。基于混合缓存，Apt-Serve采用了自适应运行时调度机制，能够动态优化批处理组成。我们正式定义了自适应调度优化问题，并提出了一种具有理论保证的高效算法。在涵盖从13B到66B参数规模的三个真实世界数据集和LLM上的广泛评估表明，与最先进的推理服务系统相比，Apt-Serve实现了最高达8.8倍的有效吞吐量提升。

> Large language model (LLM) inference serving systems are essential to various LLM-based applications. As demand for LLM services continues to grow, scaling these systems to handle high request rates while meeting latency Service-Level Objectives (SLOs), referred to as effective throughput, becomes critical. However, existing systems often struggle to improve effective throughput, primarily due to a significant decline in Time To First Token (TTFT) SLO attainment. We identify two major causes of this bottleneck: (1) memory-intensive KV cache that limits batch size expansion under GPU memory constraints, and (2) rigid batch composition enforced by the default First-Come-First-Serve scheduling policy. In this paper, we introduce Apt-Serve, a scalable framework designed to enhance effective throughput in LLM inference serving. Apt-Serve features a new hybrid cache scheme that combines KV cache with a memory-efficient hidden cache for reusable input hidden state vectors, allowing large batch sizes and improving request concurrency. Based on the hybrid cache, Apt-Serve employs an adaptive runtime scheduling mechanism that dynamically optimizes batch composition. We formally define the adaptive scheduling optimization problem and propose an efficient algorithm with theoretical guarantees. Extensive evaluations on three real-world datasets and LLMs ranging from 13B to 66B parameters demonstrate that Apt-Serve achieves up to 8.8x improvement in effective throughput compared to the state-of-the-art inference serving systems.

[Arxiv](https://arxiv.org/abs/2504.07494)