# RabakBench：通过扩展人工标注，打造面向低资源语言的本地化多语言安全基准

发布时间：2025年07月08日

`LLM应用` `语言处理` `多语言处理`

> RabakBench: Scaling Human Annotations to Construct Localized Multilingual Safety Benchmarks for Low-Resource Languages

# 摘要

> 大型语言模型（LLMs）及其安全分类器在资源匮乏语言上的表现通常不尽如人意，主要由于训练数据和评估基准的限制。本文介绍了RabakBench，这是一个针对新加坡独特语言环境的新多语言安全基准，涵盖新加坡英语、中文、马来语和泰米尔语。RabakBench通过一个可扩展的三阶段管道构建而成：(i) 生成 - 通过LLM驱动的红队方法增强真实新加坡英语网络内容以生成对抗性示例；(ii) 标注 - 使用与人工判断一致的多数投票LLM标注器进行半自动多标签安全标注；(iii) 翻译 - 保持语言细微差别和毒性跨语言一致的高保真翻译。最终数据集包含四个语言和六个细粒度安全类别（带严重程度级别）的5,000多个安全标注示例。对11个流行的开源和闭源护栏分类器的评估显示性能显著下降。RabakBench不仅使东南亚多语言环境下的安全评估更加稳健，还为在资源匮乏环境中构建本地化安全数据集提供了可复现的框架。该基准数据集（包括人工验证的翻译）和评估代码现已公开可用。

> Large language models (LLMs) and their safety classifiers often perform poorly on low-resource languages due to limited training data and evaluation benchmarks. This paper introduces RabakBench, a new multilingual safety benchmark localized to Singapore's unique linguistic context, covering Singlish, Chinese, Malay, and Tamil. RabakBench is constructed through a scalable three-stage pipeline: (i) Generate - adversarial example generation by augmenting real Singlish web content with LLM-driven red teaming; (ii) Label - semi-automated multi-label safety annotation using majority-voted LLM labelers aligned with human judgments; and (iii) Translate - high-fidelity translation preserving linguistic nuance and toxicity across languages. The final dataset comprises over 5,000 safety-labeled examples across four languages and six fine-grained safety categories with severity levels. Evaluations of 11 popular open-source and closed-source guardrail classifiers reveal significant performance degradation. RabakBench not only enables robust safety evaluation in Southeast Asian multilingual settings but also offers a reproducible framework for building localized safety datasets in low-resource environments. The benchmark dataset, including the human-verified translations, and evaluation code are publicly available.

[Arxiv](https://arxiv.org/abs/2507.05980)