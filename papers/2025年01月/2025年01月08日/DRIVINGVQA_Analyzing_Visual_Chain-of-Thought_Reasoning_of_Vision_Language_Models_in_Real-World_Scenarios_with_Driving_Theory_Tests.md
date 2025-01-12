# DRIVINGVQA: 解析视觉语言模型在驾驶理论测试中的现实场景视觉推理链

发布时间：2025年01月08日

`LLM应用

**理由**：这篇论文主要讨论了大型视觉语言模型（LVLMs）在多模态推理中的应用，特别是通过引入新的基准（DrivingVQA）来评估和改进这些模型在复杂视觉场景中的推理能力。虽然涉及视觉和语言的多模态处理，但其核心仍然是关于如何应用和改进现有的语言模型（LLMs）来处理复杂的视觉推理任务。因此，它属于LLM应用的范畴。` `自动驾驶` `视觉推理`

> DRIVINGVQA: Analyzing Visual Chain-of-Thought Reasoning of Vision Language Models in Real-World Scenarios with Driving Theory Tests

# 摘要

> 大型视觉语言模型（LVLMs）通过视觉理解增强了语言模型，实现了多模态推理。然而，由于文本和视觉数据之间的模态差异，它们常常面临重大挑战，如过度依赖文本先验、幻觉以及复杂视觉推理能力有限。现有的评估LVLMs视觉推理能力的基准通常依赖于示意图或合成图像以及不精确的机器生成解释。为了弥合模态差异，我们提出了DrivingVQA，这是一个源自驾驶理论测试的新基准，用于评估复杂现实场景中的视觉链式思维推理。它提供了3,931个专家精心设计的多项选择题和与推理过程相关的实体交织的解释。我们利用这个数据集对LVLMs在复杂视觉场景中的推理能力进行了广泛研究。我们的实验表明，开源和专有的LVLMs在零-shot设置下难以进行视觉链式思维推理。我们研究了利用相关实体改进视觉推理的训练策略。值得注意的是，当推理与这些实体相关的裁剪区域的图像标记时，我们观察到性能提升了7%。

> Large vision-language models (LVLMs) augment language models with visual understanding, enabling multimodal reasoning. However, due to the modality gap between textual and visual data, they often face significant challenges, such as over-reliance on text priors, hallucinations, and limited capacity for complex visual reasoning. Existing benchmarks to evaluate visual reasoning in LVLMs often rely on schematic or synthetic images and on imprecise machine-generated explanations. To bridge the modality gap, we present DrivingVQA, a new benchmark derived from driving theory tests to evaluate visual chain-of-thought reasoning in complex real-world scenarios. It offers 3,931 expert-crafted multiple-choice problems and interleaved explanations grounded with entities relevant to the reasoning process. We leverage this dataset to perform an extensive study of LVLMs' ability to reason about complex visual scenarios. Our experiments reveal that open-source and proprietary LVLMs struggle with visual chain-of-thought reasoning under zero-shot settings. We investigate training strategies that leverage relevant entities to improve visual reasoning. Notably, we observe a performance boost of up to 7\% when reasoning over image tokens of cropped regions tied to these entities.

[Arxiv](https://arxiv.org/abs/2501.04671)