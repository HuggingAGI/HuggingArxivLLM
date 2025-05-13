# 基于双向长短期记忆网络的多智能体深度强化学习与车辆嵌入式AI网络中智能体双子迁移的计算感知剪枝方法

发布时间：2025年05月09日

`Agent` `智能交通系统` `自动驾驶`

> Bi-LSTM based Multi-Agent DRL with Computation-aware Pruning for Agent Twins Migration in Vehicular Embodied AI Networks

# 摘要

> 大型语言模型与具身人工智能（AI）在智能交通领域的进步催生了车辆具身AI网络（VEANs）。在VEANs中，自动驾驶汽车（AVs）作为智能体，通过本地AI应用实现环境感知与多智能体协作。为应对计算时延和资源限制，我们将这些本地AI应用迁移至车辆具身AI智能体副本，推动车辆具身AI网络向 roadside units (RSUs) 卸载密集任务，从而在保持服务质量的同时缓解时延问题。针对传统方法中 RSUs 工作负载不均衡的挑战，我们采用Stackelberg博弈建模AV-RSU交互，优化带宽资源分配以实现高效迁移。为此，我们设计了一种轻量化多智能体双向LSTM近端策略优化（TMABLPPO）算法，通过分散式协调近似Stackelberg均衡。此外，提出了一种基于路径排除（PX）的个性化神经网络剪枝算法，通过识别训练模型中的任务关键参数，动态适应异构AV的计算能力，从而在性能下降较小的情况下降低模型复杂度。实验结果证实了该算法在平衡系统负载和最小化延迟方面的有效性，充分展现了车辆具身AI智能体部署的显著改进。

> With the advancement of large language models and embodied Artificial Intelligence (AI) in the intelligent transportation scenarios, the combination of them in intelligent transportation spawns the Vehicular Embodied AI Network (VEANs). In VEANs, Autonomous Vehicles (AVs) are typical agents whose local advanced AI applications are defined as vehicular embodied AI agents, enabling capabilities such as environment perception and multi-agent collaboration. Due to computation latency and resource constraints, the local AI applications and services running on vehicular embodied AI agents need to be migrated, and subsequently referred to as vehicular embodied AI agent twins, which drive the advancement of vehicular embodied AI networks to offload intensive tasks to Roadside Units (RSUs), mitigating latency problems while maintaining service quality. Recognizing workload imbalance among RSUs in traditional approaches, we model AV-RSU interactions as a Stackelberg game to optimize bandwidth resource allocation for efficient migration. A Tiny Multi-Agent Bidirectional LSTM Proximal Policy Optimization (TMABLPPO) algorithm is designed to approximate the Stackelberg equilibrium through decentralized coordination. Furthermore, a personalized neural network pruning algorithm based on Path eXclusion (PX) dynamically adapts to heterogeneous AV computation capabilities by identifying task-critical parameters in trained models, reducing model complexity with less performance degradation. Experimental validation confirms the algorithm's effectiveness in balancing system load and minimizing delays, demonstrating significant improvements in vehicular embodied AI agent deployment.

[Arxiv](https://arxiv.org/abs/2505.06378)