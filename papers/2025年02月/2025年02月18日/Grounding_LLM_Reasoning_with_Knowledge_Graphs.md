# # 知识图谱助力LLM推理能力

发布时间：2025年02月18日

`LLM应用` `知识图谱` `问答系统`

> Grounding LLM Reasoning with Knowledge Graphs

# 摘要

> 知识图谱（KGs）是表示实体间关系的重要工具，采用结构化格式。传统上，这些知识库被用来查询以提取特定信息。然而，在这些知识图谱上进行问答任务仍然面临挑战，这主要源于自然语言本身的复杂性与结构化格式之间的差距，以及知识图谱规模的庞大。尽管存在这些挑战，知识图谱的结构化特性可以为大型语言模型（LLMs）的输出提供坚实的基础，从而为组织带来更高的可靠性和控制力。

近年来，大型语言模型的进步引入了推理方法，以提升模型性能并最大化其能力。在本研究中，我们提出将这些推理策略与知识图谱相结合，旨在将推理链中的每一步或“思路”都锚定在知识图谱数据上。具体而言，我们采用GRBench——一个基于领域特定图的图推理基准数据集，评估了多种推理策略（包括思维链（CoT）、思维树（ToT）和思维图（GoT））下的智能体搜索和自动化搜索方法。实验结果表明，这种方法在基准模型上表现更优，突显了将大型语言模型推理过程扎根于结构化知识图谱数据的优势。


> Knowledge Graphs (KGs) are valuable tools for representing relationships between entities in a structured format. Traditionally, these knowledge bases are queried to extract specific information. However, question-answering (QA) over such KGs poses a challenge due to the intrinsic complexity of natural language compared to the structured format and the size of these graphs. Despite these challenges, the structured nature of KGs can provide a solid foundation for grounding the outputs of Large Language Models (LLMs), offering organizations increased reliability and control.
  Recent advancements in LLMs have introduced reasoning methods at inference time to improve their performance and maximize their capabilities. In this work, we propose integrating these reasoning strategies with KGs to anchor every step or "thought" of the reasoning chains in KG data. Specifically, we evaluate both agentic and automated search methods across several reasoning strategies, including Chain-of-Thought (CoT), Tree-of-Thought (ToT), and Graph-of-Thought (GoT), using GRBench, a benchmark dataset for graph reasoning with domain-specific graphs. Our experiments demonstrate that this approach consistently outperforms baseline models, highlighting the benefits of grounding LLM reasoning processes in structured KG data.

[Arxiv](https://arxiv.org/abs/2502.13247)