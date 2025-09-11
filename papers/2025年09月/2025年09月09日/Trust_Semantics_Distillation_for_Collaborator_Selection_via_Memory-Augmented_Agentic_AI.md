# 基于记忆增强智能体AI的合作者选择：信任语义蒸馏

发布时间：2025年09月09日

`Agent` `工业与制造`

> Trust Semantics Distillation for Collaborator Selection via Memory-Augmented Agentic AI

# 摘要

> 对潜在协作设备进行准确的可信度评估，是复杂计算任务高效执行的关键。这一评估过程需要从潜在协作者处收集各类信任相关数据，如历史表现和可用资源，用于协作者筛选。然而，若每个任务所有者独立评估所有协作者的可信度，频繁的数据交互、复杂的推理过程以及动态变化的场景会造成巨大开销，同时降低可信度评估效果。为应对这些挑战，我们提出了特定任务信任语义蒸馏（2TSD）模型，该模型基于大型AI模型（LAM）驱动的师生智能体架构。教师智能体部署在配备强大计算能力和增强内存模块的服务器中，专门负责多维信任相关数据的收集、特定任务信任语义的提取，以及任务与协作者的匹配分析。当接收到设备端学生智能体的特定任务请求后，教师智能体便将潜在协作者的信任语义传递给学生智能体，进而实现协作者的快速准确筛选。实验结果显示，所提2TSD模型可缩短协作者评估时间、降低设备资源消耗，同时提升协作者选择的准确性。

> Accurate trustworthiness evaluation of potential collaborating devices is essential for the effective execution of complex computing tasks. This evaluation process involves collecting diverse trust-related data from potential collaborators, including historical performance and available resources, for collaborator selection. However, when each task owner independently assesses all collaborators' trustworthiness, frequent data exchange, complex reasoning, and dynamic situation changes can result in significant overhead and deteriorated trust evaluation. To overcome these challenges, we propose a task-specific trust semantics distillation (2TSD) model based on a large AI model (LAM)-driven teacher-student agent architecture. The teacher agent is deployed on a server with powerful computational capabilities and an augmented memory module dedicated to multidimensional trust-related data collection, task-specific trust semantics extraction, and task-collaborator matching analysis. Upon receiving task-specific requests from device-side student agents, the teacher agent transfers the trust semantics of potential collaborators to the student agents, enabling rapid and accurate collaborator selection. Experimental results demonstrate that the proposed 2TSD model can reduce collaborator evaluation time, decrease device resource consumption, and improve the accuracy of collaborator selection.

[Arxiv](https://arxiv.org/abs/2509.08151)