# # MoManipVLA: 迁移视觉-语言-动作模型应用于通用移动操作
MoManipVLA: 迁移视觉-语言-动作模型的能力，应用于通用移动操作任务。

发布时间：2025年03月17日

`LLM应用` `机器人技术` `视觉语言动作模型`

> MoManipVLA: Transferring Vision-language-action Models for General Mobile Manipulation

# 摘要

> # 摘要  
移动操作是机器人协助人类处理日常多样化任务与环境的核心挑战。传统方法因缺乏大规模训练，往往难以实现跨任务与跨环境的泛化。近期视觉语言动作（VLA）模型虽展现强大泛化能力，但专为固定基座操作设计。为此，我们提出MoManipVLA框架，将预训练的固定基座VLA模型迁移至移动操作，实现跨任务与环境的高泛化能力。具体而言，我们利用VLA模型生成高泛化能力的末端执行器路点，并为移动基座与机械臂设计运动规划目标，以确保轨迹的物理可行性。最后，我们提出双层优化框架：上层优化预测基座路点以扩展操作策略空间，下层优化选择最优末端轨迹完成任务。通过零样本调整基座位置，使固定基座VLA模型的预测路点可行。实验结果表明，MoManipVLA的成功率比现有方法高出4.2%，且仅需50次训练即可部署，得益于VLA模型的强大泛化能力。

> Mobile manipulation is the fundamental challenge for robotics to assist humans with diverse tasks and environments in everyday life. However, conventional mobile manipulation approaches often struggle to generalize across different tasks and environments because of the lack of large-scale training. In contrast, recent advances in vision-language-action (VLA) models have shown impressive generalization capabilities, but these foundation models are developed for fixed-base manipulation tasks. Therefore, we propose an efficient policy adaptation framework named MoManipVLA to transfer pre-trained VLA models of fix-base manipulation to mobile manipulation, so that high generalization ability across tasks and environments can be achieved in mobile manipulation policy. Specifically, we utilize pre-trained VLA models to generate waypoints of the end-effector with high generalization ability. We design motion planning objectives for the mobile base and the robot arm, which aim at maximizing the physical feasibility of the trajectory. Finally, we present an efficient bi-level objective optimization framework for trajectory generation, where the upper-level optimization predicts waypoints for base movement to enhance the manipulator policy space, and the lower-level optimization selects the optimal end-effector trajectory to complete the manipulation task. In this way, MoManipVLA can adjust the position of the robot base in a zero-shot manner, thus making the waypoints predicted from the fixed-base VLA models feasible. Extensive experimental results on OVMM and the real world demonstrate that MoManipVLA achieves a 4.2% higher success rate than the state-of-the-art mobile manipulation, and only requires 50 training cost for real world deployment due to the strong generalization ability in the pre-trained VLA models.

[Arxiv](https://arxiv.org/abs/2503.13446)