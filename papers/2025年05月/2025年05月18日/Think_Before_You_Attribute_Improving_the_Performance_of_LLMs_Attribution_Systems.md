# 思考后再归因：优化大语言模型归因系统的性能表现

发布时间：2025年05月18日

`RAG` `归属系统`

> Think Before You Attribute: Improving the Performance of LLMs Attribution Systems

# 摘要

> 大型语言模型（LLMs）正广泛应用于科学领域，但可信输出的缺失仍制约着其应用。当前LLMs常常生成答案却缺乏可靠的来源归属，甚至给出错误归属，这为科学和高风险场景中的应用设置了障碍。为了使归属系统可靠，需具备高准确性和简短的数据检索能力，即归因于文档中的一句话。我们为RAG系统提出了一种句子级别的预归因步骤，将句子分为三类：不可归因、归因于一个引用，以及归因于多个引用。通过在归因前分离句子，可以根据类型选择合适的归因方法，或跳过归因。我们的研究表明，分类器非常适合这一任务。本研究提出了一种预归因步骤，以降低归因复杂度，提供了一个干净的HAGRID数据集，并提供了一个开箱即用的端到端归因系统。

> Large Language Models (LLMs) are increasingly applied in various science domains, yet their broader adoption remains constrained by a critical challenge: the lack of trustworthy, verifiable outputs. Current LLMs often generate answers without reliable source attribution, or worse, with incorrect attributions, posing a barrier to their use in scientific and high-stakes settings, where traceability and accountability are non-negotiable. To be reliable, attribution systems need high accuracy and retrieve data with short lengths, i.e., attribute to a sentence within a document rather than a whole document. We propose a sentence-level pre-attribution step for Retrieve-Augmented Generation (RAG) systems that classify sentences into three categories: not attributable, attributable to a single quote, and attributable to multiple quotes. By separating sentences before attribution, a proper attribution method can be selected for the type of sentence, or the attribution can be skipped altogether. Our results indicate that classifiers are well-suited for this task. In this work, we propose a pre-attribution step to reduce the computational complexity of attribution, provide a clean version of the HAGRID dataset, and provide an end-to-end attribution system that works out of the box.

[Arxiv](https://arxiv.org/abs/2505.12621)