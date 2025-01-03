# TimelyLLM: 为时间敏感机器人应用量身打造的分段LLM服务系统

发布时间：2024年12月24日

`Agent

理由：这篇论文主要讨论了如何改进大型语言模型（LLMs）在机器人控制中的应用，特别是针对时间敏感的任务。论文提出了 TimelyLLM 系统，该系统通过分段生成和调度机制来优化多个机器人代理的请求处理。这涉及到多个自主代理（机器人）的协调和控制，因此属于Agent分类。` `机器人` `无人机`

> TimelyLLM: Segmented LLM Serving System for Time-sensitive Robotic Applications

# 摘要

> 像 GPT-4 和 Llama3 这样的大型语言模型（LLMs）已经能够理解复杂指令并处理多样化任务，这为它们在无人机和机器人控制中的应用铺平了道路。然而，现有的 LLM 服务系统通常采用先到先得（FCFS）的批处理机制，难以满足机器人应用对时间敏感的需求。为此，本文提出了 TimelyLLM 系统，专门服务多个具有时间敏感请求的机器人代理。TimelyLLM 引入了分段生成和调度机制，充分利用机器人计划生成与执行阶段的冗余。我们在一个广泛使用的 LLM 服务框架上实现了 TimelyLLM，并在多种机器人应用中进行了评估。结果显示，TimelyLLM 将时间效用提升了 1.97 倍，并将总体等待时间减少了 84%。

> Large Language Models (LLMs) such as GPT-4 and Llama3 can already comprehend complex commands and process diverse tasks. This advancement facilitates their application in controlling drones and robots for various tasks. However, existing LLM serving systems typically employ a first-come, first-served (FCFS) batching mechanism, which fails to address the time-sensitive requirements of robotic applications. To address it, this paper proposes a new system named TimelyLLM serving multiple robotic agents with time-sensitive requests. TimelyLLM introduces novel mechanisms of segmented generation and scheduling that optimally leverage redundancy between robot plan generation and execution phases. We report an implementation of TimelyLLM on a widely-used LLM serving framework and evaluate it on a range of robotic applications. Our evaluation shows that TimelyLLM improves the time utility up to 1.97x, and reduces the overall waiting time by 84%.

[Arxiv](https://arxiv.org/abs/2412.18695)