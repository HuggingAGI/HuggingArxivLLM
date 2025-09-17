# FLARE：下一代无人机网络中提升资源效率的飞行学习智能体

发布时间：2025年09月15日

`Agent` `基础理论`

> FLARE: Flying Learning Agents for Resource Efficiency in Next-Gen UAV Networks

# 摘要

> 本文聚焦于6G及未来无线网络的核心难题：在存在移动地面用户设备（UEs）的高度动态环境中，如何对空中智能平台（尤其是无人驾驶飞行器，UAVs）的功率与带宽资源进行联合优化。为此，我们提出飞行学习智能体资源效率框架（FLARE）——一个具备学习能力的空中智能框架，可实时联合优化UAV的定位、高度、发射功率及带宽分配。为应对UE移动性，我们采用基于轮廓系数的K均值聚类算法，实现用户动态分组与UAV在聚类中心的部署，从而高效提供服务。该问题被建模为多智能体控制任务：带宽被离散为资源块，功率则作为连续变量处理。仿真结果显示，该方法显著提升了用户覆盖性能：在5 Mbps数据速率约束下，服务用户数量较MADDPG基准方法提升73.45%。

> This letter addresses a critical challenge in the context of 6G and beyond wireless networks, the joint optimization of power and bandwidth resource allocation for aerial intelligent platforms, specifically uncrewed aerial vehicles (UAVs), operating in highly dynamic environments with mobile ground user equipment (UEs). We introduce FLARE (Flying Learning Agents for Resource Efficiency), a learning-enabled aerial intelligence framework that jointly optimizes UAV positioning, altitude, transmit power, and bandwidth allocation in real-time. To adapt to UE mobility, we employ Silhouette-based K-Means clustering, enabling dynamic grouping of users and UAVs' deployment at cluster centroids for efficient service delivery. The problem is modeled as a multi-agent control task, with bandwidth discretized into resource blocks and power treated as a continuous variable. To solve this, our proposed framework, FLARE, employs a hybrid reinforcement learning strategy that combines Multi-Agent Deep Deterministic Policy Gradient (MADDPG) and Deep Q-Network (DQN) to enhance learning efficiency. Simulation results demonstrate that our method significantly enhances user coverage, achieving a 73.45% improvement in the number of served users under a 5 Mbps data rate constraint, outperforming MADDPG baseline.

[Arxiv](https://arxiv.org/abs/2509.12307)