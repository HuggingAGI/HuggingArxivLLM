# # 视觉覆盖路径规划中的提示增强强化学习  
通过强化学习实现视觉覆盖路径规划的提示增强方法

发布时间：2025年07月14日

`Agent` `无人机` `路径规划`

> Prompt Informed Reinforcement Learning for Visual Coverage Path Planning

# 摘要

> 基于无人机的视觉覆盖路径规划要求智能体巧妙地协调无人机的运动与摄像头控制，以实现最大覆盖范围、最小化冗余并保持电池效率。传统的强化学习 (RL) 方法依赖于特定于环境的奖励函数，缺乏语义适应性。本研究提出了一种名为提示增强型强化学习 (PIRL) 的新方法，该方法将大型语言模型的零样本推理能力和上下文学习能力与基于好奇心的强化学习相结合。PIRL 利用大语言模型 GPT-3.5 提供的语义反馈，动态塑造 Proximal Policy Optimization (PPO) 强化学习策略的奖励函数，从而引导智能体进行位置和摄像头调整以实现最佳视觉覆盖。PIRL 代理使用 OpenAI Gym 进行训练，并在各种环境中进行评估。此外，通过在引入现实物理动力学的 Webots 模拟器中运行代理，测试了代理的仿真到现实迁移能力和零样本泛化能力。实验结果表明，PIRL 在多个基于学习的基线方法中表现最佳，包括静态奖励 PPO、探索性权重初始化 PPO、模仿学习和仅使用 LLM 的控制器。在不同环境中，与表现最好的基线相比，PIRL 在 OpenAI Gym 中实现了高达 14% 的视觉覆盖提升，在 Webots 中实现了 27% 的提升，电池效率提高了 25%，冗余降低了 18%。结果突显了基于大语言模型的奖励塑造在复杂空间探索任务中的有效性，并为将自然语言先验融入强化学习在机器人领域的应用指明了有前景的方向。

> Visual coverage path planning with unmanned aerial vehicles (UAVs) requires agents to strategically coordinate UAV motion and camera control to maximize coverage, minimize redundancy, and maintain battery efficiency. Traditional reinforcement learning (RL) methods rely on environment-specific reward formulations that lack semantic adaptability. This study proposes Prompt-Informed Reinforcement Learning (PIRL), a novel approach that integrates the zero-shot reasoning ability and in-context learning capability of large language models with curiosity-driven RL. PIRL leverages semantic feedback from an LLM, GPT-3.5, to dynamically shape the reward function of the Proximal Policy Optimization (PPO) RL policy guiding the agent in position and camera adjustments for optimal visual coverage. The PIRL agent is trained using OpenAI Gym and evaluated in various environments. Furthermore, the sim-to-real-like ability and zero-shot generalization of the agent are tested by operating the agent in Webots simulator which introduces realistic physical dynamics. Results show that PIRL outperforms multiple learning-based baselines such as PPO with static rewards, PPO with exploratory weight initialization, imitation learning, and an LLM-only controller. Across different environments, PIRL outperforms the best-performing baseline by achieving up to 14% higher visual coverage in OpenAI Gym and 27% higher in Webots, up to 25% higher battery efficiency, and up to 18\% lower redundancy, depending on the environment. The results highlight the effectiveness of LLM-guided reward shaping in complex spatial exploration tasks and suggest a promising direction for integrating natural language priors into RL for robotics.

[Arxiv](https://arxiv.org/abs/2507.10284)