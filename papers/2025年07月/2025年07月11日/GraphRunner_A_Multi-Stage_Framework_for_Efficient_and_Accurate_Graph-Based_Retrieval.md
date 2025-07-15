# GraphRunner：高效精准的多阶段图检索框架

发布时间：2025年07月11日

`RAG` `知识图谱` `信息检索`

> GraphRunner: A Multi-Stage Framework for Efficient and Accurate Graph-Based Retrieval

# 摘要

> 传统的检索增强生成（RAG）方法在文本应用中广泛应用，但在处理知识图谱等结构化、相互关联的数据集时面临挑战，因为理解这些数据中的底层关系对于准确检索至关重要。基于图的检索中，一种常见方法是利用大型语言模型（LLMs）引导的迭代、基于规则的遍历。然而，现有迭代方法通常在每一步结合推理与单跳遍历，容易受到LLM推理错误和幻觉的影响，从而影响信息检索效果。  
    为了解决这些局限性，我们提出了一种名为GraphRunner的新型基于图的检索框架，它分为规划、验证和执行三个阶段。GraphRunner引入了高层次的遍历动作，能够在单一步骤中实现多跳探索。此外，它生成一个整体的遍历计划，并在执行前根据图结构和预定义的遍历动作进行验证，从而有效减少推理错误并检测幻觉。通过验证，GraphRunner显著降低了LLM推理错误率。在GRBench数据集上的评估结果显示，与现有方法相比，GraphRunner不仅性能提升了10-50%，还将推理成本降低了3.0-12.9倍，响应生成时间减少了2.5-7.1倍，使其在基于图的检索任务中更加稳健和高效。

> Conventional Retrieval Augmented Generation (RAG) approaches are common in text-based applications. However, they struggle with structured, interconnected datasets like knowledge graphs, where understanding underlying relationships is crucial for accurate retrieval. A common direction in graph-based retrieval employs iterative, rule-based traversal guided by Large Language Models (LLMs). Such existing iterative methods typically combine reasoning with single hop traversal at each step, making them vulnerable to LLM reasoning errors and hallucinations that ultimately hinder the retrieval of relevant information.
  To address these limitations, we propose GraphRunner, a novel graph-based retrieval framework that operates in three distinct stages: planning, verification, and execution. This introduces high-level traversal actions that enable multi-hop exploration in a single step. It also generates a holistic traversal plan, which is verified against the graph structure and pre-defined traversal actions, reducing reasoning errors and detecting hallucinations before execution. GraphRunner significantly reduces LLM reasoning errors and detects hallucinations through validation. Our evaluation using the GRBench dataset shows that GraphRunner consistently outperforms existing approaches, achieving 10-50% performance improvements over the strongest baseline while reducing inference cost by 3.0-12.9x and response generation time by 2.5-7.1x, making it significantly more robust and efficient for graph-based retrieval tasks.

[Arxiv](https://arxiv.org/abs/2507.08945)