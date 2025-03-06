# LLM 身化 GNN：专为文本属性图设计的图词汇学习模型

发布时间：2025年03月05日

`LLM应用` `人工智能`

> LLM as GNN: Graph Vocabulary Learning for Text-Attributed Graph Foundation Models

# 摘要

> 文本属性图（TAGs）在现实场景中随处可见，每个节点都带有文本描述。它们独特的结构和领域特定的知识推动了跨多种图和任务的图基础模型（GFM）的发展。尽管在将大型语言模型（LLMs）与图神经网络（GNNs）结合用于TAGs方面付出了巨大努力，但现有方法仍存在架构解耦和两阶段对齐的问题，限制了它们的协同潜力。更糟糕的是，现有方法将未登录词（OOV）分配给图节点，导致特定于图的语义、词汇爆炸以及与面向任务的提示模板不兼容，这阻碍了跨图和跨任务的迁移能力。为了解决这些挑战，我们提出了PromptGFM，这是一种基于图词汇学习的通用TAGs GFM。PromptGFM包含两个关键组件：（1）图理解模块，显式地提示LLMs在文本空间中复制最精细的GNN工作流程，实现无缝的GNN-LLM集成和优雅的图-文本对齐；（2）图推理模块，建立一个基于语言的图词汇，确保表达性、迁移性和可扩展性，从而为LLM微调提供可读的指令。大量实验表明，我们在多样化的图和任务中具有优越性和可迁移性。代码可在以下链接获取：https://github.com/agiresearch/PromptGFM。


> Text-Attributed Graphs (TAGs), where each node is associated with text descriptions, are ubiquitous in real-world scenarios. They typically exhibit distinctive structure and domain-specific knowledge, motivating the development of a Graph Foundation Model (GFM) that generalizes across diverse graphs and tasks. Despite large efforts to integrate Large Language Models (LLMs) and Graph Neural Networks (GNNs) for TAGs, existing approaches suffer from decoupled architectures with two-stage alignment, limiting their synergistic potential. Even worse, existing methods assign out-of-vocabulary (OOV) tokens to graph nodes, leading to graph-specific semantics, token explosion, and incompatibility with task-oriented prompt templates, which hinders cross-graph and cross-task transferability. To address these challenges, we propose PromptGFM, a versatile GFM for TAGs grounded in graph vocabulary learning. PromptGFM comprises two key components: (1) Graph Understanding Module, which explicitly prompts LLMs to replicate the finest GNN workflow within the text space, facilitating seamless GNN-LLM integration and elegant graph-text alignment; (2) Graph Inference Module, which establishes a language-based graph vocabulary ensuring expressiveness, transferability, and scalability, enabling readable instructions for LLM fine-tuning. Extensive experiments demonstrate our superiority and transferability across diverse graphs and tasks. The code is available at this: https://github.com/agiresearch/PromptGFM.

[Arxiv](https://arxiv.org/abs/2503.03313)