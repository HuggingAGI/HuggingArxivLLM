# # 标题
GKG-LLM：构建广义知识图谱的统一框架

发布时间：2025年03月14日

`LLM应用` `知识图谱`

> GKG-LLM: A Unified Framework for Generalized Knowledge Graph Construction

# 摘要

> 广义知识图谱（GKG）的构建，包括知识图谱、事件知识图谱和常识知识图谱，是多种自然语言处理任务的基础。然而，现有研究通常将这些图谱分开构建，忽视了整体视角下可能带来的统一性优势，这在计算资源和使用效率上可能更有益。然而，开发一个统一的GKG框架面临一个关键挑战，即任务特定差异带来的障碍。本研究提出了一种构建广义知识图谱的统一框架，旨在解决这一问题。首先，我们从涵盖三种图谱的29个数据集中收集了15个子任务的数据，并将其分类为样本内、反向任务和分布外（OOD）数据。然后，我们提出了一种三阶段课程学习微调框架，通过迭代地将三种图谱的知识注入大型语言模型中。大量实验结果表明，我们的模型在领域内、OOD和反向任务数据上，均显著提升了三种图谱的构建效果。

> The construction of Generalized Knowledge Graph (GKG), including knowledge graph, event knowledge graph and commonsense knowledge graph, is fundamental for various natural language processing tasks. Current studies typically construct these types of graph separately, overlooking holistic insights and potential unification that could be beneficial in computing resources and usage perspectives. However, a key challenge in developing a unified framework for GKG is obstacles arising from task-specific differences. In this study, we propose a unified framework for constructing generalized knowledge graphs to address this challenge. First, we collect data from 15 sub-tasks in 29 datasets across the three types of graphs, categorizing them into in-sample, counter-task, and out-of-distribution (OOD) data. Then, we propose a three-stage curriculum learning fine-tuning framework, by iteratively injecting knowledge from the three types of graphs into the Large Language Models. Extensive experiments show that our proposed model improves the construction of all three graph types across in-domain, OOD and counter-task data.

[Arxiv](https://arxiv.org/abs/2503.11227)