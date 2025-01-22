# GREEN-CODE: 提升代码生成中大型语言模型的能效优化

发布时间：2025年01月19日

`LLM应用

解释：这篇论文主要讨论了大型语言模型（LLMs）在软件开发中的应用，特别是代码生成任务中的能源效率问题。论文提出了一个名为GREEN-CODE的框架，旨在通过动态早期退出策略和强化学习代理来优化LLM推理过程中的能源消耗。虽然论文涉及了LLM的理论（如推理过程的资源消耗），但其核心关注点是如何在实际应用中提高LLM的能源效率，因此更适合归类为“LLM应用”。` `软件开发` `能源管理`

> GREEN-CODE: Optimizing Energy Efficiency in Large Language Models for Code Generation

# 摘要

> 大型语言模型（LLMs）正日益融入日常生活，展现了其在自然语言处理（NLP）任务中的广泛应用潜力。不仅如此，LLMs在软件开发领域也大显身手，如代码补全、修改、错误修复和代码翻译等任务。GitHub Copilot和Amazon Q等工具被软件工程师广泛使用，极大地简化了工作流程并实现了高精度的任务自动化。尽管LLM训练的资源消耗和能源需求常被提及，但推理过程因其高调用频率和持续性，可能更加资源密集。因此，开发资源高效的LLM推理方案对可持续发展至关重要。本研究提出了GREEN-CODE框架，旨在实现LLM中的能源感知代码生成。GREEN-CODE在推理过程中采用动态早期退出策略，并通过训练强化学习（RL）代理来平衡准确性、延迟和能耗之间的权衡。我们在Llama 3.2 3B和OPT 2.7B两个开源LLM上，使用JavaCorpus和PY150数据集进行评估。结果显示，该方法在代码生成任务中平均减少了23-50%的能耗，且对准确性影响甚微。

> Large Language Models (LLMs) are becoming integral to daily life, showcasing their vast potential across various Natural Language Processing (NLP) tasks. Beyond NLP, LLMs are increasingly used in software development tasks, such as code completion, modification, bug fixing, and code translation. Software engineers widely use tools like GitHub Copilot and Amazon Q, streamlining workflows and automating tasks with high accuracy. While the resource and energy intensity of LLM training is often highlighted, inference can be even more resource-intensive over time, as it's a continuous process with a high number of invocations. Therefore, developing resource-efficient alternatives for LLM inference is crucial for sustainability. This work proposes GREEN-CODE, a framework for energy-aware code generation in LLMs. GREEN-CODE performs dynamic early exit during LLM inference. We train a Reinforcement Learning (RL) agent that learns to balance the trade-offs between accuracy, latency, and energy consumption. Our approach is evaluated on two open-source LLMs, Llama 3.2 3B and OPT 2.7B, using the JavaCorpus and PY150 datasets. Results show that our method reduces the energy consumption between 23-50 % on average for code generation tasks without significantly affecting accuracy.

[Arxiv](https://arxiv.org/abs/2501.11006)