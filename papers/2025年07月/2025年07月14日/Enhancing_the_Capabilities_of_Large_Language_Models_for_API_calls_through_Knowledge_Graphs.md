# # 增强大型语言模型通过知识图谱调用API的能力

发布时间：2025年07月14日

`LLM应用

理由：这篇论文主要探讨了大型语言模型在气象学等知识密集型领域的应用，特别是通过结合知识图谱、ReAct代理等技术，提升数据获取和查询处理的能力。虽然提到了ReAct代理，但论文的核心是围绕LLMs的应用，因此归类为LLM应用。` `气象学` `知识图谱`

> Enhancing the Capabilities of Large Language Models for API calls through Knowledge Graphs

# 摘要

> 大型语言模型（LLMs）的API调用为数据分析开辟了前沿途径，但在气象学等知识密集型领域，其工具利用能力尚未得到充分挖掘。本文介绍的KG2data系统，巧妙结合知识图谱、LLMs、ReAct代理和工具使用技术，为气象领域的智能数据获取和查询处理提供了全新解决方案。通过虚拟API，我们从名称识别失败、幻觉失败和调用正确性三个维度评估API调用的准确性。结果显示，KG2data（1.43%、0%、88.57%）显著优于RAG2data（16%、10%、72.14%）和chat2data（7.14%、8.57%、71.43%）。与传统LLM系统不同，KG2data突破了领域知识获取的限制，有效解决了复杂或术语密集型查询的处理难题。通过将知识图谱作为持久化记忆，KG2data显著提升了内容检索效率、复杂查询处理能力、领域推理深度、语义关系解析精度以及异构数据整合能力。此外，该系统大幅降低了对LLMs微调的需求，使其更适应领域知识和API结构的动态变化。总之，KG2data为知识密集型领域的智能问答和数据分析提供了创新性的解决方案，展现了强大的应用前景。


> API calls by large language models (LLMs) offer a cutting-edge approach for data analysis. However, their ability to effectively utilize tools via API calls remains underexplored in knowledge-intensive domains like meteorology. This paper introduces KG2data, a system that integrates knowledge graphs, LLMs, ReAct agents, and tool-use technologies to enable intelligent data acquisition and query handling in the meteorological field. Using a virtual API, we evaluate API call accuracy across three metrics: name recognition failure, hallucination failure, and call correctness. KG2data achieves superior performance (1.43%, 0%, 88.57%) compared to RAG2data (16%, 10%, 72.14%) and chat2data (7.14%, 8.57%, 71.43%). KG2data differs from typical LLM-based systems by addressing their limited access to domain-specific knowledge, which hampers performance on complex or terminology-rich queries. By using a knowledge graph as persistent memory, our system enhances content retrieval, complex query handling, domain-specific reasoning, semantic relationship resolution, and heterogeneous data integration. It also mitigates the high cost of fine-tuning LLMs, making the system more adaptable to evolving domain knowledge and API structures. In summary, KG2data provides a novel solution for intelligent, knowledge-based question answering and data analysis in domains with high knowledge demands.

[Arxiv](https://arxiv.org/abs/2507.10630)