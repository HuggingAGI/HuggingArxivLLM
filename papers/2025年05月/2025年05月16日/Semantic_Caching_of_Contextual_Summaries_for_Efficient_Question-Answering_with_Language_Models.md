# # 上下文摘要的语义缓存，提升语言模型问答效率

发布时间：2025年05月16日

`LLM应用` `边缘计算` `云计算`

> Semantic Caching of Contextual Summaries for Efficient Question-Answering with Language Models

# 摘要

> 大型语言模型（LLMs）正被广泛应用于边缘和云平台，支持实时问答和检索增强生成。然而，处理长上下文在分布式系统中会产生高昂的计算开销、内存占用和网络带宽消耗。本文提出了一种新颖的语义缓存方法，用于存储和重用中间上下文摘要，实现类似查询间的信息高效复用，从而提升基于LLM的问答流程效率。我们在NaturalQuestions、TriviaQA和合成的ArXiv数据集上的实验证明，相比完整文档处理，该方法可减少高达50-60%的冗余计算，同时保持相当的回答准确性。这种方法在计算成本和响应质量之间实现了平衡，这对于实时AI助手至关重要。


> Large Language Models (LLMs) are increasingly deployed across edge and cloud platforms for real-time question-answering and retrieval-augmented generation. However, processing lengthy contexts in distributed systems incurs high computational overhead, memory usage, and network bandwidth. This paper introduces a novel semantic caching approach for storing and reusing intermediate contextual summaries, enabling efficient information reuse across similar queries in LLM-based QA workflows. Our method reduces redundant computations by up to 50-60% while maintaining answer accuracy comparable to full document processing, as demonstrated on NaturalQuestions, TriviaQA, and a synthetic ArXiv dataset. This approach balances computational cost and response quality, critical for real-time AI assistants.

[Arxiv](https://arxiv.org/abs/2505.11271)