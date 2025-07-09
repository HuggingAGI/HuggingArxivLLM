# # 基准评测：面向开放无线接入网络（ORAN）的向量、图与混合检索增强生成（RAG）管道基准测试

发布时间：2025年07月04日

`RAG` `生成式AI`

> Benchmarking Vector, Graph and Hybrid Retrieval Augmented Generation (RAG) Pipelines for Open Radio Access Networks (ORAN)

# 摘要

> 生成式AI（GenAI）将在未来无线网络的自主优化中发挥关键作用。在开放无线接入网（ORAN）架构中，大型语言模型（LLMs）可以通过利用无线接入网智能控制器（RIC）平台的规范和API定义，专门用于生成xApps和rApps。然而，针对电信特定任务对基础LLMs进行微调仍然成本高昂且资源密集。通过上下文学习，检索增强生成（RAG）提供了一种实用的替代方案，能够在无需完全重新训练的情况下实现领域适应。尽管传统RAG系统依赖向量检索，但新兴的GraphRAG和Hybrid GraphRAG变体通过整合知识图谱或双检索策略，支持多跳推理并增强事实基础。尽管这些方法展现出巨大潜力，但在ORAN等高风险领域，它们仍缺乏系统化、指标驱动的评估。本研究通过ORAN规范对向量RAG、GraphRAG和Hybrid GraphRAG进行了对比评估。我们采用已有的生成指标——忠实度、答案相关性、上下文相关性和事实正确性，对不同问题复杂度下的性能进行了评估。结果显示，GraphRAG和Hybrid GraphRAG均优于传统RAG。Hybrid GraphRAG将事实正确性提高了8%，而GraphRAG将上下文相关性提高了7%。

> Generative AI (GenAI) is expected to play a pivotal role in enabling autonomous optimization in future wireless networks. Within the ORAN architecture, Large Language Models (LLMs) can be specialized to generate xApps and rApps by leveraging specifications and API definitions from the RAN Intelligent Controller (RIC) platform. However, fine-tuning base LLMs for telecom-specific tasks remains expensive and resource-intensive. Retrieval-Augmented Generation (RAG) offers a practical alternative through in-context learning, enabling domain adaptation without full retraining. While traditional RAG systems rely on vector-based retrieval, emerging variants such as GraphRAG and Hybrid GraphRAG incorporate knowledge graphs or dual retrieval strategies to support multi-hop reasoning and improve factual grounding. Despite their promise, these methods lack systematic, metric-driven evaluations, particularly in high-stakes domains such as ORAN. In this study, we conduct a comparative evaluation of Vector RAG, GraphRAG, and Hybrid GraphRAG using ORAN specifications. We assess performance across varying question complexities using established generation metrics: faithfulness, answer relevance, context relevance, and factual correctness. Results show that both GraphRAG and Hybrid GraphRAG outperform traditional RAG. Hybrid GraphRAG improves factual correctness by 8%, while GraphRAG improves context relevance by 7%.

[Arxiv](https://arxiv.org/abs/2507.03608)