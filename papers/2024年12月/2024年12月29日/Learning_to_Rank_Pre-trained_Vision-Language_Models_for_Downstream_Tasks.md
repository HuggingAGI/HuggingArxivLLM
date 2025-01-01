# 学习为下游任务对预训练的视觉语言模型进行排序

发布时间：2024年12月29日

`LLM应用` `视觉语言模型` `无监督学习`

> Learning to Rank Pre-trained Vision-Language Models for Downstream Tasks

# 摘要

> 像 CLIP 这样的视觉语言模型（VLMs）在分类基准测试中展现出卓越的零样本能力。然而，要在未标注的下游任务中选出性能最佳的 VLM 并非易事。现有的 VLM 选择方法聚焦于仅类名的设定，依赖有监督的大规模数据集和大型语言模型，这在部署时可能难以获取或不可行。本文提出了【无监督视觉语言模型选择】的问题，即只有无监督的下游数据集可用，无其他额外信息。为解决此问题，我们提出了一种名为视觉 - 文本图对齐（VEGA）的方法，通过测量下游任务中两种模态间的 VLM 对齐情况来选择无任何标注的 VLM。VEGA 受 VLMs 预训练范式的启发，该范式将来自视觉和文本模态的相同语义特征对齐，从而将两种模态映射到共享表示空间。具体而言，我们先分别在视觉和文本特征上构建两个图。然后，VEGA 被定义为视觉和文本图在节点和边层面的整体相似度。在涵盖多种应用场景和下游数据集的三个不同基准上进行的大量实验表明，VEGA 始终能为未标注下游任务中 VLM 的性能提供可靠且准确的评估。

> Vision language models (VLMs) like CLIP show stellar zero-shot capability on classification benchmarks. However, selecting the VLM with the highest performance on the unlabeled downstream task is non-trivial. Existing VLM selection methods focus on the class-name-only setting, relying on a supervised large-scale dataset and large language models, which may not be accessible or feasible during deployment. This paper introduces the problem of \textbf{unsupervised vision-language model selection}, where only unsupervised downstream datasets are available, with no additional information provided. To solve this problem, we propose a method termed Visual-tExtual Graph Alignment (VEGA), to select VLMs without any annotations by measuring the alignment of the VLM between the two modalities on the downstream task. VEGA is motivated by the pretraining paradigm of VLMs, which aligns features with the same semantics from the visual and textual modalities, thereby mapping both modalities into a shared representation space. Specifically, we first construct two graphs on the vision and textual features, respectively. VEGA is then defined as the overall similarity between the visual and textual graphs at both node and edge levels. Extensive experiments across three different benchmarks, covering a variety of application scenarios and downstream datasets, demonstrate that VEGA consistently provides reliable and accurate estimates of VLMs' performance on unlabeled downstream tasks.

[Arxiv](https://arxiv.org/abs/2412.20682)