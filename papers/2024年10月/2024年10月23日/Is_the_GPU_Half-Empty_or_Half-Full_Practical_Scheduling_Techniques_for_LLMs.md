# GPU 是半空还是半满？LLM 的实用调度技巧

发布时间：2024年10月23日

`LLM应用

**解释**：这篇论文主要讨论了大型语言模型（LLMs）服务系统中的调度策略，目的是提升吞吐量和性能。虽然涉及调度技术，但其核心关注点是如何优化LLM在实际部署中的性能，因此属于LLM应用的范畴。` `云计算` `调度系统`

> Is the GPU Half-Empty or Half-Full? Practical Scheduling Techniques for LLMs

# 摘要

> 大型语言模型（LLMs）的服务系统通过并发处理多个请求来提升吞吐量。然而，硬件资源在并发请求间的复用涉及复杂的调度决策。实际服务系统通常分两步进行调度：首先，负载均衡器将请求分发到持有LLM副本的不同服务器；其次，服务器上的引擎级调度器决定请求的执行、排队或抢占时机。改进的调度策略能为LLM部署带来广泛收益，且常可作为现有策略的“即插即用”替代方案。本文调研了文献和实际系统中的调度技术，发现文献中的调度器虽性能优异但复杂度高，而实际部署中的调度器虽易于实现却常错失性能提升机会。基于此，我们提出了两种新的调度技术，它们不仅易于实现，还在生产工作负载跟踪上表现更优。

> Serving systems for Large Language Models (LLMs) improve throughput by processing several requests concurrently. However, multiplexing hardware resources between concurrent requests involves non-trivial scheduling decisions. Practical serving systems typically implement these decisions at two levels: First, a load balancer routes requests to different servers which each hold a replica of the LLM. Then, on each server, an engine-level scheduler decides when to run a request, or when to queue or preempt it. Improved scheduling policies may benefit a wide range of LLM deployments and can often be implemented as "drop-in replacements" to a system's current policy. In this work, we survey scheduling techniques from the literature and from practical serving systems. We find that schedulers from the literature often achieve good performance but introduce significant complexity. In contrast, schedulers in practical deployments often leave easy performance gains on the table but are easy to implement, deploy and configure. This finding motivates us to introduce two new scheduling techniques, which are both easy to implement, and outperform current techniques on production workload traces.

[Arxiv](https://arxiv.org/abs/2410.17840)