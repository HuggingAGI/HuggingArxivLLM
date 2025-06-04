# 三思而后行：LLM与RL在大规模决策中的协同进化框架

发布时间：2025年06月03日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在大规模工业决策问题中的应用，结合强化学习（RL）代理，提出了一种协同进化的框架（ACE）。论文的重点在于将LLMs应用于复杂的决策场景，并通过实验证明其有效性，属于LLM的应用层面。`

> Think Twice, Act Once: A Co-Evolution Framework of LLM and RL for Large-Scale Decision Making

# 摘要

> 大型语言模型（LLMs）与强化学习（RL）在决策任务中展现出巨大潜力，但面对大规模工业决策问题时，两者各有局限：LLMs缺乏实时长序列决策能力，而RL在广阔动作空间中采样效率不足。为解决这一难题，我们提出Agents协同进化（ACE）框架，结合LLMs与RL代理，专为大规模决策场景设计。ACE创新性地引入双角色轨迹优化机制，在RL训练过程中，LLMs同时扮演策略执行者与价值评估者的角色：执行者通过多步推理和环境验证优化次优动作，评估者则通过轨迹级奖励塑造实现时间信用分配。同时，RL代理通过优先经验回放生成高质量微调数据，反向提升LLMs的任务特定决策能力。在涵盖6万以上离散动作的多电力系统运营挑战中，ACE通过大量实验验证，展现出优于现有RL方法和LLM基方法的卓越性能。

> Recent advancements in Large Language Models (LLMs) and Reinforcement Learning (RL) have shown significant promise in decision-making tasks. Nevertheless, for large-scale industrial decision problems, both approaches face distinct challenges: LLMs lack real-time long-sequence decision-making capabilities, while RL struggles with sample efficiency in vast action spaces. To bridge this gap, we propose Agents Co-Evolution (ACE), a synergistic framework between LLMs and RL agents for large-scale decision-making scenarios. ACE introduces a dual-role trajectory refinement mechanism where LLMs act as both Policy Actor and Value Critic during RL's training: the Actor refines suboptimal actions via multi-step reasoning and environment validation, while the Critic performs temporal credit assignment through trajectory-level reward shaping. Concurrently, RL agent enhances LLMs' task-specific decision-making with high-quality fine-tuning datasets generated via prioritized experience replay. Through extensive experiments across multiple power grid operation challenges with action spaces exceeding 60K discrete actions, ACE demonstrates superior performance over existing RL methods and LLM-based methods.

[Arxiv](https://arxiv.org/abs/2506.02522)