# 多模态信息检索在开放世界中的应用：利用编辑距离的弱监督方法

发布时间：2025年06月24日

`LLM应用` `公共安全`

> Multimodal Information Retrieval for Open World with Edit Distance Weak Supervision

# 摘要

> 现有的多模态检索模型主要依赖于两种方法：一种是基于模态特定表示模型创建共同子空间，另一种是通过模态间的模式映射来衡量多模态数据的相似性。我们的目标是避免将检索任务视为有监督分类时产生的标注开销，并重用大型语言模型和视觉任务中预训练的编码器。为此，我们提出了"FemmIR"框架，它能够通过示例无需任何相似性标签，检索与多模态查询表达的信息需求相关的多模态结果。

这种检索能力对于现实世界的应用至关重要，尤其是在数据标注稀缺且需要在不使用跨应用通用框架进行微调的情况下实现高性能。为此，我们整理了一个名为MuQNOL的新数据集，用于评估在此任务上的进展。

我们的技术基于通过样本间编辑距离引入的弱监督机制：图编辑距离可被修改以考虑替换数据样本在属性方面的成本，相关性则通过对象间编辑成本量的隐式信号来衡量。与度量学习或编码网络不同，FemmIR重用了高级属性，并通过数据样本与用户提供的查询示例之间的多级交互分数，保持属性值和关系约束。

我们在使用MuQNOL的失踪人口用例中对FemmIR进行了实证评估。结果表明，FemmIR在提供按需检索结果方面与类似的检索系统表现相当，同时在使用系统中现有的属性标识符时，能够实现精确和近似的相似性检索。


> Existing multi-media retrieval models either rely on creating a common subspace with modality-specific representation models or require schema mapping among modalities to measure similarities among multi-media data. Our goal is to avoid the annotation overhead incurred from considering retrieval as a supervised classification task and re-use the pretrained encoders in large language models and vision tasks. We propose "FemmIR", a framework to retrieve multimodal results relevant to information needs expressed with multimodal queries by example without any similarity label. Such identification is necessary for real-world applications where data annotations are scarce and satisfactory performance is required without fine-tuning with a common framework across applications. We curate a new dataset called MuQNOL for benchmarking progress on this task. Our technique is based on weak supervision introduced through edit distance between samples: graph edit distance can be modified to consider the cost of replacing a data sample in terms of its properties, and relevance can be measured through the implicit signal from the amount of edit cost among the objects. Unlike metric learning or encoding networks, FemmIR re-uses the high-level properties and maintains the property value and relationship constraints with a multi-level interaction score between data samples and the query example provided by the user. We empirically evaluate FemmIR on a missing person use case with MuQNOL. FemmIR performs comparably to similar retrieval systems in delivering on-demand retrieval results with exact and approximate similarities while using the existing property identifiers in the system.

[Arxiv](https://arxiv.org/abs/2506.20070)