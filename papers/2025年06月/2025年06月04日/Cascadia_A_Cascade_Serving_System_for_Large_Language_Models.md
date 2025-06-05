# # 级联服务系统Cascadia：面向大型语言模型的级联服务架构
Cascadia 是一个专为大型语言模型打造的级联服务架构，旨在优化模型服务的效率与性能。

发布时间：2025年06月04日

`LLM应用

理由：这篇论文探讨了如何通过模型级联优化大型语言模型的推理服务，属于应用层面的研究，旨在提升服务性能。` `云计算` `分布式系统`

> Cascadia: A Cascade Serving System for Large Language Models

# 摘要

> 大型语言模型（LLMs）的最新进展凸显了对快速响应和高质量答案的迫切需求。更强大的模型固然能带来更好的结果，但推理延迟也随之增加；相比之下，较小的模型运行更快，但能力有限。近期研究提出通过模型级联平衡这一延迟与质量的权衡：将简单的查询分配给较小的模型，而将复杂的查询路由到较大的模型。然而，实现高效的级联服务仍面临诸多挑战。现有框架在处理（i）不同LLMs的巨大且多变的资源需求，（ii）LLM工作负载的内在异构性，以及（iii）系统部署与路由策略的协同优化方面仍显不足。基于这些观察，我们推出了Cascadia——一个专为快速、保质的LLM服务设计的新型级联服务框架，用于调度请求路由和部署模型级联。Cascadia采用双层优化方法：在内层，它使用混合整数线性规划，根据LLM信息和工作负载特性选择资源分配和平行策略；在外层，它应用加权Tchebycheff算法，迭代协同优化由内层产生的路由策略和系统部署。我们在多种工作负载轨迹和不同模型级联（包括DeepSeek和Llama系列）上的广泛评估表明，Cascadia相较于单模型部署和最先进的级联服务基线，性能有了显著提升：延迟SLO紧了多达4倍（平均提升2.3倍），吞吐量提高了多达5倍（平均提升2.4倍），同时保持了目标答案质量。

> Recent advances in large language models (LLMs) have intensified the need to deliver both rapid responses and high-quality answers. More powerful models yield better results but incur higher inference latency, whereas smaller models are faster yet less capable. Recent work proposes balancing this latency-quality trade-off using model cascades, which route simpler queries to smaller models and more complex ones to larger models. However, enabling efficient cascade serving remains challenging. Current frameworks lack effective mechanisms for handling (i) the huge and varying resource demands of different LLMs, (ii) the inherent heterogeneity of LLM workloads, and (iii) the co-optimization of system deployment and routing strategy. Motivated by these observations, we introduce Cascadia, a novel cascade serving framework designed explicitly to schedule request routing and deploy model cascades for fast, quality-preserving LLM serving. Cascadia employs a bi-level optimization method: at the inner level, it uses a mixed-integer linear program to select resource allocations and parallelism strategies based on LLM information and workload characteristics; at the outer level, it applies a weighted Tchebycheff algorithm to iteratively co-optimize the routing strategy and the system deployment produced by the inner level. Our extensive evaluation on diverse workload traces and different model cascades (DeepSeek and the Llama series) demonstrates that Cascadia significantly outperforms both single-model deployments and the state-of-the-art cascade serving baseline, achieving up to 4x (2.3x on average) tighter latency SLOs and up to 5x (2.4x on average) higher throughput while maintaining target answer quality.

[Arxiv](https://arxiv.org/abs/2506.04203)