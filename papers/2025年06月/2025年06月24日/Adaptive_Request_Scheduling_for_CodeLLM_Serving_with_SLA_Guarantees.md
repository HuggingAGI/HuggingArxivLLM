# 自适应请求调度：保障CodeLLM服务的服务级别协议

发布时间：2025年06月24日

`LLM应用` `软件开发` `云计算`

> Adaptive Request Scheduling for CodeLLM Serving with SLA Guarantees

# 摘要

> 代码大型语言模型（CodeLLMs）正逐步融入现代软件开发工作流，但要在资源受限的自托管环境中高效运行仍面临挑战。现有的LLM服务系统通过连续批处理提升吞吐量，但其静态批量大小配置无法应对波动的请求速率或异构工作负载，导致频繁的SLA违规和性能不稳定。本研究提出了一种动态批处理策略SABER，能够实时预测每项请求的SLA可行性并调整决策。与最佳静态配置相比，SABER将有效吞吐量提升了26%，延迟波动降低了45%，且无需手动调优或重启服务。研究表明，具备SLA意识且自适应的调度是实现稳健、高性能CodeLLM服务的关键。

> Code Large Language Models (CodeLLMs) are increasingly integrated into modern software development workflows, yet efficiently serving them in resource-constrained, self-hosted environments remains a significant challenge. Existing LLM serving systems employs Continuous Batching for throughput improvement. However, they rely on static batch size configurations that cannot adapt to fluctuating request rates or heterogeneous workloads, leading to frequent SLA (Service Level Agreement) violations and unstable performance. In this study, We propose SABER, a dynamic batching strategy that predicts per-request SLA feasibility and adjusts decisions in real time. SABER improves goodput by up to 26% over the best static configurations and reduces latency variability by up to 45%, all without manual tuning or service restarts. Our results demonstrate that SLA-aware, adaptive scheduling is key to robust, high-performance CodeLLM serving.

[Arxiv](https://arxiv.org/abs/2506.19677)