# 动态无线环境下的自适应资源分配优化：大型语言模型的应用

发布时间：2025年02月04日

`LLM应用

理由：这篇论文主要讨论的是利用大语言模型（LLM）来解决复杂资源分配问题，特别是在无线网络控制中的应用。论文提出了一个基于LLM的资源分配优化器（LLM-RAO），并通过仿真展示了其在动态环境中的性能和适应性。这属于LLM在实际问题中的应用，因此归类为LLM应用。` `网络优化`

> Adaptive Resource Allocation Optimization Using Large Language Models in Dynamic Wireless Environments

# 摘要

> 深度学习（DL）在解决传统方法难以应对的复杂无线网络控制问题上取得了显著进展。然而，DL 在处理网络优化中的约束 NP 难问题（如涉及 QoS 或用户索引等离散变量）时仍有局限。现有方案多依赖特定领域架构或启发式技术，通用的 DL 约束优化方法尚未成熟。此外，通信目标的微小变化往往需要耗时重新训练，限制了其在动态环境中的适应性。为此，我们提出了基于大语言模型的资源分配优化器（LLM-RAO），利用 LLM 的能力解决复杂资源分配问题，同时满足 QoS 约束。通过基于提示的调优策略，LLM-RAO 能够灵活应对不断变化的任务需求，在动态环境中表现出强大的性能和适应性，无需大量重新训练。仿真结果显示，LLM-RAO 相比传统 DL 方法性能提升高达 40%，相比分析方法提升高达 80%。在通信目标波动的情况下，其性能更是传统 DL 网络的 2.9 倍。

> Deep learning (DL) has made notable progress in addressing complex radio access network control challenges that conventional analytic methods have struggled to solve. However, DL has shown limitations in solving constrained NP-hard problems often encountered in network optimization, such as those involving quality of service (QoS) or discrete variables like user indices. Current solutions rely on domain-specific architectures or heuristic techniques, and a general DL approach for constrained optimization remains undeveloped. Moreover, even minor changes in communication objectives demand time-consuming retraining, limiting their adaptability to dynamic environments where task objectives, constraints, environmental factors, and communication scenarios frequently change. To address these challenges, we propose a large language model for resource allocation optimizer (LLM-RAO), a novel approach that harnesses the capabilities of LLMs to address the complex resource allocation problem while adhering to QoS constraints. By employing a prompt-based tuning strategy to flexibly convey ever-changing task descriptions and requirements to the LLM, LLM-RAO demonstrates robust performance and seamless adaptability in dynamic environments without requiring extensive retraining. Simulation results reveal that LLM-RAO achieves up to a 40% performance enhancement compared to conventional DL methods and up to an $80$\% improvement over analytical approaches. Moreover, in scenarios with fluctuating communication objectives, LLM-RAO attains up to 2.9 times the performance of traditional DL-based networks.

[Arxiv](https://arxiv.org/abs/2502.02287)