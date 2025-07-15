# EAT: 基于注意力引导扩散强化学习的边缘计算协作生成式AI任务调度方法，兼顾服务质量感知

发布时间：2025年07月14日

`其他` `边缘计算` `云数据中心`

> EAT: QoS-Aware Edge-Collaborative AIGC Task Scheduling via Attention-Guided Diffusion Reinforcement Learning

# 摘要

> 人工智能 (AI) 和大型语言模型的快速发展推动了生成式 AI (GenAI) 在云数据中心的广泛应用，支持多样化的 AI 生成内容 (AIGC) 任务。然而，像 Stable Diffusion 这样的模型不可避免地引入了延迟和显著的资源开销，这对网络边缘高 QoS 要求的用户来说并不适用。虽然将 AIGC 服务部署在边缘服务器上可以减少传输时间，但却常常导致资源利用率低下，并未能在推理延迟和质量之间实现最优平衡。

为了解决这些问题，本文提出了一种基于 QoS 的边缘协作 AIGC 任务调度 (EAT) 算法。具体来说：
1) 我们将 AIGC 任务进行分割，并将任务块分配到不同的边缘服务器上，将其建模为一个兼顾推理延迟和质量的并行调度问题，同时考虑服务器异构性，例如模型分布差异和冷启动问题。
2) 我们提出了基于强化学习的 EAT 算法，该算法通过注意力层从边缘服务器提取负载和任务队列信息，并采用基于扩散的策略网络进行调度，从而高效实现模型复用。
3) 我们开发了一个 AIGC 任务调度系统，利用我们的 EAT 算法将任务分割并分配到多个边缘服务器进行处理。

基于我们的系统和大规模仿真实验的结果表明，与基线方法相比，我们的 EAT 算法可以将推理延迟降低高达 56%。我们的开源代码已发布在 https://github.com/zzf1955/EAT。


> The growth of Artificial Intelligence (AI) and large language models has enabled the use of Generative AI (GenAI) in cloud data centers for diverse AI-Generated Content (AIGC) tasks. Models like Stable Diffusion introduce unavoidable delays and substantial resource overhead, which are unsuitable for users at the network edge with high QoS demands. Deploying AIGC services on edge servers reduces transmission times but often leads to underutilized resources and fails to optimally balance inference latency and quality. To address these issues, this paper introduces a QoS-aware underline{E}dge-collaborative underline{A}IGC underline{T}ask scheduling (EAT) algorithm. Specifically: 1) We segment AIGC tasks and schedule patches to various edge servers, formulating it as a gang scheduling problem that balances inference latency and quality while considering server heterogeneity, such as differing model distributions and cold start issues. 2) We propose a reinforcement learning-based EAT algorithm that uses an attention layer to extract load and task queue information from edge servers and employs a diffusion-based policy network for scheduling, efficiently enabling model reuse. 3) We develop an AIGC task scheduling system that uses our EAT algorithm to divide tasks and distribute them across multiple edge servers for processing. Experimental results based on our system and large-scale simulations show that our EAT algorithm can reduce inference latency by up to 56\% compared to baselines. We release our open-source code at https://github.com/zzf1955/EAT.

[Arxiv](https://arxiv.org/abs/2507.10026)