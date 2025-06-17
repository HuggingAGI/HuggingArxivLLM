# 通过自适应查询路由实现高效神经符号检索增强生成

发布时间：2025年06月15日

`RAG` `问答系统`

> Efficient Neuro-Symbolic Retrieval-Augmented Generation through Adaptive Query Routing

# 摘要

> 检索增强生成（RAG）系统通过外部知识解决了大型语言模型的事实不一致问题，但面临一个根本性效率难题：简单查询与复杂多跳推理任务消耗相同计算资源。我们提出SymRAG，一种基于实时复杂度和系统负载评估的神经符号框架，实现自适应查询路由。SymRAG动态选择符号、神经或混合处理路径，使资源使用与查询需求匹配。在HotpotQA和DROP数据集的2000个查询上，使用Llama-3.2-3B和Mistral-7B模型评估，SymRAG实现97.6--100.0%的精确匹配准确率，同时显著降低CPU利用率（3.6--6.2%）和处理时间（0.985--3.165秒）。禁用自适应逻辑使处理时间增加169--1151%，凸显框架重要性。这些结果表明，自适应神经符号路由对构建可扩展、可持续AI系统潜力巨大。

> Retrieval-Augmented Generation (RAG) systems address factual inconsistencies in Large Language Models by grounding generation in external knowledge, yet they face a fundamental efficiency problem: simple queries consume computational resources equivalent to complex multi-hop reasoning tasks. We present SymRAG, a neuro-symbolic framework that introduces adaptive query routing based on real-time complexity and system load assessments. SymRAG dynamically selects symbolic, neural, or hybrid processing paths to align resource use with query demands. Evaluated on 2,000 queries from HotpotQA and DROP using Llama-3.2-3B and Mistral-7B models, SymRAG achieves 97.6--100.0% exact match accuracy with significantly lower CPU utilization (3.6--6.2%) and processing time (0.985--3.165s). Disabling adaptive logic results in 169--1151% increase in processing time, highlighting the framework's impact. These results underscore the potential of adaptive neuro-symbolic routing for scalable, sustainable AI systems.

[Arxiv](https://arxiv.org/abs/2506.12981)