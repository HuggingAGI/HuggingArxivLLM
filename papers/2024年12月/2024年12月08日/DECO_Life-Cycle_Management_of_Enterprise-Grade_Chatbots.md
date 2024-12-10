# DECO：企业级聊天机器人的全生命周期管理

发布时间：2024年12月08日

`RAG` `软件工程` `企业管理`

> DECO: Life-Cycle Management of Enterprise-Grade Chatbots

# 摘要

> 软件工程师常常为获取各式各样的文档和遥测数据而烦恼，像故障排除指南（TSGs）、事件报告、代码库，还有多个利益相关方开发的各种内部工具。值班任务在所难免，可由于遗留资源模糊不清，加上严格的时间限制带来的压力，事件解决变得难上加难。为提升值班工程师（OCEs）的效率，优化他们的日常工作流程，我们推出了 DECO——一个用于开发、部署和管理企业级聊天机器人的综合性框架，旨在提高工程日常工作的生产力。本文详述了 DECO 框架的设计与实现，着重介绍了其创新的 NL2SearchQuery 功能和分层规划器。这些特性支持高效且定制化的检索增强生成（RAG）算法，不但能从各种来源提取相关信息，还能依据用户的查询选择最相关的工具包。这有助于解决复杂的技术问题，并实现对内部资源的无缝、自动化访问。另外，DECO 还具备强大的机制，能将非结构化的事件日志转化为用户友好的结构化指南，有效地填补了文档的空白。用户的反馈凸显了 DECO 在简化复杂工程任务、加快事件解决速度以及增强组织生产力方面的关键作用。自 2023 年 9 月推出以来，DECO 通过广泛的参与展现出了有效性，公司内多个组织的数百名活跃用户产生了数万次的交互。

> Software engineers frequently grapple with the challenge of accessing disparate documentation and telemetry data, including Troubleshooting Guides (TSGs), incident reports, code repositories, and various internal tools developed by multiple stakeholders. While on-call duties are inevitable, incident resolution becomes even more daunting due to the obscurity of legacy sources and the pressures of strict time constraints. To enhance the efficiency of on-call engineers (OCEs) and streamline their daily workflows, we introduced DECO -- a comprehensive framework for developing, deploying, and managing enterprise-grade chatbots tailored to improve productivity in engineering routines. This paper details the design and implementation of the DECO framework, emphasizing its innovative NL2SearchQuery functionality and a hierarchical planner. These features support efficient and customized retrieval-augmented-generation (RAG) algorithms that not only extract relevant information from diverse sources but also select the most pertinent toolkits in response to user queries. This enables the addressing of complex technical questions and provides seamless, automated access to internal resources. Additionally, DECO incorporates a robust mechanism for converting unstructured incident logs into user-friendly, structured guides, effectively bridging the documentation gap. Feedback from users underscores DECO's pivotal role in simplifying complex engineering tasks, accelerating incident resolution, and bolstering organizational productivity. Since its launch in September 2023, DECO has demonstrated its effectiveness through extensive engagement, with tens of thousands of interactions from hundreds of active users across multiple organizations within the company.

[Arxiv](https://arxiv.org/abs/2412.06099)