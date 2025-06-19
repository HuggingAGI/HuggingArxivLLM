# # 摘要
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年06月16日

`LLM应用` `系统与服务优化`

> Efficient Serving of LLM Applications with Probabilistic Demand Modeling

# 摘要

> 基于大型语言模型（LLMs）的应用程序通过一系列任务解决现实世界问题，这些任务对多样化后端有动态需求。现有服务系统将LLM应用的资源需求视为黑箱，导致端到端效率低下。我们发现，LLM应用的资源需求可通过概率需求图（PDGraph）进行准确建模。为此，我们提出了Hermes，利用PDGraph实现LLM应用的高效服务。面对概率需求，Hermes采用Gittins策略确定最优调度顺序，以最小化平均完成时间。同时，Hermes通过PDGraph模型在合适时机预热冷后端。实验结果表明，Hermes显著提升了应用服务效率，平均完成时间减少70%以上，P95完成时间减少80%以上。

> Applications based on Large Language Models (LLMs) contains a series of tasks to address real-world problems with boosted capability, which have dynamic demand volumes on diverse backends. Existing serving systems treat the resource demands of LLM applications as a blackbox, compromising end-to-end efficiency due to improper queuing order and backend warm up latency. We find that the resource demands of LLM applications can be modeled in a general and accurate manner with Probabilistic Demand Graph (PDGraph). We then propose Hermes, which leverages PDGraph for efficient serving of LLM applications. Confronting probabilistic demand description, Hermes applies the Gittins policy to determine the scheduling order that can minimize the average application completion time. It also uses the PDGraph model to help prewarm cold backends at proper moments. Experiments with diverse LLM applications confirm that Hermes can effectively improve the application serving efficiency, reducing the average completion time by over 70% and the P95 completion time by over 80%.

[Arxiv](https://arxiv.org/abs/2506.14851)