# 看见不等于推理：MVPBench——多路径视觉物理推理链的评估工具

发布时间：2025年05月29日

`LLM应用

论文摘要：理解由运动定律、空间关系和因果关系所主导的物理世界，对多模态大型语言模型（MLLMs）来说是一项根本性的挑战。尽管近期的进展如OpenAI o3和GPT-4o展示了令人印象深刻的感知和推理能力，但我们的研究发现，这些模型在视觉物理推理方面存在严重困难，无法掌握复杂场景中的基本物理定律、空间互动和因果效应。更重要的是，它们常常无法遵循基于视觉证据的连贯推理链，尤其是在需要多个步骤才能得出正确答案的情况下。

为了严格评估这一能力，我们引入了MVPBench，这是一个经过精心策划的基准测试，旨在通过视觉链式思维（CoT）的视角，严格评估视觉物理推理能力。每个示例都包含交错的多图像输入，不仅要求正确的最终答案，还要求一条基于不断变化的视觉线索的连贯、逐步推理路径。这种设置模仿了人类如何随着时间推移通过实际物理过程进行推理。

为了确保精细的评估，我们引入了一种基于图的CoT一致性指标，用于验证模型的推理路径是否符合有效的物理逻辑。此外，我们尽量减少从文本先验中获取捷径，鼓励模型依赖视觉理解。实验结果揭示了一个令人担忧的趋势：即使是前沿的MLLMs在视觉推理准确性方面表现不佳，并且在物理领域中图像文本对齐能力较弱。令人惊讶的是，强化学习（RL）的后训练对齐——通常被认为可以提高视觉推理性能——往往会损害空间推理，这表明需要重新考虑当前的微调实践。` `计算机视觉` `物理推理`

> Seeing is Not Reasoning: MVPBench for Graph-based Evaluation of Multi-path Visual Physical CoT

# 摘要

> 理解由运动定律、空间关系和因果关系所主导的物理世界，对多模态大型语言模型（MLLMs）来说是一项根本性的挑战。尽管近期的进展如OpenAI o3和GPT-4o展示了令人印象深刻的感知和推理能力，但我们的研究发现，这些模型在视觉物理推理方面存在严重困难，无法掌握复杂场景中的基本物理定律、空间互动和因果效应。更重要的是，它们常常无法遵循基于视觉证据的连贯推理链，尤其是在需要多个步骤才能得出正确答案的情况下。

为了严格评估这一能力，我们引入了MVPBench，这是一个经过精心策划的基准测试，旨在通过视觉链式思维（CoT）的视角，严格评估视觉物理推理能力。每个示例都包含交错的多图像输入，不仅要求正确的最终答案，还要求一条基于不断变化的视觉线索的连贯、逐步推理路径。这种设置模仿了人类如何随着时间推移通过实际物理过程进行推理。

为了确保精细的评估，我们引入了一种基于图的CoT一致性指标，用于验证模型的推理路径是否符合有效的物理逻辑。此外，我们尽量减少从文本先验中获取捷径，鼓励模型依赖视觉理解。实验结果揭示了一个令人担忧的趋势：即使是前沿的MLLMs在视觉推理准确性方面表现不佳，并且在物理领域中图像文本对齐能力较弱。令人惊讶的是，强化学习（RL）的后训练对齐——通常被认为可以提高视觉推理性能——往往会损害空间推理，这表明需要重新考虑当前的微调实践。

> Understanding the physical world - governed by laws of motion, spatial relations, and causality - poses a fundamental challenge for multimodal large language models (MLLMs). While recent advances such as OpenAI o3 and GPT-4o demonstrate impressive perceptual and reasoning capabilities, our investigation reveals these models struggle profoundly with visual physical reasoning, failing to grasp basic physical laws, spatial interactions, and causal effects in complex scenes. More importantly, they often fail to follow coherent reasoning chains grounded in visual evidence, especially when multiple steps are needed to arrive at the correct answer. To rigorously evaluate this capability, we introduce MVPBench, a curated benchmark designed to rigorously evaluate visual physical reasoning through the lens of visual chain-of-thought (CoT). Each example features interleaved multi-image inputs and demands not only the correct final answer but also a coherent, step-by-step reasoning path grounded in evolving visual cues. This setup mirrors how humans reason through real-world physical processes over time. To ensure fine-grained evaluation, we introduce a graph-based CoT consistency metric that verifies whether the reasoning path of model adheres to valid physical logic. Additionally, we minimize shortcut exploitation from text priors, encouraging models to rely on visual understanding. Experimental results reveal a concerning trend: even cutting-edge MLLMs exhibit poor visual reasoning accuracy and weak image-text alignment in physical domains. Surprisingly, RL-based post-training alignment - commonly believed to improve visual reasoning performance - often harms spatial reasoning, suggesting a need to rethink current fine-tuning practices.

[Arxiv](https://arxiv.org/abs/2505.24182)