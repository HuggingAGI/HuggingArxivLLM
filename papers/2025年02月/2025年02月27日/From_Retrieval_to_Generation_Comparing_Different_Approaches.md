# 从检索到生成：探索不同方法的优劣

发布时间：2025年02月27日

`LLM应用` `问答系统` `信息检索`

> From Retrieval to Generation: Comparing Different Approaches

# 摘要

> 知识密集型任务，尤其是开放域问答（ODQA）、文档重排序和增强型语言建模，需要在检索精度与生成灵活性之间找到平衡点。传统检索模型如BM25和密集段落检索（DPR）能够高效检索信息，但语义深度不足。生成模型如GPT-4-o则在上下文理解上更胜一筹，但在事实一致性方面仍有提升空间。本研究系统评估了基于检索、生成和混合的模型，重点关注它们在ODQA及相关增强型任务中的表现。

实验结果显示，密集检索器，尤其是DPR，在ODQA中表现优异，NQ数据集上的Top-1准确率达到50.17%。混合模型在BEIR数据集上的nDCG@10指标从BM25的43.42提升至52.59，展现了其在文档重排序方面的优势。此外，通过对WikiText-103的语言建模任务分析，发现基于检索的方法如BM25相比生成和混合方法能够实现更低的困惑度，凸显了其在增强型生成中的实用性。

通过提供详细对比和实用见解，我们揭示了不同方法在特定条件下的优势，为ODQA及相关知识密集型应用中检索、重排序和生成模型的未来优化提供了指导。

> Knowledge-intensive tasks, particularly open-domain question answering (ODQA), document reranking, and retrieval-augmented language modeling, require a balance between retrieval accuracy and generative flexibility. Traditional retrieval models such as BM25 and Dense Passage Retrieval (DPR), efficiently retrieve from large corpora but often lack semantic depth. Generative models like GPT-4-o provide richer contextual understanding but face challenges in maintaining factual consistency. In this work, we conduct a systematic evaluation of retrieval-based, generation-based, and hybrid models, with a primary focus on their performance in ODQA and related retrieval-augmented tasks. Our results show that dense retrievers, particularly DPR, achieve strong performance in ODQA with a top-1 accuracy of 50.17\% on NQ, while hybrid models improve nDCG@10 scores on BEIR from 43.42 (BM25) to 52.59, demonstrating their strength in document reranking. Additionally, we analyze language modeling tasks using WikiText-103, showing that retrieval-based approaches like BM25 achieve lower perplexity compared to generative and hybrid methods, highlighting their utility in retrieval-augmented generation. By providing detailed comparisons and practical insights into the conditions where each approach excels, we aim to facilitate future optimizations in retrieval, reranking, and generative models for ODQA and related knowledge-intensive applications.

[Arxiv](https://arxiv.org/abs/2502.20245)