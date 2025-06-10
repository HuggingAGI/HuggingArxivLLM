# LLM增强型快速反射异步反思具身智能体，在动态变化环境中实现实时决策

发布时间：2025年06月08日

`Agent` `灾害应对` `智能体`

> LLM-Enhanced Rapid-Reflex Async-Reflect Embodied Agent for Real-Time Decision-Making in Dynamically Changing Environments

# 摘要

> 在具身智能领域，大型语言模型（LLMs）的演进显著提升了智能体的决策能力。因此，研究者开始探索智能体在动态变化的高风险场景中的表现，即HAZARD基准测试中的火灾、洪水和风灾场景。在这些极端条件下，决策延迟成为一个关键但研究不足的问题。我们提出了一种时间转换机制（TCM），将决策过程中的推理延迟转换为等效的模拟帧数，从而在单一的FPS指标下统一认知成本和物理成本。通过为HAZARD扩展响应延迟（RL）和延迟到动作比率（LAR），我们提供了一套完整的延迟感知评估协议。此外，我们提出了快速反射异步反思智能体（RRARA），该智能体结合了轻量级LLM引导的反馈模块和基于规则的智能体，以实现即时的反应行为和现场的异步反思改进。在HAZARD上的实验表明，RRARA在对延迟敏感的场景中显著优于现有基线。


> In the realm of embodied intelligence, the evolution of large language models (LLMs) has markedly enhanced agent decision making. Consequently, researchers have begun exploring agent performance in dynamically changing high-risk scenarios, i.e., fire, flood, and wind scenarios in the HAZARD benchmark. Under these extreme conditions, the delay in decision making emerges as a crucial yet insufficiently studied issue. We propose a Time Conversion Mechanism (TCM) that translates inference delays in decision-making into equivalent simulation frames, thus aligning cognitive and physical costs under a single FPS-based metric. By extending HAZARD with Respond Latency (RL) and Latency-to-Action Ratio (LAR), we deliver a fully latency-aware evaluation protocol. Moreover, we present the Rapid-Reflex Async-Reflect Agent (RRARA), which couples a lightweight LLM-guided feedback module with a rule-based agent to enable immediate reactive behaviors and asynchronous reflective refinements in situ. Experiments on HAZARD show that RRARA substantially outperforms existing baselines in latency-sensitive scenarios.

[Arxiv](https://arxiv.org/abs/2506.07223)