# # DRAGON: 新闻领域的动态 RAG 基准测试

发布时间：2025年07月08日

`RAG` `信息检索`

> DRAGON: Dynamic RAG Benchmark On News

# 摘要

> 检索增强生成（RAG）是一种广受欢迎的方法，通过在推理阶段整合外部知识来提升大型语言模型（LLMs）的事实准确性。尽管英语领域已有多个RAG基准测试，但针对俄语等其他语言的评估资源仍然匮乏且静态，未能捕捉到现实世界部署中动态变化的特性。
    
    在这项研究中，我们推出了DRAGON（基于新闻的动态RAG基准），这是首个用于在不断更新的俄语新闻语料库上评估RAG系统的动态基准。DRAGON建立在一个定期更新的俄语新闻和公共文档语料库之上，并支持对检索器和生成器组件的全面评估。借助从语料库构建的知识图谱，我们实现了自动问题生成，并能够提取四种与不同子图模式相匹配的核心问题类型。我们还发布了一个完整的评估框架，其中包括自动问题生成管道、评估脚本（这些脚本可能适用于其他语言和多语言环境）以及基准数据集。此外，我们还启动了一个公开排行榜，以鼓励社区参与和对比分析。

> Retrieval-Augmented Generation (RAG) is a widely adopted approach for improving the factuality of large language models (LLMs) by incorporating external knowledge at inference time. Although there exist multiple RAG benchmarks for English, evaluation resources for other languages, including Russian, remain scarce and static, failing to capture the dynamic nature of real-world deployments.
  In this work, we present DRAGON (Dynamic RAG Benchmark On News), the first dynamic benchmark for evaluating RAG systems in Russian on a changing news corpora. DRAGON is built upon a regularly updated corpus of Russian news and public documents and supports comprehensive evaluation of both the retriever and generator components. Question generation is performed automatically with the use of Knowledge Graph constructed from the corpus and enables the extraction of four core question types aligned with distinct subgraph patterns. We release a complete evaluation framework comprising the pipeline for automatic question generation, evaluation scripts, which are potentially reusable for other languages and multilingual settings, and benchmark data. We also launch a public leaderboard to encourage community participation and comparison.

[Arxiv](https://arxiv.org/abs/2507.05713)