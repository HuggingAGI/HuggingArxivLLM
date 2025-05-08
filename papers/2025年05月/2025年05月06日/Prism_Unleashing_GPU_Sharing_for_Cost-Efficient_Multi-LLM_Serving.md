# 棱镜：通过 GPU 共享实现多 LLM 服务的高效部署

发布时间：2025年05月06日

`LLM应用` `云计算`

> Prism: Unleashing GPU Sharing for Cost-Efficient Multi-LLM Serving

# 摘要

> 托管大型语言模型（LLMs）成本高昂，尤其是对于托管多个模型的服务提供商而言，因此降低成本至关重要。多 LLM 托管的独特工作负载模式带来了新的机遇与挑战。模型的长尾流行度及其漫长的空闲期为通过 GPU 共享提高利用率提供了机会。然而，现有的 GPU 共享系统缺乏在运行时调整资源分配和共享策略的能力，因此在面对快速波动的工作负载时，它们无法有效满足延迟服务级别目标（SLO）。本文介绍了 Prism，这是一个多 LLM 托管系统，通过充分利用 GPU 共享的潜力，实现了成本效率和服务级别目标的双重达成。其核心在于解决现有系统的一个关键限制——缺乏跨模型内存协调能力，这对于在动态工作负载下灵活共享 GPU 内存至关重要。Prism 通过两项关键设计实现了这一点。首先，它支持按需内存分配，通过动态映射物理到虚拟内存页，允许在共享 GPU 的模型之间灵活重新分配内存。其次，它通过两级调度策略提高内存效率，根据模型的实时需求动态调整共享策略。基于真实工作负载的评估表明，与最先进的系统相比，Prism 实现了超过 【数学公式】 的成本节约和 【数学公式】 的服务级别目标达成。

> Serving large language models (LLMs) is expensive, especially for providers hosting many models, making cost reduction essential. The unique workload patterns of serving multiple LLMs (i.e., multi-LLM serving) create new opportunities and challenges for this task. The long-tail popularity of models and their long idle periods present opportunities to improve utilization through GPU sharing. However, existing GPU sharing systems lack the ability to adjust their resource allocation and sharing policies at runtime, making them ineffective at meeting latency service-level objectives (SLOs) under rapidly fluctuating workloads.
  This paper presents Prism, a multi-LLM serving system that unleashes the full potential of GPU sharing to achieve both cost efficiency and SLO attainment. At its core, Prism tackles a key limitation of existing systems$\unicode{x2014}$the lack of $\textit{cross-model memory coordination}$, which is essential for flexibly sharing GPU memory across models under dynamic workloads. Prism achieves this with two key designs. First, it supports on-demand memory allocation by dynamically mapping physical to virtual memory pages, allowing flexible memory redistribution among models that space- and time-share a GPU. Second, it improves memory efficiency through a two-level scheduling policy that dynamically adjusts sharing strategies based on models' runtime demands. Evaluations on real-world traces show that Prism achieves more than $2\times$ cost savings and $3.3\times$ SLO attainment compared to state-of-the-art systems.

[Arxiv](https://arxiv.org/abs/2505.04021)