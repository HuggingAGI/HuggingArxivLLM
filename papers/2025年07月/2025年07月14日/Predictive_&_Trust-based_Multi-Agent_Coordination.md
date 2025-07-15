# 预测与基于信任的多智能体协调

发布时间：2025年07月14日

`Agent` `人工智能` `分布式系统`

> Predictive & Trust-based Multi-Agent Coordination

# 摘要

> 本文提出了一种基于信任的预测多智能体共识协议，通过分析邻居的预期数据来实现协调决策。网络中的智能体会通过有限的预测时间窗口，与邻居共享未来预测数据，并以滚动时间窗的方式持续更新预测结果。智能体利用这些预测数据，学习邻居随时间展现出的信任和承诺特征。该协议被命名为预期分布式协调（ADC）协议。本文还提供了基于Lyapunov理论的共识收敛性证明，并通过数值模拟进行了验证。

> This paper presents a trust-based predictive multi-agent consensus protocol that analyses neighbours' anticipation data and makes coordination decisions. Agents in the network share their future predicted data over a finite look-ahead horizon with their neighbours and update their predictions in a rolling-horizon fashion. The prediction data is then used by agents to learn both the trust and the commitment traits exhibited by their neighbours over time. The proposed protocol is named as the Anticipatory Distributed Coordination (ADC) protocol. Lyapunov theory-based agreement convergence between agents is provided, followed by demonstrations using numerical simulations.

[Arxiv](https://arxiv.org/abs/2507.09997)