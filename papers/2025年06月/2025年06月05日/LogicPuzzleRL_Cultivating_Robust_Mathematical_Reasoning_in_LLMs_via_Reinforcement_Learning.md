# LogicPuzzleRL：通过强化学习提升大型语言模型的数学推理能力

发布时间：2025年06月05日

`LLM理论` `推理系统` `数学推理`

> LogicPuzzleRL: Cultivating Robust Mathematical Reasoning in LLMs via Reinforcement Learning

# 摘要

> 大型语言模型（LLMs）在监督任务中表现优异，但在不熟悉的环境中进行结构化推理时往往力不从心。这表明标准微调流程可能培养了狭窄的领域特定启发式方法，而非通用型思维策略。本研究提出了一种“通过游戏学习”的框架，通过强化学习在七个定制逻辑谜题上对LLMs进行微调，每个谜题旨在培养不同的推理技能，如约束传播、空间一致性和符号演绎。利用具有可验证奖励的强化学习设置，模型会根据谜题的正确性获得二进制反馈，鼓励迭代的、基于假设的问题解决方法。实验表明，这种训练方法显著提升了数学基准测试中的分布外表现，特别是在需要多步推理的中等难度问题上。跨问题类别和难度水平的分析显示，谜题训练促进了可迁移的推理过程，增强了代数运算、几何推理和组合逻辑，同时在死记硬背或高度专业化的任务上仅带来有限的提升。这些发现表明，通过逻辑谜题进行强化学习重塑了LLMs的内部推理机制，使其能够实现更稳健且组合化的泛化，而无需依赖特定任务的符号工具。

> Large language models (LLMs) excel at many supervised tasks but often struggle with structured reasoning in unfamiliar settings. This discrepancy suggests that standard fine-tuning pipelines may instill narrow, domain-specific heuristics rather than fostering general-purpose thinking strategies. In this work, we propose a "play to learn" framework that fine-tunes LLMs through reinforcement learning on a suite of seven custom logic puzzles, each designed to cultivate distinct reasoning skills such as constraint propagation, spatial consistency, and symbolic deduction. Using a reinforcement learning setup with verifiable rewards, models receive binary feedback based on puzzle correctness, encouraging iterative, hypothesis-driven problem solving. We demonstrate that this training approach significantly improves out-of-distribution performance on a range of mathematical benchmarks, especially for mid-difficulty problems that require multi-step reasoning. Analyses across problem categories and difficulty levels reveal that puzzle training promotes transferable reasoning routines, strengthening algebraic manipulation, geometric inference, and combinatorial logic, while offering limited gains on rote or highly specialized tasks. These findings show that reinforcement learning over logic puzzles reshapes the internal reasoning of LLMs, enabling more robust and compositional generalization without relying on task-specific symbolic tools.

[Arxiv](https://arxiv.org/abs/2506.04821)