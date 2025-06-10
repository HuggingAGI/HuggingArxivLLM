# 优化阿拉伯语RAG管道：核心组件的系统性分析

发布时间：2025年05月31日

`RAG` `信息检索`

> Optimizing RAG Pipelines for Arabic: A Systematic Analysis of Core Components

# 摘要

> 检索增强生成（RAG）作为一种强大的架构，结合了检索系统的精准性和大型语言模型的流畅性。尽管已有研究探讨了高资源语言的RAG流水线，但针对阿拉伯语的RAG组件优化仍鲜有探索。本研究通过RAGAS框架，对包括分块策略、嵌入模型、重排器和语言模型在内的先进RAG组件，在多样化的阿拉伯语数据集上进行了全面的实证评估。我们系统性地比较了四个核心指标：上下文精准度、上下文召回率、答案忠实度和答案相关性。实验结果表明，基于句子感知的分块策略优于其他所有分段方法，而BGE-M3和Multilingual-E5-large则是最有效的嵌入模型。引入重排器（bge-reranker-v2-m3）显著提升了复杂数据集中的答案忠实度，同时Aya-8B在生成质量上超越了StableLM。这些发现为构建高质量的阿拉伯语RAG流水线提供了关键见解，并为不同文档类型下选择最优组件提供了实用指南。

> Retrieval-Augmented Generation (RAG) has emerged as a powerful architecture for combining the precision of retrieval systems with the fluency of large language models. While several studies have investigated RAG pipelines for high-resource languages, the optimization of RAG components for Arabic remains underexplored. This study presents a comprehensive empirical evaluation of state-of-the-art RAG components-including chunking strategies, embedding models, rerankers, and language models-across a diverse set of Arabic datasets. Using the RAGAS framework, we systematically compare performance across four core metrics: context precision, context recall, answer faithfulness, and answer relevancy. Our experiments demonstrate that sentence-aware chunking outperforms all other segmentation methods, while BGE-M3 and Multilingual-E5-large emerge as the most effective embedding models. The inclusion of a reranker (bge-reranker-v2-m3) significantly boosts faithfulness in complex datasets, and Aya-8B surpasses StableLM in generation quality. These findings provide critical insights for building high-quality Arabic RAG pipelines and offer practical guidelines for selecting optimal components across different document types.

[Arxiv](https://arxiv.org/abs/2506.06339)