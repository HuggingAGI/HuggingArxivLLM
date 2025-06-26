# # 大型语言模型推荐系统中的模型并行与数据并行优化方法研究

发布时间：2025年06月20日

`LLM应用` `推荐系统` `分布式计算`

> Research on Model Parallelism and Data Parallelism Optimization Methods in Large Language Model-Based Recommendation Systems

# 摘要

> 大规模语言模型（LLMs）在推荐系统中的广泛应用，带来了计算与通信瓶颈的严峻挑战。本文系统性地研究了两类优化方法——模型并行与数据并行，用于推荐场景下大规模语言模型的分布式训练。在模型并行方面，我们实现了张量并行与流水线并行，并引入自适应负载均衡机制以减少设备间通信开销。在数据并行方面，我们对比了同步与异步模式，结合梯度压缩与稀疏化技术，搭配高效的聚合通信框架，显著提升了带宽利用率。实验表明，相较于传统单模式并行，我们的混合并行方案在真实推荐数据集上训练吞吐量提升超30%，资源利用率提升约20%，同时保持了良好的可扩展性与鲁棒性。最后，我们探讨了在线部署中不同并行策略的权衡，并展望了异构硬件集成与自动化调度技术的未来发展方向。

> With the rapid adoption of large language models (LLMs) in recommendation systems, the computational and communication bottlenecks caused by their massive parameter sizes and large data volumes have become increasingly prominent. This paper systematically investigates two classes of optimization methods-model parallelism and data parallelism-for distributed training of LLMs in recommendation scenarios. For model parallelism, we implement both tensor parallelism and pipeline parallelism, and introduce an adaptive load-balancing mechanism to reduce cross-device communication overhead. For data parallelism, we compare synchronous and asynchronous modes, combining gradient compression and sparsification techniques with an efficient aggregation communication framework to significantly improve bandwidth utilization. Experiments conducted on a real-world recommendation dataset in a simulated service environment demonstrate that our proposed hybrid parallelism scheme increases training throughput by over 30% and improves resource utilization by approximately 20% compared to traditional single-mode parallelism, while maintaining strong scalability and robustness. Finally, we discuss trade-offs among different parallel strategies in online deployment and outline future directions involving heterogeneous hardware integration and automated scheduling technologies.

[Arxiv](https://arxiv.org/abs/2506.17551)