# Graph-R1: 提出了一种基于端到端强化学习的智能体GraphRAG框架

发布时间：2025年07月29日

`LLM应用` `问答系统`

> Graph-R1: Towards Agentic GraphRAG Framework via End-to-end Reinforcement Learning

# 摘要

> 检索增强生成（RAG）通过整合外部知识有效缓解了大型语言模型中的幻觉问题，但其基于分块的检索方法缺乏结构化语义。图增强生成（GraphRAG）方法通过将知识建模为实体-关系图来改进RAG，但仍面临构建成本高昂、固定一次性检索以及对长上下文推理和提示设计的依赖等挑战。为了解决这些问题，我们提出了Graph-R1，这是一个通过端到端强化学习（RL）构建的智能体图增强生成框架。它引入了轻量级知识超图构建方法，将检索建模为多轮智能体-环境交互过程，并通过端到端奖励机制优化智能体行为。在标准RAG数据集上的实验表明，Graph-R1在推理准确性、检索效率和生成质量方面均优于传统GraphRAG和强化学习增强的RAG方法。

> Retrieval-Augmented Generation (RAG) mitigates hallucination in LLMs by incorporating external knowledge, but relies on chunk-based retrieval that lacks structural semantics. GraphRAG methods improve RAG by modeling knowledge as entity-relation graphs, but still face challenges in high construction cost, fixed one-time retrieval, and reliance on long-context reasoning and prompt design. To address these challenges, we propose Graph-R1, an agentic GraphRAG framework via end-to-end reinforcement learning (RL). It introduces lightweight knowledge hypergraph construction, models retrieval as a multi-turn agent-environment interaction, and optimizes the agent process via an end-to-end reward mechanism. Experiments on standard RAG datasets show that Graph-R1 outperforms traditional GraphRAG and RL-enhanced RAG methods in reasoning accuracy, retrieval efficiency, and generation quality.

[Arxiv](https://arxiv.org/abs/2507.21892)