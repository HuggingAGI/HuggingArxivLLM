# 多实例间GPU功率分配研究

发布时间：2025年01月29日

`其他

**理由**：这篇论文主要讨论了云数据中心的电源管理，特别是GPU的功耗估计问题。虽然提到了大型语言模型（LLM）推理任务，但论文的核心内容是功耗估计和电源管理，而不是直接研究或应用LLM。因此，它不属于Agent、RAG、LLM应用或LLM理论中的任何一个分类，更适合归类为其他。` `数据中心` `能源管理`

> On the Partitioning of GPU Power among Multi-Instances

# 摘要

> # 摘要
云数据中心的电源管理至关重要，它不仅能降低成本、提升性能，还能减少环境影响。GPU在机器学习和生成式AI等任务中扮演着关键角色，同时也是功耗的主要来源。NVIDIA的多实例GPU（MIG）技术通过分区隔离和资源跟踪，实现了多租户共享GPU，显著提升了利用率。然而，由于硬件支持的不足，准确分配MIG实例间的GPU功耗仍是一大挑战。本文通过开发软件方法，成功估计了每个MIG分区的功耗。我们深入分析了NVIDIA GPU的利用率指标，发现构建高精度的轻量级方法颇具难度。为此，我们探索了基于机器学习的功耗模型，以实现精准的分区级功耗估计。研究显示，单一的通用离线模型或建模方法难以应对多样化的工作负载，尤其是在并发MIG使用的情况下。而基于执行中工作负载的分区级利用率指标构建的在线模型，则能显著提升准确性。通过NVIDIA A100 GPU，我们展示了该方法在矩阵乘法和大型语言模型推理等任务中的精准分区级功耗估计，为透明和公平的碳报告提供了有力支持。

> Efficient power management in cloud data centers is essential for reducing costs, enhancing performance, and minimizing environmental impact. GPUs, critical for tasks like machine learning (ML) and GenAI, are major contributors to power consumption. NVIDIA's Multi-Instance GPU (MIG) technology improves GPU utilization by enabling isolated partitions with per-partition resource tracking, facilitating GPU sharing by multiple tenants. However, accurately apportioning GPU power consumption among MIG instances remains challenging due to a lack of hardware support. This paper addresses this challenge by developing software methods to estimate power usage per MIG partition. We analyze NVIDIA GPU utilization metrics and find that light-weight methods with good accuracy can be difficult to construct. We hence explore the use of ML-based power models to enable accurate, partition-level power estimation. Our findings reveal that a single generic offline power model or modeling method is not applicable across diverse workloads, especially with concurrent MIG usage, and that online models constructed using partition-level utilization metrics of workloads under execution can significantly improve accuracy. Using NVIDIA A100 GPUs, we demonstrate this approach for accurate partition-level power estimation for workloads including matrix multiplication and Large Language Model inference, contributing to transparent and fair carbon reporting.

[Arxiv](https://arxiv.org/abs/2501.17752)