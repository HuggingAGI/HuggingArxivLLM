# 增强GraphRAG的知识过滤与集成

发布时间：2025年03月17日

`RAG` `知识图谱`

> Empowering GraphRAG with Knowledge Filtering and Integration

# 摘要

> 近年来，大型语言模型（LLMs）彻底改变了自然语言处理领域。然而，它们常常面临知识缺口和幻觉现象的困扰。图检索增强生成（GraphRAG）通过整合外部图谱中的结构化知识，增强了LLMs的推理能力。然而，我们发现GraphRAG存在两个关键挑战：（1）检索到的噪声和不相关信息会损害性能；（2）过度依赖外部知识会抑制模型的内在推理能力。

为了解决这些问题，我们提出了GraphRAG-FI（过滤与整合），包括GraphRAG-过滤和GraphRAG-整合两个部分。GraphRAG-过滤采用两阶段过滤机制来优化检索信息。GraphRAG-整合采用基于logits的选择策略，平衡GraphRAG提供的外部知识与LLM的内在推理能力，从而减少对检索的过度依赖。

在知识图谱问答任务上的实验表明，GraphRAG-FI显著提升了多个基础模型的推理性能，构建了一个更加可靠和有效的GraphRAG框架。

> In recent years, large language models (LLMs) have revolutionized the field of natural language processing. However, they often suffer from knowledge gaps and hallucinations. Graph retrieval-augmented generation (GraphRAG) enhances LLM reasoning by integrating structured knowledge from external graphs. However, we identify two key challenges that plague GraphRAG:(1) Retrieving noisy and irrelevant information can degrade performance and (2)Excessive reliance on external knowledge suppresses the model's intrinsic reasoning. To address these issues, we propose GraphRAG-FI (Filtering and Integration), consisting of GraphRAG-Filtering and GraphRAG-Integration. GraphRAG-Filtering employs a two-stage filtering mechanism to refine retrieved information. GraphRAG-Integration employs a logits-based selection strategy to balance external knowledge from GraphRAG with the LLM's intrinsic reasoning,reducing over-reliance on retrievals. Experiments on knowledge graph QA tasks demonstrate that GraphRAG-FI significantly improves reasoning performance across multiple backbone models, establishing a more reliable and effective GraphRAG framework.

[Arxiv](https://arxiv.org/abs/2503.13804)