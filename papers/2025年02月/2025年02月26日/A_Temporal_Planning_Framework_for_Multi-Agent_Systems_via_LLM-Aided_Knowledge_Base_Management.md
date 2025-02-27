# 基于LLM赋能的知识库管理的多智能体系统时序规划框架

发布时间：2025年02月26日

`LLM应用` `机器人` `自动化`

> A Temporal Planning Framework for Multi-Agent Systems via LLM-Aided Knowledge Base Management

# 摘要

> 本文提出了一种名为PLANTOR的创新框架，将大型语言模型（LLMs）与基于Prolog的知识管理和规划相结合，专为多机器人任务设计。该系统采用两阶段生成面向机器人的知识库，确保了知识的可重用性和组合推理能力。同时，通过三步规划流程，利用混合整数线性规划处理时间依赖性、资源约束以及并行任务执行。最终规划方案被转换为行为树，便于在ROS2中直接应用。我们在积木世界和拱门搭建场景中进行了多机器人装配任务的测试。结果显示，LLMs能够生成准确的知识库，仅需少量人工反馈，而Prolog则确保了规划的严谨性和可解释性。这一方法充分展现了将LLMs应用于需要灵活、可扩展且人类可理解规划能力的先进机器人任务的巨大潜力。

> This paper presents a novel framework, called PLANTOR (PLanning with Natural language for Task-Oriented Robots), that integrates Large Language Models (LLMs) with Prolog-based knowledge management and planning for multi-robot tasks. The system employs a two-phase generation of a robot-oriented knowledge base, ensuring reusability and compositional reasoning, as well as a three-step planning procedure that handles temporal dependencies, resource constraints, and parallel task execution via mixed-integer linear programming. The final plan is converted into a Behaviour Tree for direct use in ROS2. We tested the framework in multi-robot assembly tasks within a block world and an arch-building scenario. Results demonstrate that LLMs can produce accurate knowledge bases with modest human feedback, while Prolog guarantees formal correctness and explainability. This approach underscores the potential of LLM integration for advanced robotics tasks requiring flexible, scalable, and human-understandable planning.

[Arxiv](https://arxiv.org/abs/2502.19135)