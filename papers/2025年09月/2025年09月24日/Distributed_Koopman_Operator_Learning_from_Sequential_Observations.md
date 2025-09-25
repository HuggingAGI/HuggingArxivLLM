# 基于序列观测的分布式库普曼算子学习

发布时间：2025年09月24日

`Agent` `工业与制造`

> Distributed Koopman Operator Learning from Sequential Observations

# 摘要

> 本文提出一种分布式Koopman算子学习框架，通过多个智能体的序列观测对未知非线性动力学进行建模。每个智能体基于提升数据估计局部Koopman近似，并借助通信图协作，最终在一致的分布式近似上达成指数一致性。该方法支持在异步感知和资源受限的条件下实现分布式计算。仿真结果验证了其性能，在感知受限场景与通信有限的条件下，该框架的收敛性和预测精度均得到有效验证。

> This paper presents a distributed Koopman operator learning framework for modeling unknown nonlinear dynamics using sequential observations from multiple agents. Each agent estimates a local Koopman approximation based on lifted data and collaborates over a communication graph to reach exponential consensus on a consistent distributed approximation. The approach supports distributed computation under asynchronous and resource-constrained sensing. Its performance is demonstrated through simulation results, validating convergence and predictive accuracy under sensing-constrained scenarios and limited communication.

[Arxiv](https://arxiv.org/abs/2509.20071)