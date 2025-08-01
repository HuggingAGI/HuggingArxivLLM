# 基于流程约束的强化学习驱动的图检索增强生成

发布时间：2025年07月31日

`RAG` `人工智能` `知识图谱`

> GraphRAG-R1: Graph Retrieval-Augmented Generation with Process-Constrained Reinforcement Learning

# 摘要

> 图增强生成（GraphRAG）通过利用图结构进行知识表示和建模复杂的现实关系，显著提升了大型语言模型（LLMs）的推理能力。然而，现有GraphRAG方法在处理需要多跳推理的复杂问题时仍面临重大瓶颈，因为它们的查询和检索阶段主要依赖于预定义的启发式方法，未能充分利用LLMs的推理潜力。为了解决这一问题，我们提出了GraphRAG-R1，这是一种通过训练LLMs采用基于结果的过程约束强化学习（RL）来增强多跳推理能力的自适应GraphRAG框架。

我们的方法能够分解复杂问题，自主调用检索工具获取必要信息，并进行有效推理。具体而言，我们采用了支持带思考回放功能的改进版组相对策略优化（GRPO）。接下来，我们设计了两个过程约束奖励函数。为了解决浅层检索问题，我们设计了渐进式检索衰减（PRA）奖励以鼓励关键检索。然后，为了解决过度思考问题，我们设计了成本感知F1（CAF）奖励以平衡模型性能与计算成本。我们还设计了一种阶段依赖的训练策略，包含三个训练阶段，分别对应冷启动和这两个奖励。最后，我们的方法采用混合图-文本检索来提升推理能力。

大量实验结果表明，与现有的GraphRAG方法相比，GraphRAG-R1在处理领域内和领域外数据集的复杂推理问题时，显著提升了LLMs的能力。此外，我们的框架可以灵活地与各种现有的检索方法相结合，始终带来性能提升。

> Graph Retrieval-Augmented Generation (GraphRAG) has shown great effectiveness in enhancing the reasoning abilities of LLMs by leveraging graph structures for knowledge representation and modeling complex real-world relationships. However, existing GraphRAG methods still face significant bottlenecks when handling complex problems that require multi-hop reasoning, as their query and retrieval phases are largely based on pre-defined heuristics and do not fully utilize the reasoning potentials of LLMs. To address this problem, we propose GraphRAG-R1, an adaptive GraphRAG framework by training LLMs with process-constrained outcome-based reinforcement learning (RL) to enhance the multi-hop reasoning ability. Our method can decompose complex problems, autonomously invoke retrieval tools to acquire necessary information, and perform effective reasoning. Specifically, we utilize a modified version of Group Relative Policy Optimization (GRPO) that supports rollout-with-thinking capability. Next, we design two process-constrained reward functions. To handle the shallow retrieval problem, we design a Progressive Retrieval Attenuation (PRA) reward to encourage essential retrievals. Then, to handle the over-thinking problem, we design Cost-Aware F1 (CAF) reward to balance the model performance with computational costs. We further design a phase-dependent training strategy, containing three training stages corresponding to cold start and these two rewards. Lastly, our method adopts a hybrid graph-textual retrieval to improve the reasoning capacity. Extensive experimental results demonstrate that GraphRAG-R1 boosts LLM capabilities in solving complex reasoning problems compared to state-of-the-art GraphRAG methods on both in-domain and out-of-domain datasets. Furthermore, our framework can be flexibly integrated with various existing retrieval methods, consistently delivering performance improvements.

[Arxiv](https://arxiv.org/abs/2507.23581)