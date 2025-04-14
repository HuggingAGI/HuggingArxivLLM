# # TickIt: 利用大型语言模型实现工单自动化升级

发布时间：2025年04月11日

`LLM应用` `云服务` `客户服务`

> TickIt: Leveraging Large Language Models for Automated Ticket Escalation

# 摘要

> 在大规模云服务系统中，支持票证是解决客户问题和维护服务质量的关键机制。然而，传统的手动票证升级流程面临重大挑战，包括低效、不准确以及难以处理大量复杂票证。尽管先前的研究提出了多种用于票证分类的机器学习模型，但这些方法往往忽视了现实世界升级的实际需求，如动态票证更新、特定主题路由以及票证关系分析。为了解决这一差距，本文引入了 TickIt，一个基于大型语言模型的创新在线票证升级框架。TickIt 通过持续更新票证状态、将票证分配给最合适的支持团队、探索票证相关性以及利用类别指导的监督微调来不断提升性能，从而实现主题感知、动态和关系驱动的票证升级。通过在字节跳动的云服务平台火山引擎中部署 TickIt，我们验证了其有效性和实用性，标志着在大规模云服务系统自动票证升级领域取得了重要进展。

> In large-scale cloud service systems, support tickets serve as a critical mechanism for resolving customer issues and maintaining service quality. However, traditional manual ticket escalation processes encounter significant challenges, including inefficiency, inaccuracy, and difficulty in handling the high volume and complexity of tickets. While previous research has proposed various machine learning models for ticket classification, these approaches often overlook the practical demands of real-world escalations, such as dynamic ticket updates, topic-specific routing, and the analysis of ticket relationships. To bridge this gap, this paper introduces TickIt, an innovative online ticket escalation framework powered by Large Language Models. TickIt enables topic-aware, dynamic, and relationship-driven ticket escalations by continuously updating ticket states, assigning tickets to the most appropriate support teams, exploring ticket correlations, and leveraging category-guided supervised fine-tuning to continuously improve its performance. By deploying TickIt in ByteDance's cloud service platform Volcano Engine, we validate its efficacy and practicality, marking a significant advancement in the field of automated ticket escalation for large-scale cloud service systems.

[Arxiv](https://arxiv.org/abs/2504.08475)