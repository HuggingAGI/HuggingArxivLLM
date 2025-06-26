# 利用大型语言模型，通过开放式的指令重标签方法学习遵循指令的策略。

发布时间：2025年06月24日

`LLM应用

理由：这篇论文探讨了如何利用大型语言模型（LLMs）来生成指令，从而提升强化学习中的策略开发。它主要关注于LLMs在数据生成和任务处理中的实际应用，属于LLM的应用层面。` `机器人`

> Learning Instruction-Following Policies through Open-Ended Instruction Relabeling with Large Language Models

# 摘要

> 强化学习中开发遵循指令策略仍面临两大挑战：依赖大量人工标注指令数据集，以及难以从稀疏奖励中学习。本文提出了一种创新方法，借助大型语言模型（LLMs）从历史智能体轨迹中自动生成开放指令。我们的核心思路是利用LLMs重新标注未成功轨迹，通过识别智能体隐式完成的子任务，丰富训练数据，大幅降低人工标注依赖。通过这种开放指令重新标注，我们高效地学习了一个统一策略，使其能处理多种任务。我们在具挑战性的Craftax环境中验证了方法，结果显示在样本效率、指令覆盖和整体性能上均优于现有方法。这表明LLM引导的开放指令重新标注能显著提升强化学习效果。

> Developing effective instruction-following policies in reinforcement learning remains challenging due to the reliance on extensive human-labeled instruction datasets and the difficulty of learning from sparse rewards. In this paper, we propose a novel approach that leverages the capabilities of large language models (LLMs) to automatically generate open-ended instructions retrospectively from previously collected agent trajectories. Our core idea is to employ LLMs to relabel unsuccessful trajectories by identifying meaningful subtasks the agent has implicitly accomplished, thereby enriching the agent's training data and substantially alleviating reliance on human annotations. Through this open-ended instruction relabeling, we efficiently learn a unified instruction-following policy capable of handling diverse tasks within a single policy. We empirically evaluate our proposed method in the challenging Craftax environment, demonstrating clear improvements in sample efficiency, instruction coverage, and overall policy performance compared to state-of-the-art baselines. Our results highlight the effectiveness of utilizing LLM-guided open-ended instruction relabeling to enhance instruction-following reinforcement learning.

[Arxiv](https://arxiv.org/abs/2506.20061)