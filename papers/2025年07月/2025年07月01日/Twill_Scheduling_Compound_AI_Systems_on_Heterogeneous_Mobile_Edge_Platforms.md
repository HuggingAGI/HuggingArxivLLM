# Twill：复合AI系统在异构移动边缘平台上的调度管理

发布时间：2025年07月01日

`LLM应用` `移动边缘计算` `AI推理`

> Twill: Scheduling Compound AI Systems on Heterogeneous Mobile Edge Platforms

# 摘要

> 多模型AI系统（cAI）通过串联多个AI模型来解决复杂问题。这些系统通常由深度神经网络（DNN）、Transformer和大型语言模型（LLM）组成，展现出高度的计算多样性与动态负载变化。将cAI服务部署在移动边缘平台上，面临巨大挑战：如何调度并行的DNN-Transformer推理任务，这些任务以未知序列动态到达。现有移动边缘AI推理策略仅能处理多DNN或仅Transformer的任务负载，依赖设计时的性能分析，无法应对cAI系统所需的DNN与Transformer并发推理需求。本研究致力于解决在异构移动边缘平台上调度cAI系统的难题。我们提出了Twill，一个运行时框架，通过任务亲和力感知的集群映射与迁移、优先级感知的任务冻结/解冻，以及动态电压频率调节（DVFS），在满足功耗预算的前提下，尽可能降低推理延迟。我们在Nvidia Jetson Orin NX平台上实现了并部署了Twill框架。通过对比实验，Twill在当代DNN和LLM上相较于现有前沿边缘AI推理技术，平均将推理延迟降低了54%，同时严格遵守功耗预算。


> Compound AI (cAI) systems chain multiple AI models to solve complex problems. cAI systems are typically composed of deep neural networks (DNNs), transformers, and large language models (LLMs), exhibiting a high degree of computational diversity and dynamic workload variation. Deploying cAI services on mobile edge platforms poses a significant challenge in scheduling concurrent DNN-transformer inference tasks, which arrive dynamically in an unknown sequence. Existing mobile edge AI inference strategies manage multi-DNN or transformer-only workloads, relying on design-time profiling, and cannot handle concurrent inference of DNNs and transformers required by cAI systems. In this work, we address the challenge of scheduling cAI systems on heterogeneous mobile edge platforms. We present Twill, a run-time framework to handle concurrent inference requests of cAI workloads through task affinity-aware cluster mapping and migration, priority-aware task freezing/unfreezing, and DVFS, while minimizing inference latency within power budgets. We implement and deploy our Twill framework on the Nvidia Jetson Orin NX platform. We evaluate Twill against state-of-the-art edge AI inference techniques over contemporary DNNs and LLMs, reducing inference latency by 54% on average, while honoring power budgets.

[Arxiv](https://arxiv.org/abs/2507.00491)