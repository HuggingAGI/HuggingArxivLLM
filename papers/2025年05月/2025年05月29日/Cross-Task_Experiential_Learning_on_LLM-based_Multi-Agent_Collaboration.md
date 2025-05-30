# LLM驱动的多智能体协作中的跨任务经验学习探索

发布时间：2025年05月29日

`Agent` `人工智能` `机器人学`

> Cross-Task Experiential Learning on LLM-based Multi-Agent Collaboration

# 摘要

> 基于大型语言模型的多智能体系统 (MAS) 在解决复杂任务方面取得了显著进展，尤其在协作推理和跨智能体 critique 方面表现突出。然而，现有方法通常将每个任务孤立处理，导致冗余计算，并限制了在结构相似任务上的泛化能力。为了解决这一问题，我们提出了多智能体跨任务经验学习 (MAEL) 框架，赋予智能体跨任务学习和经验积累的能力。我们通过图结构的多智能体协作网络建模任务解决工作流，智能体在该网络中通过显式连接传播信息并进行协调。在经验学习阶段，我们量化任务解决过程中的每一步质量，并将奖励、输入输出存储到智能体的经验池中。在推理阶段，智能体检索高奖励的经验作为 few-shot 示例，提升推理有效性，实现更高效和准确的协作。实验结果表明，MAEL 赋予智能体有效利用先前经验的能力，显著提升了当前任务的收敛速度和解决方案质量。

> Large Language Model-based multi-agent systems (MAS) have shown remarkable progress in solving complex tasks through collaborative reasoning and inter-agent critique. However, existing approaches typically treat each task in isolation, resulting in redundant computations and limited generalization across structurally similar tasks. To address this, we introduce multi-agent cross-task experiential learning (MAEL), a novel framework that endows LLM-driven agents with explicit cross-task learning and experience accumulation. We model the task-solving workflow on a graph-structured multi-agent collaboration network, where agents propagate information and coordinate via explicit connectivity. During the experiential learning phase, we quantify the quality for each step in the task-solving workflow and store the resulting rewards along with the corresponding inputs and outputs into each agent's individual experience pool. During inference, agents retrieve high-reward, task-relevant experiences as few-shot examples to enhance the effectiveness of each reasoning step, thereby enabling more accurate and efficient multi-agent collaboration. Experimental results on diverse datasets demonstrate that MAEL empowers agents to learn from prior task experiences effectively-achieving faster convergence and producing higher-quality solutions on current tasks.

[Arxiv](https://arxiv.org/abs/2505.23187)