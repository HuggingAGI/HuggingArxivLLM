# 本研究致力于探究基于大型语言模型（LLM）的智能体在根因分析任务中的应用与潜力。

发布时间：2024年03月06日

`Agent`

> Exploring LLM-based Agents for Root Cause Analysis

# 摘要

> 随着云软件系统复杂性的增长，事件管理已成为软件开发流程中必不可少的一环。其中，根本原因分析（RCA）是事件管理过程中至关重要的一环，却也是值班工程师面临的一项挑战，需深厚的专业背景和对团队特有服务的广泛了解。为缓解压力并节约时间，RCA的自动化显得尤为关键。近期，有研究者采用大型语言模型（LLMs）执行RCA，并取得初步成效。然而，现有方法受限于无法实时获取如事件相关日志、度量数据或数据库等附加诊断信息，极大地制约了其根因定位能力。本研究着眼于利用LLM驱动的智能代理改善这一问题，通过在微软采集的真实生产事件离群数据集上，对配备了检索工具的ReAct代理进行全面深入的实证评估。结果显示，ReAct代理在与强大检索和推理基准的较量中表现强劲，同时大幅提升了事实准确率。为进一步探索改进空间，我们尝试将与事件报告相关的讨论内容作为模型额外输入，然而意外的是，此举并未明显提升性能。最后，我们携手微软某团队开展了一项案例研究，赋予ReAct代理调用团队用于人工RCA的外部诊断服务的能力。实验结果揭示了智能代理如何突破以往研究瓶颈，并提出了实际应用中实施此类系统的实用考量。

> The growing complexity of cloud based software systems has resulted in incident management becoming an integral part of the software development lifecycle. Root cause analysis (RCA), a critical part of the incident management process, is a demanding task for on-call engineers, requiring deep domain knowledge and extensive experience with a team's specific services. Automation of RCA can result in significant savings of time, and ease the burden of incident management on on-call engineers. Recently, researchers have utilized Large Language Models (LLMs) to perform RCA, and have demonstrated promising results. However, these approaches are not able to dynamically collect additional diagnostic information such as incident related logs, metrics or databases, severely restricting their ability to diagnose root causes. In this work, we explore the use of LLM based agents for RCA to address this limitation. We present a thorough empirical evaluation of a ReAct agent equipped with retrieval tools, on an out-of-distribution dataset of production incidents collected at Microsoft. Results show that ReAct performs competitively with strong retrieval and reasoning baselines, but with highly increased factual accuracy. We then extend this evaluation by incorporating discussions associated with incident reports as additional inputs for the models, which surprisingly does not yield significant performance improvements. Lastly, we conduct a case study with a team at Microsoft to equip the ReAct agent with tools that give it access to external diagnostic services that are used by the team for manual RCA. Our results show how agents can overcome the limitations of prior work, and practical considerations for implementing such a system in practice.

[Arxiv](https://arxiv.org/abs/2403.04123)