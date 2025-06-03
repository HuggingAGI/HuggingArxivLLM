# ThinkEval：通过思维知识图谱评估大型语言模型编辑中的知识保存与一致性

发布时间：2025年06月02日

`LLM应用

LLM应用` `模型编辑` `知识图谱`

> ThinkEval: Practical Evaluation of Knowledge Preservation and Consistency in LLM Editing with Thought-based Knowledge Graphs

# 摘要

> 模型编辑已成为处理大型语言模型（LLMs）中隐私、偏见和错误信息的重要工具，它无需从头重新训练模型即可更新知识。然而，现有的编辑技术通常只针对孤立的事实，忽视了对相关知识的连锁反应，导致编辑后的事实仍可推导，并损害了更广泛的知识完整性。例如，将哈利·波特的学校从霍格沃茨改为伊尔弗莫尼，需要将他的学院从格兰芬多重新分配到一个合适的替代学院，同时保留格兰芬多与霍格沃茨的关系。在这项研究中，我们提出了一个新的模型编辑设置——深度编辑，以展示：（1）编辑技术如何无法处理相互关联的事实，评估原始知识如何通过未受影响的因果关系链潜入；（2）它们对更广泛的知识背景的影响。我们引入了ThinkEval框架，通过构建特定于模型的知识图谱来系统地评估模型编辑技术，分析编辑前后事实的持久性和灾难性遗忘效应。我们提出了KnowGIC基准，使用ThinkEval创建，包含一系列相互关联的查询，用于测量这些效应。我们评估了五种编辑技术：AlphaEdit、RECT、ROME、MEMIT和PRUNE，跨越多个LLMs。我们发现，这些技术难以在间接事实抑制与相关知识保留之间取得平衡。我们的数据集可在以下链接获取：https://anonymous.4open.science/r/KnowGIC。

> Model editing has become an important tool for addressing privacy, bias, and misinformation in large language models (LLMs) by enabling updates to knowledge without the need for retraining from scratch. However, existing editing techniques often target isolated facts, ignoring ripple effects on related knowledge, allowing edited facts to remain deducible and compromising broader contextual integrity. For example, changing Harry Potter's school from Hogwarts to Ilvermorny requires reassigning his house from Gryffindor to a suitable alternative while preserving Gryffindor's relationship with Hogwarts. In this work, we present a new model-editing setting, deep editing, to show: (1) how editing techniques fail to handle connected facts, evaluating how original knowledge sneaks through unchanged causal links, and (2) their impact on broader contextual knowledge. We introduce ThinkEval, a framework to systematically evaluate model- editing techniques by building model-specific knowledge graphs to analyze pre- and post-edit effects on fact persistence and catastrophic forgetting. We present KnowGIC, a benchmark created with ThinkEval, consisting of sequentially linked queries to measure these effects. We evaluate five editing techniques: AlphaEdit, RECT, ROME, MEMIT, and PRUNE across multiple LLMs. We find that these techniques struggle to balance indirect fact suppression with the preservation of related knowledge. Our dataset is available at: https://anonymous.4open.science/r/KnowGIC.

[Arxiv](https://arxiv.org/abs/2506.01386)