# # 当前AI模型能否计数我们所指，而非它们所见？一项基准测试与系统性评估

发布时间：2025年09月17日

`LLM应用` `基础理论`

> Can Current AI Models Count What We Mean, Not What They See? A Benchmark and Systematic Evaluation

# 摘要

> 视觉计数是一项基础却极具挑战的任务，尤其当用户需在复杂场景中计数特定类型物体时。尽管最新模型（包括类别无关计数模型和大型视觉语言模型（VLMs））已在计数任务中展现潜力，但其执行细粒度、意图驱动计数的能力仍有待明确。本文中，我们提出PairTally——一个专为评估细粒度视觉计数而设计的基准数据集。该数据集包含681张高分辨率图像，每张均含两个物体类别，需模型依据形状、大小、颜色或语义的细微差异进行区分与计数。数据集涵盖类别间（不同类别）和类别内（密切相关子类别）两种设置，可用于对选择性计数能力的严格评估。我们对多种最先进模型（包括基于示例的方法、语言提示模型及大型VLMs）进行了基准测试。结果显示，尽管近期有所突破，当前模型仍难以可靠计数用户意图的物体，尤其在细粒度及视觉模糊场景中。PairTally为诊断与改进细粒度视觉计数系统奠定了新基础。

> Visual counting is a fundamental yet challenging task, especially when users need to count objects of a specific type in complex scenes. While recent models, including class-agnostic counting models and large vision-language models (VLMs), show promise in counting tasks, their ability to perform fine-grained, intent-driven counting remains unclear. In this paper, we introduce PairTally, a benchmark dataset specifically designed to evaluate fine-grained visual counting. Each of the 681 high-resolution images in PairTally contains two object categories, requiring models to distinguish and count based on subtle differences in shape, size, color, or semantics. The dataset includes both inter-category (distinct categories) and intra-category (closely related subcategories) settings, making it suitable for rigorous evaluation of selective counting capabilities. We benchmark a variety of state-of-the-art models, including exemplar-based methods, language-prompted models, and large VLMs. Our results show that despite recent advances, current models struggle to reliably count what users intend, especially in fine-grained and visually ambiguous cases. PairTally provides a new foundation for diagnosing and improving fine-grained visual counting systems.

[Arxiv](https://arxiv.org/abs/2509.13939)