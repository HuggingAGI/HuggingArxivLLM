# # DRAG：蒸馏RAG方法，从LLMs向SLMs转移知识并缓解幻觉，基于证据与图蒸馏技术

发布时间：2025年06月02日

`RAG` `知识图谱`

> DRAG: Distilling RAG for SLMs from LLMs to Transfer Knowledge and Mitigate Hallucination via Evidence and Graph-based Distillation

# 摘要

> 检索增强生成（RAG）方法在事实一致性和知识检索任务中表现出色，但大规模RAG系统计算资源消耗高且易生成幻觉内容。我们提出了$	exttt{DRAG}$框架，通过从大规模语言模型（LLMs）向小规模语言模型（SLMs）蒸馏RAG知识，采用基于证据和知识图谱的蒸馏方法，在大幅减小模型规模和计算成本的同时保留关键事实知识。通过将小模型预测与知识图谱和排序证据对齐，$	exttt{DRAG}$有效缓解幻觉问题并提升事实准确性。我们展示了如何通过该框架缓解用户隐私风险，并引入了相应基准测试。实验表明，$	exttt{DRAG}$在多个基准测试中超越现有RAG方法，性能提升高达27.7%，同时保持高效可靠。这一框架为小规模LLMs的增强检索和生成能力部署提供了实用且资源高效的解决方案。

> Retrieval-Augmented Generation (RAG) methods have proven highly effective for tasks requiring factual consistency and robust knowledge retrieval. However, large-scale RAG systems consume significant computational resources and are prone to generating hallucinated content from Humans. In this work, we introduce $\texttt{DRAG}$, a novel framework for distilling RAG knowledge from large-scale Language Models (LLMs) into small LMs (SLMs). Our approach leverages evidence- and knowledge graph-based distillation, ensuring that the distilled model retains critical factual knowledge while significantly reducing model size and computational cost. By aligning the smaller model's predictions with a structured knowledge graph and ranked evidence, $\texttt{DRAG}$ effectively mitigates hallucinations and improves factual accuracy. We further present a case demonstrating how our framework mitigates user privacy risks and introduce a corresponding benchmark. Experimental evaluations on multiple benchmarks demonstrate that our method outperforms the prior competitive RAG methods like MiniRAG for SLMs by up to 27.7% using the same models, preserving high-level efficiency and reliability. With $\texttt{DRAG}$, we provide a practical and resource-efficient roadmap to deploying enhanced retrieval and generation capabilities in small-sized LLMs.

[Arxiv](https://arxiv.org/abs/2506.01954)