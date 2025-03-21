# 通过大型语言模型实现安全感知任务规划的机器人方法

发布时间：2025年03月19日

`Agent` `机器人` `任务规划`

> Safety Aware Task Planning via Large Language Models in Robotics

# 摘要

> 将大语言模型（LLMs）整合到机器人任务规划中，为复杂、长周期的工作流程带来了更强大的推理能力。然而，确保LLM驱动计划的安全性仍然是一个关键挑战，因为这些模型往往优先考虑任务完成而非风险缓解。本文介绍了SAFER（面向机器人执行的安全感知框架），这是一个多LLM框架，旨在将安全意识嵌入机器人任务规划。SAFER采用一个安全代理，与主要任务规划器协同工作，提供安全反馈。此外，我们引入了LLM-as-a-Judge，一种新型度量，利用LLMs作为评估器来量化生成任务计划中的安全违规。我们的框架在执行的多个阶段整合安全反馈，实现实时风险评估、主动错误纠正和透明的安全评估。我们还集成了一个基于控制障碍函数（CBFs）的控制框架，以确保SAFER任务规划中的安全保证。我们在涉及异构机器人代理的复杂长周期任务上将SAFER与最先进的LLM规划器进行了比较，证明了其在减少安全违规的同时保持任务效率的有效性。我们还通过涉及多台机器人和人类的实际硬件实验验证了任务规划器和安全规划器。

> The integration of large language models (LLMs) into robotic task planning has unlocked better reasoning capabilities for complex, long-horizon workflows. However, ensuring safety in LLM-driven plans remains a critical challenge, as these models often prioritize task completion over risk mitigation. This paper introduces SAFER (Safety-Aware Framework for Execution in Robotics), a multi-LLM framework designed to embed safety awareness into robotic task planning. SAFER employs a Safety Agent that operates alongside the primary task planner, providing safety feedback. Additionally, we introduce LLM-as-a-Judge, a novel metric leveraging LLMs as evaluators to quantify safety violations within generated task plans. Our framework integrates safety feedback at multiple stages of execution, enabling real-time risk assessment, proactive error correction, and transparent safety evaluation. We also integrate a control framework using Control Barrier Functions (CBFs) to ensure safety guarantees within SAFER's task planning. We evaluated SAFER against state-of-the-art LLM planners on complex long-horizon tasks involving heterogeneous robotic agents, demonstrating its effectiveness in reducing safety violations while maintaining task efficiency. We also verify the task planner and safety planner through actual hardware experiments involving multiple robots and a human.

[Arxiv](https://arxiv.org/abs/2503.15707)