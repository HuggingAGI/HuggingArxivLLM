# PARTONOMY：大型多模态模型，具备部件级视觉理解能力

发布时间：2025年05月27日

`LLM应用

理由：这篇论文主要探讨了大型多模态模型（LMMs）在部件定位和分割任务中的应用，提出了新的基准测试PARTONOMY，并开发了改进的模型PLUM。研究集中在模型的应用和性能提升上，属于LLM应用类别。` `计算机视觉` `图像处理`

> PARTONOMY: Large Multimodal Models with Part-Level Visual Understanding

# 摘要

> # 摘要
真实世界的物体由独特的部件组成，识别这些部件是进行细粒度组合推理的关键。然而，大型多模态模型 (LMMs) 在这一看似简单的任务上表现不佳。为此，我们提出了 PARTONOMY——一个专为像素级部件定位设计的基准测试。该基准由现有部件数据集和我们严格标注的图像集合构建而成，包含 862 个部件标签和 534 个物体标签用于评估。

与现有仅要求模型识别通用部件的数据集不同，PARTONOMY 采用专业概念（如农业飞机），并要求模型在比较部件、理解部件与整体关系以及通过视觉分割解释文本预测方面更具能力。实验表明，当前最先进的 LMMs 在这一任务上表现有限（例如，LISA-13B 仅达到 5.9% 的 gIoU），凸显了它们在部件定位能力上的不足。

我们发现，现有支持分割的 LMMs 存在两大架构缺陷：其一，使用预训练中未见过的特殊 [SEG] 标记，导致分布偏移；其二，未能利用过去预测指导未来推理，而是简单丢弃了预测结果。为解决这些问题，我们开发了 PLUM——一种新型分割型 LMM。PLUM 采用跨度标记而非传统分割标记，并通过反馈循环利用先前预测进行条件推理。

实验结果显示，经过预训练的 PLUM 在推理分割、视觉问答 (VQA) 和视觉幻觉基准上均优于现有分割型 LMM。进一步，在我们提出的解释性部件分割任务上进行微调的 PLUM，其性能可与基于大量更多分割数据训练的分割型 LMM 相媲美。本研究为提升 LMM 的细粒度、基于视觉理解能力开辟了新的研究方向。


> Real-world objects are composed of distinctive, object-specific parts. Identifying these parts is key to performing fine-grained, compositional reasoning-yet, large multimodal models (LMMs) struggle to perform this seemingly straightforward task. In this work, we introduce PARTONOMY, an LMM benchmark designed for pixel-level part grounding. We construct PARTONOMY from existing part datasets and our own rigorously annotated set of images, encompassing 862 part labels and 534 object labels for evaluation. Unlike existing datasets that simply ask models to identify generic parts, PARTONOMY uses specialized concepts (e.g., agricultural airplane), and challenges models to compare objects' parts, consider part-whole relationships, and justify textual predictions with visual segmentations. Our experiments demonstrate significant limitations in state-of-the-art LMMs (e.g., LISA-13B achieves only 5.9% gIoU), highlighting a critical gap in their part grounding abilities. We note that existing segmentation-enabled LMMs (segmenting LMMs) have two key architectural shortcomings: they use special [SEG] tokens not seen during pretraining which induce distribution shift, and they discard predicted segmentations instead of using past predictions to guide future ones. To address these deficiencies, we train several part-centric LMMs and propose PLUM, a novel segmenting LMM that uses span tagging instead of segmentation tokens and that conditions on prior predictions in a feedback loop. We find that pretrained PLUM outperforms existing segmenting LMMs on reasoning segmentation, VQA, and visual hallucination benchmarks. In addition, PLUM finetuned on our proposed Explanatory Part Segmentation task is competitive with segmenting LMMs trained on significantly more segmentation data. Our work opens up new avenues towards enabling fine-grained, grounded visual understanding in LMMs.

[Arxiv](https://arxiv.org/abs/2505.20759)