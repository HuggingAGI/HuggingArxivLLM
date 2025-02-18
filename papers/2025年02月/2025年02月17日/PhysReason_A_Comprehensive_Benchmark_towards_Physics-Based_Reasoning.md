# # PhysReason: 为物理推理打造的全面基准测试

发布时间：2025年02月17日

`LLM应用` `人工智能`

> PhysReason: A Comprehensive Benchmark towards Physics-Based Reasoning

# 摘要

> 大型语言模型在数学和逻辑推理等领域表现突出，但目前的评估却忽视了基于物理的推理能力——这一需要运用物理定理和约束条件的复杂任务。我们推出PhysReason，一个包含1,200个问题的基准测试，其中25%为知识型问题，75%为推理型问题，后者又细分为简单、中等和困难三个难度等级。值得注意的是，这些问题平均需要8.1个步骤来解答，其中困难问题甚至需要15.6个步骤，凸显了基于物理推理的复杂性。我们提出了物理解决方案自动评分框架，结合高效的答案级别和全面的步骤级别评估。目前表现最佳的模型如Deepseek-R1、Gemini-2.0-Flash-Thinking和o3-mini-high在答案级别评估中的得分均低于60%，且从知识型问题（75.11%）到困难问题（31.95%）的表现呈现明显下降趋势。通过深入的步骤级别评估，我们识别出四个关键瓶颈：物理定理应用、物理过程理解、计算能力和物理条件分析。这些发现使PhysReason成为评估大型语言模型基于物理推理能力的全新且全面的基准测试。我们的代码和数据将在https://dxzxy12138.github.io/PhysReason上公开发布。

> Large language models demonstrate remarkable capabilities across various domains, especially mathematics and logic reasoning. However, current evaluations overlook physics-based reasoning - a complex task requiring physics theorems and constraints. We present PhysReason, a 1,200-problem benchmark comprising knowledge-based (25%) and reasoning-based (75%) problems, where the latter are divided into three difficulty levels (easy, medium, hard). Notably, problems require an average of 8.1 solution steps, with hard requiring 15.6, reflecting the complexity of physics-based reasoning. We propose the Physics Solution Auto Scoring Framework, incorporating efficient answer-level and comprehensive step-level evaluations. Top-performing models like Deepseek-R1, Gemini-2.0-Flash-Thinking, and o3-mini-high achieve less than 60% on answer-level evaluation, with performance dropping from knowledge questions (75.11%) to hard problems (31.95%). Through step-level evaluation, we identified four key bottlenecks: Physics Theorem Application, Physics Process Understanding, Calculation, and Physics Condition Analysis. These findings position PhysReason as a novel and comprehensive benchmark for evaluating physics-based reasoning capabilities in large language models. Our code and data will be published at https:/dxzxy12138.github.io/PhysReason.

[Arxiv](https://arxiv.org/abs/2502.12054)