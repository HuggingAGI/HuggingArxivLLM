# Sadeed：借助小型语言模型提升阿拉伯语标点符号

发布时间：2025年04月30日

`LLM应用` `语言处理` `机器翻译`

> Sadeed: Advancing Arabic Diacritization Through Small Language Model

# 摘要

> 阿拉伯语文本断句化一直是自然语言处理中的难题，这主要源于其丰富的形态学特征。本文中，我们介绍了 Sadeed，这是一种基于 Kuwain 1.5B Hennara et al. [2025] 适应而来的解码器-only 语言模型的创新方法，该模型最初是针对多样化的阿拉伯语语料库进行训练的紧凑型模型。通过在精心策划的高质量断句化数据集上进行微调，这些数据集是通过严格的清洗和规范化管道构建而成，Sadeed 在仅使用适度计算资源的情况下，表现不仅与专有大型语言模型相媲美，还在类似领域的传统模型中表现更优。此外，我们还指出了当前阿拉伯语断句化基准测试实践中存在的关键限制。为了解决这些问题，我们引入了 SadeedDiac-25，这是一个新的基准测试，旨在实现更公平、更全面的跨多种文本类型和复杂度水平的评估。Sadeed 和 SadeedDiac-25 一起，为推动阿拉伯语 NLP 应用（包括机器翻译、文本转语音和语言学习工具）的发展提供了坚实的基础。

> Arabic text diacritization remains a persistent challenge in natural language processing due to the language's morphological richness. In this paper, we introduce Sadeed, a novel approach based on a fine-tuned decoder-only language model adapted from Kuwain 1.5B Hennara et al. [2025], a compact model originally trained on diverse Arabic corpora. Sadeed is fine-tuned on carefully curated, high-quality diacritized datasets, constructed through a rigorous data-cleaning and normalization pipeline. Despite utilizing modest computational resources, Sadeed achieves competitive results compared to proprietary large language models and outperforms traditional models trained on similar domains. Additionally, we highlight key limitations in current benchmarking practices for Arabic diacritization. To address these issues, we introduce SadeedDiac-25, a new benchmark designed to enable fairer and more comprehensive evaluation across diverse text genres and complexity levels. Together, Sadeed and SadeedDiac-25 provide a robust foundation for advancing Arabic NLP applications, including machine translation, text-to-speech, and language learning tools.

[Arxiv](https://arxiv.org/abs/2504.21635)