# REMAC: 自我反思与自我进化的多智能体协作系统，用于长期规划的机器人操作。

发布时间：2025年03月27日

`Agent

理由：这篇论文主要探讨了视觉语言模型在机器人规划中的应用，特别是通过多智能体框架REMAC实现任务规划和执行。它重点在于智能体的自适应性和协作能力，符合Agent类别的定义。` `机器人` `多智能体系统`

> REMAC: Self-Reflective and Self-Evolving Multi-Agent Collaboration for Long-Horizon Robot Manipulation

# 摘要

> 视觉语言模型（VLMs）在机器人规划领域展现了卓越的能力，尤其在需要对环境进行全面理解以进行任务分解的长期任务中表现突出。然而，现有方法通常依赖于预先掌握的环境知识或精心设计的任务特定提示，这使得它们难以应对动态场景变化或意外的任务条件，例如机器人试图将胡萝卜放入微波炉却发现门是关着的。这些挑战凸显了适应性和效率两大关键问题。

为了解决这些问题，我们提出了一种自适应的多智能体规划框架——REMAC。它通过持续的反思和自我进化，实现了高效、场景无关的多机器人长期任务规划与执行。REMAC包含两个核心模块：一个在循环中执行事前和事后检查的自我反思模块，用于评估进度并完善计划；以及一个根据场景特定推理动态调整计划的自我进化模块。

REMAC提供了三个显著优势：首先，机器人可以在无需复杂提示设计的情况下，初步探索和推理环境。其次，机器人能够持续反思潜在的规划错误，并根据任务特定的见解调整计划。最后，在迭代之后，一个机器人可以调用另一个机器人来协调任务并行执行，从而最大化任务执行效率。

为了验证REMAC的有效性，我们基于RoboCasa构建了一个多智能体的长期机器人操作与导航环境，包含4类任务、27种任务风格以及50多种不同物体。在此基础上，我们进一步对包括DeepSeek-R1、o3-mini、QwQ和Grok3在内的最新推理模型进行了基准测试。结果显示，与单机器人基线相比，REMAC将平均成功率提升了40%，执行效率提升了52.7%，充分证明了其优越性。


> Vision-language models (VLMs) have demonstrated remarkable capabilities in robotic planning, particularly for long-horizon tasks that require a holistic understanding of the environment for task decomposition. Existing methods typically rely on prior environmental knowledge or carefully designed task-specific prompts, making them struggle with dynamic scene changes or unexpected task conditions, e.g., a robot attempting to put a carrot in the microwave but finds the door was closed. Such challenges underscore two critical issues: adaptability and efficiency. To address them, in this work, we propose an adaptive multi-agent planning framework, termed REMAC, that enables efficient, scene-agnostic multi-robot long-horizon task planning and execution through continuous reflection and self-evolution. REMAC incorporates two key modules: a self-reflection module performing pre-condition and post-condition checks in the loop to evaluate progress and refine plans, and a self-evolvement module dynamically adapting plans based on scene-specific reasoning. It offers several appealing benefits: 1) Robots can initially explore and reason about the environment without complex prompt design. 2) Robots can keep reflecting on potential planning errors and adapting the plan based on task-specific insights. 3) After iterations, a robot can call another one to coordinate tasks in parallel, maximizing the task execution efficiency. To validate REMAC's effectiveness, we build a multi-agent environment for long-horizon robot manipulation and navigation based on RoboCasa, featuring 4 task categories with 27 task styles and 50+ different objects. Based on it, we further benchmark state-of-the-art reasoning models, including DeepSeek-R1, o3-mini, QwQ, and Grok3, demonstrating REMAC's superiority by boosting average success rates by 40% and execution efficiency by 52.7% over the single robot baseline.

[Arxiv](https://arxiv.org/abs/2503.22122)