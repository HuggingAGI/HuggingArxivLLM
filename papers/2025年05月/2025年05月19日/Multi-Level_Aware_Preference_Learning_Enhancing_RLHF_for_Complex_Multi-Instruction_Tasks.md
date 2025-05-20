# 多层级感知偏好学习：提升RLHF在复杂多指令任务中的效果

发布时间：2025年05月19日

`LLM理论` `人工智能`

> Multi-Level Aware Preference Learning: Enhancing RLHF for Complex Multi-Instruction Tasks

# 摘要

> RLHF 已经成为将人工智能系统与人类偏好对齐的主要方法，在遵循指令任务中展现了卓越且可衡量的效果；然而，在面对复杂多指令任务时，它表现出不足的合规能力。传统方法严重依赖人工标注或更复杂的大型语言模型，导致巨大的资源消耗或潜在的偏见问题。同时，增强标准偏好数据集的替代合成方法常常损害模型的语义质量。

我们的研究发现现有技术存在一个关键疏漏：这些方法主要关注比较响应，而忽视了提示输入中嵌入的有价值潜在信号。它们仅关注样本内的偏好差异，而忽视了偏好数据中样本间存在的偏好差异。为了利用这些被忽视的指标，我们提出了一种新型的多层级感知偏好学习（MAPL）框架，能够增强多指令能力。

具体来说，对于原始偏好数据对中的任何给定响应，我们构建在不同条件下具有偏好关系的多样化提示，以学习样本内的偏好差异。此外，对于任何给定的原始偏好对，我们合成多指令偏好对以捕获样本间的偏好差异。基于上述构建的两个数据集，我们进而设计了两个复杂的训练目标函数。随后，我们的框架无缝集成到奖励建模和直接偏好优化范式中。通过在多个基准上的严格评估，我们实证验证了我们框架的有效性。


> RLHF has emerged as a predominant approach for aligning artificial intelligence systems with human preferences, demonstrating exceptional and measurable efficacy in instruction following tasks; however, it exhibits insufficient compliance capabilities when confronted with complex multi-instruction tasks. Conventional approaches rely heavily on human annotation or more sophisticated large language models, thereby introducing substantial resource expenditure or potential bias concerns. Meanwhile, alternative synthetic methods that augment standard preference datasets often compromise the model's semantic quality. Our research identifies a critical oversight in existing techniques, which predominantly focus on comparing responses while neglecting valuable latent signals embedded within prompt inputs, and which only focus on preference disparities at the intra-sample level, while neglecting to account for the inter-sample level preference differentials that exist among preference data. To leverage these previously neglected indicators, we propose a novel Multi-level Aware Preference Learning (MAPL) framework, capable of enhancing multi-instruction capabilities. Specifically, for any given response in original preference data pairs, we construct varied prompts with a preference relation under different conditions, in order to learn intra-sample level preference disparities. Furthermore, for any given original preference pair, we synthesize multi-instruction preference pairs to capture preference discrepancies at the inter-sample level. Building on the two datasets constructed above, we consequently devise two sophisticated training objective functions. Subsequently, our framework integrates seamlessly into both Reward Modeling and Direct Preference Optimization paradigms. Through rigorous evaluation across multiple benchmarks, we empirically validate the efficacy of our framework.

[Arxiv](https://arxiv.org/abs/2505.12845)