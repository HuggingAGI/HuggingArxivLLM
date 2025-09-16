# 辅助推理如何赋能视觉语言模型中的GUI定位

发布时间：2025年09月14日

`Agent` `基础理论`

> How Auxiliary Reasoning Unleashes GUI Grounding in VLMs

# 摘要

> 图形用户界面（GUI）接地是构建GUI智能体的核心基础任务。然而，通用视觉语言模型（VLMs）因缺乏针对性优化，在该任务上表现不佳。本文指出一个关键问题：VLMs虽在指向游戏中展现出显著的潜在接地能力，但在输出明确坐标时却表现欠佳。为解决这一矛盾，并规避当前微调方法高昂的数据与标注成本，我们提出三种零样本辅助推理方法。这些方法通过在输入图像中加入坐标轴、网格和标记交点等明确空间线索，使VLMs得以充分发挥其隐含的空间理解能力。我们在四个GUI接地基准上，对七个开源及专有VLMs进行了方法评估。结果显示，所提方法显著提升了GUI接地性能。

> Graphical user interface (GUI) grounding is a fundamental task for building GUI agents. However, general vision-language models (VLMs) struggle with this task due to a lack of specific optimization. We identify a key gap in this paper: while VLMs exhibit significant latent grounding potential, as demonstrated by their performance measured by Pointing Game, they underperform when tasked with outputting explicit coordinates. To address this discrepancy, and bypass the high data and annotation costs of current fine-tuning approaches, we propose three zero-shot auxiliary reasoning methods. By providing explicit spatial cues such as axes, grids and labeled intersections as part of the input image, these methods enable VLMs to articulate their implicit spatial understanding capabilities. We evaluate these methods on four GUI grounding benchmarks across seven open-source and proprietary VLMs. The evaluation results demonstrate that the proposed methods substantially improve the performance of GUI grounding.

[Arxiv](https://arxiv.org/abs/2509.11548)