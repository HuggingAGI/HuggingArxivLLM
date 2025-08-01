# LLM智能体高效长期推理的分层记忆机制

发布时间：2025年07月23日

`Agent` `人工智能` `智能代理`

> Hierarchical Memory for High-Efficiency Long-Term Reasoning in LLM Agents

# 摘要

> 长期记忆是影响大型语言模型代理（LLM代理）推理能力的重要因素。通过整合过去交互的有效记忆机制，可以显著提升LLM代理的决策能力和情境连贯性。尽管近期在记忆存储和检索方面取得了进展，例如将记忆编码为密集向量以进行基于相似性的搜索，或以图的形式组织知识，但这些方法在结构化记忆组织和高效检索方面仍存在不足。为了解决这些问题，我们提出了一种适用于LLM代理的分层记忆（H-MEM）架构。该架构根据语义抽象程度以多级方式组织和更新记忆。每个记忆向量都嵌入了指向其语义相关子记忆的 positional index 编码，这些子记忆位于下一层。在推理阶段，基于索引的路由机制能够实现逐层高效检索，无需进行耗时的相似性计算。我们通过LoCoMo数据集的五个任务设置对我们的方法进行了评估。实验结果显示，我们的方法在五个基线方法上始终表现出色，证明了其在长期对话场景中的有效性。

> Long-term memory is one of the key factors influencing the reasoning capabilities of Large Language Model Agents (LLM Agents). Incorporating a memory mechanism that effectively integrates past interactions can significantly enhance decision-making and contextual coherence of LLM Agents. While recent works have made progress in memory storage and retrieval, such as encoding memory into dense vectors for similarity-based search or organizing knowledge in the form of graph, these approaches often fall short in structured memory organization and efficient retrieval. To address these limitations, we propose a Hierarchical Memory (H-MEM) architecture for LLM Agents that organizes and updates memory in a multi-level fashion based on the degree of semantic abstraction. Each memory vector is embedded with a positional index encoding pointing to its semantically related sub-memories in the next layer. During the reasoning phase, an index-based routing mechanism enables efficient, layer-by-layer retrieval without performing exhaustive similarity computations. We evaluate our method on five task settings from the LoCoMo dataset. Experimental results show that our approach consistently outperforms five baseline methods, demonstrating its effectiveness in long-term dialogue scenarios.

[Arxiv](https://arxiv.org/abs/2507.22925)