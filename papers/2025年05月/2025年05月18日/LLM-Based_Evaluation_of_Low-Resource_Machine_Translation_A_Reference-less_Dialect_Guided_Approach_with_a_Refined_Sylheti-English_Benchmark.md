# # 基于大语言模型的低资源机器翻译评估：无参考方言引导方法及优化的锡尔赫提-英语基准

发布时间：2025年05月18日

`LLM应用` `机器翻译`

> LLM-Based Evaluation of Low-Resource Machine Translation: A Reference-less Dialect Guided Approach with a Refined Sylheti-English Benchmark

# 摘要

> 低资源语言的机器翻译评估面临两大核心挑战：高质量参考译文的稀缺性，以及多方言语言中语言多样性与数据稀缺性的双重制约。传统方法在这些场景下往往力不从心。本研究提出了一种基于大型语言模型（LLMs）的全新解决方案，通过无参考评估技术突破了传统限制。我们对ONUBAD数据集进行了扩展，新增了孟语-英语句子对、机器翻译结果以及母语者标注的直接评估（DA）分数。为弥合方言间的词汇鸿沟，我们对分词器进行了优化，加入了大量方言特定术语。通过引入回归头实现精准的标量分数预测，并设计了创新的方言引导（DG）提示策略。实验结果表明，我们的方法在多个评估维度上均表现出色，特别是在斯皮尔曼相关性方面取得了+0.1083的显著提升。所有资源均已开源，详情请访问我们的GitHub仓库。

> Evaluating machine translation (MT) for low-resource languages poses a persistent challenge, primarily due to the limited availability of high quality reference translations. This issue is further exacerbated in languages with multiple dialects, where linguistic diversity and data scarcity hinder robust evaluation. Large Language Models (LLMs) present a promising solution through reference-free evaluation techniques; however, their effectiveness diminishes in the absence of dialect-specific context and tailored guidance. In this work, we propose a comprehensive framework that enhances LLM-based MT evaluation using a dialect guided approach. We extend the ONUBAD dataset by incorporating Sylheti-English sentence pairs, corresponding machine translations, and Direct Assessment (DA) scores annotated by native speakers. To address the vocabulary gap, we augment the tokenizer vocabulary with dialect-specific terms. We further introduce a regression head to enable scalar score prediction and design a dialect-guided (DG) prompting strategy. Our evaluation across multiple LLMs shows that the proposed pipeline consistently outperforms existing methods, achieving the highest gain of +0.1083 in Spearman correlation, along with improvements across other evaluation settings. The dataset and the code are available at https://github.com/180041123-Atiq/MTEonLowResourceLanguage.

[Arxiv](https://arxiv.org/abs/2505.12273)