# 动态推理的成本：从AI基础设施视角解析AI代理与推理时扩展能力

发布时间：2025年06月04日

`Agent` `数据中心` `云计算`

> The Cost of Dynamic Reasoning: Demystifying AI Agents and Test-Time Scaling from an AI Infrastructure Perspective

# 摘要

> 基于 LLM 的 AI 代理通过动态推理展示了强大的多功能性，这种多步骤的适应性过程能够与外部工具协同工作。从静态单轮推理到多轮智能体工作流的转变，虽然提升了任务的泛化和行为的灵活性，但也带来了系统级成本、效率和可持续性方面的挑战。本文首次对 AI 代理进行了全面的系统级分析，评估了资源使用、延迟行为、能源消耗以及跨不同设计和扩展策略的数据中心电力需求。研究发现，尽管增加计算提升了代理的准确性，但收益递减、延迟方差扩大和高昂的基础设施成本也随之而来。通过分析代表性代理，我们揭示了 AI 工作流的巨大计算需求，预示着一场迫在眉睫的可持续性危机。这些发现呼吁在代理设计上进行范式转变，转向高效推理，实现在现实约束下性能与部署性的平衡。

> Large-language-model (LLM)-based AI agents have recently showcased impressive versatility by employing dynamic reasoning, an adaptive, multi-step process that coordinates with external tools. This shift from static, single-turn inference to agentic, multi-turn workflows broadens task generalization and behavioral flexibility, but it also introduces serious concerns about system-level cost, efficiency, and sustainability. This paper presents the first comprehensive system-level analysis of AI agents, quantifying their resource usage, latency behavior, energy consumption, and datacenter-wide power consumption demands across diverse agent designs and test-time scaling strategies. We further characterize how AI agent design choices, such as few-shot prompting, reflection depth, and parallel reasoning, impact accuracy-cost tradeoffs. Our findings reveal that while agents improve accuracy with increased compute, they suffer from rapidly diminishing returns, widening latency variance, and unsustainable infrastructure costs. Through detailed evaluation of representative agents, we highlight the profound computational demands introduced by AI agent workflows, uncovering a looming sustainability crisis. These results call for a paradigm shift in agent design toward compute-efficient reasoning, balancing performance with deployability under real-world constraints.

[Arxiv](https://arxiv.org/abs/2506.04301)