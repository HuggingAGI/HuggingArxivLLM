# # 基于 Chiron 的 LLM 服务分层自动扩展

发布时间：2025年01月14日

`LLM应用

**理由**：这篇论文主要讨论了大型语言模型（LLM）在云服务中的推理请求管理，特别是如何通过自动扩展器（Chiron）来优化资源利用和满足服务级别目标（SLO）。这属于LLM在实际应用中的优化和管理问题，因此归类为LLM应用。` `云计算` `资源管理`

> Hierarchical Autoscaling for Large Language Model Serving with Chiron

# 摘要

> 大型语言模型（LLM）服务正成为云服务提供商的重要工作负载。根据性能SLO要求，LLM推理请求可分为两类：（a）SLO严格（秒级）的交互式请求，和（b）SLO宽松（分钟到小时级）的批量请求。这些SLO可能因到达率、多路复用和配置参数而降低，因此需要在服务实例及其批量大小上使用资源自动扩展。然而，现有LLM服务自动扩展器未考虑请求SLO，导致不必要的扩展和资源利用不足。为此，我们提出了Chiron，一种基于队列大小、利用率和SLO估计的分层反压自动扩展器。实验表明，Chiron的SLO达成率提升高达90%，GPU效率提升高达70%。

> Large language model (LLM) serving is becoming an increasingly important workload for cloud providers. Based on performance SLO requirements, LLM inference requests can be divided into (a) interactive requests that have tight SLOs in the order of seconds, and (b) batch requests that have relaxed SLO in the order of minutes to hours. These SLOs can degrade based on the arrival rates, multiplexing, and configuration parameters, thus necessitating the use of resource autoscaling on serving instances and their batch sizes. However, previous autoscalers for LLM serving do not consider request SLOs leading to unnecessary scaling and resource under-utilization. To address these limitations, we introduce Chiron, an autoscaler that uses the idea of hierarchical backpressure estimated using queue size, utilization, and SLOs. Our experiments show that Chiron achieves up to 90% higher SLO attainment and improves GPU efficiency by up to 70% compared to existing solutions.

[Arxiv](https://arxiv.org/abs/2501.08090)