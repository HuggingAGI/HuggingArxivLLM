# PL-Guard：波兰语语言模型安全基准测试

发布时间：2025年06月19日

`LLM应用` `语言模型`

> PL-Guard: Benchmarking Language Model Safety for Polish

# 摘要

> 尽管人们不断努力确保大型语言模型（LLMs）的安全性，但现有的大多数安全评估和内容审核工具仍然严重偏向于英语和其他资源丰富的语言，导致全球大部分语言的安全性问题未得到充分关注。为了填补这一空白，我们引入了一个针对波兰语语言模型安全分类的手动标注基准数据集。同时，我们还创建了这些样本的对抗性扰动变体，旨在挑战模型的鲁棒性。我们开展了一系列实验，评估了不同规模和架构的LLM基模型和分类器基模型。具体而言，我们微调了三个模型：Llama-Guard-3-8B、基于HerBERT的分类器（一种波兰语BERT变体）以及PLLuM（一种适应波兰语的Llama-8B模型）。通过使用不同组合的标注数据对这些模型进行训练，并评估其性能，将其与公开可用的防护模型进行比较。结果表明，基于HerBERT的分类器在整体性能上表现最佳，尤其是在对抗条件下。

> Despite increasing efforts to ensure the safety of large language models (LLMs), most existing safety assessments and moderation tools remain heavily biased toward English and other high-resource languages, leaving majority of global languages underexamined. To address this gap, we introduce a manually annotated benchmark dataset for language model safety classification in Polish. We also create adversarially perturbed variants of these samples designed to challenge model robustness. We conduct a series of experiments to evaluate LLM-based and classifier-based models of varying sizes and architectures. Specifically, we fine-tune three models: Llama-Guard-3-8B, a HerBERT-based classifier (a Polish BERT derivative), and PLLuM, a Polish-adapted Llama-8B model. We train these models using different combinations of annotated data and evaluate their performance, comparing it against publicly available guard models. Results demonstrate that the HerBERT-based classifier achieves the highest overall performance, particularly under adversarial conditions.

[Arxiv](https://arxiv.org/abs/2506.16322)