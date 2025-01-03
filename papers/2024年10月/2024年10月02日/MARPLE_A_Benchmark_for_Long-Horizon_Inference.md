# MARPLE: 长时推理基准

发布时间：2024年10月02日

`Agent

理由：这篇论文主要讨论了一个模拟代理与家庭互动的基准（MARPLE），用于评估基于多模态证据的长时间跨度推理能力。论文的核心是研究代理在复杂环境中的推理和决策能力，这与“Agent”这一分类密切相关。虽然论文中提到了GPT-4等大型语言模型的表现，但重点在于代理在多模态环境中的推理能力，而不是LLM本身的理论或应用。因此，将其归类为“Agent”更为合适。` `推理系统` `多模态学习`

> MARPLE: A Benchmark for Long-Horizon Inference

# 摘要

> # 摘要
重建过去的事件需要跨越长时间跨度的推理。为了弄清真相，我们需要结合对世界和人类行为的先验知识，并从视觉、语言和听觉等多模态线索中推断。我们推出了MARPLE基准，用于评估基于多模态证据的长时间跨度推理能力。该基准模拟了代理与家庭的互动，支持视觉、语言和听觉刺激，并包含程序生成的环境和代理行为。受经典“谁是真凶”故事的启发，我们要求AI模型和人类参与者根据事件回放，推断出导致环境变化的代理。目标是尽早锁定“真凶”。结果显示，人类参与者在这项任务上优于传统的蒙特卡罗模拟方法和GPT-4基线。传统推理模型在稳健性和性能上不及人类，而GPT-4在理解环境变化时表现欠佳。我们分析了影响推理性能的因素，并验证了不同证据模式的价值，发现所有模式都对性能有贡献。总体而言，实验表明，基准中的长时间跨度、多模态推理任务对现有模型提出了挑战。

> Reconstructing past events requires reasoning across long time horizons. To figure out what happened, we need to use our prior knowledge about the world and human behavior and draw inferences from various sources of evidence including visual, language, and auditory cues. We introduce MARPLE, a benchmark for evaluating long-horizon inference capabilities using multi-modal evidence. Our benchmark features agents interacting with simulated households, supporting vision, language, and auditory stimuli, as well as procedurally generated environments and agent behaviors. Inspired by classic ``whodunit'' stories, we ask AI models and human participants to infer which agent caused a change in the environment based on a step-by-step replay of what actually happened. The goal is to correctly identify the culprit as early as possible. Our findings show that human participants outperform both traditional Monte Carlo simulation methods and an LLM baseline (GPT-4) on this task. Compared to humans, traditional inference models are less robust and performant, while GPT-4 has difficulty comprehending environmental changes. We analyze what factors influence inference performance and ablate different modes of evidence, finding that all modes are valuable for performance. Overall, our experiments demonstrate that the long-horizon, multimodal inference tasks in our benchmark present a challenge to current models.

[Arxiv](https://arxiv.org/abs/2410.01926)