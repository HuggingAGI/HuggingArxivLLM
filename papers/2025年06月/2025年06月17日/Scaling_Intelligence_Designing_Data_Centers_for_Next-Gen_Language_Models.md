# 扩展智慧：打造下一代语言模型的数据中心

发布时间：2025年06月17日

`LLM应用` `人工智能` `数据中心`

> Scaling Intelligence: Designing Data Centers for Next-Gen Language Models

# 摘要

> 大型语言模型（LLMs）的爆炸式增长——例如拥有1.8万亿参数的GPT-4——要求我们对数据中心架构进行全面重新思考，以确保其可扩展性、效率和成本效益。我们提供了一个综合性的协同设计框架，同时探索了计算性能（FLOPS）、高带宽内存（HBM）的带宽和容量、多种网络拓扑（两层式 vs. 全平面光学）、扩展域的规模，以及在LLMs中常用的并行化/优化策略。我们引入并评估了全平面网络架构，该架构为所有节点提供了统一的高带宽、低延迟连接，并展示了其对性能和可扩展性的变革性影响。通过详细的敏感性分析，我们量化了计算与通信重叠的优势，利用硬件加速的集合操作、更广泛的扩展域以及更大的内存容量。我们的研究涵盖了稀疏（专家混合）和密集的基于变换器的LLMs，揭示了系统设计选择如何影响模型FLOPS利用率（MFU）和整体吞吐量。对于协同设计研究，我们扩展并验证了一个性能建模工具，该工具能够将LLM的运行时间预测与实际测量值控制在10%以内。我们的发现提供了可操作的见解和实用路线图，用于设计能够高效支持万亿参数模型、降低优化复杂性并持续支持AI能力快速发展的AI数据中心。

> The explosive growth of Large Language Models (LLMs) - such as GPT-4 with 1.8 trillion parameters - demands a radical rethinking of data center architecture to ensure scalability, efficiency, and cost-effectiveness. Our work provides a comprehensive co-design framework that jointly explores FLOPS, HBM bandwidth and capacity, multiple network topologies (two-tier vs. FullFlat optical), the size of the scale-out domain, and popular parallelism/optimization strategies used in LLMs. We introduce and evaluate FullFlat network architectures, which provide uniform high-bandwidth, low-latency connectivity between all nodes, and demonstrate their transformative impact on performance and scalability. Through detailed sensitivity analyses, we quantify the benefits of overlapping compute and communication, leveraging hardware-accelerated collectives, wider scale-out domains, and larger memory capacity. Our study spans both sparse (mixture of experts) and dense transformer-based LLMs, revealing how system design choices affect Model FLOPS Utilization (MFU = Model flops per token x Observed tokens per sec / Peak flops of the hardware) and overall throughput. For the co-design study, we extended and validated a performance modeling tool capable of predicting LLM runtime within 10% of real-world measurements. Our findings offer actionable insights and a practical roadmap for designing AI data centers that can efficiently support trillion-parameter models, reduce optimization complexity, and sustain the rapid evolution of AI capabilities.

[Arxiv](https://arxiv.org/abs/2506.15006)