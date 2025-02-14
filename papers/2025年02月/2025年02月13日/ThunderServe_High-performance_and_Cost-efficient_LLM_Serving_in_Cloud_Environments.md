# ThunderServe：在云环境中打造高性能、高性价比的LLM服务方案

发布时间：2025年02月13日

`LLM应用` `云计算` `高性能计算`

> ThunderServe: High-performance and Cost-efficient LLM Serving in Cloud Environments

# 摘要

> 大型语言模型（LLMs）近期在多种任务中展现了卓越的能力。在云环境中部署异构GPU类型的LLMs，对于解决GPU短缺问题并实现更具成本效益的解决方案至关重要。然而，云环境中网络环境的多样性和不同GPU类型的多样性给实现高性能服务带来了挑战。

为此，我们提出了ThunderServe——一个专为异构云环境设计的高性能且成本高效的LLM服务系统。我们引入了一种新型调度算法，该算法优化了LLM服务的部署计划，以适应云环境中异构资源和网络带宽条件。此外，我们提出了一种轻量级的重调度机制，旨在适应在线环境的波动（例如节点故障、负载转移等），而无需进行代价高昂的正在进行服务的重启。

实验结果表明，与现有最优系统相比，在相同的价格预算下，ThunderServe在异构云环境中实现了高达2.1倍的吞吐量提升，平均提升1.7倍，并且将延迟降低至最高2.5倍，平均降低1.5倍。这表明，选择云服务提供了更具成本效益的解决方案。


> Recent developments in large language models (LLMs) have demonstrated their remarkable proficiency in a range of tasks. Compared to in-house homogeneous GPU clusters, deploying LLMs in cloud environments with diverse types of GPUs is crucial for addressing the GPU shortage problem and being more cost-effective. However, the diversity of network environments and various GPU types on the cloud bring difficulties to achieving high-performance serving. In this work, we propose ThunderServe, a high-performance and cost-efficient LLM serving system for heterogeneous cloud environments. We introduce a novel scheduling algorithm, which optimizes the deployment plan of LLM serving to accommodate the heterogeneous resource and network bandwidth conditions in cloud environments. Furthermore, we propose a lightweight re-scheduling mechanism, designed to adapt to fluctuating online conditions (e.g., node failures, workload shifts) without the need for costly restarts of ongoing services. Empirical results in both heterogeneous cloud and homogeneous in-house environments reveal that ThunderServe delivers up to a 2.1$\times$ and on average a $1.7\times$ increase in throughput and achieves up to a 2.5$\times$ and on average a $1.5\times$ reduction in latency deadlines compared with state-of-the-art systems given the same price budget, suggesting opting for cloud services provides a more cost-efficient solution.

[Arxiv](https://arxiv.org/abs/2502.09334)