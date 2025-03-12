# RefactorBench：通过代码评估语言智能体的状态化推理能力

发布时间：2025年03月10日

`Agent` `软件工程` `代码重构`

> RefactorBench: Evaluating Stateful Reasoning in Language Agents Through Code

# 摘要

> 语言模型 (LM) 代理和函数调用的最新进展让自主且反馈驱动的系统能够跨多个数字领域解决问题。为深入理解 LM 代理的独特局限性，我们推出了 RefactorBench —— 一个包含 100 个大规模手工多文件重构任务的基准测试，这些任务均基于 popular open-source repositories。要解决 RefactorBench 中的任务，不仅需要全面探索多文件间的依赖关系，还需严格遵循相关指令。每个任务由 3 个不同具体性的自然语言指令定义，且彼此互斥，从而支持在同一仓库中构建更长的组合任务。基线测试结果显示，当前 LM 代理在简单组合任务上的表现不尽如人意，仅能解决 22% 的基本指令任务，而受时间限制的人类开发者则能解决 87%。通过轨迹分析，我们识别出 LM 代理的多种独特失败模式，并进一步深入研究了追踪过去动作的失败模式。通过将基线代理适应为基于状态表示进行条件判断，我们在解决 RefactorBench 任务上实现了 43.9% 的性能提升。我们进一步扩展了我们的状态感知方法，以涵盖整个数字环境，并概述了未来研究的潜在方向。RefactorBench 致力于支持 LM 代理的研究，提供了一系列现实世界中的多跳任务，这些任务均围绕代码领域展开。

> Recent advances in language model (LM) agents and function calling have enabled autonomous, feedback-driven systems to solve problems across various digital domains. To better understand the unique limitations of LM agents, we introduce RefactorBench, a benchmark consisting of 100 large handcrafted multi-file refactoring tasks in popular open-source repositories. Solving tasks within RefactorBench requires thorough exploration of dependencies across multiple files and strong adherence to relevant instructions. Every task is defined by 3 natural language instructions of varying specificity and is mutually exclusive, allowing for the creation of longer combined tasks on the same repository. Baselines on RefactorBench reveal that current LM agents struggle with simple compositional tasks, solving only 22% of tasks with base instructions, in contrast to a human developer with short time constraints solving 87%. Through trajectory analysis, we identify various unique failure modes of LM agents, and further explore the failure mode of tracking past actions. By adapting a baseline agent to condition on representations of state, we achieve a 43.9% improvement in solving RefactorBench tasks. We further extend our state-aware approach to encompass entire digital environments and outline potential directions for future research. RefactorBench aims to support the study of LM agents by providing a set of real-world, multi-hop tasks within the realm of code.

[Arxiv](https://arxiv.org/abs/2503.07832)