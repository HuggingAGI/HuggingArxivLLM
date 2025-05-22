# 我的语言模型如何从数据集中学习临床信息？数据集诊断指南

发布时间：2025年05月20日

`LLM应用` `临床自然语言处理`

> Diagnosing our datasets: How does my language model learn clinical information?

# 摘要

> 大型语言模型（LLMs）在临床自然语言处理任务中表现优异，尽管它们并未直接基于电子健康记录（EHR）数据进行训练。本研究通过两个关键但未充分探索的视角，深入分析了开源LLMs如何从大规模语料库中学习临床信息：（1）理解临床术语的能力，这是解读真实临床笔记的基础；（2）对未经支持医疗声明的反应。我们从相关临床信息在预训练语料库中的频率、预训练数据构成与模型输出的关系，以及数据来源三个方面进行了研究。通过MedLingo新数据集评估，我们发现临床术语的频率与模型性能密切相关。然而，临床笔记中常用的术语在预训练语料库中却罕见，揭示了数据与实际应用的不匹配。此外，我们发现相当一部分文档支持有争议的声明，可能被模型重复。最后，我们分类并分析了临床术语和未经支持医疗声明出现的在线资源类型，为未来数据集的构建提供了重要启示。

> Large language models (LLMs) have performed well across various clinical natural language processing tasks, despite not being directly trained on electronic health record (EHR) data. In this work, we examine how popular open-source LLMs learn clinical information from large mined corpora through two crucial but understudied lenses: (1) their interpretation of clinical jargon, a foundational ability for understanding real-world clinical notes, and (2) their responses to unsupported medical claims. For both use cases, we investigate the frequency of relevant clinical information in their corresponding pretraining corpora, the relationship between pretraining data composition and model outputs, and the sources underlying this data. To isolate clinical jargon understanding, we evaluate LLMs on a new dataset MedLingo. Unsurprisingly, we find that the frequency of clinical jargon mentions across major pretraining corpora correlates with model performance. However, jargon frequently appearing in clinical notes often rarely appears in pretraining corpora, revealing a mismatch between available data and real-world usage. Similarly, we find that a non-negligible portion of documents support disputed claims that can then be parroted by models. Finally, we classified and analyzed the types of online sources in which clinical jargon and unsupported medical claims appear, with implications for future dataset composition.

[Arxiv](https://arxiv.org/abs/2505.15024)