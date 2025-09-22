# SmolRGPT：6亿参数的仓库环境高效空间推理

发布时间：2025年09月18日

`LLM应用` `工业与制造`

> SmolRGPT: Efficient Spatial Reasoning for Warehouse Environments with 600M Parameters

# 摘要

> 视觉语言模型（VLMs）的最新进展已实现强大的多模态推理能力，但当前最先进的方法往往依赖超大规模模型，其计算和内存成本高得令人却步。这导致它们在仓库、机器人技术和工业应用等资源受限场景中难以部署——而在这些场景中，效率与可靠的空间理解能力缺一不可。为此，我们提出了SmolRGPT——一种紧凑的视觉语言架构，它通过融合RGB与深度信息，将区域级空间推理明确纳入模型设计。SmolRGPT采用三阶段训练策略：逐步对齐视觉与语言特征、构建空间关系理解能力、并适配特定任务数据集。实验表明，仅需6亿参数，SmolRGPT就在极具挑战性的仓库空间推理基准测试中表现优异，其性能媲美甚至超越了那些规模大得多的替代模型。这些发现揭示：无需牺牲核心空间推理能力，就能在真实场景中构建高效、可部署的多模态智能系统，其应用潜力巨大。实验代码将公开于：https://github.com/abtraore/SmolRGPT

> Recent advances in vision-language models (VLMs) have enabled powerful multimodal reasoning, but state-of-the-art approaches typically rely on extremely large models with prohibitive computational and memory requirements. This makes their deployment challenging in resource-constrained environments such as warehouses, robotics, and industrial applications, where both efficiency and robust spatial understanding are critical. In this work, we present SmolRGPT, a compact vision-language architecture that explicitly incorporates region-level spatial reasoning by integrating both RGB and depth cues. SmolRGPT employs a three-stage curriculum that progressively align visual and language features, enables spatial relationship understanding, and adapts to task-specific datasets. We demonstrate that with only 600M parameters, SmolRGPT achieves competitive results on challenging warehouse spatial reasoning benchmarks, matching or exceeding the performance of much larger alternatives. These findings highlight the potential for efficient, deployable multimodal intelligence in real-world settings without sacrificing core spatial reasoning capabilities. The code of the experimentation will be available at: https://github.com/abtraore/SmolRGPT

[Arxiv](https://arxiv.org/abs/2509.15490)