# RAGtifier：全面评估最新RAG系统在SIGIR LiveRAG竞赛中的生成方法

发布时间：2025年06月17日

`RAG` `问答系统` `信息检索`

> RAGtifier: Evaluating RAG Generation Approaches of State-of-the-Art RAG Systems for the SIGIR LiveRAG Competition

# 摘要

> 检索增强生成（RAG）通过整合大型语言模型（LLMs）内部的参数化知识与外部非参数化来源，显著提升了模型的事实准确性并减少了生成中的错误信息。在LiveRAG 2025挑战赛中，我们探索了多种RAG解决方案，目标是在DataMorgana的问答对上实现最佳表现，这些问答对涵盖了单跳和多跳问题。比赛提供了基于Fineweb 10BT数据集的稀疏OpenSearch和密集Pinecone索引，要求参赛模型的参数量不超过100亿，并使用Falcon-3-10B生成最终答案。由评测LLM和人工评估员组成的评审团队对提交的答案进行了全面评估。通过在挑战条件下深入探索不同的检索器组合和RAG解决方案，我们最终采用了InstructRAG与Pinecone检索器和BGE重排序器的组合方案。在SIGIR 2025 LiveRAG挑战中，我们的方案以1.13的正确性评分和0.55的忠实性评分，成功获得第四名的优异成绩。

> Retrieval-Augmented Generation (RAG) enriches Large Language Models (LLMs) by combining their internal, parametric knowledge with external, non-parametric sources, with the goal of improving factual correctness and minimizing hallucinations. The LiveRAG 2025 challenge explores RAG solutions to maximize accuracy on DataMorgana's QA pairs, which are composed of single-hop and multi-hop questions. The challenge provides access to sparse OpenSearch and dense Pinecone indices of the Fineweb 10BT dataset. It restricts model use to LLMs with up to 10B parameters and final answer generation with Falcon-3-10B. A judge-LLM assesses the submitted answers along with human evaluators. By exploring distinct retriever combinations and RAG solutions under the challenge conditions, our final solution emerged using InstructRAG in combination with a Pinecone retriever and a BGE reranker. Our solution achieved a correctness score of 1.13 and a faithfulness score of 0.55, placing fourth in the SIGIR 2025 LiveRAG Challenge.

[Arxiv](https://arxiv.org/abs/2506.14412)