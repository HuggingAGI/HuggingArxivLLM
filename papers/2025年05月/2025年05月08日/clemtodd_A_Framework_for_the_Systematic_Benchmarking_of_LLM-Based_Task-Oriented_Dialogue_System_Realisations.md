# clem:todd: 一个系统评估基于大型语言模型的任务导向对话系统实现的框架

发布时间：2025年05月08日

`LLM应用` `对话系统`

> clem:todd: A Framework for the Systematic Benchmarking of LLM-Based Task-Oriented Dialogue System Realisations

# 摘要

> 指令微调的大型语言模型（LLMs）为对话系统领域带来了重大突破，不仅实现了逼真的用户模拟，还催生了强大的多轮对话代理。然而，现有研究往往局限于孤立地评估单一组件——要么专注于用户模拟器，要么专注于特定系统设计——这限制了研究成果在不同架构和配置间的普适性。为此，我们提出了clem todd（面向任务导向型对话系统开发的聊天优化LLMs），一个灵活且系统化的对话系统评估框架。clem todd支持对现有文献中的用户模拟器和对话系统进行组合基准测试，同时也兼容新开发的模型。它通过即插即用的模块化设计，确保统一的数据集、评估指标和计算约束。我们通过在统一框架下重新评估现有任务导向型对话系统，并将三种新提出的对话系统整合到相同的评估流程中，充分展示了clem todd的灵活性。研究结果揭示了架构、规模和提示策略对对话性能的影响，为构建高效且实用的对话式AI系统提供了重要指导。

> The emergence of instruction-tuned large language models (LLMs) has advanced the field of dialogue systems, enabling both realistic user simulations and robust multi-turn conversational agents. However, existing research often evaluates these components in isolation-either focusing on a single user simulator or a specific system design-limiting the generalisability of insights across architectures and configurations. In this work, we propose clem todd (chat-optimized LLMs for task-oriented dialogue systems development), a flexible framework for systematically evaluating dialogue systems under consistent conditions. clem todd enables detailed benchmarking across combinations of user simulators and dialogue systems, whether existing models from literature or newly developed ones. It supports plug-and-play integration and ensures uniform datasets, evaluation metrics, and computational constraints. We showcase clem todd's flexibility by re-evaluating existing task-oriented dialogue systems within this unified setup and integrating three newly proposed dialogue systems into the same evaluation pipeline. Our results provide actionable insights into how architecture, scale, and prompting strategies affect dialogue performance, offering practical guidance for building efficient and effective conversational AI systems.

[Arxiv](https://arxiv.org/abs/2505.05445)