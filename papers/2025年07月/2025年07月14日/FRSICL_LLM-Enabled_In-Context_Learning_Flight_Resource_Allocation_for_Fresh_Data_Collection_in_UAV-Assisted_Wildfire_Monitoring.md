# # FRSICL系统：基于LLM的上下文学习在无人机辅助野火监测中的飞行资源分配
FRSICL系统通过结合大型语言模型（LLM）的上下文学习能力，实现高效的新鲜数据收集，特别适用于无人机辅助的野火监测场景。

发布时间：2025年07月14日

`LLM应用` `公共安全` `应急管理`

> FRSICL: LLM-Enabled In-Context Learning Flight Resource Allocation for Fresh Data Collection in UAV-Assisted Wildfire Monitoring

# 摘要

> 无人机（UAVs）在公共安全中发挥着重要作用，尤其是在野火监测领域，早期检测可显著降低环境损害。在无人机辅助野火监测（UAWM）系统中，传感器传输调度与速度的联合优化对于减少过时数据带来的信新度（AoI）至关重要。深度强化学习（DRL）曾被用于此类优化，但其采样效率低、仿真与现实差距大及训练复杂度高等局限性，使其难以适用于野火监测等时间敏感任务。本研究提出了一种基于LLM使能的上下文学习的在线飞行资源分配方案（FRSICL），该方案能够在无人机飞行轨迹上实时优化飞行控制与数据收集计划，从而逐步降低地面传感器的平均AoI。与DRL不同，FRSICL通过自然语言任务描述和环境反馈生成数据收集计划并控制无人机速度，无需大量重新训练即可实现动态决策。仿真结果表明，FRSICL相较于近端策略优化（PPO）和最近邻基线，展现出显著优势。

> Unmanned Aerial Vehicles (UAVs) are vital for public safety, particularly in wildfire monitoring, where early detection minimizes environmental impact. In UAV-Assisted Wildfire Monitoring (UAWM) systems, joint optimization of sensor transmission scheduling and velocity is critical for minimizing Age of Information (AoI) from stale sensor data. Deep Reinforcement Learning (DRL) has been used for such optimization; however, its limitations such as low sampling efficiency, simulation-to-reality gaps, and complex training render it unsuitable for time-critical applications like wildfire monitoring. This paper introduces a new online Flight Resource Allocation scheme based on LLM-Enabled In-Context Learning (FRSICL) to jointly optimize the UAV's flight control and data collection schedule along the trajectory in real time, thereby asymptotically minimizing the average AoI across ground sensors. In contrast to DRL, FRSICL generates data collection schedules and controls velocity using natural language task descriptions and feedback from the environment, enabling dynamic decision-making without extensive retraining. Simulation results confirm the effectiveness of the proposed FRSICL compared to Proximal Policy Optimization (PPO) and Nearest-Neighbor baselines.

[Arxiv](https://arxiv.org/abs/2507.10134)