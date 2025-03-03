# LADs：借助LLMs实现AI驱动的DevOps

发布时间：2025年02月28日

`LLM应用` `云计算` `DevOps`

> LADs: Leveraging LLMs for AI-Driven DevOps

# 摘要

> 云配置与部署的自动化面临诸多挑战，源于不断演进的基础设施、异构硬件及波动的工作负载。现有方案缺乏适应性，需大量手动调整，导致效率低下与配置失误。我们推出LADs，首个基于LLM的框架，专为克服这些挑战而设计，确保自动化云管理的健壮、灵活与高效。LADs不局限于现有技术，而是通过深入解析不同条件下有效的优化手段，提供系统性的配置优化方案。借助检索增强生成、少样本学习、思维链及基于反馈的提示链，LADs生成精准配置，并从部署故障中学习，持续优化系统设置。我们的研究揭示了性能、成本与可扩展性间的权衡，助从业者制定适合不同场景的策略。例如，基于提示链的自适应反馈机制提升多租户环境的容错能力，而带示例的结构化日志分析则增强配置准确性。经广泛评估，LADs减少人工投入，优化资源使用，提升系统可靠性。开源LADs，旨在推动AI驱动的DevOps自动化创新。

> Automating cloud configuration and deployment remains a critical challenge due to evolving infrastructures, heterogeneous hardware, and fluctuating workloads. Existing solutions lack adaptability and require extensive manual tuning, leading to inefficiencies and misconfigurations. We introduce LADs, the first LLM-driven framework designed to tackle these challenges by ensuring robustness, adaptability, and efficiency in automated cloud management. Instead of merely applying existing techniques, LADs provides a principled approach to configuration optimization through in-depth analysis of what optimization works under which conditions. By leveraging Retrieval-Augmented Generation, Few-Shot Learning, Chain-of-Thought, and Feedback-Based Prompt Chaining, LADs generates accurate configurations and learns from deployment failures to iteratively refine system settings. Our findings reveal key insights into the trade-offs between performance, cost, and scalability, helping practitioners determine the right strategies for different deployment scenarios. For instance, we demonstrate how prompt chaining-based adaptive feedback loops enhance fault tolerance in multi-tenant environments and how structured log analysis with example shots improves configuration accuracy. Through extensive evaluations, LADs reduces manual effort, optimizes resource utilization, and improves system reliability. By open-sourcing LADs, we aim to drive further innovation in AI-powered DevOps automation.

[Arxiv](https://arxiv.org/abs/2502.20825)