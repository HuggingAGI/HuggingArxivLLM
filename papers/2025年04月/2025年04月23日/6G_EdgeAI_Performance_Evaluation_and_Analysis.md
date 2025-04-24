# 6G边缘AI性能评估与分析

发布时间：2025年04月23日

`LLM应用` `人工智能`

> 6G EdgeAI: Performance Evaluation and Analysis

# 摘要

> 基于大型语言模型（LLMs）的生成式AI（GenAI）服务正日益实现实时交互，但现有的5G多接入边缘计算（MEC）架构往往将通信与计算视为独立领域，这限制了它们满足严格延迟要求的能力。为了解决这一挑战，我们提出了一种名为综合通信与计算（ICC）的框架，该框架使计算能力能够直接部署在无线接入网络（RAN）节点中，并协同管理带宽和计算资源。通过队列理论分析，我们发现ICC的表现优于5G MEC，其服务能力（定义为在给定延迟预算内完成指定比例任务的最大到达率）提高了98%。通过考虑基于Transformer的LLM工作负载、实际GPU规格和基于优先级的调度方案的系统级仿真，我们进一步验证了这些改进。仿真结果表明，ICC将服务能力提升了60%，展示了其在实现6G中高效且经济的实时GenAI服务方面的潜力。

> Generative AI (GenAI) services powered by large language models (LLMs) increasingly deliver real-time interactions, yet existing 5G multi-access edge computing (MEC) architectures often treat communication and computing as separate domains, limiting their ability to meet stringent latency requirements. To address this challenge, we introduce an Integrated Communication and Computing (ICC) framework where computing capabilities are enabled to reside directly in radio access network (RAN) nodes and jointly manage bandwidth and computing resources. Our queueing-theoretic analysis shows that ICC outperforms 5G MEC, achieving higher service capacity (defined as the maximum arrival rate that maintains a specified fraction of jobs completed within a given delay budget) by 98%. We corroborate these gains through system-level simulations that account for transformer-based LLM workloads, realistic GPU specifications, and a priority-based scheduling scheme. The simulations show that ICC improves service capacity by 60%, demonstrating its potential to enable efficient, cost-effective real-time GenAI services in 6G.

[Arxiv](https://arxiv.org/abs/2504.16529)