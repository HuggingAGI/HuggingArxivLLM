# Tac2Motion：面向机器人手部操作的触觉反馈接触感知强化学习

发布时间：2025年09月22日

`强化学习` `工业与制造`

> Tac2Motion: Contact-Aware Reinforcement Learning with Tactile Feedback for Robotic Hand Manipulation

# 摘要

> 本文提出Tac2Motion——一个接触感知强化学习框架，助力学习移除盖子等富含接触的手部操作任务。为此，我们设计了基于触觉感知的奖励塑造方法，并通过嵌入将触觉信号融入观察空间。所构建的奖励机制能同时激励智能体实现稳固抓握与平滑手指移动，相比基线方法，数据效率和鲁棒性均显著提升。我们在开盖场景中验证了该框架，结果显示训练后的策略可泛化至多种物体类型及扭转摩擦等复杂动态场景。最后，通过多指机器人Shadow Robot演示了所学策略，证实其具备向真实环境迁移的能力。视频链接：https://youtu.be/poeJBPR7urQ。

> This paper proposes Tac2Motion, a contact-aware reinforcement learning framework to facilitate the learning of contact-rich in-hand manipulation tasks, such as removing a lid. To this end, we propose tactile sensing-based reward shaping and incorporate the sensing into the observation space through embedding. The designed rewards encourage an agent to ensure firm grasping and smooth finger gaiting at the same time, leading to higher data efficiency and robust performance compared to the baseline. We verify the proposed framework on the opening a lid scenario, showing generalization of the trained policy into a couple of object types and various dynamics such as torsional friction. Lastly, the learned policy is demonstrated on the multi-fingered robot, Shadow Robot, showing that the control policy can be transferred to the real world. The video is available: https://youtu.be/poeJBPR7urQ.

[Arxiv](https://arxiv.org/abs/2509.17812)