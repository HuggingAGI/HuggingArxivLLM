# OLaPh：最优语言音素化器

发布时间：2025年09月24日

`LLM应用` `媒体与娱乐`

> OLaPh: Optimal Language Phonemizer

# 摘要

> 音素化（即文本转音素的过程）是文本转语音技术的核心环节。传统方案依赖基于规则的转换与词典查询，而更先进的方法则通过预处理技术或神经网络提升对域外词汇的处理精度。但所有系统在人名、外来词、缩写词和同形异义词的处理上均面临挑战。本研究提出OLaPh（最优语言音素化器）框架，它融合了大型词典、多种NLP技术、复合词解析及概率评分函数。在德语和英语上的评估结果显示，该方法准确率超越以往方案，在高难度数据集上亦表现优异。为进一步解决未处理案例，我们利用OLaPh生成的数据训练大型语言模型，其泛化能力与性能均显著提升。综上，该框架与大型语言模型协同增强了音素化的一致性，并为未来研究提供免费开放的资源。

> Phonemization, the conversion of text into phonemes, is a key step in text-to-speech. Traditional approaches use rule-based transformations and lexicon lookups, while more advanced methods apply preprocessing techniques or neural networks for improved accuracy on out-of-domain vocabulary. However, all systems struggle with names, loanwords, abbreviations, and homographs. This work presents OLaPh (Optimal Language Phonemizer), a framework that combines large lexica, multiple NLP techniques, and compound resolution with a probabilistic scoring function. Evaluations in German and English show improved accuracy over previous approaches, including on a challenging dataset. To further address unresolved cases, we train a large language model on OLaPh-generated data, which achieves even stronger generalization and performance. Together, the framework and LLM improve phonemization consistency and provide a freely available resource for future research.

[Arxiv](https://arxiv.org/abs/2509.20086)