# EchoLM: 实时知识蒸馏助力LLM服务加速

发布时间：2025年01月22日

`LLM应用

**理由**：这篇论文主要讨论了如何通过EchoLM系统优化大型语言模型（LLMs）的部署和响应效率，特别是在大规模应用场景中。论文提出的方法涉及请求的语义相似性分析、历史请求的缓存与复用、以及请求路由和缓存回放机制的优化。这些内容都属于如何在实际应用中提升LLMs的性能和效率，因此应归类为LLM应用。` `系统优化`

> EchoLM: Accelerating LLM Serving with Real-time Knowledge Distillation

# 摘要

> 大型语言模型（LLMs）在众多应用中表现卓越，但其庞大的资源消耗和高延迟使得大规模部署成为难题。我们的研究发现，超过60%的用户请求存在语义相似性，这意味着请求间存在知识共享的可能。然而，简单地缓存和复用历史响应会导致质量显著下降。本文提出的EchoLM系统，通过利用历史请求作为示例来指导响应生成，实现了对高效LLMs的选择性卸载。然而，实现这种实时知识转移需要在响应质量、延迟和系统吞吐量之间进行精细权衡。对于新请求，EchoLM能够识别出相似且高效的示例，并将其前置到输入中以优化响应。在大规模场景下，EchoLM能够自适应地将请求路由到不同能力的LLMs，同时兼顾响应质量和服务负载。EchoLM还采用了成本感知的缓存回放机制，离线提升示例质量和覆盖率，从而最大化缓存效用和运行时效率。对数百万开源请求的评估显示，EchoLM的吞吐量提升了1.4-5.9倍，同时平均减少了28-71%的延迟，且未影响响应质量。

> Large language models (LLMs) have excelled in various applications, yet serving them at scale is challenging due to their substantial resource demands and high latency. Our real-world studies reveal that over 60% of user requests to LLMs have semantically similar counterparts, suggesting the potential for knowledge sharing among requests. However, naively caching and reusing past responses leads to large quality degradation. In this paper, we introduce EchoLM, an in-context caching system that leverages historical requests as examples to guide response generation, enabling selective offloading of requests to more efficient LLMs. However, enabling this real-time knowledge transfer leads to intricate tradeoffs between response quality, latency, and system throughput at scale. For a new request, EchoLM identifies similar, high-utility examples and efficiently prepends them to the input for better response. At scale, EchoLM adaptively routes requests to LLMs of varying capabilities, accounting for response quality and serving loads. EchoLM employs a cost-aware cache replay mechanism to improve example quality and coverage offline, maximizing cache utility and runtime efficiency. Evaluations on millions of open-source requests demonstrate that EchoLM has a throughput improvement of 1.4-5.9x while reducing latency by 28-71% without hurting response quality on average.

[Arxiv](https://arxiv.org/abs/2501.12689)