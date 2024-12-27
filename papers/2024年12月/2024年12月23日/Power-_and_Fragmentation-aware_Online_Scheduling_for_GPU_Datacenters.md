# 面向 GPU 数据中心的功率和碎片感知在线调度

发布时间：2024年12月23日

`其他` `数据中心` `人工智能`

> Power- and Fragmentation-aware Online Scheduling for GPU Datacenters

# 摘要

> 人工智能和大型语言模型的兴起促使数据中心在复杂的训练和推理任务中加大了 GPU 的使用量，这对运营成本、能源需求以及大规模计算基础设施的环境影响颇大。此项工作致力于解决 GPU 数据中心的在线调度难题，即要在不了解任务未来到达情况下去调度任务。我们聚焦于两个目标：将 GPU 碎片最小化以及降低功耗。当部分 GPU 分配妨碍了剩余资源的高效利用，特别是数据中心接近满容量时，就会产生 GPU 碎片。近期的一种调度策略——碎片梯度下降（FGD），借助碎片度量来应对此问题。鉴于 GPU 的巨大功率需求，降低功耗也极为关键。为此，我们提出了 PWR 这一新的调度策略，通过选取节能的 GPU 和 CPU 组合来将功耗最小化。这涉及一个集成到 Kubernetes 得分插件中的简化功耗测量模型。通过在模拟集群中的大量实验评估，我们展示了 PWR 与 FGD 相结合时，是如何在降低功耗和最小化 GPU 碎片之间达成平衡的。

> The rise of Artificial Intelligence and Large Language Models is driving increased GPU usage in data centers for complex training and inference tasks, impacting operational costs, energy demands, and the environmental footprint of large-scale computing infrastructures. This work addresses the online scheduling problem in GPU datacenters, which involves scheduling tasks without knowledge of their future arrivals. We focus on two objectives: minimizing GPU fragmentation and reducing power consumption. GPU fragmentation occurs when partial GPU allocations hinder the efficient use of remaining resources, especially as the datacenter nears full capacity. A recent scheduling policy, Fragmentation Gradient Descent (FGD), leverages a fragmentation metric to address this issue. Reducing power consumption is also crucial due to the significant power demands of GPUs. To this end, we propose PWR, a novel scheduling policy to minimize power usage by selecting power-efficient GPU and CPU combinations. This involves a simplified model for measuring power consumption integrated into a Kubernetes score plugin. Through an extensive experimental evaluation in a simulated cluster, we show how PWR, when combined with FGD, achieves a balanced trade-off between reducing power consumption and minimizing GPU fragmentation.

[Arxiv](https://arxiv.org/abs/2412.17484)