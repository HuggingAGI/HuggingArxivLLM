# 多层级感知偏好学习：优化复杂多指令任务中的RLHF效果

发布时间：2025年05月19日

`LLM应用` `人工智能`

> Multi-Level Aware Preference Learning: Enhancing RLHF for Complex Multi-Instruction Tasks

# 摘要

> RLHF 已经成为一种主要的方法，用于将人工智能系统与人类偏好对齐，并在遵循指令的任务中表现出卓越且可衡量的效果。然而，当面对复杂的多指令任务时，它显示出不足的合规能力。传统方法严重依赖于人工标注或更复杂的大型语言模型，导致了巨大的资源消耗或潜在的偏见问题。同时，替代的合成方法通过增强标准偏好数据集，通常会损害模型的语义质量。我们的研究发现，现有技术主要关注比较响应，忽视了提示输入中嵌入的潜在信号，并且只关注样本内级别的偏好差异，而忽略了跨样本级别的偏好差异。为了解决这些问题，我们提出了一种新的多级感知偏好学习（MAPL）框架，能够提升多指令能力。具体来说，对于原始偏好数据对中的任何给定响应，我们会在不同条件下构建具有偏好关系的多样化提示，以学习样本内级别的偏好差异。此外，对于任何给定的原始偏好对，我们合成多指令偏好对以捕捉样本间级别的偏好差异。基于以上构建的两个数据集，我们进而设计了两个复杂的训练目标函数。随后，我们的框架无缝集成到奖励建模和直接偏好优化范式中。通过在多个基准上的严格评估，我们实证验证了我们框架的有效性。

> RLHF has emerged as a predominant approach for aligning artificial intelligence systems with human preferences, demonstrating exceptional and measurable efficacy in instruction following tasks; however, it exhibits insufficient compliance capabilities when confronted with complex multi-instruction tasks. Conventional approaches rely heavily on human annotation or more sophisticated large language models, thereby introducing substantial resource expenditure or potential bias concerns. Meanwhile, alternative synthetic methods that augment standard preference datasets often compromise the model's semantic quality. Our research identifies a critical oversight in existing techniques, which predominantly focus on comparing responses while neglecting valuable latent signals embedded within prompt inputs, and which only focus on preference disparities at the intra-sample level, while neglecting to account for the inter-sample level preference differentials that exist among preference data. To leverage these previously neglected indicators, we propose a novel Multi-level Aware Preference Learning (MAPL) framework, capable of enhancing multi-instruction capabilities. Specifically, for any given response in original preference data pairs, we construct varied prompts with a preference relation under different conditions, in order to learn intra-sample level preference disparities. Furthermore, for any given original preference pair, we synthesize multi-instruction preference pairs to capture preference discrepancies at the inter-sample level. Building on the two datasets constructed above, we consequently devise two sophisticated training objective functions. Subsequently, our framework integrates seamlessly into both Reward Modeling and Direct Preference Optimization paradigms. Through rigorous evaluation across multiple benchmarks, we empirically validate the efficacy of our framework.

[Arxiv](https://arxiv.org/abs/2505.12845)