# 面向控制的接触动力学学习：基于动作条件面部交互图网络

发布时间：2025年09月15日

`其他` `工业与制造`

> Learning Contact Dynamics for Control with Action-conditioned Face Interaction Graph Networks

# 摘要

> 我们提出了一款可学习物理模拟器，能在接触密集型操作中精准预测机器人末端执行器的运动及力-扭矩。该模型通过新增节点与边类型，扩展了最先进的基于图神经网络（GNN）的模拟器（FIGNet），实现了控制与状态估计任务所需的动作条件预测。仿真实验中，在极具挑战性的 peg-in-hole 任务中，采用我们模型的 MPC 智能体性能媲美使用真实动力学模型的同款控制器；而在真实世界实验中，相比基准物理模拟器，我们的模型运动预测精度提升50%，力-扭矩预测精度更是提高了3×。源代码与数据已公开。

> We present a learnable physics simulator that provides accurate motion and force-torque prediction of robot end effectors in contact-rich manipulation. The proposed model extends the state-of-the-art GNN-based simulator (FIGNet) with novel node and edge types, enabling action-conditional predictions for control and state estimation tasks. In simulation, the MPC agent using our model matches the performance of the same controller with the ground truth dynamics model in a challenging peg-in-hole task, while in the real-world experiment, our model achieves a 50% improvement in motion prediction accuracy and 3$\times$ increase in force-torque prediction precision over the baseline physics simulator. Source code and data are publicly available.

[Arxiv](https://arxiv.org/abs/2509.12151)