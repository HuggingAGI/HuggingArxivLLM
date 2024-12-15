# 提升多模态冷启动主动学习中的模态表示与对齐

发布时间：2024年12月12日

`LLM应用` `多模态` `主动学习`

> Enhancing Modality Representation and Alignment for Multimodal Cold-start Active Learning

# 摘要

> 训练多模态模型需要大量的标注数据，主动学习（AL）意在降低标注成本。多数AL方法采用热启动方式，依赖充足的标注数据来训练能评估未标注数据不确定性和多样性的校准良好的模型。然而，在构建数据集时，初始阶段有标注数据通常稀缺，从而引发冷启动问题。另外，大多数AL方法很少处理多模态数据，这凸显了该领域的研究空缺。我们的研究通过开发一种用于多模态冷启动主动学习（MMCSAL）的两阶段方法来应对这些问题。
  首先，仅使用跨模态配对信息作为自监督信号时，我们会观察到模态差距，即不同模态的表示质心之间存在显著距离。这种模态差距会影响数据选择过程，因为我们要计算单模态和跨模态距离。为解决此问题，我们引入单模态原型来缩小模态差距。其次，传统AL方法在多模态场景中常因忽视模态间的对齐而表现不佳。所以，我们提议通过正则化增强跨模态对齐，进而提升AL中所选多模态数据对的质量。最后，我们的实验表明MMCSAL在三个多模态数据集中选择多模态数据对的效果显著。

> Training multimodal models requires a large amount of labeled data. Active learning (AL) aim to reduce labeling costs. Most AL methods employ warm-start approaches, which rely on sufficient labeled data to train a well-calibrated model that can assess the uncertainty and diversity of unlabeled data. However, when assembling a dataset, labeled data are often scarce initially, leading to a cold-start problem. Additionally, most AL methods seldom address multimodal data, highlighting a research gap in this field. Our research addresses these issues by developing a two-stage method for Multi-Modal Cold-Start Active Learning (MMCSAL).
  Firstly, we observe the modality gap, a significant distance between the centroids of representations from different modalities, when only using cross-modal pairing information as self-supervision signals. This modality gap affects data selection process, as we calculate both uni-modal and cross-modal distances. To address this, we introduce uni-modal prototypes to bridge the modality gap. Secondly, conventional AL methods often falter in multimodal scenarios where alignment between modalities is overlooked. Therefore, we propose enhancing cross-modal alignment through regularization, thereby improving the quality of selected multimodal data pairs in AL. Finally, our experiments demonstrate MMCSAL's efficacy in selecting multimodal data pairs across three multimodal datasets.

[Arxiv](https://arxiv.org/abs/2412.09126)