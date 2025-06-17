# # 华为云矩阵384上的大型语言模型部署实践

发布时间：2025年06月14日

`其他` `AI数据中心` `LLM服务`

> Serving Large Language Models on Huawei CloudMatrix384

# 摘要

> 大型语言模型（LLMs）的快速发展，得益于参数规模的不断扩大、专家混合（MoE）架构的采用以及上下文长度的扩展，给AI基础设施带来了前所未有的挑战。传统AI集群在计算强度、内存带宽、芯片间通信和延迟等方面存在局限性，再加上多变的工作负载和严格的SLA要求，使得问题更加复杂。解决这些问题需要从根本上重新设计软硬件集成方案。本文介绍了华为云矩阵（Huawei CloudMatrix），这是一种下一代AI数据中心架构，已在量产级的CloudMatrix384超节点中实现。该架构集成了384个昇腾910C NPUs和192个鲲鹏CPU，通过超高速带宽的统一总线（UB）网络互连，支持直接的全对全通信和资源动态池化。这些特性优化了通信密集型操作的性能，如大规模MoE专家并行和分布式键值缓存访问。为了充分发挥CloudMatrix384的潜力，我们提出了CloudMatrix-Infer，这是一种先进的LLM服务解决方案，包含三大核心创新：点对点服务架构，可独立扩展预填充、解码和缓存功能；支持通过基于UB的高效令牌分发实现大规模专家并行策略（EP320）；以及硬件感知优化，包括专用算子、基于微批处理的流水线和INT8量化。使用DeepSeek-R1模型进行的评估表明，CloudMatrix-Infer达到了最先进的效率水平：每个NPU的预填充吞吐量为6,688 token/s，解码吞吐量为1,943 token/s（TPOT<50 ms）。它在吞吐量和延迟之间实现了有效平衡，在严格的15 ms延迟限制下仍能保持538 token/s的性能，而INT8量化则在各种基准测试中保持了模型的准确性。

> The rapid evolution of large language models (LLMs), driven by growing parameter scales, adoption of mixture-of-experts (MoE) architectures, and expanding context lengths, imposes unprecedented demands on AI infrastructure. Traditional AI clusters face limitations in compute intensity, memory bandwidth, inter-chip communication, and latency, compounded by variable workloads and strict service-level objectives. Addressing these issues requires fundamentally redesigned hardware-software integration. This paper introduces Huawei CloudMatrix, a next-generation AI datacenter architecture, realized in the production-grade CloudMatrix384 supernode. It integrates 384 Ascend 910C NPUs and 192 Kunpeng CPUs interconnected via an ultra-high-bandwidth Unified Bus (UB) network, enabling direct all-to-all communication and dynamic pooling of resources. These features optimize performance for communication-intensive operations, such as large-scale MoE expert parallelism and distributed key-value cache access. To fully leverage CloudMatrix384, we propose CloudMatrix-Infer, an advanced LLM serving solution incorporating three core innovations: a peer-to-peer serving architecture that independently scales prefill, decode, and caching; a large-scale expert parallelism strategy supporting EP320 via efficient UB-based token dispatch; and hardware-aware optimizations including specialized operators, microbatch-based pipelining, and INT8 quantization. Evaluation with the DeepSeek-R1 model shows CloudMatrix-Infer achieves state-of-the-art efficiency: prefill throughput of 6,688 tokens/s per NPU and decode throughput of 1,943 tokens/s per NPU (<50 ms TPOT). It effectively balances throughput and latency, sustaining 538 tokens/s even under stringent 15 ms latency constraints, while INT8 quantization maintains model accuracy across benchmarks.

[Arxiv](https://arxiv.org/abs/2506.12708)