# PRGB基准测试：一种用于检索增强生成评测的鲁棒占位符辅助算法

发布时间：2025年07月23日

`RAG` `问答系统` `大型语言模型`

> PRGB Benchmark: A Robust Placeholder-Assisted Algorithm for Benchmarking Retrieval-Augmented Generation

# 摘要

> 检索增强生成（RAG）通过整合外部知识提升大型语言模型（LLM）的能力，其中LLM结合给定查询与检索文档生成回复的能力是关键所在。然而，现有基准主要关注整体RAG系统性能，却很少评估LLM的特定能力。当前基准虽然强调噪声鲁棒性等广泛方面，但缺乏系统化、细致化的文档利用评估框架。为此，我们推出	extit{Placeholder-RAG-Benchmark}，一个多层级细粒度基准，着重以下递进维度：（1）多层级过滤能力，（2）结合能力，（3）参考推理能力。为了更深入地理解LLM在RAG系统中的作用，我们提出了一种基于占位符的创新方法，以分离LLM参数化知识与外部知识的贡献。实验表明，代表性LLM在RAG系统的生成能力方面存在局限性，尤其是在错误恢复和上下文忠实性方面。我们的基准为开发更可靠、高效的RAG系统提供了可复现的框架。我们的代码可在https://github.com/Alipay-Med/PRGB获取。

> Retrieval-Augmented Generation (RAG) enhances large language models (LLMs) by integrating external knowledge, where the LLM's ability to generate responses based on the combination of a given query and retrieved documents is crucial. However, most benchmarks focus on overall RAG system performance, rarely assessing LLM-specific capabilities. Current benchmarks emphasize broad aspects such as noise robustness, but lack a systematic and granular evaluation framework on document utilization. To this end, we introduce \textit{Placeholder-RAG-Benchmark}, a multi-level fine-grained benchmark, emphasizing the following progressive dimensions: (1) multi-level filtering abilities, (2) combination abilities, and (3) reference reasoning. To provide a more nuanced understanding of LLMs' roles in RAG systems, we formulate an innovative placeholder-based approach to decouple the contributions of the LLM's parametric knowledge and the external knowledge. Experiments demonstrate the limitations of representative LLMs in the RAG system's generation capabilities, particularly in error resilience and context faithfulness. Our benchmark provides a reproducible framework for developing more reliable and efficient RAG systems. Our code is available in https://github.com/Alipay-Med/PRGB.

[Arxiv](https://arxiv.org/abs/2507.22927)