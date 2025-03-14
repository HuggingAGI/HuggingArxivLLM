# SCOOP：通过自然语言交互与因果推理实现主动协作与社会持续学习的框架

发布时间：2025年03月13日

`Agent` `人工智能` `协作系统`

> SCOOP: A Framework for Proactive Collaboration and Social Continual Learning through Natural Language Interaction andCausal Reasoning

# 摘要

> 在动态环境中，用户与AI协作的多模态信息收集场景越来越普遍。这些场景涉及复杂的文本和多模态交互，通常需要通过成本高昂的请求获取额外的结构化信息。然而，AI助手无法访问用户的真正目标、信念和偏好，难以有效整合多样化的信息。

为解决这一问题，我们提出了一种社会持续学习框架，专注于因果知识获取和协作决策。该框架通过对话、提问和在开放、部分可观察的环境中进行交互，帮助自主代理实现学习。其核心是一个自然语言oracle，它回答代理关于环境机制和状态的查询，在平衡探索与学习、利用与知识使用的同时，完善因果理解。

受发展心理学启发的评估任务，强调因果推理和提问技能。它们通过评估代理识别知识缺口、生成有意义查询以及逐步更新推理的能力，补充了现有基准。该框架还评估在同一环境中跨任务的知识获取成本分摊情况。

我们提出了两种架构：1）结合大型语言模型（LLMs）与ReAct框架和问题生成的系统；2）具备因果世界模型的高级系统，该系统采用符号化、图结构或亚符号化方法进行推理和决策。后者构建因果知识图谱，以在约束条件下实现高效推理和适应性。挑战包括将因果推理整合到ReAct框架中，以及在易出错场景下优化探索和提问。该框架不仅适用于实际应用，还建模了结合因果推理、问题生成和社会学习的发展过程。


> Multimodal information-gathering settings, where users collaborate with AI in dynamic environments, are increasingly common. These involve complex processes with textual and multimodal interactions, often requiring additional structural information via cost-incurring requests. AI helpers lack access to users' true goals, beliefs, and preferences and struggle to integrate diverse information effectively.
  We propose a social continual learning framework for causal knowledge acquisition and collaborative decision-making. It focuses on autonomous agents learning through dialogues, question-asking, and interaction in open, partially observable environments. A key component is a natural language oracle that answers the agent's queries about environmental mechanisms and states, refining causal understanding while balancing exploration or learning, and exploitation or knowledge use.
  Evaluation tasks inspired by developmental psychology emphasize causal reasoning and question-asking skills. They complement benchmarks by assessing the agent's ability to identify knowledge gaps, generate meaningful queries, and incrementally update reasoning. The framework also evaluates how knowledge acquisition costs are amortized across tasks within the same environment.
  We propose two architectures: 1) a system combining Large Language Models (LLMs) with the ReAct framework and question-generation, and 2) an advanced system with a causal world model, symbolic, graph-based, or subsymbolic, for reasoning and decision-making. The latter builds a causal knowledge graph for efficient inference and adaptability under constraints. Challenges include integrating causal reasoning into ReAct and optimizing exploration and question-asking in error-prone scenarios. Beyond applications, this framework models developmental processes combining causal reasoning, question generation, and social learning.

[Arxiv](https://arxiv.org/abs/2503.10241)