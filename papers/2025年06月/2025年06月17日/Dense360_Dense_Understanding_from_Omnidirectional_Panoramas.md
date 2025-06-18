# Dense360：通过全向全景图实现深度理解

发布时间：2025年06月17日

`LLM应用` `计算机视觉` `多模态学习`

> Dense360: Dense Understanding from Omnidirectional Panoramas

# 摘要

> 多模态大型语言模型（MLLMs）需要全面的视觉输入来实现对物理世界的密集理解。尽管现有的MLLMs通过有限的视野（FOV）视觉输入（例如70度）展示了令人印象深刻的对世界的理解能力，但我们迈出了从全向全景图实现密集理解的第一步。

我们介绍了一个全向全景图数据集，该数据集包含一系列可靠性评分的标注。具体来说，我们的数据集包含160K全景图，5M密集实体级描述，1M唯一的引用表达，以及100K基于实体的全景场景描述。与多视图替代方案相比，全景图可以通过等距圆柱投影（ERP）提供更完整、紧凑和连续的场景表示。

然而，ERP的使用为MLLMs带来了两个关键挑战：i) 纬度圆上的空间连续性，以及 ii) 信息密度随纬度的变化。我们通过ERP-RoPE解决了这些挑战，这是一种专门针对全景ERP设计的位置编码方案。

此外，我们引入了Dense360-Bench，这是首个用于评估MLLMs在全向描述和定位任务中性能的基准，为在全景设置下推进密集的视觉-语言理解建立了一个全面的框架。

> Multimodal Large Language Models (MLLMs) require comprehensive visual inputs to achieve dense understanding of the physical world. While existing MLLMs demonstrate impressive world understanding capabilities through limited field-of-view (FOV) visual inputs (e.g., 70 degree), we take the first step toward dense understanding from omnidirectional panoramas. We first introduce an omnidirectional panoramas dataset featuring a comprehensive suite of reliability-scored annotations. Specifically, our dataset contains 160K panoramas with 5M dense entity-level captions, 1M unique referring expressions, and 100K entity-grounded panoramic scene descriptions. Compared to multi-view alternatives, panoramas can provide more complete, compact, and continuous scene representations through equirectangular projections (ERP). However, the use of ERP introduces two key challenges for MLLMs: i) spatial continuity along the circle of latitude, and ii) latitude-dependent variation in information density. We address these challenges through ERP-RoPE, a position encoding scheme specifically designed for panoramic ERP. In addition, we introduce Dense360-Bench, the first benchmark for evaluating MLLMs on omnidirectional captioning and grounding, establishing a comprehensive framework for advancing dense visual-language understanding in panoramic settings.

[Arxiv](https://arxiv.org/abs/2506.14471)