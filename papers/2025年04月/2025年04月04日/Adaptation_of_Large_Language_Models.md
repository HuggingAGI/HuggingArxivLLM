# # 大型语言模型的适配与调整

发布时间：2025年04月04日

`LLM应用`

> Adaptation of Large Language Models

# 摘要

> 本教程聚焦于LLM适应技术，旨在满足超越传统通用LLMs静态能力的需求。通用LLMs虽在多种任务中表现卓越，但在金融、医疗和欠发达语言代码生成等专业领域往往力不从心。其静态特性和庞大模型规模也限制了实际应用的灵活性和经济性。因此，自LLMs诞生以来，适应性问题就成为行业和学术界关注的核心。为解决这一问题，本教程将系统介绍LLM适应技术。首先，我们将从数据和模型两个维度全面解读LLM适应的基础概念。随后，我们将重点阐述评估指标和基准与其他技术的不同之处。在明确问题后，我们将深入探讨各类适应技术。我们将适应技术主要分为两大类：参数化知识迁移和半参数化知识迁移。参数化知识迁移专注于更新LLMs内部的参数化知识，而半参数化知识迁移则通过检索增强生成（RAG）和基于代理的系统等技术，优化LLM参数以更高效地整合外部知识或工具。此外，我们还将探讨实时适应技术，包括模型编辑，使LLMs能够在实际应用环境中实现动态更新。

> This tutorial on adaptation of LLMs is designed to address the growing demand for models that go beyond the static capabilities of generic LLMs by providing an overview of dynamic, domain-specific, and task-adaptive LLM adaptation techniques. While general LLMs have demonstrated strong generalization across a variety of tasks, they often struggle to perform well in specialized domains such as finance, healthcare, and code generation for underrepresented languages. Additionally, their static nature limits their ability to evolve with the changing world, and they are often extremely large in size, making them impractical and costly to deploy at scale. As a result, the adaptation of LLMs has drawn much attention since the birth of LLMs and is of core importance, both for industry, which focuses on serving its targeted users, and academia, which can greatly benefit from small but powerful LLMs. To address this gap, this tutorial aims to provide an overview of the LLM adaptation techniques. We start with an introduction to LLM adaptation, from both the data perspective and the model perspective. We then emphasize how the evaluation metrics and benchmarks are different from other techniques. After establishing the problems, we explore various adaptation techniques. We categorize adaptation techniques into two main families. The first is parametric knowledge adaptation, which focuses on updating the parametric knowledge within LLMs. Additionally, we will discuss real-time adaptation techniques, including model editing, which allows LLMs to be updated dynamically in production environments. The second kind of adaptation is semi-parametric knowledge adaptation, where the goal is to update LLM parameters to better leverage external knowledge or tools through techniques like retrieval-augmented generation (RAG) and agent-based systems.

[Arxiv](https://arxiv.org/abs/2504.03931)