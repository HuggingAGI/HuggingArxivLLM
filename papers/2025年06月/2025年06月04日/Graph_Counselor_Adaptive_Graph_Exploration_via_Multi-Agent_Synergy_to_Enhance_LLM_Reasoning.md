# 图导览器：通过多智能体协同实现自适应图探索，提升大语言模型推理能力。

发布时间：2025年06月04日

`RAG` `图推理` `知识图谱`

> Graph Counselor: Adaptive Graph Exploration via Multi-Agent Synergy to Enhance LLM Reasoning

# 摘要

> 图检索增强生成（GraphRAG）通过显式建模知识关系，有效提升了大型语言模型（LLMs）在特定领域中的事实准确性和生成质量。然而，现有方法存在两个固有局限性：1）信息聚合低效：它们依赖单一智能体和固定迭代模式，难以自适应地捕获图数据中的多级文本、结构和度信息。2） rigid推理机制：它们采用预设推理方案，无法动态调整推理深度，也难以实现精准语义修正。为克服这些限制，我们提出了基于多智能体协作的GraphRAG方法——Graph Counselor。该方法采用自适应图信息抽取模块（AGIEM），其中规划、思考和执行智能体协同工作，精确建模复杂图结构并动态调整信息抽取策略，从而解决多级依赖建模和自适应推理深度的难题。此外，多视角自我反思（SR）模块通过自我反思和反向推理机制，提升推理结果的准确性和语义一致性。实验表明，Graph Counselor在多个图推理任务中超越现有方法，展现出更高的推理准确性和泛化能力。我们的代码可在https://github.com/gjq100/Graph-Counselor.git获取。

> Graph Retrieval Augmented Generation (GraphRAG) effectively enhances external knowledge integration capabilities by explicitly modeling knowledge relationships, thereby improving the factual accuracy and generation quality of Large Language Models (LLMs) in specialized domains. However, existing methods suffer from two inherent limitations: 1) Inefficient Information Aggregation: They rely on a single agent and fixed iterative patterns, making it difficult to adaptively capture multi-level textual, structural, and degree information within graph data. 2) Rigid Reasoning Mechanism: They employ preset reasoning schemes, which cannot dynamically adjust reasoning depth nor achieve precise semantic correction. To overcome these limitations, we propose Graph Counselor, an GraphRAG method based on multi-agent collaboration. This method uses the Adaptive Graph Information Extraction Module (AGIEM), where Planning, Thought, and Execution Agents work together to precisely model complex graph structures and dynamically adjust information extraction strategies, addressing the challenges of multi-level dependency modeling and adaptive reasoning depth. Additionally, the Self-Reflection with Multiple Perspectives (SR) module improves the accuracy and semantic consistency of reasoning results through self-reflection and backward reasoning mechanisms. Experiments demonstrate that Graph Counselor outperforms existing methods in multiple graph reasoning tasks, exhibiting higher reasoning accuracy and generalization ability. Our code is available at https://github.com/gjq100/Graph-Counselor.git.

[Arxiv](https://arxiv.org/abs/2506.03939)