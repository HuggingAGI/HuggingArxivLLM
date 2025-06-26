# 上下文感知的 CodeLLM 替换策略，为 AI 辅助编程提供优化方案。

发布时间：2025年06月23日

`LLM应用` `软件工程` `AI辅助编程`

> Context-Aware CodeLLM Eviction for AI-assisted Coding

# 摘要

> 代码大型语言模型（CodeLLMs）驱动的AI辅助编码工具正在逐步融入现代软件开发流程。为了应对隐私、延迟和模型定制方面的担忧，许多企业选择自行托管这些模型。然而，代码LLM的数量和多样性不断增加，加上有限的加速器内存，给模型管理和服务效率带来了实际挑战。本文提出了一种名为CACE的新颖上下文感知模型替换策略，旨在在资源受限的情况下优化自托管CodeLLM的服务性能。与仅基于近期使用情况的传统替换策略（如最近最少使用算法）不同，CACE结合了多个上下文感知因素，包括模型加载时间、任务特定的延迟敏感性、预期输出长度，以及通过滑动窗口跟踪的最近使用情况和未来需求。我们使用包含延迟敏感型代码补全和吞吐量密集型代码推理任务的现实工作负载来评估CACE。实验表明，CACE能够降低首次生成令牌的时间（TTFT）和端到端（E2E）延迟，同时与现有最优系统相比，显著减少了模型替换的数量。消融研究进一步证明了多因素替换在平衡响应速度和资源效率方面的重要性。这项研究为在实际软件工程环境中部署可扩展、低延迟的AI编码助手提供了实用策略。

> AI-assisted coding tools powered by Code Large Language Models (CodeLLMs) are increasingly integrated into modern software development workflows. To address concerns around privacy, latency, and model customization, many enterprises opt to self-host these models. However, the diversity and growing number of CodeLLMs, coupled with limited accelerator memory, introduce practical challenges in model management and serving efficiency. This paper presents CACE, a novel context-aware model eviction strategy designed specifically to optimize self-hosted CodeLLM serving under resource constraints. Unlike traditional eviction strategies based solely on recency (e.g., Least Recently Used), CACE leverages multiple context-aware factors, including model load time, task-specific latency sensitivity, expected output length, and recent usage and future demand tracked through a sliding window. We evaluate CACE using realistic workloads that include both latency-sensitive code completion and throughput-intensive code reasoning tasks. Our experiments show that CACE reduces Time-to-First-Token (TTFT) and end-to-end (E2E) latency, while significantly lowering the number of model evictions compared to state-of-the-art systems. Ablation studies further demonstrate the importance of multi-factor eviction in balancing responsiveness and resource efficiency. This work contributes practical strategies for deploying scalable, low-latency AI coding assistants in real-world software engineering environments.

[Arxiv](https://arxiv.org/abs/2506.18796)