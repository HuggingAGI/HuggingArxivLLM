# NetIntent：基于大型语言模型的端到端意图驱动SDN自动化方案

发布时间：2025年07月18日

`LLM应用` `网络管理` `软件定义网络（SDN）`

> NetIntent: Leveraging Large Language Models for End-to-End Intent-Based SDN Automation

# 摘要

> 意图驱动网络（IBN）借助软件定义网络（SDN）的可编程性简化网络管理，但实现从用户高层次意图到设备低层次配置的全流程自动化仍具挑战。现有方案多依赖 rigid 的规则转换器和固定API，限制了扩展性和灵活性。大型语言模型（LLMs）的突破为IBN带来了新机遇，其自然语言理解和灵活推理能力令人瞩目，但其在IBN任务中的潜力尚待验证。

为此，我们推出IBNBench——首个专注于IBN的基准测试套件，包含四个全新数据集：Intent2Flow-ODL、Intent2Flow-ONOS、FlowConflict-ODL 和 FlowConflict-ONOS。这些数据集专为评估LLMs在工业级SDN控制器ODL和ONOS中的意图翻译和冲突检测任务而设计。通过全面对比33个开源LLMs在IBNBench上的表现，我们首次揭示了LLMs在IBN任务中的广泛性能差异。

然而，尽管LLMs在孤立IBN任务中展现出巨大潜力，要将其融入完整自主的IBN流程仍需突破。为此，我们提出NetIntent——一个统一灵活的框架，借助LLMs实现IBN全生命周期自动化，涵盖翻译、激活和保证环节。NetIntent协调LLM与非LLM代理，支持动态重新提示和上下文反馈，确保用户意图稳健执行，同时大幅减少人为干预。我们在ODL和ONOS控制器上的实现证明，NetIntent能够提供一致且适应性强的端到端IBN解决方案。

> Intent-Based Networking (IBN) often leverages the programmability of Software-Defined Networking (SDN) to simplify network management. However, significant challenges remain in automating the entire pipeline, from user-specified high-level intents to device-specific low-level configurations. Existing solutions often rely on rigid, rule-based translators and fixed APIs, limiting extensibility and adaptability. By contrast, recent advances in large language models (LLMs) offer a promising pathway that leverages natural language understanding and flexible reasoning. However, it is unclear to what extent LLMs can perform IBN tasks. To address this, we introduce IBNBench, a first-of-its-kind benchmarking suite comprising four novel datasets: Intent2Flow-ODL, Intent2Flow-ONOS, FlowConflict-ODL, and FlowConflict-ONOS. These datasets are specifically designed for evaluating LLMs performance in intent translation and conflict detection tasks within the industry-grade SDN controllers ODL and ONOS. Our results provide the first comprehensive comparison of 33 open-source LLMs on IBNBench and related datasets, revealing a wide range of performance outcomes. However, while these results demonstrate the potential of LLMs for isolated IBN tasks, integrating LLMs into a fully autonomous IBN pipeline remains unexplored. Thus, our second contribution is NetIntent, a unified and adaptable framework that leverages LLMs to automate the full IBN lifecycle, including translation, activation, and assurance within SDN systems. NetIntent orchestrates both LLM and non-LLM agents, supporting dynamic re-prompting and contextual feedback to robustly execute user-defined intents with minimal human intervention. Our implementation of NetIntent across both ODL and ONOS SDN controllers achieves a consistent and adaptive end-to-end IBN realization.

[Arxiv](https://arxiv.org/abs/2507.14398)