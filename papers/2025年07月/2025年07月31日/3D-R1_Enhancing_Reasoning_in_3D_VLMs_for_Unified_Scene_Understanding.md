# 3D-R1：提升三维视觉语言模型推理能力，助力统一场景理解

发布时间：2025年07月31日

`LLM应用` `3D场景理解` `视觉推理`

> 3D-R1: Enhancing Reasoning in 3D VLMs for Unified Scene Understanding

# 摘要

> 大规模视觉语言模型（VLMs）在2D视觉理解领域取得了显著进展，这激发了将其能力扩展至3D场景理解的兴趣。然而，当前3D VLMs在推理和泛化方面面临挑战，主要源于高质量空间数据的匮乏和视角假设的静态特性。为解决这些问题，我们提出了3D-R1，一个专注于提升3D VLMs推理能力的基础模型。具体而言，我们构建了一个高质量的合成数据集Scene-30K，利用现有3D-VL数据集和基于Gemini 2.5 Pro的数据引擎，作为3D-R1的冷启动初始化数据。此外，我们在强化学习训练中采用了RLHF策略（如GRPO），并引入了感知奖励、语义相似性奖励和格式奖励，以提升推理能力并保持检测准确性和答案精度。我们还引入了一种动态视图选择策略，能够自适应地选择对3D场景理解最有信息量的视角。大量实验表明，3D-R1在多种3D场景基准测试中平均提升了10%的表现，证明了其在增强3D场景理解推理和泛化能力方面的有效性。代码：https://github.com/AIGeeksGroup/3D-R1。网站：https://aigeeksgroup.github.io/3D-R1。

> Large vision-language models (VLMs) have made significant strides in 2D visual understanding tasks, sparking interest in extending these capabilities to 3D scene understanding. However, current 3D VLMs often struggle with robust reasoning and generalization due to limitations in high-quality spatial data and the static nature of viewpoint assumptions. To address these challenges, we propose 3D-R1, a foundation model that enhances the reasoning capabilities of 3D VLMs. Specifically, we first construct a high-quality synthetic dataset with CoT, named Scene-30K, leveraging existing 3D-VL datasets and a data engine based on Gemini 2.5 Pro. It serves as cold-start initialization data for 3D-R1. Moreover, we leverage RLHF policy such as GRPO in the reinforcement learning training process to enhance reasoning capabilities and introduce three reward functions: a perception reward, a semantic similarity reward and a format reward to maintain detection accuracy and answer semantic precision. Furthermore, we introduce a dynamic view selection strategy that adaptively chooses the most informative perspectives for 3D scene understanding. Extensive experiments demonstrate that 3D-R1 delivers an average improvement of 10% across various 3D scene benchmarks, highlighting its effectiveness in enhancing reasoning and generalization in 3D scene understanding. Code: https://github.com/AIGeeksGroup/3D-R1. Website: https://aigeeksgroup.github.io/3D-R1.

[Arxiv](https://arxiv.org/abs/2507.23478)