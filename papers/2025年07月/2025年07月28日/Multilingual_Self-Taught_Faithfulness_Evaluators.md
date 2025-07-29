# # 多语言自训练忠实度评估器

发布时间：2025年07月28日

`LLM应用` `机器翻译`

> Multilingual Self-Taught Faithfulness Evaluators

# 摘要

> 随着大型语言模型（LLMs）的广泛应用，自动评估系统的需求日益增长，尤其是针对信息虚构这一挑战。尽管现有的忠实性评估方法颇具潜力，但它们多专注于英语，并且通常需要昂贵的人工标注数据来微调专业模型。随着LLMs在多语言环境中的应用增加，我们需要一种无需大量标注数据即可跨语言运行的准确忠实性评估器。本文提出了一种名为“多语言忠实性自我训练评估器”的框架，该框架仅从合成的多语言摘要数据中学习，并结合跨语言迁移学习。通过比较特定语言和混合语言微调方法的实验，我们发现LLM的一般语言能力与其在特定语言评估任务中的性能之间存在显著关联。与现有基线相比，我们的框架取得了显著改进，包括超越最先进的英语评估器和基于机器翻译的方法。

> The growing use of large language models (LLMs) has increased the need for automatic evaluation systems, particularly to address the challenge of information hallucination. Although existing faithfulness evaluation approaches have shown promise, they are predominantly English-focused and often require expensive human-labeled training data for fine-tuning specialized models. As LLMs see increased adoption in multilingual contexts, there is a need for accurate faithfulness evaluators that can operate across languages without extensive labeled data. This paper presents Self-Taught Evaluators for Multilingual Faithfulness, a framework that learns exclusively from synthetic multilingual summarization data while leveraging cross-lingual transfer learning. Through experiments comparing language-specific and mixed-language fine-tuning approaches, we demonstrate a consistent relationship between an LLM's general language capabilities and its performance in language-specific evaluation tasks. Our framework shows improvements over existing baselines, including state-of-the-art English evaluators and machine translation-based approaches.

[Arxiv](https://arxiv.org/abs/2507.20752)