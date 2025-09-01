# ThinkDial：调控大型语言模型推理努力的开放方案

发布时间：2025年08月26日

`LLM应用` `基础理论`

> ThinkDial: An Open Recipe for Controlling Reasoning Effort in Large Language Models

# 摘要

> 具备思维链推理能力的大型语言模型（LLMs）虽已展现出卓越的问题解决能力，但在实际部署中，控制其计算量仍是一大难题。近来，OpenAI的gpt-oss系列等专有系统已推出离散操作模式，可实现直观的推理控制，然而开源社区却迟迟未能掌握这一能力。本文提出ThinkDial——首个通过离散操作模式成功实现gpt-oss风格可控推理的开源端到端框架。该系统支持三种推理模式的无缝切换：High模式（完整推理能力）、Medium模式（token数量减少50%，性能下降<10%）及Low模式（token数量减少75%，性能下降<15%）。这一成果通过端到端训练范式实现，该范式在全流程中整合了预算模式控制：预算模式监督微调将可控推理能力直接嵌入学习过程，辅以两阶段预算感知强化学习与自适应奖励塑造。大量实验证实，ThinkDial在达成目标压缩-性能权衡的同时，既能显著缩短响应长度，又能维持性能阈值。该框架在分布外任务上亦展现出优异的泛化性能。

> Large language models (LLMs) with chain-of-thought reasoning have demonstrated remarkable problem-solving capabilities, but controlling their computational effort remains a significant challenge for practical deployment. Recent proprietary systems like OpenAI's gpt-oss series have introduced discrete operational modes for intuitive reasoning control, but the open-source community has largely failed to achieve such capabilities. In this paper, we introduce ThinkDial, the first open-recipe end-to-end framework that successfully implements gpt-oss-style controllable reasoning through discrete operational modes. Our system enables seamless switching between three distinct reasoning regimes: High mode (full reasoning capability), Medium mode (50 percent token reduction with <10 percent performance degradation), and Low mode (75 percent token reduction with <15 percent performance degradation). We achieve this through an end-to-end training paradigm that integrates budget-mode control throughout the entire pipeline: budget-mode supervised fine-tuning that embeds controllable reasoning capabilities directly into the learning process, and two-phase budget-aware reinforcement learning with adaptive reward shaping. Extensive experiments demonstrate that ThinkDial achieves target compression-performance trade-offs with clear response length reductions while maintaining performance thresholds. The framework also exhibits strong generalization capabilities on out-of-distribution tasks.

[Arxiv](https://arxiv.org/abs/2508.18773)