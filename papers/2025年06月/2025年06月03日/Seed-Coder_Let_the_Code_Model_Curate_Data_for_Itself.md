# Seed-Coder：让代码模型自己整理数据

发布时间：2025年06月03日

`LLM应用` `代码智能` `人工智能`

> Seed-Coder: Let the Code Model Curate Data for Itself

# 摘要

> 代码数据在大型语言模型（LLM）预训练中扮演着双重关键角色：它不仅为代码相关任务提供重要支持，更是提升LLM通用智能水平的基石。现有的开源LLMs在构建代码预训练数据时往往严重依赖人工干预，例如通过针对特定编程语言的手工编写过滤规则，或利用人工标注的数据来训练质量筛选器。然而，这些方法在扩展性上存在根本性限制，容易受主观偏见影响，且在跨多种编程语言的环境中维护和扩展成本高昂。

为了解决这些挑战，我们推出了Seed-Coder——一系列开源LLMs，包含80亿参数规模的基础模型、指令模型和推理模型，力求在数据构建过程中最大限度地减少人工干预。我们的代码预训练数据通过一种以模型为中心的数据管道生成，该管道主要利用LLMs对代码数据进行评分和筛选。指令模型通过监督微调和偏好优化进一步训练，而推理模型则借助长链式思维（LongCoT）强化学习来提升多步骤代码推理能力。

Seed-Coder在同规模开源模型中达到了最先进水平，甚至超越了一些规模大得多的模型。它在代码生成、代码补全、代码编辑、代码推理和软件工程任务中均展现出卓越性能，标志着开源LLM在代码智能领域的重大突破。

> Code data in large language model (LLM) pretraining is recognized crucial not only for code-related tasks but also for enhancing general intelligence of LLMs. Current open-source LLMs often heavily rely on human effort to produce their code pretraining data, such as employing hand-crafted filtering rules tailored to individual programming languages, or using human-annotated data to train quality filters. However, these approaches are inherently limited in scalability, prone to subjective biases, and costly to extend and maintain across diverse programming languages. To address these challenges, we introduce Seed-Coder, a series of open-source LLMs comprising base, instruct and reasoning models of 8B size, minimizing human involvement in data construction. Our code pretraining data is produced by a model-centric data pipeline, which predominantly leverages LLMs for scoring and filtering code data. The instruct model is further trained via supervised fine-tuning and preference optimization, and the reasoning model leverages Long-Chain-of-Thought (LongCoT) reinforcement learning to improve multi-step code reasoning. Seed-Coder achieves state-of-the-art results among open-source models of similar size and even surpasses some much larger models, demonstrating superior performance in code generation, code completion, code editing, code reasoning, and software engineering tasks.

[Arxiv](https://arxiv.org/abs/2506.03524)