# FinMTEB: 金融领域大规模文本嵌入基准测试

发布时间：2025年02月15日

`LLM应用`

> FinMTEB: Finance Massive Text Embedding Benchmark

# 摘要

> 嵌入模型在各类NLP应用的信息表示和检索中发挥着关键作用。大型语言模型（LLMs）的最新进展进一步提升了嵌入模型的性能。尽管这些模型通常在通用数据集上进行基准测试，但实际应用需要领域特定的评估。

在本研究中，我们介绍了金融大规模文本嵌入基准（FinMTEB），这是一个专为金融领域设计的MTEB专用版本。FinMTEB包含7项任务的64个金融领域特定嵌入数据集，涵盖中文和英文的多种文本类型，如财经新闻、企业年报、ESG报告、监管文件和财报电话会议记录。我们还开发了一个适应金融领域的模型FinPersona-E5，使用基于角色的数据合成方法，覆盖多样化的金融嵌入任务用于训练。

通过对包括FinPersona-E5在内的15种嵌入模型进行广泛评估，我们得出三个关键发现：
（1）通用基准上的性能与金融领域任务的相关性有限；
（2）领域自适应模型在性能上始终优于通用模型；
（3）令人意外的是，简单的词袋（BoW）方法在金融语义文本相似度（STS）任务中优于复杂的密集嵌入，凸显了当前密集嵌入技术的局限性。

我们的工作为金融NLP应用建立了强大的评估框架，并为开发领域特定的嵌入模型提供了关键见解。

> Embedding models play a crucial role in representing and retrieving information across various NLP applications. Recent advances in large language models (LLMs) have further enhanced the performance of embedding models. While these models are often benchmarked on general-purpose datasets, real-world applications demand domain-specific evaluation. In this work, we introduce the Finance Massive Text Embedding Benchmark (FinMTEB), a specialized counterpart to MTEB designed for the financial domain. FinMTEB comprises 64 financial domain-specific embedding datasets across 7 tasks that cover diverse textual types in both Chinese and English, such as financial news articles, corporate annual reports, ESG reports, regulatory filings, and earnings call transcripts. We also develop a finance-adapted model, FinPersona-E5, using a persona-based data synthetic method to cover diverse financial embedding tasks for training. Through extensive evaluation of 15 embedding models, including FinPersona-E5, we show three key findings: (1) performance on general-purpose benchmarks shows limited correlation with financial domain tasks; (2) domain-adapted models consistently outperform their general-purpose counterparts; and (3) surprisingly, a simple Bag-of-Words (BoW) approach outperforms sophisticated dense embeddings in financial Semantic Textual Similarity (STS) tasks, underscoring current limitations in dense embedding techniques. Our work establishes a robust evaluation framework for financial NLP applications and provides crucial insights for developing domain-specific embedding models.

[Arxiv](https://arxiv.org/abs/2502.10990)