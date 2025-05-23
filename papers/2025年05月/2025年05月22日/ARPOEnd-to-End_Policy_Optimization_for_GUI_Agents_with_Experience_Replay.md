# ARPO：利用经验回放实现 GUI 代理的端到端策略优化

发布时间：2025年05月22日

`LLM应用` `图形用户界面` `交互式代理`

> ARPO:End-to-End Policy Optimization for GUI Agents with Experience Replay

# 摘要

> 将大型语言模型（LLMs）训练为交互式代理以控制图形用户界面（GUI）带来了独特的挑战，需要优化从复杂环境反馈的多模态信息中生成的长跨度动作序列。尽管近期研究在多轮强化学习（RL）方面取得了进展，用于提升LLMs的推理和工具使用能力，但将其应用于基于GUI的代理仍面临诸多挑战，主要源于稀疏奖励、延迟反馈和高昂的 rollout 成本。本文旨在研究基于视觉-语言的GUI代理的端到端策略优化，以提升其在复杂、长跨度计算机任务中的表现。我们提出了一种名为 Agentic Replay Policy Optimization (ARPO) 的端到端 RL 方法，该方法通过引入回放缓存来增强 Group Relative Policy Optimization (GRPO)，从而跨训练迭代复用成功经验。为进一步稳定训练过程，我们提出了一种基于基线代理性能的任务筛选策略，使代理能够专注于从具有信息量的交互中学习。此外，我们还将 ARPO 与离线偏好优化方法进行了对比，突出了基于策略的方法在 GUI 环境中的优势。在 OSWorld 基准测试中的实验表明，ARPO 达到了具有竞争力的结果，为通过强化学习训练的基于 LLM 的 GUI 代理设立了新的性能基准。我们的研究结果强调了强化学习在训练多轮视觉-语言 GUI 代理方面的有效性，这些代理能够处理复杂的现实世界 UI 交互。代码和模型已开源：https://github.com/dvlab-research/ARPO.git。

> Training large language models (LLMs) as interactive agents for controlling graphical user interfaces (GUIs) presents a unique challenge to optimize long-horizon action sequences with multimodal feedback from complex environments. While recent works have advanced multi-turn reinforcement learning (RL) for reasoning and tool-using capabilities in LLMs, their application to GUI-based agents remains relatively underexplored due to the difficulty of sparse rewards, delayed feedback, and high rollout costs. In this paper, we investigate end-to-end policy optimization for vision-language-based GUI agents with the aim of improving performance on complex, long-horizon computer tasks. We propose Agentic Replay Policy Optimization (ARPO), an end-to-end RL approach that augments Group Relative Policy Optimization (GRPO) with a replay buffer to reuse the successful experience across training iterations. To further stabilize the training process, we propose a task selection strategy that filters tasks based on baseline agent performance, allowing the agent to focus on learning from informative interactions. Additionally, we compare ARPO with offline preference optimization approaches, highlighting the advantages of policy-based methods in GUI environments. Experiments on the OSWorld benchmark demonstrate that ARPO achieves competitive results, establishing a new performance baseline for LLM-based GUI agents trained via reinforcement learning. Our findings underscore the effectiveness of reinforcement learning for training multi-turn, vision-language GUI agents capable of managing complex real-world UI interactions. Codes and models:https://github.com/dvlab-research/ARPO.git.

[Arxiv](https://arxiv.org/abs/2505.16282)