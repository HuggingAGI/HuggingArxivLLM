# 策略蒸馏的精炼：从多任务通用模型走向强化学习专家

发布时间：2025年03月06日

`LLM应用` `机器人` `机器学习`

> Refined Policy Distillation: From VLA Generalists to RL Experts

# 摘要

> 近期的通用视觉-语言-动作模型（VLAs）展现了强大的泛化能力，能够在真实机器人上执行多种任务。然而，其成功率往往不及专家策略，且通常需要针对具体设置进行微调。我们提出了一种基于强化学习（RL）的策略优化方法——精炼策略蒸馏（RPD），能够将大型通用模型高效地转化为小型、高性能的专家策略。在RL探索过程中，学生策略通过模仿教师VLA的动作来提升学习效率。与以往专注于真实世界实验的研究不同，我们在ManiSkill2平台上为Octo和OpenVLA创建了微调版本，用于在模拟环境中评估RPD。实验结果表明，RPD使RL代理能够学习超越教师表现的专家策略，无论是在密集还是稀疏奖励设置下。此外，我们的方法对摄像头视角的变化具有良好的鲁棒性，并能够推广到基础VLA无法解决的任务变体。

> Recent generalist Vision-Language-Action Models (VLAs) can perform a variety of tasks on real robots with remarkable generalization capabilities. However, reported success rates are often not on par with those of expert policies. Moreover, VLAs usually do not work out of the box and often must be fine-tuned as they are sensitive to setup changes. In this work, we present Refined Policy Distillation (RPD), an RL-based policy refinement method that enables the distillation of large generalist models into small, high-performing expert policies. The student policy is guided during the RL exploration by actions of a teacher VLA for increased sample efficiency and faster convergence. Different from previous work that focuses on applying VLAs to real-world experiments, we create fine-tuned versions of Octo and OpenVLA for ManiSkill2 to evaluate RPD in simulation. As our results for different manipulation tasks demonstrate, RPD enables the RL agent to learn expert policies that surpass the teacher's performance in both dense and sparse reward settings. Our approach is even robust to changes in the camera perspective and can generalize to task variations that the underlying VLA cannot solve.

[Arxiv](https://arxiv.org/abs/2503.05833)