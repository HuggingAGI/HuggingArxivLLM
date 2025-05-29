# # 长文档检索中的分块大小再思考：多数据集分析

发布时间：2025年05月27日

`RAG` `信息检索`

> Rethinking Chunk Size For Long-Document Retrieval: A Multi-Dataset Analysis

# 摘要

> 分块是RAG系统中不可或缺的预处理步骤，对检索效果有着重要影响。本研究系统评估了固定大小的分块策略及其对检索性能的影响，使用了多种嵌入模型进行分析。实验结果表明，分块大小对不同数据集的检索效果至关重要：较小的分块（64-128个token）适合简洁事实性的答案，而较大的分块（512-1024个token）则更适用于需要广泛上下文理解的场景。我们还发现不同嵌入模型对分块的敏感度各异：Stella模型擅长利用较大分块进行长距离检索，而Snowflake则在小分块上表现出色，擅长细粒度的实体匹配。研究结果强调了分块大小、嵌入模型与数据集特性之间的权衡关系，凸显了提升分块质量度量和构建更全面数据集的重要性，以推动长文档信息检索中基于分块的检索技术发展。

> Chunking is a crucial preprocessing step in retrieval-augmented generation (RAG) systems, significantly impacting retrieval effectiveness across diverse datasets. In this study, we systematically evaluate fixed-size chunking strategies and their influence on retrieval performance using multiple embedding models. Our experiments, conducted on both short-form and long-form datasets, reveal that chunk size plays a critical role in retrieval effectiveness -- smaller chunks (64-128 tokens) are optimal for datasets with concise, fact-based answers, whereas larger chunks (512-1024 tokens) improve retrieval in datasets requiring broader contextual understanding. We also analyze the impact of chunking on different embedding models, finding that they exhibit distinct chunking sensitivities. While models like Stella benefit from larger chunks, leveraging global context for long-range retrieval, Snowflake performs better with smaller chunks, excelling at fine-grained, entity-based matching. Our results underscore the trade-offs between chunk size, embedding models, and dataset characteristics, emphasizing the need for improved chunk quality measures, and more comprehensive datasets to advance chunk-based retrieval in long-document Information Retrieval (IR).

[Arxiv](https://arxiv.org/abs/2505.21700)