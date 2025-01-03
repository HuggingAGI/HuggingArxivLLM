# 检索增强生成的不可回答性评估

发布时间：2024年12月16日

`RAG

理由：这篇论文主要讨论的是RAG（Retrieval-Augmented Generation）系统的评估框架，特别是针对处理不可回答查询的能力。论文提出了一个新的评估框架UAEval4RAG，并对其进行了实验和分析。因此，这篇论文应归类为RAG。` `信息检索` `问答系统`

> Unanswerability Evaluation for Retreival Augmented Generation

# 摘要

> 现有的RAG系统评估框架主要针对可回答的查询，却忽略了拒绝不可回答请求的重要性。本文提出的UAEval4RAG框架，旨在评估RAG系统处理不可回答查询的能力。我们定义了六类不可回答的查询，UAEval4RAG能够自动生成多样且具有挑战性的查询，并通过未回答率和可接受率指标进行评估。我们对多种RAG组件进行了实验，包括检索模型、重写方法、重排序器、语言模型和提示策略，揭示了系统性能中的隐藏权衡。研究结果表明，组件选择和提示设计在优化RAG系统、平衡可回答查询的准确性与高拒绝率不可回答查询方面至关重要。UAEval4RAG为开发更强大、可靠的RAG系统提供了宝贵的工具和见解。

> Existing evaluation frameworks for retrieval-augmented generation (RAG) systems focus on answerable queries, but they overlook the importance of appropriately rejecting unanswerable requests. In this paper, we introduce UAEval4RAG, a framework designed to evaluate whether RAG systems can handle unanswerable queries effectively. We define a taxonomy with six unanswerable categories, and UAEval4RAG automatically synthesizes diverse and challenging queries for any given knowledge base with unanswered ratio and acceptable ratio metrics. We conduct experiments with various RAG components, including retrieval models, rewriting methods, rerankers, language models, and prompting strategies, and reveal hidden trade-offs in performance of RAG systems. Our findings highlight the critical role of component selection and prompt design in optimizing RAG systems to balance the accuracy of answerable queries with high rejection rates of unanswerable ones. UAEval4RAG provides valuable insights and tools for developing more robust and reliable RAG systems.

[Arxiv](https://arxiv.org/abs/2412.12300)