# # SkyLB: 感知区域的跨区域负载均衡器

发布时间：2025年05月29日

`其他

摘要主要讨论了大规模语言模型的多区域部署优化，特别是通过负载均衡来提高资源利用率和成本效益，属于系统架构和优化层面，而非直接涉及LLM的应用或理论，因此归类为其他。` `云计算` `分布式系统`

> SkyLB: A Locality-Aware Cross-Region Load Balancer for LLM Inference

# 摘要

> 大规模语言模型的高效多区域部署仍面临诸多挑战。由于成本和GPU资源的限制，服务提供商通常采用长期承诺的实例（如预留实例或本地集群）在多个区域部署LLMs。然而，这些实例往往因区域本地流量处理和每日流量波动而利用率较低。本文提出了一种基于跨区域流量处理的区域感知型多区域负载均衡器 SkyLB，该方法能够聚合各区域的每日流量模式。通过这种方式，SkyLB使服务提供商可以根据预期的全球需求预留实例，而非仅仅基于各区域的峰值需求。同时，SkyLB保留了KV-Cache的本地性并实现了负载均衡，从而在不牺牲性能的前提下提高了成本效益。SkyLB通过一种缓存感知的跨区域流量处理器和基于检查待处理请求的有选择的推式负载均衡机制实现了上述目标。基于真实工作负载的评估表明，与现有负载均衡器相比，SkyLB的吞吐量提高了1.12至2.06倍，延迟降低了1.74至6.30倍，同时将总服务成本降低了25%。

> Serving Large Language Models (LLMs) efficiently in multi-region setups remains a challenge. Due to cost and GPU availability concerns, providers typically deploy LLMs in multiple regions using instance with long-term commitments, like reserved instances or on-premise clusters, which are often underutilized due to their region-local traffic handling and diurnal traffic variance. In this paper, we introduce SkyLB, a locality-aware multi-region load balancer for LLM inference that aggregates regional diurnal patterns through cross-region traffic handling. By doing so, SkyLB enables providers to reserve instances based on expected global demand, rather than peak demand in each individual region. Meanwhile, SkyLB preserves KV-Cache locality and a balanced load, ensuring cost efficiency without sacrificing performance. SkyLB achieves this with a cache-aware cross-region traffic handler and a selective pushing load balancing mechanism based on checking pending requests. Our evaluation on real-world workloads shows that it achieves 1.12-2.06x higher throughput and 1.74-6.30x lower latency compared to existing load balancers, while reducing total serving cost by 25%.

[Arxiv](https://arxiv.org/abs/2505.24095)