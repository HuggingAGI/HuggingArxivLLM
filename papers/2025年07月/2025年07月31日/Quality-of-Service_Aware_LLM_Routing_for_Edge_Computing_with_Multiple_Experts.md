# 服务质量感知的多专家边缘计算大型语言模型路由方案。

发布时间：2025年07月31日

`LLM应用

理由：这篇论文探讨了在边缘计算环境中优化大型语言模型（LLMs）服务的路由问题，属于实际应用层面的优化和部署，因此归类为LLM应用。` `边缘计算` `移动物联网`

> Quality-of-Service Aware LLM Routing for Edge Computing with Multiple Experts

# 摘要

> 大型语言模型（LLMs）的卓越能力引发了用户对其服务的强烈需求。然而，基于云的LLM服务常受高延迟、响应不稳定及隐私问题困扰。因此，为满足众多新兴智能移动和物联网应用需求，通常会在网络边缘部署多个LLMs，以提升实时响应并保护数据隐私。鉴于LLM服务的响应质量和延迟差异显著，如何将移动和物联网设备的用户请求路由至合适的LLM服务（即边缘LLM专家），以确保可接受的服务质量（QoS），成为一个关键问题。现有路由算法难以同时解决LLM服务的异构性、请求间的相互干扰以及维持长期稳定QoS所需的动态工作负载问题。为应对这些挑战，本文提出了一种基于深度强化学习（DRL）的QoS感知LLM路由框架，以实现持续的高质量LLM服务。针对全局状态的动态特性，我们提出了一种动态状态抽象技术，利用异构图注意力网络（HAN）紧凑地表示全局状态特征。此外，我们引入了动作影响估计器和定制奖励函数，以引导DRL代理最大化QoS并防止延迟违规。实验结果表明，与现有基线相比，我们的算法在平均QoS和计算资源效率方面均有显著提升。

> Large Language Models (LLMs) have demonstrated remarkable capabilities, leading to a significant increase in user demand for LLM services. However, cloud-based LLM services often suffer from high latency, unstable responsiveness, and privacy concerns. Therefore, multiple LLMs are usually deployed at the network edge to boost real-time responsiveness and protect data privacy, particularly for many emerging smart mobile and IoT applications. Given the varying response quality and latency of LLM services, a critical issue is how to route user requests from mobile and IoT devices to an appropriate LLM service (i.e., edge LLM expert) to ensure acceptable quality-of-service (QoS). Existing routing algorithms fail to simultaneously address the heterogeneity of LLM services, the interference among requests, and the dynamic workloads necessary for maintaining long-term stable QoS. To meet these challenges, in this paper we propose a novel deep reinforcement learning (DRL)-based QoS-aware LLM routing framework for sustained high-quality LLM services. Due to the dynamic nature of the global state, we propose a dynamic state abstraction technique to compactly represent global state features with a heterogeneous graph attention network (HAN). Additionally, we introduce an action impact estimator and a tailored reward function to guide the DRL agent in maximizing QoS and preventing latency violations. Extensive experiments on both Poisson and real-world workloads demonstrate that our proposed algorithm significantly improves average QoS and computing resource efficiency compared to existing baselines.

[Arxiv](https://arxiv.org/abs/2508.00234)