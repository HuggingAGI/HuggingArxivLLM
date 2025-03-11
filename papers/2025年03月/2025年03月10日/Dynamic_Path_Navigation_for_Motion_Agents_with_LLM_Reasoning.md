# 基于LLM推理的运动智能体动态路径导航

发布时间：2025年03月10日

`LLM应用` `机器人` `自动驾驶`

> Dynamic Path Navigation for Motion Agents with LLM Reasoning

# 摘要

> 大型语言模型（LLMs）展现了强大的通用推理和规划能力。然而，它们在空间路径规划和无障礙轨迹生成方面的有效性仍待进一步探索。利用LLMs进行导航具有巨大潜力，因其能够处理未见场景、支持用户-智能体交互，并在整个复杂系统中提供全局控制，使其非常适合用于智能体规划和人形运动生成。作为该领域首批研究之一，我们通过构建数据集并提出评估协议，探索了LLMs的零样本导航和路径生成能力。具体而言，我们使用直线连接的锚点来表示路径，支持多方向移动。与以往方法相比，此方法在保持简单直观的同时，为LLMs提供了更大的灵活性和实用性。我们证明，当任务以这种方式良好构建时，现代LLMs在避障规划方面表现出显著的能力，并能通过生成的运动自主优化导航以到达目标。此外，单个LLM运动智能体在静态环境中的空间推理能力可以无缝扩展到动态环境中多智能体的协调。与依赖单步规划或局部策略的传统方法不同，我们无需训练的LLM基方法实现了全局、动态、闭环规划，并能自主解决碰撞问题。

> Large Language Models (LLMs) have demonstrated strong generalizable reasoning and planning capabilities. However, their efficacies in spatial path planning and obstacle-free trajectory generation remain underexplored. Leveraging LLMs for navigation holds significant potential, given LLMs' ability to handle unseen scenarios, support user-agent interactions, and provide global control across complex systems, making them well-suited for agentic planning and humanoid motion generation. As one of the first studies in this domain, we explore the zero-shot navigation and path generation capabilities of LLMs by constructing a dataset and proposing an evaluation protocol. Specifically, we represent paths using anchor points connected by straight lines, enabling movement in various directions. This approach offers greater flexibility and practicality compared to previous methods while remaining simple and intuitive for LLMs. We demonstrate that, when tasks are well-structured in this manner, modern LLMs exhibit substantial planning proficiency in avoiding obstacles while autonomously refining navigation with the generated motion to reach the target. Further, this spatial reasoning ability of a single LLM motion agent interacting in a static environment can be seamlessly generalized in multi-motion agents coordination in dynamic environments. Unlike traditional approaches that rely on single-step planning or local policies, our training-free LLM-based method enables global, dynamic, closed-loop planning, and autonomously resolving collision issues.

[Arxiv](https://arxiv.org/abs/2503.07323)