# # 摘要
迈向对话式AI驱动的人机协作MLOps

发布时间：2025年04月16日

`Agent` `MLOps` `对话系统`

> Towards Conversational AI for Human-Machine Collaborative MLOps

# 摘要

> 本文介绍了一种基于大型语言模型（LLM）的对话式代理系统，旨在提升机器学习运维（MLOps）中的人机协作效率。我们提出了Swarm Agent这一可扩展架构，通过整合专用代理，利用自然语言交互实现ML工作流的创建与管理。该系统采用分层模块化设计，集成了用于ML管道编排的KubeFlow管道（KFP）代理、用于数据管理的MinIO代理以及用于领域特定知识整合的检索增强生成（RAG）代理。通过迭代推理循环和上下文感知处理，系统使具备不同技术背景的用户能够通过直观的对话界面发现、执行和监控ML管道，管理数据集和工件，以及访问相关文档。我们的方法弥补了复杂MLOps平台（如Kubeflow）的可访问性差距，使高级ML工具广泛可用，同时保留了扩展到其他平台的灵活性。本文详细描述了该架构和实现细节，并展示了这种对话式MLOps助手如何降低复杂性并消除不同技术水平用户进入的障碍。

> This paper presents a Large Language Model (LLM) based conversational agent system designed to enhance human-machine collaboration in Machine Learning Operations (MLOps). We introduce the Swarm Agent, an extensible architecture that integrates specialized agents to create and manage ML workflows through natural language interactions. The system leverages a hierarchical, modular design incorporating a KubeFlow Pipelines (KFP) Agent for ML pipeline orchestration, a MinIO Agent for data management, and a Retrieval-Augmented Generation (RAG) Agent for domain-specific knowledge integration. Through iterative reasoning loops and context-aware processing, the system enables users with varying technical backgrounds to discover, execute, and monitor ML pipelines; manage datasets and artifacts; and access relevant documentation, all via intuitive conversational interfaces. Our approach addresses the accessibility gap in complex MLOps platforms like Kubeflow, making advanced ML tools broadly accessible while maintaining the flexibility to extend to other platforms. The paper describes the architecture, implementation details, and demonstrates how this conversational MLOps assistant reduces complexity and lowers barriers to entry for users across diverse technical skill levels.

[Arxiv](https://arxiv.org/abs/2504.12477)