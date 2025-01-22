# 结合图结构与大型语言模型，实现端到端的合成任务导向对话

发布时间：2025年01月21日

`LLM应用

解释：这篇论文讨论了如何利用大型语言模型（LLMs）来生成面向任务的对话数据，从而简化对话系统的训练过程。虽然论文提到了LLMs的使用，但主要关注的是如何应用这些模型来生成对话数据，而不是深入研究LLMs的理论或架构。因此，这篇论文更适合归类为“LLM应用”。` `对话系统`

> Leveraging Graph Structures and Large Language Models for End-to-End Synthetic Task-Oriented Dialogues

# 摘要

> 训练面向任务的对话系统既费时又昂贵，因为需要涵盖多种意图的高质量数据集。传统方法依赖大量人工标注，而最新进展则利用大型语言模型（LLMs）生成合成数据。然而，这些方法通常需要自定义提示或代码，对非技术用户不够友好。我们推出了GraphTOD，一个端到端框架，简化了面向任务对话的生成。用户只需通过JSON格式的转换图即可创建对话。评估显示，GraphTOD能生成跨领域的高质量对话，大幅降低了数据集创建的成本和复杂度。

> Training task-oriented dialogue systems is both costly and time-consuming, due to the need for high-quality datasets encompassing diverse intents. Traditional methods depend on extensive human annotation, while recent advancements leverage large language models (LLMs) to generate synthetic data. However, these approaches often require custom prompts or code, limiting accessibility for non-technical users. We introduce GraphTOD, an end-to-end framework that simplifies the generation of task-oriented dialogues. Users can create dialogues by specifying transition graphs in JSON format. Our evaluation demonstrates that GraphTOD generates high-quality dialogues across various domains, significantly lowering the cost and complexity of dataset creation.

[Arxiv](https://arxiv.org/abs/2501.11977)