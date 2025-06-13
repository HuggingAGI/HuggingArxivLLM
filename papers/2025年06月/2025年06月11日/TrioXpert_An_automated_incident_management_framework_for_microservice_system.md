# TrioXpert：专为微服务系统打造的自动化事件管理框架

发布时间：2025年06月11日

`LLM应用` `微服务系统` `自动化事件管理`

> TrioXpert: An automated incident management framework for microservice system

# 摘要

> 自动化事件管理在大规模微服务系统中发挥着关键作用。然而，现有方法往往仅依赖单一模态数据（如指标、日志和追踪信息），难以同时处理异常检测（AD）、故障分类（FT）和根本原因定位（RCL）等多下游任务。此外，当前技术中缺乏清晰的推理依据，常导致可解释性不足。为解决这些局限，我们提出TrioXpert——一个能够充分利用多模态数据的端到端事件管理框架。TrioXpert基于不同模态数据的特性设计了三条独立的数据处理管道，从数值和文本两个维度全面刻画微服务系统的运行状态。它采用基于大型语言模型（LLMs）的协作推理机制，实现多任务同时处理，并提供清晰的推理依据，以确保强大的可解释性。我们在两个流行的微服务系统数据集上进行了广泛评估，实验结果表明，TrioXpert在AD任务中提升了4.7%至57.7%，FT任务中提升了2.1%至40.6%，RCL任务中提升了1.6%至163.1%，展现出卓越性能。


> Automated incident management plays a pivotal role in large-scale microservice systems. However, many existing methods rely solely on single-modal data (e.g., metrics, logs, and traces) and struggle to simultaneously address multiple downstream tasks, including anomaly detection (AD), failure triage (FT), and root cause localization (RCL). Moreover, the lack of clear reasoning evidence in current techniques often leads to insufficient interpretability. To address these limitations, we propose TrioXpert, an end-to-end incident management framework capable of fully leveraging multimodal data. TrioXpert designs three independent data processing pipelines based on the inherent characteristics of different modalities, comprehensively characterizing the operational status of microservice systems from both numerical and textual dimensions. It employs a collaborative reasoning mechanism using large language models (LLMs) to simultaneously handle multiple tasks while providing clear reasoning evidence to ensure strong interpretability. We conducted extensive evaluations on two popular microservice system datasets, and the experimental results demonstrate that TrioXpert achieves outstanding performance in AD (improving by 4.7% to 57.7%), FT (improving by 2.1% to 40.6%), and RCL (improving by 1.6% to 163.1%) tasks.

[Arxiv](https://arxiv.org/abs/2506.10043)