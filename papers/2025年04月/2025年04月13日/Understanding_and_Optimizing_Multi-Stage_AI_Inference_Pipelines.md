# # 深入理解与优化多阶段AI推理流水线
深入理解与优化多阶段AI推理流水线

发布时间：2025年04月13日

`LLM应用` `人工智能` `硬件系统`

> Understanding and Optimizing Multi-Stage AI Inference Pipelines

# 摘要

> 大型语言模型（LLMs）的快速发展推动了对日益复杂的推理管道和硬件平台的需求。现代LLM服务已超越传统的预填-解码工作流，整合了检索增强生成（RAG）、键值（KV）缓存检索、动态模型路由和多步推理等多阶段流程。这些阶段具有多样化的计算需求，需要集成GPU、ASIC、CPU和以内存为中心架构的分布式系统。然而，现有模拟器缺乏对这些异构多引擎工作流的高保真建模能力，限制了它们在架构决策中的作用。

为填补这一空白，我们推出HERMES——一个异构多阶段LLM推理执行模拟器。HERMES能够模拟复杂的硬件层次结构中多样化的请求阶段，包括RAG、KV检索、推理、预填和解码。与先前框架不同，HERMES支持异构客户端并发执行多个模型，同时结合先进的批处理策略和多级内存层次结构。通过将真实硬件追踪与分析建模相结合，HERMES捕捉了混合CPU-加速器部署中的关键权衡，如内存带宽竞争、集群间通信延迟和批处理效率。通过案例研究，我们探讨了推理阶段对端到端延迟的影响、混合管道的最优批处理策略，以及远程KV缓存检索的架构影响。HERMES助力系统设计师驾驭LLM推理的不断演变，为下一代AI负载的硬件-软件协同优化提供切实可行的见解。


> The rapid evolution of Large Language Models (LLMs) has driven the need for increasingly sophisticated inference pipelines and hardware platforms. Modern LLM serving extends beyond traditional prefill-decode workflows, incorporating multi-stage processes such as Retrieval Augmented Generation (RAG), key-value (KV) cache retrieval, dynamic model routing, and multi step reasoning. These stages exhibit diverse computational demands, requiring distributed systems that integrate GPUs, ASICs, CPUs, and memory-centric architectures. However, existing simulators lack the fidelity to model these heterogeneous, multi-engine workflows, limiting their ability to inform architectural decisions.
  To address this gap, we introduce HERMES, a Heterogeneous Multi-stage LLM inference Execution Simulator. HERMES models diverse request stages; including RAG, KV retrieval, reasoning, prefill, and decode across complex hardware hierarchies. HERMES supports heterogeneous clients executing multiple models concurrently unlike prior frameworks while incorporating advanced batching strategies and multi-level memory hierarchies. By integrating real hardware traces with analytical modeling, HERMES captures critical trade-offs such as memory bandwidth contention, inter-cluster communication latency, and batching efficiency in hybrid CPU-accelerator deployments. Through case studies, we explore the impact of reasoning stages on end-to-end latency, optimal batching strategies for hybrid pipelines, and the architectural implications of remote KV cache retrieval. HERMES empowers system designers to navigate the evolving landscape of LLM inference, providing actionable insights into optimizing hardware-software co-design for next-generation AI workloads.

[Arxiv](https://arxiv.org/abs/2504.09775)