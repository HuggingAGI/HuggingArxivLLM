# PilotRL: 利用全局规划引导的渐进式强化学习训练语言模型代理

发布时间：2025年08月01日

`Agent` `智能体`

> PilotRL: Training Language Model Agents via Global Planning-Guided Progressive Reinforcement Learning

# 摘要

> 大型语言模型（LLMs）在agent-oriented任务中展现出卓越能力，但现有方法在agent环境中的应用仍存在诸多挑战。当前主流的ReAct范式（反应式智能体）虽将单步推理与即时行动执行相结合，但在需要长期战略性规划的复杂任务中表现有限。此外，规划与执行的协同优化也是agent设计中的关键难题。现有方法多依赖监督微调，这导致模型倾向于记忆既定任务路径，限制了其在新问题情境中的泛化能力。针对这些挑战，我们提出了自适应全局规划范式AdaPlan，旨在通过高层显式指引与执行的协同，支持长视界决策。基于此，我们进一步开发了PilotRL——一个由渐进式强化学习驱动的LLM代理训练框架。首先，我们培养模型在agent任务中遵循全局计划显式指引的能力。随后，我们专注于提升生成计划的质量。最后，我们实现了规划与执行协同的联合优化。实验结果表明，PilotRL表现优异，LLaMA3.1-8B-Instruct + PilotRL较闭源GPT-4o提升了3.60%，与参数规模相当的GPT-4o-mini相比更是大幅领先了55.78%。

> Large Language Models (LLMs) have shown remarkable advancements in tackling agent-oriented tasks. Despite their potential, existing work faces challenges when deploying LLMs in agent-based environments. The widely adopted agent paradigm ReAct centers on integrating single-step reasoning with immediate action execution, which limits its effectiveness in complex tasks requiring long-term strategic planning. Furthermore, the coordination between the planner and executor during problem-solving is also a critical factor to consider in agent design. Additionally, current approaches predominantly rely on supervised fine-tuning, which often leads models to memorize established task completion trajectories, thereby restricting their generalization ability when confronted with novel problem contexts. To address these challenges, we introduce an adaptive global plan-based agent paradigm AdaPlan, aiming to synergize high-level explicit guidance with execution to support effective long-horizon decision-making. Based on the proposed paradigm, we further put forward PilotRL, a global planning-guided training framework for LLM agents driven by progressive reinforcement learning. We first develop the model's ability to follow explicit guidance from global plans when addressing agent tasks. Subsequently, based on this foundation, we focus on optimizing the quality of generated plans. Finally, we conduct joint optimization of the model's planning and execution coordination. Experiments indicate that PilotRL could achieve state-of-the-art performances, with LLaMA3.1-8B-Instruct + PilotRL surpassing closed-sourced GPT-4o by 3.60%, while showing a more substantial gain of 55.78% comparing to GPT-4o-mini at a comparable parameter scale.

[Arxiv](https://arxiv.org/abs/2508.00344)