# 云LLM推理中的碳足迹分摊：年龄感知CPU核心管理

发布时间：2025年01月27日

`LLM应用

理由：这篇论文主要讨论了大型语言模型（LLM）在云推理集群中的应用，特别是如何通过优化CPU管理技术来减少碳排放和提高资源利用率。虽然涉及了硬件和可持续性方面的内容，但其核心关注点仍然是LLM在实际应用中的性能和效率问题，因此应归类为LLM应用。` `云计算` `可持续发展`

> Aging-aware CPU Core Management for Embodied Carbon Amortization in Cloud LLM Inference

# 摘要

> # 摘要
随着大型语言模型（LLM）的广泛应用，云LLM推理集群的快速扩展导致了体现碳的积累——即制造和供应IT资产所产生的排放，主要集中在推理服务器的CPU上。本文探讨了云LLM推理可持续增长的挑战，重点在于延长CPU体现碳的摊销周期。考虑到硅老化的可靠性风险，我们提出了一种老化感知的CPU核心管理技术，通过延迟CPU老化效应，使集群运营商能够安全地延长CPU寿命。该技术利用了我们发现的云LLM推理中CPU利用率不足的模式，通过停止未使用核心的老化，并通过选择性深度闲置和老化感知的推理任务分配来均衡活动核心的老化。通过使用真实的Azure推理跟踪和微软扩展的LLM集群模拟器进行广泛模拟，我们展示了该技术在管理CPU老化效应方面的卓越性能，预计每年体现碳排放减少37.67%，CPU利用率不足减少77%，并且对推理服务质量的影响不到10%。

> Broad adoption of Large Language Models (LLM) demands rapid expansions of cloud LLM inference clusters, leading to accumulation of embodied carbon$-$the emissions from manufacturing and supplying IT assets$-$that mostly concentrate on inference server CPU. This paper delves into the challenges of sustainable growth of cloud LLM inference, emphasizing extended amortization of CPU embodied over an increased lifespan. Given the reliability risks of silicon aging, we propose an aging-aware CPU core management technique to delay CPU aging effects, allowing the cluster operator to safely increase CPU life. Our technique exploits CPU underutilization patterns that we uncover in cloud LLM inference by halting aging in unused cores and even-outing aging in active cores via selective deep idling and aging-aware inference task allocation. Through extensive simulations using real-world Azure inference traces and an extended LLM cluster simulator from Microsoft, we show superior performance of our technique over existing methods with an estimated 37.67\% reduction in yearly embodied carbon emissions through p99 performance of managing CPU aging effects, a 77\% reduction in CPU underutilization, and less than 10\% impact to the inference service quality.

[Arxiv](https://arxiv.org/abs/2501.15829)