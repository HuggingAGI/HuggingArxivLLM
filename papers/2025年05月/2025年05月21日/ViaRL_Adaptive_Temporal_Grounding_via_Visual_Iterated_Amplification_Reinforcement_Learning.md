# # ViaRL: 基于视觉迭代放大强化学习的自适应时序关联

发布时间：2025年05月21日

`LLM应用` `视频理解` `视频分析`

> ViaRL: Adaptive Temporal Grounding via Visual Iterated Amplification Reinforcement Learning

# 摘要

> 视频理解本质上是基于意图的，人类会根据目标自然关注相关的帧。近年来，多模态大语言模型（MLLMs）的进步使得基于意图的灵活推理成为可能；然而，基于视频的方法如视频链式推理（Video Chain-of-Thought）缺乏直接的训练信号来有效识别相关帧。现有方法通常依赖于启发式方法或伪标签监督标注，这两种方法成本高昂且在不同场景下的可扩展性有限。

为了解决这些挑战，我们引入了ViaRL，这是首个利用基于规则的强化学习（RL）来优化基于意图的视频理解中帧选择的框架。我们采用迭代增强策略，在视频链式推理系统中进行交替循环训练，其中每个组件都经历迭代的优化周期以提升其能力。ViaRL利用下游模型的准确性作为奖励信号，通过试错法训练帧选择器，无需昂贵的标注，同时与人类学习过程紧密对齐。

在VideoMME、LVBench和MLVU等多个基准上的全面实验表明，ViaRL在各种视频理解任务中始终提供更优的时序定位性能和强大的泛化能力，凸显其有效性和可扩展性。值得注意的是，在MLVU的子集Needle QA上，ViaRL实现了近15%的性能提升，该任务要求在长视频中搜索特定针线并被视为评估时序定位的最合适的基准之一。

> Video understanding is inherently intention-driven-humans naturally focus on relevant frames based on their goals. Recent advancements in multimodal large language models (MLLMs) have enabled flexible query-driven reasoning; however, video-based frameworks like Video Chain-of-Thought lack direct training signals to effectively identify relevant frames. Current approaches often rely on heuristic methods or pseudo-label supervised annotations, which are both costly and limited in scalability across diverse scenarios. To overcome these challenges, we introduce ViaRL, the first framework to leverage rule-based reinforcement learning (RL) for optimizing frame selection in intention-driven video understanding. An iterated amplification strategy is adopted to perform alternating cyclic training in the video CoT system, where each component undergoes iterative cycles of refinement to improve its capabilities. ViaRL utilizes the answer accuracy of a downstream model as a reward signal to train a frame selector through trial-and-error, eliminating the need for expensive annotations while closely aligning with human-like learning processes. Comprehensive experiments across multiple benchmarks, including VideoMME, LVBench, and MLVU, demonstrate that ViaRL consistently delivers superior temporal grounding performance and robust generalization across diverse video understanding tasks, highlighting its effectiveness and scalability. Notably, ViaRL achieves a nearly 15\% improvement on Needle QA, a subset of MLVU, which is required to search a specific needle within a long video and regarded as one of the most suitable benchmarks for evaluating temporal grounding.

[Arxiv](https://arxiv.org/abs/2505.15447)