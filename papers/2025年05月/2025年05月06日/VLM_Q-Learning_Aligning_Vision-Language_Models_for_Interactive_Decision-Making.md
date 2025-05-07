# VLM Q-学习：优化视觉-语言模型，助力交互式决策

发布时间：2025年05月06日

`Agent

摘要讨论了将大型语言模型（LLMs）的能力整合到智能体中，并特别关注了视觉语言模型（VLMs）在多模态数据中的应用。研究重点在于提升智能体在交互式环境中的任务执行能力，探讨了监督微调（SFT）和强化学习（RL）在智能体任务中的应用，属于智能体领域的研究。` `计算机自动化`

> VLM Q-Learning: Aligning Vision-Language Models for Interactive Decision-Making

# 摘要

> 近期研究致力于将大型语言模型（LLMs）的通用知识和推理能力整合到智能体中，使其能够在交互式环境中完成用户指定的目标。视觉语言模型（VLMs）将 LLMs 扩展到多模态数据，并为智能体提供了在计算机自动化等领域新兴应用所需的视觉推理能力。然而，智能体任务强调的技能方面，现有的开源权重 VLMs 仍落后于其 LLM 对应模型。例如，VLMs 在遵循环境严格的输出语法要求方面能力较弱，且更侧重于开放式的问答任务。克服这些局限，需要在任务特定的专家演示上进行监督微调（SFT）。我们的研究从离线到在线强化学习（RL）的角度应对这些挑战。RL 使我们能够对 VLMs 进行微调以适应智能体任务，同时从自身模型或更强大（更大）模型的失败决策中学习。我们探索了一种离策略 RL 解决方案，既保留了广泛使用的 SFT 工作流的稳定性和简单性，又允许智能体自我改进并从低质量数据集中学习。我们通过两个开源 VLMs 在三个多模态智能体领域展示了这项技术。

> Recent research looks to harness the general knowledge and reasoning of large language models (LLMs) into agents that accomplish user-specified goals in interactive environments. Vision-language models (VLMs) extend LLMs to multi-modal data and provide agents with the visual reasoning necessary for new applications in areas such as computer automation. However, agent tasks emphasize skills where accessible open-weight VLMs lag behind their LLM equivalents. For example, VLMs are less capable of following an environment's strict output syntax requirements and are more focused on open-ended question answering. Overcoming these limitations requires supervised fine-tuning (SFT) on task-specific expert demonstrations. Our work approaches these challenges from an offline-to-online reinforcement learning (RL) perspective. RL lets us fine-tune VLMs to agent tasks while learning from the unsuccessful decisions of our own model or more capable (larger) models. We explore an off-policy RL solution that retains the stability and simplicity of the widely used SFT workflow while allowing our agent to self-improve and learn from low-quality datasets. We demonstrate this technique with two open-weight VLMs across three multi-modal agent domains.

[Arxiv](https://arxiv.org/abs/2505.03181)