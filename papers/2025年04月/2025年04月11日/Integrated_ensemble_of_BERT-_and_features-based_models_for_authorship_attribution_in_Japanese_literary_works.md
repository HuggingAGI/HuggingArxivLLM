# # 集成BERT与特征模型的日语文学作品作者归属分析

发布时间：2025年04月11日

`LLM应用`

> Integrated ensemble of BERT- and features-based models for authorship attribution in Japanese literary works

# 摘要

> 传统作者身份识别（AA）任务主要依赖从文本中提取文体特征进行统计分析和分类。近年来，预训练语言模型（PLMs）在文本分类领域备受关注。尽管它们在大规模短文本数据集上表现出色，但小样本情况下的效果仍有待探索，尤其是AA任务。另一个关键挑战是如何结合PLMs与传统基于特征的方法推动AA研究。本研究通过整合传统特征和现代PLM方法，在小样本AA任务中取得了显著提升。实验使用两个文学语料库，分别包含10位作者的作品进行分类。结果显示，BERT在小样本AA任务中表现优异。基于BERT和分类器的集成模型均优于独立模型，而整合后的集成方法进一步显著提升了性能。对于未包含在预训练数据中的语料库，整合集成方法使F1分数较最佳单模型提高了约14个百分点。本研究为有效利用不断扩大的数据处理工具提供了可行方案，助力未来挑战。


> Traditionally, authorship attribution (AA) tasks relied on statistical data analysis and classification based on stylistic features extracted from texts. In recent years, pre-trained language models (PLMs) have attracted significant attention in text classification tasks. However, although they demonstrate excellent performance on large-scale short-text datasets, their effectiveness remains under-explored for small samples, particularly in AA tasks. Additionally, a key challenge is how to effectively leverage PLMs in conjunction with traditional feature-based methods to advance AA research. In this study, we aimed to significantly improve performance using an integrated integrative ensemble of traditional feature-based and modern PLM-based methods on an AA task in a small sample. For the experiment, we used two corpora of literary works to classify 10 authors each. The results indicate that BERT is effective, even for small-sample AA tasks. Both BERT-based and classifier ensembles outperformed their respective stand-alone models, and the integrated ensemble approach further improved the scores significantly. For the corpus that was not included in the pre-training data, the integrated ensemble improved the F1 score by approximately 14 points, compared to the best-performing single model. Our methodology provides a viable solution for the efficient use of the ever-expanding array of data processing tools in the foreseeable future.

[Arxiv](https://arxiv.org/abs/2504.08527)