# SCORPIO：精准服务异构SLO，实现大语言模型推理的高效请求处理

发布时间：2025年05月28日

`LLM应用` `服务系统` `计算机系统`

> SCORPIO: Serving the Right Requests at the Right Time for Heterogeneous SLOs in LLM Inference

# 摘要

> 现有的大语言模型 (LLM) 服务系统往往将最大吞吐量作为首要目标，却忽视了首次生成令牌时间 (TTFT) 和每输出令牌时间 (TPOT) 等关键服务级别目标 (SLO)，导致 SLO 达成效果不尽如人意。本文提出了一种面向 SLO 的 LLM 服务系统 SCORpio，旨在为具有异构 SLO 的工作负载同时优化系统吞吐量和 SLO 达成效果。我们的核心理念是通过利用 SLO 的异构性，在准入控制、队列管理和批选择等多个环节实现自适应调度。SCORpio 配备了 TTFT 保护机制，采用基于最短截止日期优先的重新排序策略并拒绝无法达成的请求，以及 TPOT 保护机制，利用基于 VBS 的准入控制和一种创新的基于信用的批处理机制。这两个保护机制都得到了一个预测模块的支持。实验结果表明，与最先进的基线相比，SCORpio 在系统吞吐量上实现了高达 14.4 倍的提升，并将 SLO 符合率提升了高达 46.5%。

> Existing Large Language Model (LLM) serving systems prioritize maximum throughput. They often neglect Service Level Objectives (SLOs) such as Time to First Token (TTFT) and Time Per Output Token (TPOT), which leads to suboptimal SLO attainment. This paper introduces SCORPIO, an SLO-oriented LLM serving system designed to maximize system goodput and SLO attainment for workloads with heterogeneous SLOs. Our core insight is to exploit SLO heterogeneity for adaptive scheduling across admission control, queue management, and batch selection. SCORPIO features a TTFT Guard, which employs least-deadline-first reordering and rejects unattainable requests, and a TPOT Guard, which utilizes a VBS-based admission control and a novel credit-based batching mechanism. Both guards are supported by a predictive module. Evaluations demonstrate that SCORPIO improves system goodput by up to 14.4X and SLO adherence by up to 46.5% compared to state-of-the-art baselines.

[Arxiv](https://arxiv.org/abs/2505.23022)