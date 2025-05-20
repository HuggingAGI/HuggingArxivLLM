# HydraInfer: 面向多模态大型语言模型服务的混合分散式调度方案

发布时间：2025年05月18日

`LLM应用` `人工智能` `分布式系统`

> HydraInfer: Hybrid Disaggregated Scheduling for Multimodal Large Language Model Serving

# 摘要

> 多模态大语言模型（MLLMs）正迅速发展，实现了跨模态理解和生成，推动人工智能向通用人工智能迈进。然而，现有的多模态推理系统通常基于语言模型架构设计，将图像处理和语言处理整合为单一调度单元。这种设计难以满足不同阶段在计算资源、内存访问模式和服务级别目标（SLO）方面的异构需求，导致资源利用率低、请求延迟高，最终无法满足多样化推理场景的服务要求。为了解决这些挑战，我们提出了HydraInfer——一种采用混合编码-预填-解码（EPD）解耦架构的高效多模态推理系统。通过将编码、预填和解码三个阶段调度到不同的异构推理实例上，系统能够在各阶段间灵活重新分配资源，显著减少空闲计算、缓解资源瓶颈，提升整体系统吞吐量和扩展性。此外，HydraInfer还支持基于阶段的批量处理策略，增强负载均衡，实现视觉模型与语言模型的并行执行，进一步优化推理性能。在真实多模态推理工作负载下的实验表明，与现有最优系统（如vLLM）相比，HydraInfer在单节点8xH800 GPU集群上可实现高达4倍的推理吞吐量提升，同时满足90百分位请求SLO。

> Multimodal Large Language Models (MLLMs) have been rapidly advancing, enabling cross-modal understanding and generation, and propelling artificial intelligence towards artificial general intelligence. However, existing MLLM inference systems are typically designed based on the architecture of language models, integrating image processing and language processing as a single scheduling unit. This design struggles to accommodate the heterogeneous demands of different stages in terms of computational resources, memory access patterns, and service-level objectives (SLOs), leading to low resource utilization and high request latency, ultimately failing to meet the service requirements of diverse inference scenarios.
  To address these challenges, we propose HydraInfer, an efficient MLLM inference system that adopts a Hybrid Encode-Prefill-Decode (EPD) Disaggregation architecture. By scheduling the three stages - encode, prefill, and decode - onto separate heterogeneous inference instances, the system flexibly reallocates resources across stages, significantly reducing idle computation, alleviating resource bottlenecks, and improving overall system throughput and scalability. In addition, HydraInfer supports a stage-level batching strategy that enhances load balancing, enables parallel execution of visual and language models, and further optimizes inference performance. Experiments under real multimodal inference workloads demonstrate that HydraInfer can achieve up to 4x higher inference throughput compared to state-of-the-art systems (e.g., vLLM) on a single-node 8xH800 GPU cluster, while meeting the 90th percentile request SLO.

[Arxiv](https://arxiv.org/abs/2505.12658)