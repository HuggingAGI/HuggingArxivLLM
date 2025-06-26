# 大型语言模型推荐系统中的模型并行与数据并行优化方法探讨

发布时间：2025年06月20日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在推荐系统中的应用，并提出了一种混合并行训练方案以优化计算与通信效率。该研究关注的是如何在实际应用中提升LLMs的训练性能，属于LLM应用类别。` `推荐系统` `分布式训练`

> Research on Model Parallelism and Data Parallelism Optimization Methods in Large Language Model-Based Recommendation Systems

# 摘要

> 大型语言模型（LLMs）在推荐系统中的广泛应用带来了计算与通信瓶颈的挑战，主要源于其庞大的参数规模和数据量。本文系统性地研究了在推荐场景下分布式训练LLMs的两类优化方法：模型并行和数据并行。在模型并行方面，我们实现了张量并行与流水线并行，并引入自适应负载均衡机制以优化跨设备通信效率。对于数据并行，我们对比了同步与异步模式，结合梯度压缩与稀疏化技术，搭配高效的聚合通信框架，显著提升了带宽利用率。基于真实推荐数据集的模拟服务环境实验表明，与传统单模式并行相比，我们提出的混合并行方案使训练吞吐量提升超过30%，资源利用率提升约20%，同时保持了良好的扩展性和鲁棒性。最后，我们探讨了不同并行策略在在线部署中的权衡，并展望了异构硬件集成与自动化调度技术的未来发展方向。

> With the rapid adoption of large language models (LLMs) in recommendation systems, the computational and communication bottlenecks caused by their massive parameter sizes and large data volumes have become increasingly prominent. This paper systematically investigates two classes of optimization methods-model parallelism and data parallelism-for distributed training of LLMs in recommendation scenarios. For model parallelism, we implement both tensor parallelism and pipeline parallelism, and introduce an adaptive load-balancing mechanism to reduce cross-device communication overhead. For data parallelism, we compare synchronous and asynchronous modes, combining gradient compression and sparsification techniques with an efficient aggregation communication framework to significantly improve bandwidth utilization. Experiments conducted on a real-world recommendation dataset in a simulated service environment demonstrate that our proposed hybrid parallelism scheme increases training throughput by over 30% and improves resource utilization by approximately 20% compared to traditional single-mode parallelism, while maintaining strong scalability and robustness. Finally, we discuss trade-offs among different parallel strategies in online deployment and outline future directions involving heterogeneous hardware integration and automated scheduling technologies.

[Arxiv](https://arxiv.org/abs/2506.17551)