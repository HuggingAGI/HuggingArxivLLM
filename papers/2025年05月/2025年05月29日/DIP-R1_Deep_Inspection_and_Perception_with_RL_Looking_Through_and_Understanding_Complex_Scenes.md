# DIP-R1：强化学习驱动的深度检测与感知，深入解析复杂场景

发布时间：2025年05月29日

`LLM应用

理由：这篇论文探讨了如何通过强化学习（RL）来提升多模态大型语言模型（MLLMs）的视觉感知能力，特别是在复杂场景中的应用。它提出了一种新的框架DIP-R1，通过奖励建模来优化模型的视觉分析和决策能力。研究属于将强化学习应用于提升LLM在特定任务中的表现，因此归类为LLM应用。` `计算机视觉` `人工智能`

> DIP-R1: Deep Inspection and Perception with RL Looking Through and Understanding Complex Scenes

# 摘要

> 多模态大型语言模型（MLLMs）在视觉理解方面表现突出，但在复杂场景如拥挤公共场所中的精细视觉感知仍有待提升。受强化学习（RL）在LLMs和MLLMs中的成功启发，本研究探索了RL如何增强MLLMs的视觉感知能力。为此，我们开发了一种基于RL的新框架——深度检查与感知框架（DIP-R1），旨在通过细致分析复杂场景和深入观察视觉实例，提升MLLMs的视觉感知能力。DIP-R1通过三个简单设计的基于规则的奖励建模，引导MLLMs对视觉场景进行详细检查。首先，采用标准推理奖励，鼓励模型依次完成三个步骤：理解视觉场景、观察模糊区域、做出决策。其次，设计了方差引导的观察奖励，用于检查不确定区域，帮助模型明确关注模糊区域，从而提高其缓解感知不确定性的能力。第三，引入加权精确召回准确度奖励，提升模型的决策准确性。通过在包含挑战性现实环境（如拥挤场景）的精细物体检测数据上进行测试，我们发现DIP-R1在各种内部和外部场景中均表现出显著且持续的改进。与现有基线模型和监督微调方法相比，DIP-R1表现更优。这表明将RL整合到MLLMs中，在提升复杂真实感知任务能力方面具有巨大潜力。

> Multimodal Large Language Models (MLLMs) have demonstrated significant visual understanding capabilities, yet their fine-grained visual perception in complex real-world scenarios, such as densely crowded public areas, remains limited. Inspired by the recent success of reinforcement learning (RL) in both LLMs and MLLMs, in this paper, we explore how RL can enhance visual perception ability of MLLMs. Then we develop a novel RL-based framework, Deep Inspection and Perception with RL (DIP-R1) designed to enhance the visual perception capabilities of MLLMs, by comprehending complex scenes and looking through visual instances closely. DIP-R1 guides MLLMs through detailed inspection of visual scene via three simply designed rule-based reward modelings. First, we adopt a standard reasoning reward encouraging the model to include three step-by-step processes: 1) reasoning for understanding visual scenes, 2) observing for looking through interested but ambiguous regions, and 3) decision-making for predicting answer. Second, a variance-guided looking reward is designed to examine uncertain regions for the second observing process. It explicitly enables the model to inspect ambiguous areas, improving its ability to mitigate perceptual uncertainties. Third, we model a weighted precision-recall accuracy reward enhancing accurate decision-making. We explore its effectiveness across diverse fine-grained object detection data consisting of challenging real-world environments, such as densely crowded scenes. Built upon existing MLLMs, DIP-R1 achieves consistent and significant improvement across various in-domain and out-of-domain scenarios. It also outperforms various existing baseline models and supervised fine-tuning methods. Our findings highlight the substantial potential of integrating RL into MLLMs for enhancing capabilities in complex real-world perception tasks.

[Arxiv](https://arxiv.org/abs/2505.23179)