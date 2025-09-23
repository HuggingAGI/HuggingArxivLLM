# 论Lakh MIDI数据集的去重

发布时间：2025年09月20日

`其他` `媒体与娱乐`

> On the de-duplication of the Lakh MIDI dataset

# 摘要

> 大规模数据集是训练泛化能力优异的深度学习模型的关键。这类数据集大多通过抓取各类网络资源收集，难免混入重复数据。在符号音乐领域，这些重复数据往往源于用户的多种改编版本，或是简单编辑后的元数据变动。然而，尽管随机分割时的数据泄露会导致训练评估失真等严重问题，音乐信息检索（MIR）社区对数据集重复问题的关注仍较为有限。本研究聚焦符号音乐领域最大的公开资源之一——Lakh MIDI数据集（LMD），深入探究其数据重复问题。为筛选并评估最优的重复数据检索方法，我们将LMD的Clean MIDI子集用作基准测试集，该子集已将同一歌曲的不同版本归为一组。我们首先评估了基于规则的方法和现有符号音乐检索模型的去重效果，同时还探究了结合多种增强手段的对比学习BERT模型在重复文件检测中的表现。最终，我们提出了三个LMD过滤列表版本，在最保守的过滤条件下，能从178,561个文件中至少剔除38,134个样本。

> A large-scale dataset is essential for training a well-generalized deep-learning model. Most such datasets are collected via scraping from various internet sources, inevitably introducing duplicated data. In the symbolic music domain, these duplicates often come from multiple user arrangements and metadata changes after simple editing. However, despite critical issues such as unreliable training evaluation from data leakage during random splitting, dataset duplication has not been extensively addressed in the MIR community. This study investigates the dataset duplication issues regarding Lakh MIDI Dataset (LMD), one of the largest publicly available sources in the symbolic music domain. To find and evaluate the best retrieval method for duplicated data, we employed the Clean MIDI subset of the LMD as a benchmark test set, in which different versions of the same songs are grouped together. We first evaluated rule-based approaches and previous symbolic music retrieval models for de-duplication and also investigated with a contrastive learning-based BERT model with various augmentations to find duplicate files. As a result, we propose three different versions of the filtered list of LMD, which filters out at least 38,134 samples in the most conservative settings among 178,561 files.

[Arxiv](https://arxiv.org/abs/2509.16662)