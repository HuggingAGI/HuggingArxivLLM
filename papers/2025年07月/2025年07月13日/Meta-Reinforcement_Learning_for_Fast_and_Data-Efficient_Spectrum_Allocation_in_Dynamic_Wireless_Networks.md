# # 用于动态无线网络中快速且数据高效的频谱分配的元强化学习

发布时间：2025年07月13日

`Agent` `无线网络` `网络资源管理`

> Meta-Reinforcement Learning for Fast and Data-Efficient Spectrum Allocation in Dynamic Wireless Networks

# 摘要

> 5G/6G网络中的频谱动态分配对资源利用效率至关重要。然而，传统的深度强化学习（DRL）方法在频谱分配中面临两大难题：一是其巨大的采样复杂度，二是无指导探索带来的安全风险，可能导致严重的网络干扰。为了解决这些挑战，我们提出了一种元学习框架，使智能体能够学习到健壮的初始策略，并在仅需少量数据的情况下快速适应新的无线场景。我们实现了三种元学习架构，包括模型不可知元学习（MAML）、循环神经网络（RNN）和注意力增强型RNN，并在模拟的动态接入/回传（IAB）环境中，将其与非元学习的DRL算法——近端策略优化（PPO）基准进行了对比评估。实验结果表明，基于注意力的元学习智能体达到了峰值平均网络吞吐量48 Mbps，而PPO基准算法则大幅下降至10 Mbps。此外，与PPO相比，我们的方法将SINR和时延违规减少了50%以上。它还展示了快速适应能力，公平性指数为0.7，表明更好的资源分配效果。这项研究证明，元学习是复杂无线系统智能控制中非常有效且安全的选择。


> The dynamic allocation of spectrum in 5G / 6G networks is critical to efficient resource utilization. However, applying traditional deep reinforcement learning (DRL) is often infeasible due to its immense sample complexity and the safety risks associated with unguided exploration, which can cause severe network interference. To address these challenges, we propose a meta-learning framework that enables agents to learn a robust initial policy and rapidly adapt to new wireless scenarios with minimal data. We implement three meta-learning architectures, model-agnostic meta-learning (MAML), recurrent neural network (RNN), and an attention-enhanced RNN, and evaluate them against a non-meta-learning DRL algorithm, proximal policy optimization (PPO) baseline, in a simulated dynamic integrated access/backhaul (IAB) environment. Our results show a clear performance gap. The attention-based meta-learning agent reaches a peak mean network throughput of 48 Mbps, while the PPO baseline decreased drastically to 10 Mbps. Furthermore, our method reduces SINR and latency violations by more than 50% compared to PPO. It also shows quick adaptation, with a fairness index 0.7, showing better resource allocation. This work proves that meta-learning is a very effective and safer option for intelligent control in complex wireless systems.

[Arxiv](https://arxiv.org/abs/2507.10619)