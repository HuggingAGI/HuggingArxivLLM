# # 利用大型语言模型实现轨迹适应

发布时间：2025年04月17日

`LLM应用` `机器人` `机器人控制`

> Trajectory Adaptation using Large Language Models

# 摘要

> 根据人类指令，让机器人轨迹灵活适应新情况，对于实现更直观、更具扩展性的人机交互至关重要。我们提出了一种灵活的语言框架，用于调整由现成的运动规划算法（如RRT、A-star等）生成的通用机器人轨迹，或从人类演示中学习得到的轨迹。通过利用预训练的大语言模型（LLMs）生成代码作为策略，我们能够对轨迹关键点进行适应，从而实现比现有方法更复杂、更灵活的指令。这种方法不仅支持更广泛的命令类型，包括数值输入，还无需特定任务的训练，提供更高的可解释性以及更有效的反馈机制。我们在Pybullet和Gazebo仿真环境中，对机械臂、飞行器和地面机器人进行了模拟实验，结果表明LLMs能够成功地将轨迹适应于复杂的用户指令。

> Adapting robot trajectories based on human instructions as per new situations is essential for achieving more intuitive and scalable human-robot interactions. This work proposes a flexible language-based framework to adapt generic robotic trajectories produced by off-the-shelf motion planners like RRT, A-star, etc, or learned from human demonstrations. We utilize pre-trained LLMs to adapt trajectory waypoints by generating code as a policy for dense robot manipulation, enabling more complex and flexible instructions than current methods. This approach allows us to incorporate a broader range of commands, including numerical inputs. Compared to state-of-the-art feature-based sequence-to-sequence models which require training, our method does not require task-specific training and offers greater interpretability and more effective feedback mechanisms. We validate our approach through simulation experiments on the robotic manipulator, aerial vehicle, and ground robot in the Pybullet and Gazebo simulation environments, demonstrating that LLMs can successfully adapt trajectories to complex human instructions.

[Arxiv](https://arxiv.org/abs/2504.12755)