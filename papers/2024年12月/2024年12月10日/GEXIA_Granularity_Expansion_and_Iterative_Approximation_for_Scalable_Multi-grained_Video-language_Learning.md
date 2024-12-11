# GEXIA：用于实现可扩展多粒度视频语言学习的粒度扩展与迭代逼近

发布时间：2024年12月10日

`LLM应用` `语言学习`

> GEXIA: Granularity Expansion and Iterative Approximation for Scalable Multi-grained Video-language Learning

# 摘要

> 在各类视频语言学习任务中，实现多粒度数据的跨模态对齐一直是个难题。我们从数据和建模这两个关键角度提出应对之法。由于缺乏多粒度的视频文本预训练数据集，我们引入了带有集成和压缩操作的粒度扩展（GEX）方法，来拓展单粒度数据集的粒度。为更好地对多粒度数据建模，我们推出了迭代逼近模块（IAM），它能将多粒度的视频和文本嵌入统一的低维语义空间，同时保留跨模态对齐所需的关键信息。而且，GEXIA 具有很强的可扩展性，对用于对齐的视频文本粒度数量毫无限制。我们在七个基准数据集上针对三类视频任务对工作进行评估，展现出了领先或相当的性能。特别值得一提的是，尽管预训练数据集仅含短视频片段，但我们的模型在涉及长视频理解的任务中表现出众。

> In various video-language learning tasks, the challenge of achieving cross-modality alignment with multi-grained data persists. We propose a method to tackle this challenge from two crucial perspectives: data and modeling. Given the absence of a multi-grained video-text pretraining dataset, we introduce a Granularity EXpansion (GEX) method with Integration and Compression operations to expand the granularity of a single-grained dataset. To better model multi-grained data, we introduce an Iterative Approximation Module (IAM), which embeds multi-grained videos and texts into a unified, low-dimensional semantic space while preserving essential information for cross-modal alignment. Furthermore, GEXIA is highly scalable with no restrictions on the number of video-text granularities for alignment. We evaluate our work on three categories of video tasks across seven benchmark datasets, showcasing state-of-the-art or comparable performance. Remarkably, our model excels in tasks involving long-form video understanding, even though the pretraining dataset only contains short video clips.

[Arxiv](https://arxiv.org/abs/2412.07704)