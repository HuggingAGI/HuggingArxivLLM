# HANRAG：启发式精准抗噪声检索增强生成面向多跳问答

发布时间：2025年09月08日

`RAG` `基础理论`

> HANRAG: Heuristic Accurate Noise-resistant Retrieval-Augmented Generation for Multi-hop Question Answering

# 摘要

> 检索增强生成（RAG）方法通过整合信息检索（IR）技术与大型语言模型（LLMs），有效增强了问答系统与对话生成任务的性能。该策略从外部知识库检索信息，以增强生成模型的响应能力，并已取得一定成效。然而，当前RAG方法在处理多跳查询时仍面临诸多挑战：例如，部分方法过度依赖迭代检索，在复合查询上浪费了过多检索步骤；此外，若使用原始复杂查询进行检索，可能无法捕捉与特定子查询相关的内容，导致检索内容存在噪音。若噪音未得到有效处理，还可能引发噪音累积问题。为解决这些问题，我们提出了HANRAG——一个基于启发式的新型框架，旨在高效应对不同复杂度的问题。在强大的揭示器驱动下，HANRAG能够对查询进行路由、分解为子查询，并过滤检索文档中的噪音。这一设计增强了系统的适应性与抗噪音能力，使其具备处理多样化查询的强大能力。我们在多个基准测试中，将该框架与行业内其他领先方法进行了对比。结果显示，该框架在单跳与多跳问答任务中均表现更优。

> The Retrieval-Augmented Generation (RAG) approach enhances question-answering systems and dialogue generation tasks by integrating information retrieval (IR) technologies with large language models (LLMs). This strategy, which retrieves information from external knowledge bases to bolster the response capabilities of generative models, has achieved certain successes. However, current RAG methods still face numerous challenges when dealing with multi-hop queries. For instance, some approaches overly rely on iterative retrieval, wasting too many retrieval steps on compound queries. Additionally, using the original complex query for retrieval may fail to capture content relevant to specific sub-queries, resulting in noisy retrieved content. If the noise is not managed, it can lead to the problem of noise accumulation. To address these issues, we introduce HANRAG, a novel heuristic-based framework designed to efficiently tackle problems of varying complexity. Driven by a powerful revelator, HANRAG routes queries, decomposes them into sub-queries, and filters noise from retrieved documents. This enhances the system's adaptability and noise resistance, making it highly capable of handling diverse queries. We compare the proposed framework against other leading industry methods across various benchmarks. The results demonstrate that our framework obtains superior performance in both single-hop and multi-hop question-answering tasks.

[Arxiv](https://arxiv.org/abs/2509.09713)