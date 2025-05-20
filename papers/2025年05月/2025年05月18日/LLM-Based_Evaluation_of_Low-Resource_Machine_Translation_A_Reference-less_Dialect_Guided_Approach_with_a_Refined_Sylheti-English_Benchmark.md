# 基于大型语言模型的低资源机器翻译评估：无参考方言引导方法及精炼的 Sylheti-英语基准

发布时间：2025年05月18日

`LLM应用` `机器翻译`

> LLM-Based Evaluation of Low-Resource Machine Translation: A Reference-less Dialect Guided Approach with a Refined Sylheti-English Benchmark

# 摘要

> 低资源语言机器翻译的评估一直是个难题，主要原因在于高质量参考译文的匮乏。在多方言语言中，这一问题更为突出，因为语言多样性和数据稀缺性阻碍了稳健的评估。大型语言模型 (LLMs) 通过无参考评估技术提供了一个有前景的解决方案，但在缺乏方言特定语境和定制化指导的情况下，其效果会大打折扣。我们提出了一种全面的框架，通过方言引导的方法来增强基于 LLM 的 MT 评估。我们扩展了 ONUBAD 数据集，加入了孟语-英语句子对、对应的机器翻译以及由母语者标注的直接评估 (DA) 分数。为了解决词汇差距问题，我们扩展了分词器词汇表，加入了方言特定术语。我们还引入了一个回归头来实现标量分数预测，并设计了一种方言引导 (DG) 提示策略。我们对多个 LLM 的评估表明，所提出的流水线始终优于现有方法，在斯皮尔曼相关性方面获得了 +0.1083 的最高提升，并在其他评估设置中也取得了改进。数据集和代码可在 https://github.com/180041123-Atiq/MTEonLowResourceLanguage 获取。

> Evaluating machine translation (MT) for low-resource languages poses a persistent challenge, primarily due to the limited availability of high quality reference translations. This issue is further exacerbated in languages with multiple dialects, where linguistic diversity and data scarcity hinder robust evaluation. Large Language Models (LLMs) present a promising solution through reference-free evaluation techniques; however, their effectiveness diminishes in the absence of dialect-specific context and tailored guidance. In this work, we propose a comprehensive framework that enhances LLM-based MT evaluation using a dialect guided approach. We extend the ONUBAD dataset by incorporating Sylheti-English sentence pairs, corresponding machine translations, and Direct Assessment (DA) scores annotated by native speakers. To address the vocabulary gap, we augment the tokenizer vocabulary with dialect-specific terms. We further introduce a regression head to enable scalar score prediction and design a dialect-guided (DG) prompting strategy. Our evaluation across multiple LLMs shows that the proposed pipeline consistently outperforms existing methods, achieving the highest gain of +0.1083 in Spearman correlation, along with improvements across other evaluation settings. The dataset and the code are available at https://github.com/180041123-Atiq/MTEonLowResourceLanguage.

[Arxiv](https://arxiv.org/abs/2505.12273)