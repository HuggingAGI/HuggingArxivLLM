# ProtCLIP: 基于功能信息的蛋白质多模态学习

发布时间：2024年12月27日

`LLM应用` `生物医学` `蛋白质研究`

> ProtCLIP: Function-Informed Protein Multi-Modal Learning

# 摘要

> 多模态预训练范式将蛋白质序列与生物描述相匹配，已习得通用的蛋白质表征，并在各类下游应用中表现出色。然而，由于对对齐的蛋白质 - 文本配对数据利用不佳，且缺乏有效的功能告知预训练范式，这些工作仍难以企及语言监督视觉基础模型的巨大成功。为解决这些问题，本文借助属性驱动的采样策略整理出一个名为 ProtAnno 的大规模蛋白质 - 文本配对数据集，并引入了新颖的功能告知蛋白质预训练范式。具体来说，采样策略依据样本的置信度和属性覆盖度确定选择概率，在面对大规模噪声数据时平衡数据质量与数量。此外，受蛋白质特定功能机制重要性的启发，所提出的范式通过两个分段预训练目标，对蛋白质的静态和动态功能段进行明确建模，以功能告知的方式注入细粒度信息。凭借所有这些创新，我们开发出 ProtCLIP，这一多模态基础模型能全面呈现功能感知的蛋白质嵌入。在包括蛋白质功能分类、突变效应预测、跨模态转换、语义相似性推断和蛋白质 - 蛋白质相互作用预测在内的 5 种类型的 22 个不同蛋白质基准测试中，我们的 ProtCLIP 始终达到 SOTA 性能，在五个跨模态转换基准测试中平均显著提升 75%，在 GO-CC 中提升 59.9%，在 GO-BP 蛋白质功能预测中提升 39.7%。实验结果证实了 ProtCLIP 作为蛋白质多模态基础模型的非凡潜力。

> Multi-modality pre-training paradigm that aligns protein sequences and biological descriptions has learned general protein representations and achieved promising performance in various downstream applications. However, these works were still unable to replicate the extraordinary success of language-supervised visual foundation models due to the ineffective usage of aligned protein-text paired data and the lack of an effective function-informed pre-training paradigm. To address these issues, this paper curates a large-scale protein-text paired dataset called ProtAnno with a property-driven sampling strategy, and introduces a novel function-informed protein pre-training paradigm. Specifically, the sampling strategy determines selecting probability based on the sample confidence and property coverage, balancing the data quality and data quantity in face of large-scale noisy data. Furthermore, motivated by significance of the protein specific functional mechanism, the proposed paradigm explicitly model protein static and dynamic functional segments by two segment-wise pre-training objectives, injecting fine-grained information in a function-informed manner. Leveraging all these innovations, we develop ProtCLIP, a multi-modality foundation model that comprehensively represents function-aware protein embeddings. On 22 different protein benchmarks within 5 types, including protein functionality classification, mutation effect prediction, cross-modal transformation, semantic similarity inference and protein-protein interaction prediction, our ProtCLIP consistently achieves SOTA performance, with remarkable improvements of 75% on average in five cross-modal transformation benchmarks, 59.9% in GO-CC and 39.7% in GO-BP protein function prediction. The experimental results verify the extraordinary potential of ProtCLIP serving as the protein multi-modality foundation model.

[Arxiv](https://arxiv.org/abs/2412.20014)