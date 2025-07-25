# 增强型速度自适应方案：车联网中公平接入与信息更新速度的联合优化

发布时间：2025年07月24日

`LLM应用` `车联网`

> Enhanced Velocity-Adaptive Scheme: Joint Fair Access and Age of Information Optimization in Vehicular Networks

# 摘要

> 本文探讨了5G新空口（NR）车辆到基础设施（V2I）模式2下车联网中的公平接入问题和信息年龄（AoI）。具体而言，车辆通过模式2与路边单元（RSU）通信，以获取驾驶辅助所需的精确数据。然而，由于车辆在相邻车道行驶时速度差异，导致其在RSU上的驻留时间和通信时长不同，这可能引发网络资源分配不均，进而影响驾驶安全。为确保数据新鲜度，需分析AoI。模式2引入的新型抢占机制要求我们同时优化公平接入和AoI，以实现及时、相关数据传输。为此，我们提出了一种车联网联合优化框架，定义了公平性指标，并采用随机混合系统（SHS）在抢占机制下建模AoI。通过自适应调整模式2中半持续调度（SPS）的选择窗口，我们解决了公平性和AoI的优化问题。我们采用基于大型语言模型（LLM）的多目标分解进化算法（MOEA/D）来求解该问题。仿真结果表明，我们的方案在平衡公平接入和最小化AoI方面具有显著效果。

> In this paper, we consider the fair access problem and the Age of Information (AoI) under 5G New Radio (NR) Vehicle-to-Infrastructure (V2I) Mode 2 in vehicular networks. Specifically, vehicles follow Mode 2 to communicate with Roadside Units (RSUs) to obtain accurate data for driving assistance.Nevertheless, vehicles often have different velocity when they are moving in adjacent lanes, leading to difference in RSU dwelltime and communication duration. This results in unfair access to network resources, potentially influencing driving safety. To ensure the freshness of received data, the AoI should be analyzed. Mode 2 introduces a novel preemption mechanism, necessitating simultaneous optimization of fair access and AoI to guarantee timely and relevant data delivery. We propose a joint optimization framework for vehicular network, defining a fairness index and employing Stochastic Hybrid Systems (SHS) to model AoI under preemption mechanism. By adaptively adjusting the selection window of Semi-Persistent Scheduling (SPS) in Mode 2, we address the optimization of fairness and AoI. We apply a large language model (LLM)-Based Multi-objective Evolutionary Algorithm Based on Decomposition (MOEA/D) to solve this problem. Simulation results demonstrate the effectiveness of our scheme in balancing fair access and minimizing AoI.

[Arxiv](https://arxiv.org/abs/2507.18328)