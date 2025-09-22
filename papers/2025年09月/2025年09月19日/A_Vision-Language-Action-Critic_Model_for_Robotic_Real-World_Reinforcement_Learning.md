# 面向机器人现实世界强化学习的视觉-语言-动作-评论家模型

发布时间：2025年09月19日

`强化学习` `工业与制造`

> A Vision-Language-Action-Critic Model for Robotic Real-World Reinforcement Learning

# 摘要

> 在机器人真实世界强化学习（RL）领域，基于视觉-语言-动作（VLA）模型的方法一直受限于稀疏的手工奖励设计和低效的探索过程。为此，我们提出VLAC——一种基于InternVL构建、在大规模异构数据集上训练的通用过程奖励模型。给定成对观测与语言目标，VLAC能输出密集的进度增量和完成信号，省去了特定任务的奖励工程，还支持对未见任务和环境的单样本上下文迁移。VLAC的训练融合了多类数据：在视觉-语言数据集上学习以强化感知、对话与推理能力；结合机器人和人类轨迹数据，为动作生成与进度估计奠定基础；同时通过构建大量负样本和语义不匹配样本，进一步强化了拒绝无关提示及检测倒退或停滞的能力。借助提示控制，单个VLAC模型可交替生成奖励与动作标记，实现了评论家（critic）与策略（policy）的统一。将VLAC部署到异步真实世界RL循环后，我们叠加了分级人类在环协议（包括离线演示回放、返回与探索、人类引导探索），从而加速探索过程并稳定早期学习阶段。在四项不同的真实世界操作任务中，VLAC在200次真实世界交互回合内就将成功率从约30%提升至90%左右；而结合人类在环干预后，样本效率进一步提升50%，最终成功率更是高达100%。

> Robotic real-world reinforcement learning (RL) with vision-language-action (VLA) models is bottlenecked by sparse, handcrafted rewards and inefficient exploration. We introduce VLAC, a general process reward model built upon InternVL and trained on large scale heterogeneous datasets. Given pairwise observations and a language goal, it outputs dense progress delta and done signal, eliminating task-specific reward engineering, and supports one-shot in-context transfer to unseen tasks and environments. VLAC is trained on vision-language datasets to strengthen perception, dialogic and reasoning capabilities, together with robot and human trajectories data that ground action generation and progress estimation, and additionally strengthened to reject irrelevant prompts as well as detect regression or stagnation by constructing large numbers of negative and semantically mismatched samples. With prompt control, a single VLAC model alternately generating reward and action tokens, unifying critic and policy. Deployed inside an asynchronous real-world RL loop, we layer a graded human-in-the-loop protocol (offline demonstration replay, return and explore, human guided explore) that accelerates exploration and stabilizes early learning. Across four distinct real-world manipulation tasks, VLAC lifts success rates from about 30\% to about 90\% within 200 real-world interaction episodes; incorporating human-in-the-loop interventions yields a further 50% improvement in sample efficiency and achieves up to 100% final success.

[Arxiv](https://arxiv.org/abs/2509.15937)