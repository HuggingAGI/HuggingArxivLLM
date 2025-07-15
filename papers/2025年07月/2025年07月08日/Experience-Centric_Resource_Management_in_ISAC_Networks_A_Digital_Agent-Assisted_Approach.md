# 体验驱动的ISAC网络资源管理：基于数字代理的管理方法

发布时间：2025年07月08日

`Agent` `数字代理` `资源管理`

> Experience-Centric Resource Management in ISAC Networks: A Digital Agent-Assisted Approach

# 摘要

> 本文提出了一种数字代理 (DA) 辅助的资源管理方案，旨在提升集成感知与通信 (ISAC) 网络中的用户体验质量 (QoE)。用户 QoE 是一个综合指标，融合了服务质量 (QoS)、用户行为动态和环境复杂度。创新的 DA 模块包含用户状态预测、QoS 因子选择和 QoE 拟合三个模型，通过分析历史数据构建并更新用户专属的 QoE 模型。根据 QoE 模型将用户聚类分组。利用 Cramér-Rao 下界 (CRB) 模型量化通信资源对感知精度的影响。我们制定了一个通信和计算资源管理的联合优化问题，在满足 CRB 和资源约束的前提下，最大化用户的长期 QoE。开发了一种双层数据-模型驱动算法，顶层通过深度强化学习进行组级决策，底层采用凸优化技术进行用户级决策。基于真实数据集的仿真结果表明，该方案在用户 QoE 方面优于现有基准方案。

> In this paper, we propose a digital agent (DA)-assisted resource management scheme for enhanced user quality of experience (QoE) in integrated sensing and communication (ISAC) networks. Particularly, user QoE is a comprehensive metric that integrates quality of service (QoS), user behavioral dynamics, and environmental complexity. The novel DA module includes a user status prediction model, a QoS factor selection model, and a QoE fitting model, which analyzes historical user status data to construct and update user-specific QoE models. Users are clustered into different groups based on their QoE models. A Cramér-Rao bound (CRB) model is utilized to quantify the impact of allocated communication resources on sensing accuracy. A joint optimization problem of communication and computing resource management is formulated to maximize long-term user QoE while satisfying CRB and resource constraints. A two-layer data-model-driven algorithm is developed to solve the formulated problem, where the top layer utilizes an advanced deep reinforcement learning algorithm to make group-level decisions, and the bottom layer uses convex optimization techniques to make user-level decisions. Simulation results based on a real-world dataset demonstrate that the proposed DA-assisted resource management scheme outperforms benchmark schemes in terms of user QoE.

[Arxiv](https://arxiv.org/abs/2507.06436)