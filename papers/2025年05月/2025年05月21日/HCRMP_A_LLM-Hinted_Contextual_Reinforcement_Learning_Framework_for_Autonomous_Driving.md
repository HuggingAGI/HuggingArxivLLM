# # HCRMP：基于LLM提示的上下文强化学习框架，专为自动驾驶设计

发布时间：2025年05月21日

`LLM应用

摘要中讨论了将大型语言模型（LLMs）与强化学习（RL）结合，用于提升自动驾驶的性能。这属于将LLM技术应用于具体任务（自动驾驶），因此归类为LLM应用。` `自动驾驶`

> HCRMP: A LLM-Hinted Contextual Reinforcement Learning Framework for Autonomous Driving

# 摘要

> 将大型语言模型（LLMs）与强化学习（RL）相结合能够显著提升自动驾驶（AD）在复杂场景中的性能表现。然而，现有LLM主导的RL方法存在过度依赖LLM输出的问题，而这些输出往往伴随着幻觉现象。评估结果显示，即使是最先进的LLM，在关键驾驶任务上的非幻觉率也仅为约57.95%。这意味着，LLM产生的幻觉可能直接威胁到驾驶策略的性能表现。本文认为，要解决这一幻觉问题，关键在于保持LLM与RL之间的相对独立性。基于此，本文提出了一种全新的LLM提示强化学习范式。在此范式中，LLM负责生成语义提示，用于增强状态表示并优化策略，从而辅助RL代理进行运动规划；而RL代理则通过策略学习机制，有效抵消潜在的错误语义提示，最终实现卓越的驾驶性能。基于这一创新范式，我们提出了HCRMP（LLM提示的上下文强化学习运动规划器）架构。该架构包含三个核心模块：语义增强表示模块，用于扩展状态空间；上下文稳定性锚点模块，通过知识库信息增强多批评权重提示的可靠性；以及语义缓存模块，实现LLM低频指导与RL高频控制的无缝集成。在CARLA平台上的大量实验验证了HCRMP在整体驾驶性能方面的显著优势。在不同交通密度条件下，HCRMP的任务成功率高达80.3%。特别是在安全关键驾驶场景下，HCRMP将碰撞率显著降低了11.4%，充分展现了其在复杂场景中提升驾驶性能的卓越能力。
    

> Integrating Large Language Models (LLMs) with Reinforcement Learning (RL) can enhance autonomous driving (AD) performance in complex scenarios. However, current LLM-Dominated RL methods over-rely on LLM outputs, which are prone to hallucinations.Evaluations show that state-of-the-art LLM indicates a non-hallucination rate of only approximately 57.95% when assessed on essential driving-related tasks. Thus, in these methods, hallucinations from the LLM can directly jeopardize the performance of driving policies. This paper argues that maintaining relative independence between the LLM and the RL is vital for solving the hallucinations problem. Consequently, this paper is devoted to propose a novel LLM-Hinted RL paradigm. The LLM is used to generate semantic hints for state augmentation and policy optimization to assist RL agent in motion planning, while the RL agent counteracts potential erroneous semantic indications through policy learning to achieve excellent driving performance. Based on this paradigm, we propose the HCRMP (LLM-Hinted Contextual Reinforcement Learning Motion Planner) architecture, which is designed that includes Augmented Semantic Representation Module to extend state space. Contextual Stability Anchor Module enhances the reliability of multi-critic weight hints by utilizing information from the knowledge base. Semantic Cache Module is employed to seamlessly integrate LLM low-frequency guidance with RL high-frequency control. Extensive experiments in CARLA validate HCRMP's strong overall driving performance. HCRMP achieves a task success rate of up to 80.3% under diverse driving conditions with different traffic densities. Under safety-critical driving conditions, HCRMP significantly reduces the collision rate by 11.4%, which effectively improves the driving performance in complex scenarios.

[Arxiv](https://arxiv.org/abs/2505.15793)