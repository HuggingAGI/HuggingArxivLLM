# DRR-MDPF：命名数据网络（NDN）中基于动态资源分配与马尔可夫决策过程的队列管理策略

发布时间：2025年08月27日

`强化学习` `基础理论`

> DRR-MDPF: A Queue Management Strategy Based on Dynamic Resource Allocation and Markov Decision Process in Named Data Networking (NDN)

# 摘要

> 命名数据网络（NDN）是网络架构的一次变革性突破，它以内容名称而非主机地址为核心，旨在提升数据传播效率。高效的队列与资源管理是NDN性能的关键，尤其在动态高流量环境中。本文提出新型混合策略DRR-MDPF，将马尔可夫决策过程转发（MDPF）模型与赤字轮询（DRR）算法相融合。MDPF使路由器能基于带宽、延迟及未满足Interest数量等关键指标，智能预测最优转发决策；DRR则确保竞争数据流间的公平与自适应带宽分配。该方法将每个路由器建模为学习智能体，通过持续反馈与概率更新动态调整策略。基于ndnSIM的仿真结果显示，DRR-MDPF在吞吐量、Interest满意度（ISR）、丢包率、内容检索时间及负载均衡等多项指标上，均显著优于SAF、RFA、SMDPF和LA-MDPF等现有先进策略。值得关注的是，DRR-MDPF在缓存有限和高流量场景下仍能保持稳健性，其单路径路由设计不仅提升了适应性，还降低了计算复杂度。此外，其多指标决策机制能实现更精准的接口选择，进而优化整体网络性能。综上，DRR-MDPF为NDN提供了一种智能、自适应且可扩展的队列管理方案，能有效应对动态网络环境中资源分配、拥塞控制和路由优化等核心挑战。

> Named Data Networking (NDN) represents a transformative shift in network architecture, prioritizing content names over host addresses to enhance data dissemination. Efficient queue and resource management are critical to NDN performance, especially under dynamic and high-traffic conditions. This paper introduces DRR-MDPF, a novel hybrid strategy that integrates the Markov Decision Process Forwarding (MDPF) model with the Deficit Round Robin (DRR) algorithm. MDPF enables routers to intelligently predict optimal forwarding decisions based on key metrics such as bandwidth, delay, and the number of unsatisfied Interests, while DRR ensures fair and adaptive bandwidth allocation among competing data flows. The proposed method models each router as a learning agent capable of adjusting its strategies through continuous feedback and probabilistic updates. Simulation results using ndnSIM demonstrate that DRR-MDPF significantly outperforms state-of-the-art strategies including SAF, RFA, SMDPF, and LA-MDPF across various metrics such as throughput, Interest Satisfaction Rate (ISR), packet drop rate, content retrieval time, and load balancing. Notably, DRR-MDPF maintains robustness under limited cache sizes and heavy traffic, offering enhanced adaptability and lower computational complexity due to its single-path routing design. Furthermore, its multi-metric decision-making capability enables more accurate interface selection, leading to optimized network performance. Overall, DRR-MDPF serves as an intelligent, adaptive, and scalable queue management solution for NDN, effectively addressing core challenges such as resource allocation, congestion control, and route optimization in dynamic networking environments.

[Arxiv](https://arxiv.org/abs/2508.20272)