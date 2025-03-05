# MPO：元计划优化助力LLM代理升级

发布时间：2025年03月04日

`Agent` `人工智能` `智能体`

> MPO: Boosting LLM Agents with Meta Plan Optimization

# 摘要

> 近期，大型语言模型（LLMs）的突破性进展使基于LLM的智能体能够成功应对交互式规划任务。然而，现有方法尽管取得了一定成功，仍面临规划幻觉问题，并且需要为每个新智能体重新训练模型。为了解决这些挑战，我们提出了Meta Plan Optimization（MPO）框架，通过直接整合显式指导来提升智能体的规划能力。与以往依赖复杂知识的方法不同，这些方法要么需要大量人工努力，要么缺乏质量保证，MPO通过元计划提供高级通用指导来辅助智能体规划，并能够根据智能体任务执行的反馈持续优化元计划。我们在两个代表性任务上的实验表明，MPO显著优于现有基线方法。此外，我们的分析表明，MPO提供了一个即插即用的解决方案，能够提升智能体在之前未见过场景下的任务完成效率和泛化能力。

> Recent advancements in large language models (LLMs) have enabled LLM-based agents to successfully tackle interactive planning tasks. However, despite their successes, existing approaches often suffer from planning hallucinations and require retraining for each new agent. To address these challenges, we propose the Meta Plan Optimization (MPO) framework, which enhances agent planning capabilities by directly incorporating explicit guidance. Unlike previous methods that rely on complex knowledge, which either require significant human effort or lack quality assurance, MPO leverages high-level general guidance through meta plans to assist agent planning and enables continuous optimization of the meta plans based on feedback from the agent's task execution. Our experiments conducted on two representative tasks demonstrate that MPO significantly outperforms existing baselines. Moreover, our analysis indicates that MPO provides a plug-and-play solution that enhances both task completion efficiency and generalization capabilities in previous unseen scenarios.

[Arxiv](https://arxiv.org/abs/2503.02682)