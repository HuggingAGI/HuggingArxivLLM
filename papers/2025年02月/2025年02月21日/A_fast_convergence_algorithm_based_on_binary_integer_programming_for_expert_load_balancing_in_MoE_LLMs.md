# 应用于MoE大语言模型的基于二进制整数规划的专家负载均衡快速收敛算法

发布时间：2025年02月21日

`LLM理论

论文摘要：MoE（专家混合）架构在大语言模型中应用广泛，近期专家数量甚至突破百位。然而，MoE模型预训练过程中，专家负载不平衡问题频发，可能导致路由崩溃或计算开销增加。为解决这一问题，我们提出了一种基于二进制整数规划（BIP）的负载平衡算法——BIP-Based Balancing。该算法通过维护一个额外的向量q，并借助极小计算开销的二进制整数规划求解，有效改变s的top-K顺序。仿真实验表明，BIP-Based Balancing能迅速缓解负载不平衡，同时常规评分总和仅轻微下降。从仿真视角来看，我们的算法在专家负载平衡与预训练效率之间实现了近乎完美的平衡。

LLM理论` `人工智能` `系统优化`

> A fast convergence algorithm based on binary integer programming for expert load balancing in MoE LLMs

# 摘要

> MoE（专家混合）架构在大语言模型中应用广泛，近期专家数量甚至突破百位。然而，MoE模型预训练过程中，专家负载不平衡问题频发，可能导致路由崩溃或计算开销增加。为解决这一问题，我们提出了一种基于二进制整数规划（BIP）的负载平衡算法——BIP-Based Balancing。该算法通过维护一个额外的向量q，并借助极小计算开销的二进制整数规划求解，有效改变s的top-K顺序。仿真实验表明，BIP-Based Balancing能迅速缓解负载不平衡，同时常规评分总和仅轻微下降。从仿真视角来看，我们的算法在专家负载平衡与预训练效率之间实现了近乎完美的平衡。

> MoE (Mixture-of-Expert) architectures appear frequently in large language models, and the number of experts can be over one hundred recently. However, the expert load imbalance problem always happens in MoE model pre-training, which will cause routing collapse or increased computational overhead. In order to balance loads on experts, we propose BIP-Based Balancing, an expert load balancing algorithm based on binary integer programming (BIP). The algorithm maintains an additional vector q that can help change the top-K order of s by solving a binary integer programming with very small time costs. In simulation experiments, we observe that BIP-Based Balancing make imbalance disappoint very fast, while the final sum of routine scores decreases very little. Our algorithm achieves nearly perfect trade-off between expert load balance and pre-training efficiency under the simulation view.

[Arxiv](https://arxiv.org/abs/2502.15451)