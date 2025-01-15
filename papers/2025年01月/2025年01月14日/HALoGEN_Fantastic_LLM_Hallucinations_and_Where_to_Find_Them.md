# HALoGEN: 探索LLM幻觉的奇妙世界

发布时间：2025年01月14日

`LLM理论

理由：这篇论文主要讨论了生成式大型语言模型（LLMs）的幻觉问题，并提出了一个名为HALoGEN的基准来测量和分类这些幻觉。论文的核心在于对LLM生成文本的准确性和可信度进行理论分析，并提出了新的错误分类方法。这些内容属于对LLM的理论研究和分析，因此归类为LLM理论。` `人工智能`

> HALoGEN: Fantastic LLM Hallucinations and Where to Find Them

# 摘要

> 尽管生成式大型语言模型（LLMs）在生成高质量和流畅文本方面表现出色，但它们也会产生幻觉：即与既定世界知识或提供的输入上下文不符的陈述。然而，测量幻觉具有挑战性，因为让人类即时验证模型生成既昂贵又耗时。为此，我们发布了HALoGEN，一个全面的幻觉基准，包括：（1）10,923个生成模型的提示，涵盖编程、科学归因和摘要等九个领域，（2）每个用例的自动高精度验证器，将LLM生成分解为原子单元，并根据高质量知识源验证每个单元。我们使用这个框架评估了来自14个语言模型的约150,000个生成，发现即使表现最好的模型也充满了幻觉（有时高达86%的生成原子事实，具体取决于领域）。我们进一步定义了一种新的LLM幻觉错误分类，基于它们是否可能源于训练数据的错误回忆（A类错误），或训练数据中的错误知识（B类错误），或是捏造（C类错误）。我们希望我们的框架为系统研究生成模型为何产生幻觉提供基础，并推动可信赖的大型语言模型的发展。

> Despite their impressive ability to generate high-quality and fluent text, generative large language models (LLMs) also produce hallucinations: statements that are misaligned with established world knowledge or provided input context. However, measuring hallucination can be challenging, as having humans verify model generations on-the-fly is both expensive and time-consuming. In this work, we release HALoGEN, a comprehensive hallucination benchmark consisting of: (1) 10,923 prompts for generative models spanning nine domains including programming, scientific attribution, and summarization, and (2) automatic high-precision verifiers for each use case that decompose LLM generations into atomic units, and verify each unit against a high-quality knowledge source. We use this framework to evaluate ~150,000 generations from 14 language models, finding that even the best-performing models are riddled with hallucinations (sometimes up to 86% of generated atomic facts depending on the domain). We further define a novel error classification for LLM hallucinations based on whether they likely stem from incorrect recollection of training data (Type A errors), or incorrect knowledge in training data (Type B errors), or are fabrication (Type C errors). We hope our framework provides a foundation to enable the principled study of why generative models hallucinate, and advances the development of trustworthy large language models.

[Arxiv](https://arxiv.org/abs/2501.08292)