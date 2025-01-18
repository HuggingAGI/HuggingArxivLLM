# 智能体检索增强生成：智能体RAG综述

发布时间：2025年01月15日

`Agent

理由：这篇论文主要讨论了自主检索增强生成（Agentic RAG）系统，该系统通过将自主AI代理嵌入RAG管道来增强传统RAG系统的能力。论文详细介绍了Agentic RAG的架构、设计模式（如反思、规划、工具使用和多代理协作）以及其在多个行业中的应用。这些内容主要围绕自主AI代理的设计和应用展开，因此将其分类为Agent。`

> Agentic Retrieval-Augmented Generation: A Survey on Agentic RAG

# 摘要

> # 摘要
大型语言模型（LLMs）通过实现类人文本生成和自然语言理解，彻底革新了人工智能（AI）。然而，它们对静态训练数据的依赖限制了其响应动态、实时查询的能力，导致输出过时或不准确。检索增强生成（RAG）应运而生，通过集成实时数据检索来增强LLMs，提供上下文相关且最新的响应。尽管前景广阔，传统的RAG系统受限于静态工作流，缺乏多步推理和复杂任务管理所需的适应性。
  自主检索增强生成（Agentic RAG）通过将自主AI代理嵌入RAG管道，超越了这些限制。这些代理利用自主设计模式（如反思、规划、工具使用和多代理协作）动态管理检索策略，迭代优化上下文理解，并调整工作流以满足复杂任务需求。这种集成使Agentic RAG系统在多样化应用中提供了无与伦比的灵活性、可扩展性和上下文感知能力。
  本调查全面探讨了Agentic RAG，从其基本原理和RAG范式的演变开始。它详细介绍了Agentic RAG架构的分类，突出了在医疗、金融和教育等行业的关键应用，并探讨了实际实施策略。此外，它还解决了扩展这些系统、确保道德决策和优化实际应用性能的挑战，同时提供了实施Agentic RAG的框架和工具的详细见解。

> Large Language Models (LLMs) have revolutionized artificial intelligence (AI) by enabling human like text generation and natural language understanding. However, their reliance on static training data limits their ability to respond to dynamic, real time queries, resulting in outdated or inaccurate outputs. Retrieval Augmented Generation (RAG) has emerged as a solution, enhancing LLMs by integrating real time data retrieval to provide contextually relevant and up-to-date responses. Despite its promise, traditional RAG systems are constrained by static workflows and lack the adaptability required for multistep reasoning and complex task management.
  Agentic Retrieval-Augmented Generation (Agentic RAG) transcends these limitations by embedding autonomous AI agents into the RAG pipeline. These agents leverage agentic design patterns reflection, planning, tool use, and multiagent collaboration to dynamically manage retrieval strategies, iteratively refine contextual understanding, and adapt workflows to meet complex task requirements. This integration enables Agentic RAG systems to deliver unparalleled flexibility, scalability, and context awareness across diverse applications.
  This survey provides a comprehensive exploration of Agentic RAG, beginning with its foundational principles and the evolution of RAG paradigms. It presents a detailed taxonomy of Agentic RAG architectures, highlights key applications in industries such as healthcare, finance, and education, and examines practical implementation strategies. Additionally, it addresses challenges in scaling these systems, ensuring ethical decision making, and optimizing performance for real-world applications, while providing detailed insights into frameworks and tools for implementing Agentic RAG

[Arxiv](https://arxiv.org/abs/2501.09136)