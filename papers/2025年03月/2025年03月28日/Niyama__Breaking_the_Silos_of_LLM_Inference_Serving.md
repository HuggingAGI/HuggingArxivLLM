# # Niyama：打破LLM推理服务的孤岛

发布时间：2025年03月28日

`LLM应用` `云计算` `服务系统`

> Niyama : Breaking the Silos of LLM Inference Serving

# 摘要

> 大型语言模型（LLMs）的广泛应用催生了各类对延迟需求迥异的应用场景。然而，现有的LLM服务框架由于采用孤立的基础设施和粗粒度的工作负载分离方式（如交互式与批处理），导致资源利用率低下，难以实现细粒度的服务质量（QoS）区分，进而引发运营效率低下、资源过度配置以及在流量高峰时的负载管理问题。

我们提出了一种新型的QoS驱动推理服务系统——Niyama，它能够在共享基础设施上实现多种工作负载的高效协同调度。Niyama通过细粒度的QoS分类，让应用程序能够精确指定延迟需求，并根据实时系统状态动态调整调度策略。借助LLM推理的可预测执行特性，Niyama创新性地引入动态分块机制，在严格保证服务质量的同时提升整体吞吐量。此外，Niyama采用平衡公平与效率的混合优先级策略，并通过选择性请求降级机制实现过载条件下的优雅服务降级。实验结果表明，Niyama相较于传统孤立部署，服务能力显著提升32%，同时服务质量得到保障。特别是在极端负载条件下，Niyama将服务级别目标（SLO）违规率降低了一个数量级，远超现有策略的表现。

> The widespread adoption of Large Language Models (LLMs) has enabled diverse applications with very different latency requirements. Existing LLM serving frameworks rely on siloed infrastructure with coarse-grained workload segregation -- interactive and batch -- leading to inefficient resource utilization and limited support for fine-grained Quality-of-Service (QoS) differentiation. This results in operational inefficiencies, over-provisioning and poor load management during traffic surges.
  We present Niyama, a novel QoS-driven inference serving system that enables efficient co-scheduling of diverse workloads on shared infrastructure. Niyama introduces fine-grained QoS classification allowing applications to specify precise latency requirements, and dynamically adapts scheduling decisions based on real-time system state. Leveraging the predictable execution characteristics of LLM inference, Niyama implements a dynamic chunking mechanism to improve overall throughput while maintaining strict QoS guarantees. Additionally, Niyama employs a hybrid prioritization policy that balances fairness and efficiency, and employs selective request relegation that enables graceful service degradation during overload conditions. Our evaluation demonstrates that Niyama increases serving capacity by 32% compared to current siloed deployments, while maintaining QoS guarantees. Notably, under extreme load, our system reduces SLO violations by an order of magnitude compared to current strategies.

[Arxiv](https://arxiv.org/abs/2503.22562)