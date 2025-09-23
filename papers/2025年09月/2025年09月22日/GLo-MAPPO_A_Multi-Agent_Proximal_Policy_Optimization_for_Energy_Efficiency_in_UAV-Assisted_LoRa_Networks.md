# GLo-MAPPO：面向无人机辅助LoRa网络能效的多智能体近邻策略优化

发布时间：2025年09月22日

`强化学习` `工业与制造`

> GLo-MAPPO: A Multi-Agent Proximal Policy Optimization for Energy Efficiency in UAV-Assisted LoRa Networks

# 摘要

> 基于远距离（LoRa）的低功耗广域网（LPWANs）凭借远距离、低功耗、低成本的优势，在5G/6G生态中对下一代物联网（NG-IoT）应用的实现至关重要。但此类网络的高能效实现仍是一大挑战，尤其在大规模或动态变化环境下。传统地面LoRa部署常受覆盖空白和非视距（NLoS）传播损耗困扰，卫星物联网方案则能耗过高且延迟较大，这限制了它们在能量受限和延迟敏感应用中的实用性。为解决这些问题，我们提出一种新型架构：利用多架无人机（UAVs）作为飞行LoRa网关，动态采集地面LoRa终端设备的数据。我们的方法通过联合优化扩频因子、传输功率、无人机轨迹及终端设备关联，实现系统加权全局能效的最大化。此外，我们将这一复杂优化问题建模为部分可观测马尔可夫决策过程（POMDP），并提出绿色LoRa多智能体近端策略优化（GLo-MAPPO）——一种基于集中训练与分散执行（CTDE）的多智能体强化学习（MARL）框架。仿真结果显示，GLo-MAPPO性能显著优于基准算法，在终端设备数量为10、20、30、40和50个的网络中，能效分别提升71.25%、18.56%、67.00%、59.73%和49.95%。

> Long Range (LoRa) based low-power wide area networks (LPWANs) are crucial for enabling next-generation IoT (NG-IoT) applications in 5G/6G ecosystems due to their long-range, low-power, and low-cost characteristics. However, achieving high energy efficiency in such networks remains a critical challenge, particularly in large-scale or dynamically changing environments. Traditional terrestrial LoRa deployments often suffer from coverage gaps and non-line-of-sight (NLoS) propagation losses, while satellite-based IoT solutions consume excessive energy and introduce high latency, limiting their suitability for energy-constrained and delay-sensitive applications. To address these limitations, we propose a novel architecture using multiple unmanned aerial vehicles (UAVs) as flying LoRa gateways to dynamically collect data from ground-based LoRa end devices. Our approach aims to maximize the system's weighted global energy efficiency by jointly optimizing spreading factors, transmission powers, UAV trajectories, and end-device associations. Additionally, we formulate this complex optimization problem as a partially observable Markov decision process (POMDP) and propose green LoRa multi-agent proximal policy optimization (GLo-MAPPO), a multi-agent reinforcement learning (MARL) framework based on centralized training with decentralized execution (CTDE). Simulation results show that GLo-MAPPO significantly outperforms benchmark algorithms, achieving energy efficiency improvements of 71.25%, 18.56%, 67.00%, 59.73%, and 49.95% for networks with 10, 20, 30, 40, and 50 LoRa end devices, respectively.

[Arxiv](https://arxiv.org/abs/2509.17676)