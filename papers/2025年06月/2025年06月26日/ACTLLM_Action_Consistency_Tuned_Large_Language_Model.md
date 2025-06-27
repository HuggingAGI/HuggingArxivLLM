# ACTLLM：行动一致性调优的大型语言模型

发布时间：2025年06月26日

`LLM应用` `机器人` `机器人操作`

> ACTLLM: Action Consistency Tuned Large Language Model

# 摘要

> 本文提出了一种名为ACTLLM（动作一致性调优大型语言模型）的创新方法，专为动态环境中的机器人操作而设计。传统基于视觉的系统在学习适用于任务执行与空间推理的视觉表示方面存在困难，这限制了它们在动态环境中的应用。ACTLLM通过语言构建结构化的场景描述，提供了一个统一的接口，支持通过灵活的语言指令实现空间理解与任务执行。此外，我们引入了一种新的动作一致性约束机制，将视觉感知与对应动作对齐，从而提升可操作视觉表示的学习效果。我们还创新性地将机器人操作任务的马尔可夫决策过程重新表述为一个多轮视觉对话框架，使长期任务执行的建模能够通过任务执行历史中的增强上下文相关性得到支持。在我们的评估中，ACTLLM在各种场景下表现出色，充分证明了其在具有挑战性的视觉机器人操作任务中的有效性。

> This paper introduces ACTLLM (Action Consistency Tuned Large Language Model), a novel approach for robot manipulation in dynamic environments. Traditional vision-based systems often struggle to learn visual representations that excel in both task execution and spatial reasoning, thereby limiting their adaptability in dynamic environments. ACTLLM addresses these challenges by harnessing language to craft structured scene descriptors, providing a uniform interface for both spatial understanding and task performance through flexible language instructions. Moreover, we introduce a novel action consistency constraint that aligns visual perception with corresponding actions, thereby enhancing the learning of actionable visual representations. Additionally, we have reformulated the Markov decision process for manipulation tasks into a multi-turn visual dialogue framework. This approach enables the modeling of long-term task execution with enhanced contextual relevance derived from the history of task execution. During our evaluation, ACTLLM excels in diverse scenarios, proving its effectiveness on challenging vision-based robot manipulation tasks.

[Arxiv](https://arxiv.org/abs/2506.21250)