# 语言模型中的算法相变：关于算术的机制案例研究

发布时间：2024年12月10日

`LLM理论` `语言模型` `逻辑推理`

> Algorithmic Phase Transitions in Language Models: A Mechanistic Case Study of Arithmetic

# 摘要

> 大型语言模型的零样本能力让其成为无需专门训练就能解决众多任务的有力工具。不过，这些模型是如何达成这样的性能表现，以及为何能零样本处理某些任务而不能处理另一些任务，目前仍不清楚。在本文中，我们通过定义和探究语言模型中的算法稳定性——即因任务规范变化而导致模型所采用的问题解决策略的变化——来解释这一现象。我们聚焦于一个需要算法稳定性才能实现泛化的任务：双操作数算术。令人惊讶的是，我们发现 Gemma-2-2b 在紧密相关的子任务上，比如四位数加法和八位数加法，采用了截然不同的计算模型。我们的发现表明，算法不稳定性或许是语言模型在某些逻辑推理任务中零样本表现不佳的一个影响因素，因为它们难以抽象出不同的问题解决策略并在其间顺利转换。

> Zero-shot capabilities of large language models make them powerful tools for solving a range of tasks without explicit training. It remains unclear, however, how these models achieve such performance, or why they can zero-shot some tasks but not others. In this paper, we shed some light on this phenomenon by defining and investigating algorithmic stability in language models -- changes in problem-solving strategy employed by the model as a result of changes in task specification. We focus on a task where algorithmic stability is needed for generalization: two-operand arithmetic. Surprisingly, we find that Gemma-2-2b employs substantially different computational models on closely related subtasks, i.e. four-digit versus eight-digit addition. Our findings suggest that algorithmic instability may be a contributing factor to language models' poor zero-shot performance across certain logical reasoning tasks, as they struggle to abstract different problem-solving strategies and smoothly transition between them.

[Arxiv](https://arxiv.org/abs/2412.07386)