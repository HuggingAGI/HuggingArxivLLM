# Haste Makes Waste: 评估LLMs在多任务场景下的规划能力：时间约束下的高效与可行性

发布时间：2025年03月03日

`Agent` `人工智能`

> Haste Makes Waste: Evaluating Planning Abilities of LLMs for Efficient and Feasible Multitasking with Time Constraints Between Actions

# 摘要

> 尽管基于大型语言模型的智能体在任务完成方面取得了显著进展，但现有评估基准往往过分强调单任务性能，而对实际场景中至关重要的多任务规划和执行效率关注不足。为了解决这一问题，我们提出了Recipe2Plan，一个基于真实烹饪场景的新型基准框架。与传统基准不同，Recipe2Plan要求智能体在遵守时间约束的前提下，通过并行任务执行来优化烹饪时间。过于激进的局部并行化可能会破坏这一约束，从而危及整个烹饪过程。这种严格的时间约束对智能体提出了独特挑战，要求其在最大化并发操作和遵循关键时间约束之间找到平衡。对当前最先进的模型进行的广泛实验表明，维持效率与可行性之间的平衡颇具挑战性。实验结果凸显了大型语言模型在提升时间感知和全局多任务能力方面的需求。我们已将基准和代码开源，地址为https://github.com/WilliamZR/Recipe2Plan。

> While Large Language Model-based agents have demonstrated substantial progress in task completion, existing evaluation benchmarks tend to overemphasize single-task performance, with insufficient attention given to the crucial aspects of multitask planning and execution efficiency required in real-world scenarios. To bridge this gap, we present Recipe2Plan, a novel benchmark framework based on real-world cooking scenarios. Unlike conventional benchmarks, Recipe2Plan challenges agents to optimize cooking time through parallel task execution while respecting temporal constraints i.e. specific actions need to be performed within a particular time intervals following the preceding steps. Overly aggressive local parallelization may disrupt this constraint, potentially compromising the entire cooking process. This strict time constraint between actions raises a unique challenge for agents to balance between maximizing concurrent operations and adhering to critical timing constraints. Extensive experiments with state-of-the-art models reveal challenges in maintaining this balance between efficiency and feasibility. The results highlight the need for improved temporal awareness and global multitasking capabilities in large language models. We open-source our benchmark and code at https://github.com/WilliamZR/Recipe2Plan.

[Arxiv](https://arxiv.org/abs/2503.02238)