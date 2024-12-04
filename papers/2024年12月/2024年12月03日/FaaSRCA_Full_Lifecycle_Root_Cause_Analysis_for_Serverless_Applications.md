# FaaSRCA：针对无服务器应用的全生命周期根本原因分析

发布时间：2024年12月03日

`其他` `云服务` `无服务器计算`

> FaaSRCA: Full Lifecycle Root Cause Analysis for Serverless Applications

# 摘要

> 无服务器作为云原生服务的新型计算范式日益流行。然而，无服务器应用的复杂性和动态性给保障系统可用性及性能带来巨大挑战。微服务系统虽有众多根本原因分析（RCA）方法，但不适用于无服务器应用的精确建模。原因在于：（1）相较于微服务，无服务器应用具有高度动态性，生命周期短，仅产生瞬时脉冲状数据，缺少长期连续信息。（2）现有方法仅聚焦于分析运行阶段，忽略其他阶段，无法涵盖无服务器应用的整个生命周期。为应对这些局限，我们提出 FaaSRCA，这是一种针对无服务器应用的全生命周期根本原因分析方法。它利用全局调用图整合了平台和应用端生成的多模态可观测性数据。我们训练了基于图注意力网络（GAT）的图自动编码器，为全局调用图中的节点计算重建分数。依据这些分数，在无服务器函数的生命周期阶段粒度上确定根本原因。我们在两个无服务器基准上开展实验评估，结果显示 FaaSRCA 优于其他基线方法，top-k 精度提升幅度在 21.25%至 81.63%之间。

> Serverless becomes popular as a novel computing paradigms for cloud native services. However, the complexity and dynamic nature of serverless applications present significant challenges to ensure system availability and performance. There are many root cause analysis (RCA) methods for microservice systems, but they are not suitable for precise modeling serverless applications. This is because: (1) Compared to microservice, serverless applications exhibit a highly dynamic nature. They have short lifecycle and only generate instantaneous pulse-like data, lacking long-term continuous information. (2) Existing methods solely focus on analyzing the running stage and overlook other stages, failing to encompass the entire lifecycle of serverless applications. To address these limitations, we propose FaaSRCA, a full lifecycle root cause analysis method for serverless applications. It integrates multi-modal observability data generated from platform and application side by using Global Call Graph. We train a Graph Attention Network (GAT) based graph auto-encoder to compute reconstruction scores for the nodes in global call graph. Based on the scores, we determine the root cause at the granularity of the lifecycle stage of serverless functions. We conduct experimental evaluations on two serverless benchmarks, the results show that FaaSRCA outperforms other baseline methods with a top-k precision improvement ranging from 21.25% to 81.63%.

[Arxiv](https://arxiv.org/abs/2412.02239)