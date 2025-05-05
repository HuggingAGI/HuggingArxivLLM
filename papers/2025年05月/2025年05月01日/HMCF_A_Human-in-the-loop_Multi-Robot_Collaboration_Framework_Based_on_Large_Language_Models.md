# HMCF：基于大型语言模型的多机器人协同协作框架

发布时间：2025年05月01日

`LLM应用` `机器人` `应急救援`

> HMCF: A Human-in-the-loop Multi-Robot Collaboration Framework Based on Large Language Models

# 摘要

> 近年来，人工智能的迅猛发展让机器人能够以更高精度自主完成复杂任务。然而，多机器人系统在灾害响应等大规模部署中，仍面临泛化能力、异构性和安全性等多重挑战。传统方法不仅缺乏泛化能力，需要大量工程投入适配新任务和场景，还难以有效管理多样化的机器人。为此，我们提出了一种基于大语言模型的“人机协作闭环的多机器人协作框架”（HMCF）。该框架通过大语言模型实现了任务与机器人能力的推理，同时通过人类监督确保安全与可靠性。我们的框架无缝整合了人类监督、LLM代理和异构机器人，实现了任务分配与执行的优化。每个机器人均配备了LLM代理，能够理解自身能力、将任务转化为可执行指令，并通过任务验证和人类监督减少幻觉现象。仿真结果显示，我们的框架优于现有任务规划方法，任务成功率提升了4.76%。实测验证了其强大的零样本泛化能力，能够以极低的人类干预实现多样化任务与环境的处理。


> Rapid advancements in artificial intelligence (AI) have enabled robots to performcomplex tasks autonomously with increasing precision. However, multi-robot systems (MRSs) face challenges in generalization, heterogeneity, and safety, especially when scaling to large-scale deployments like disaster response. Traditional approaches often lack generalization, requiring extensive engineering for new tasks and scenarios, and struggle with managing diverse robots. To overcome these limitations, we propose a Human-in-the-loop Multi-Robot Collaboration Framework (HMCF) powered by large language models (LLMs). LLMs enhance adaptability by reasoning over diverse tasks and robot capabilities, while human oversight ensures safety and reliability, intervening only when necessary. Our framework seamlessly integrates human oversight, LLM agents, and heterogeneous robots to optimize task allocation and execution. Each robot is equipped with an LLM agent capable of understanding its capabilities, converting tasks into executable instructions, and reducing hallucinations through task verification and human supervision. Simulation results show that our framework outperforms state-of-the-art task planning methods, achieving higher task success rates with an improvement of 4.76%. Real-world tests demonstrate its robust zero-shot generalization feature and ability to handle diverse tasks and environments with minimal human intervention.

[Arxiv](https://arxiv.org/abs/2505.00820)