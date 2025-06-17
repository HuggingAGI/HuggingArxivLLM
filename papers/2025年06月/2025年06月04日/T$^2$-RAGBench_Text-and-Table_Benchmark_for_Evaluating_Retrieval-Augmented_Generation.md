# T平方-RAG基准测试：用于评估检索增强生成的文本与表格基准

发布时间：2025年06月04日

`RAG` `文本和表格数据处理`

> T$^2$-RAGBench: Text-and-Table Benchmark for Evaluating Retrieval-Augmented Generation

# 摘要

> 尽管大多数财务文件包含文本和表格信息的组合，但要有效访问和推理此类内容以执行复杂的数值任务，强大的检索增强生成（RAG）系统至关重要。本文介绍了T$^2$-RAGBench，这是一个包含32,908个问题-上下文-答案三元组的基准测试，旨在评估RAG方法在真实世界财务数据上的表现。与通常在Oracle上下文设置下运行的典型问答数据集不同，其中相关上下文会明确提供，T$^2$-RAGBench要求模型首先检索正确的上下文，然后再进行数值推理。

现有涉及文本和表格的问答数据集通常包含上下文相关的问题，这可能会根据提供的上下文产生多个正确答案。为了解决这一问题，我们将这些数据集转换为上下文无关的格式，从而实现可靠的RAG评估。我们对流行的RAG方法进行了全面评估。我们的分析发现，结合稠密和稀疏向量的Hybrid BM25技术是处理文本和表格数据最有效的方法。然而，实验结果表明，即使对于最先进的LLMs和RAG方法，T$^2$-RAGBench仍然具有挑战性。进一步的消融研究探讨了嵌入模型和语料库大小对检索性能的影响。T$^2$-RAGBench为现有RAG方法在文本和表格数据上的应用提供了一个现实且严格的基准。代码和数据集均可在线获取。

> While most financial documents contain a combination of textual and tabular information, robust Retrieval-Augmented Generation (RAG) systems are essential for effectively accessing and reasoning over such content to perform complex numerical tasks. This paper introduces T$^2$-RAGBench, a benchmark comprising 32,908 question-context-answer triples, designed to evaluate RAG methods on real-world financial data. Unlike typical QA datasets that operate under Oracle-context settings, where the relevant context is explicitly provided, T$^2$-RAGBench challenges models to first retrieve the correct context before conducting numerical reasoning. Existing QA datasets involving text and tables typically contain context-dependent questions, which may yield multiple correct answers depending on the provided context. To address this, we transform these datasets into a context-independent format, enabling reliable RAG evaluation. We conduct a comprehensive evaluation of popular RAG methods. Our analysis identifies Hybrid BM25, a technique that combines dense and sparse vectors, as the most effective approach for text-and-table data. However, results demonstrate that T$^2$-RAGBench remains challenging even for SOTA LLMs and RAG methods. Further ablation studies examine the impact of embedding models and corpus size on retrieval performance. T$^2$-RAGBench provides a realistic and rigorous benchmark for existing RAG methods on text-and-table data. Code and dataset are available online.

[Arxiv](https://arxiv.org/abs/2506.12071)