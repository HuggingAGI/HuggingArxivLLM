# 快慢思维：利用大型语言模型解决复杂任务

发布时间：2025年04月11日

`LLM应用` `人工智能` `任务分解`

> Fast-Slow-Thinking: Complex Task Solving with Large Language Models

# 摘要

> 如今，大型语言模型（LLMs）正逐渐被用于解决复杂任务。面对这一挑战，任务分解已成为一种有效方法，该方法建议将复杂任务分解为多个更简单的子任务，然后分别解决它们，从而降低原始任务的难度。然而，现有任务分解方法在处理包含过于复杂逻辑和约束的任务时，性能可能不尽如人意。此时，LLMs生成的解决方案可能偏离任务的原始目标，或包含冗余甚至错误内容。因此，受人类拥有两种思维系统（包括快速思维和慢速思维）的启发，本文提出了一种新的任务分解方法，称为“Fast-Slow-Thinking”（FST），旨在通过快速思维（FT）和慢速思维（ST）步骤的协作，激发LLMs解决问题的能力。其中，FT更关注任务的一般性和简洁性，而ST则更关注任务的细节。在FT中，LLMs被提示去除原始任务的约束，从而将其简化为一个一般且简洁的任务。在ST中，我们重新引入FT中去除的约束，使LLMs能够改进FT生成的答案，以满足原始任务的要求。因此，我们的FST方法使LLMs能够通过从粗到细的人类认知过程来考虑复杂问题，这一有效性已在三种类型的任务实验中得到了充分验证。

> Nowadays, Large Language Models (LLMs) have been gradually employed to solve complex tasks. To face the challenge, task decomposition has become an effective way, which proposes to divide a complex task into multiple simpler subtasks and then solve them separately so that the difficulty of the original task can be reduced. However, the performance of existing task decomposition methods can be suboptimal when the task contains overly complex logic and constraints. In this situation, the solution generated by LLMs may deviate from the original purpose of the task, or contain redundant or even erroneous content. Therefore, inspired by the fact that humans possess two thinking systems including fast thinking and slow thinking, this paper introduces a new task decomposition method termed ``Fast-Slow-Thinking'' (FST), which stimulates LLMs to solve tasks through the cooperation of Fast Thinking (FT) and Slow Thinking (ST) steps. Here FT focuses more on the general and concise aspect of the task, and ST focuses more on the details of the task. In FT, LLMs are prompted to remove the constraints of the original task, therefore simplifying it to a general and concise one. In ST, we recall the constraints removed in FT, so that LLMs can improve the answer generated in FT to meet the requirements of the original task. Therefore, our FST method enables LLMs to consider a complex problem via a human-like cognition process from coarse to fine, the effectiveness of which has been well demonstrated by the experiments on three types of tasks.

[Arxiv](https://arxiv.org/abs/2504.08690)