# 思考归因之前：优化LLMs归因系统的性能

发布时间：2025年05月18日

`RAG` `可信度`

> Think Before You Attribute: Improving the Performance of LLMs Attribution Systems

# 摘要

> 大型语言模型（LLMs）在科学领域的应用日益广泛，但它们的普及仍面临一个关键挑战：输出的可信度和可验证性不足。现有LLMs常生成缺乏可靠来源归属的回答，甚至可能带有错误归属，这在科学和高风险场景中是不可接受的，因为可追溯性和问责制至关重要。为了实现可靠的归属，系统需要高精度并检索短长度的数据，即归因于文档中的一句话，而非整个文档。我们为检索增强生成（RAG）系统设计了一种基于句子级别的预归属步骤，将句子分类为不可归属、可归属到单一引用和可归属到多个引用。通过在归属前分离句子，可以根据句子类型选择合适的归属方法，或完全跳过归属过程。我们的研究表明，分类器非常适合这一任务。在此工作中，我们提出了一种预归属步骤以降低归属的计算复杂度，提供了一个干净版本的HAGRID数据集，并提供了一个开箱即用的端到端归属系统。

> Large Language Models (LLMs) are increasingly applied in various science domains, yet their broader adoption remains constrained by a critical challenge: the lack of trustworthy, verifiable outputs. Current LLMs often generate answers without reliable source attribution, or worse, with incorrect attributions, posing a barrier to their use in scientific and high-stakes settings, where traceability and accountability are non-negotiable. To be reliable, attribution systems need high accuracy and retrieve data with short lengths, i.e., attribute to a sentence within a document rather than a whole document. We propose a sentence-level pre-attribution step for Retrieve-Augmented Generation (RAG) systems that classify sentences into three categories: not attributable, attributable to a single quote, and attributable to multiple quotes. By separating sentences before attribution, a proper attribution method can be selected for the type of sentence, or the attribution can be skipped altogether. Our results indicate that classifiers are well-suited for this task. In this work, we propose a pre-attribution step to reduce the computational complexity of attribution, provide a clean version of the HAGRID dataset, and provide an end-to-end attribution system that works out of the box.

[Arxiv](https://arxiv.org/abs/2505.12621)