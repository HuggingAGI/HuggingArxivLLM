# 支持欺骗信号辅助的私人多跳分裂学习的模型分割与设备任务分配优化

发布时间：2025年07月09日

`其他` `网络安全`

> Optimizing Model Splitting and Device Task Assignment for Deceptive Signal Assisted Private Multi-hop Split Learning

# 摘要

> 本文研究了欺骗信号辅助的私有分割学习。在我们的模型中，多个边缘设备协作训练，而一些窃听者试图获取设备中的模型和数据信息。为防止信息泄露，部分设备可发送欺骗信号。因此，需确定用于发送欺骗信号的设备、模型训练设备及其分配的子模型。该问题被建模为一个优化问题，目标是在满足能耗和时延约束的同时，最小化泄露给窃听者的信。为解决此问题，我们提出了一种结合内在好奇心模块和交叉注意力机制的软 actor-critic 深度强化学习框架（ICM-CA）。该框架使集中式代理无需知道窃听者位置和监控概率，即可确定模型训练设备、欺骗信号传输设备、传输功率及子模型分配。所提出的方法通过 ICM 模块鼓励服务器探索新颖动作和状态，并利用 CA 模块确定历史状态-动作对的重要性，从而提升训练效率。仿真结果表明，与传统 SAC 算法相比，所提出方法将收敛速率提升 3 倍，并将泄露信息减少 13%。

> In this paper, deceptive signal-assisted private split learning is investigated. In our model, several edge devices jointly perform collaborative training, and some eavesdroppers aim to collect the model and data information from devices. To prevent the eavesdroppers from collecting model and data information, a subset of devices can transmit deceptive signals. Therefore, it is necessary to determine the subset of devices used for deceptive signal transmission, the subset of model training devices, and the models assigned to each model training device. This problem is formulated as an optimization problem whose goal is to minimize the information leaked to eavesdroppers while meeting the model training energy consumption and delay constraints. To solve this problem, we propose a soft actor-critic deep reinforcement learning framework with intrinsic curiosity module and cross-attention (ICM-CA) that enables a centralized agent to determine the model training devices, the deceptive signal transmission devices, the transmit power, and sub-models assigned to each model training device without knowing the position and monitoring probability of eavesdroppers. The proposed method uses an ICM module to encourage the server to explore novel actions and states and a CA module to determine the importance of each historical state-action pair thus improving training efficiency. Simulation results demonstrate that the proposed method improves the convergence rate by up to 3x and reduces the information leaked to eavesdroppers by up to 13% compared to the traditional SAC algorithm.

[Arxiv](https://arxiv.org/abs/2507.07323)