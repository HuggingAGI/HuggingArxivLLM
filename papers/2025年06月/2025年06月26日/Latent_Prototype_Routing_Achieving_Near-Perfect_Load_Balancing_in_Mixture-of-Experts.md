# 潜在原型路由：专家混合模型中的近乎完美负载均衡实现

发布时间：2025年06月26日

`LLM理论

论文摘要讨论了专家混合架构（MoE）在大型语言模型（LLMs）中的应用，并提出了一种新的路由框架LPR来解决负载不平衡问题。这属于模型架构和训练策略的优化，因此归类为LLM理论。` `人工智能` `模型优化`

> Latent Prototype Routing: Achieving Near-Perfect Load Balancing in Mixture-of-Experts

# 摘要

> 专家混合架构（Mixture-of-Experts, MoE）已成为高效扩展大型语言模型（LLMs）的关键策略。然而，当前的MoE系统面临严重的负载不平衡问题，仅有一小部分专家在训练和推理过程中持续被激活，导致模型容量和计算资源的严重利用率低下。本研究从聚类角度重新审视专家路由机制，提出了一种名为潜在原型路由（Latent Prototype Routing, LPR）的新型路由框架。LPR不仅能够推广现有方法，还能在不损害下游性能的前提下促进专家的均衡利用。通过对DeepSeek-V3、Qwen3-MoE和Mixtral等多个开源MoE模型的广泛实验，结果表明LPR将专家负载的基尼系数从0.70降至平均0.035，将最小-最大专家负载比从1e-6提升至0.70，实现了近乎完美的负载均衡。

> Mixture-of-Experts (MoE) architectures have emerged as a key strategy for scaling large language models (LLMs) efficiently. However, current MoE systems suffer from severe load imbalance, where only a small subset of experts is consistently activated during training and inference, leading to significant underutilization of model capacity and computational resources. In this work, we revisit expert routing through a clustering perspective and propose Latent Prototype Routing (LPR), a novel routing framework that generalizes existing approaches while promoting balanced expert utilization without compromising downstream performance. Extensive experiments across multiple open-source MoE models -- including DeepSeek-V3, Qwen3-MoE, and Mixtral -- demonstrate that LPR reduces the Gini coefficient of expert load from 0.70 to 0.035 on average, improves the min-max expert load ratio from 1e-6 to 0.70, achieving near-perfect load balancing.

[Arxiv](https://arxiv.org/abs/2506.21328)