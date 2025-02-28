# 大型语言模型能否揭开神秘面纱？探索它们在复杂场景中解锁信息的能力

发布时间：2025年02月27日

`LLM应用` `计算机视觉` `人工智能`

> Can Large Language Models Unveil the Mysteries? An Exploration of Their Ability to Unlock Information in Complex Scenarios

# 摘要

> 人类在复杂场景中整合多个感知输入并进行组合推理是一项高级认知功能。随着多模态大型语言模型的发展，近期的基准测试更多关注于跨多张图像的视觉理解能力。然而，这些测试往往忽略了跨多个感知信息进行组合推理的重要性。为探究先进模型在复杂场景中整合多个感知输入进行组合推理的能力，我们提出了两个基准测试：Clue-Visual Question Answering (CVQA) 和 Clue of Password-Visual Question Answering (CPVQA)。CVQA 包含三种任务类型，评估视觉理解和合成能力；CPVQA 则专注于视觉数据的准确解读与应用，包含两种任务类型。针对这些基准测试，我们提出了三种即插即用的方法：利用模型输入进行推理、通过最小边界解码结合随机性生成来增强推理能力、以及检索语义相关的视觉信息以实现有效数据整合。实验结果显示，当前模型在组合推理任务上的表现不尽如人意，即使是最先进的闭源模型 (SOTA) 在 CVQA 上的准确率也只有 33.04%，而在 CPVQA 上更是低至 7.38%。令人鼓舞的是，我们的方法显著提升了模型在组合推理任务中的性能，在 CVQA 上比 SOTA 闭源模型提升了 22.17%，CPVQA 上提升了 9.40%，充分证明了该方法在复杂场景下通过多感知输入增强组合推理能力的有效性。相关代码将公开发布。

> Combining multiple perceptual inputs and performing combinatorial reasoning in complex scenarios is a sophisticated cognitive function in humans. With advancements in multi-modal large language models, recent benchmarks tend to evaluate visual understanding across multiple images. However, they often overlook the necessity of combinatorial reasoning across multiple perceptual information. To explore the ability of advanced models to integrate multiple perceptual inputs for combinatorial reasoning in complex scenarios, we introduce two benchmarks: Clue-Visual Question Answering (CVQA), with three task types to assess visual comprehension and synthesis, and Clue of Password-Visual Question Answering (CPVQA), with two task types focused on accurate interpretation and application of visual data. For our benchmarks, we present three plug-and-play approaches: utilizing model input for reasoning, enhancing reasoning through minimum margin decoding with randomness generation, and retrieving semantically relevant visual information for effective data integration. The combined results reveal current models' poor performance on combinatorial reasoning benchmarks, even the state-of-the-art (SOTA) closed-source model achieves only 33.04% accuracy on CVQA, and drops to 7.38% on CPVQA. Notably, our approach improves the performance of models on combinatorial reasoning, with a 22.17% boost on CVQA and 9.40% on CPVQA over the SOTA closed-source model, demonstrating its effectiveness in enhancing combinatorial reasoning with multiple perceptual inputs in complex scenarios. The code will be publicly available.

[Arxiv](https://arxiv.org/abs/2502.19973)