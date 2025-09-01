# 奥德赛：自适应策略选择赋能弹性分布式训练

发布时间：2025年08月29日

`其他` `基础理论`

> Odyssey: Adaptive Policy Selection for Resilient Distributed Training

# 摘要

> 大型语言模型的训练常因各类故障频繁中断，因此亟需强大的容错机制。现有的无备份方法（如冗余计算、动态并行和数据重路由）均存在性能损耗问题，具体表现为持续开销、冗长的重新配置或恢复后的低效。为此，我们提出了Odyssey——一种自适应容错系统，能够在故障发生时智能选择最优恢复策略。Odyssey通过统一性能模型、快速执行计划搜索、精准性能预估及高效通信优化实现了这一目标。32卡集群实验显示，Odyssey可将恢复后与无故障训练的性能差距控制在11.00%以内，同时确保模型收敛和内存高效利用。与现有先进方法相比，Odyssey的平均吞吐量分别比Oobleck和Recycle提升了1.229倍和1.355倍。

> Training large language models faces frequent interruptions due to various faults, demanding robust fault-tolerance. Existing backup-free methods, such as redundant computation, dynamic parallelism, and data rerouting, each incur performance penalties, whether from ongoing overhead, lengthy reconfigurations, or post-recovery inefficiencies. We propose Odyssey, an adaptive fault-tolerant system that intelligently selects optimal recovery strategies when a failure occurs. Odyssey achieves this through a unified performance model, expedient execution plan search, accurate performance estimation, and efficient communication optimizations. Experiments on a 32-card cluster show that Odyssey maintains a performance gap of within 11.00% between post-recovery and failure-free training, while preserving model convergence and efficient memory usage. Compared to state-of-the-art methods, Odyssey achieves up to 1.229x and 1.355x higher average throughput than Oobleck and Recycle, respectively.

[Arxiv](https://arxiv.org/abs/2508.21613)