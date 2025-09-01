# # 个人健康智能体剖析

发布时间：2025年08月27日

`Agent` `医疗健康`

> The Anatomy of a Personal Health Agent

# 摘要

> 健康是人类福祉的基石，而大型语言模型（LLMs）的飞速发展正推动着新一代健康智能体的诞生。然而，在日常非临床场景中，健康智能体满足个人多样化需求的应用潜力尚未被充分挖掘。为此，本研究致力于构建一款综合型个人健康智能体，它能够对日常消费级健康设备及常见个人健康记录中的多模态数据进行分析推理，并提供个性化健康建议。

为弄清终端用户与这类助手交互时的真实需求，我们深入分析了网络搜索及健康论坛的查询内容，并通过用户中心设计流程收集了用户与健康专家的定性反馈。基于这些发现，我们划分出三类核心消费者健康需求，每类需求均由一个专业子智能体提供支持：（1）数据科学智能体，负责分析个人时间序列可穿戴设备数据及健康记录；（2）健康领域专家智能体，整合用户健康与情境数据，生成准确的个性化见解；（3）健康教练智能体，综合数据洞察，采用特定心理策略指导用户并追踪其进展。

在此基础上，我们提出并开发了个人健康智能体（PHA）——一个可通过动态、个性化交互满足个体健康需求的多智能体框架。为评估各子智能体及多智能体系统的性能，我们在10项基准任务中开展了自动与人工评估，其间健康专家与终端用户累计完成了7000余条注释，投入超1100小时工作量。本研究是迄今为止对健康智能体最全面的评估，为实现“人人享有个人健康智能体”这一未来愿景筑牢了基础。

> Health is a fundamental pillar of human wellness, and the rapid advancements in large language models (LLMs) have driven the development of a new generation of health agents. However, the application of health agents to fulfill the diverse needs of individuals in daily non-clinical settings is underexplored. In this work, we aim to build a comprehensive personal health agent that is able to reason about multimodal data from everyday consumer wellness devices and common personal health records, and provide personalized health recommendations. To understand end-users' needs when interacting with such an assistant, we conducted an in-depth analysis of web search and health forum queries, alongside qualitative insights from users and health experts gathered through a user-centered design process. Based on these findings, we identified three major categories of consumer health needs, each of which is supported by a specialist sub-agent: (1) a data science agent that analyzes personal time-series wearable and health record data, (2) a health domain expert agent that integrates users' health and contextual data to generate accurate, personalized insights, and (3) a health coach agent that synthesizes data insights, guiding users using a specified psychological strategy and tracking users' progress. Furthermore, we propose and develop the Personal Health Agent (PHA), a multi-agent framework that enables dynamic, personalized interactions to address individual health needs. To evaluate each sub-agent and the multi-agent system, we conducted automated and human evaluations across 10 benchmark tasks, involving more than 7,000 annotations and 1,100 hours of effort from health experts and end-users. Our work represents the most comprehensive evaluation of a health agent to date and establishes a strong foundation towards the futuristic vision of a personal health agent accessible to everyone.

[Arxiv](https://arxiv.org/abs/2508.20148)