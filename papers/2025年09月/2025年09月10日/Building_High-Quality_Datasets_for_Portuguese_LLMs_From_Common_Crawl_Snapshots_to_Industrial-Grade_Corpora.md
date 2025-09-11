# 构建葡萄牙语大型语言模型（LLMs）高质量数据集：从Common Crawl快照到工业级语料库

发布时间：2025年09月10日

`LLM应用` `基础理论`

> Building High-Quality Datasets for Portuguese LLMs: From Common Crawl Snapshots to Industrial-Grade Corpora

# 摘要

> 大型语言模型（LLMs）的性能很大程度上取决于训练数据的质量和构成。现有研究多聚焦于英语，而对于如何构建其他语言的高效训练语料库，仍存在认知空白。我们探索了构建基于网络的LLM语料库的可扩展方法，并将其应用于葡萄牙语，构建出包含1200亿token的新语料库，性能可与工业级语料库媲美。通过持续预训练框架，我们研究了在将英语预训练模型迁移至其他语言时，不同数据选择和预处理策略对LLM性能的影响。结果表明，特定语言过滤管道（包括教育、科学、技术、工程和数学（STEM）领域内容及有毒信息的分类器）具有重要价值。我们发现，让模型适应目标语言能显著提升性能，这进一步凸显了高质量、特定语言数据的关键作用。尽管本案例研究以葡萄牙语为对象，但我们的方法可推广至其他语言，为多语言LLM的开发提供了有益启示。

> The performance of large language models (LLMs) is deeply influenced by the quality and composition of their training data. While much of the existing work has centered on English, there remains a gap in understanding how to construct effective training corpora for other languages. We explore scalable methods for building web-based corpora for LLMs. We apply them to build a new 120B token corpus in Portuguese that achieves competitive results to an industrial-grade corpus. Using a continual pretraining setup, we study how different data selection and preprocessing strategies affect LLM performance when transitioning a model originally trained in English to another language. Our findings demonstrate the value of language-specific filtering pipelines, including classifiers for education, science, technology, engineering, and mathematics (STEM), as well as toxic content. We show that adapting a model to the target language leads to performance improvements, reinforcing the importance of high-quality, language-specific data. While our case study focuses on Portuguese, our methods are applicable to other languages, offering insights for multilingual LLM development.

[Arxiv](https://arxiv.org/abs/2509.08824)