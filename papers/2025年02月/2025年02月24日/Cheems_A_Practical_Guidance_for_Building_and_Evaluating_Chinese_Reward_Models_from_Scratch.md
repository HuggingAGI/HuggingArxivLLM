# 从零构建与评估中文奖励模型的实用指南：Cheems

发布时间：2025年02月24日

`LLM应用` `奖励模型`

> Cheems: A Practical Guidance for Building and Evaluating Chinese Reward Models from Scratch

# 摘要

> 奖励模型（RMs）在对齐大型语言模型（LLMs）与人类偏好方面发挥着关键作用。然而，当前研究多集中于英语领域并依赖合成资源，导致中文环境下数据集和基准的匮乏与不可靠。为此，我们推出了CheemsBench，一个基于人工标注的中文奖励模型评估基准，以及CheemsPreference，一个通过人机协作构建的大规模多样化偏好数据集，旨在支持中文奖励模型的训练。我们对开源的判别式和生成式奖励模型在CheemsBench上进行了系统性评估，发现它们在中文场景下捕捉人类偏好方面存在明显局限。此外，基于CheemsPreference，我们构建了一个在CheemsBench上达到最新技术水平的奖励模型，证明了人工监督在奖励模型训练中的必要性。研究发现，单纯依赖大规模AI生成数据难以全面捕捉人类偏好，凸显了高质量人工监督在奖励模型开发中的重要性。

> Reward models (RMs) are crucial for aligning large language models (LLMs) with human preferences. However, most RM research is centered on English and relies heavily on synthetic resources, which leads to limited and less reliable datasets and benchmarks for Chinese. To address this gap, we introduce CheemsBench, a fully human-annotated RM evaluation benchmark within Chinese contexts, and CheemsPreference, a large-scale and diverse preference dataset annotated through human-machine collaboration to support Chinese RM training. We systematically evaluate open-source discriminative and generative RMs on CheemsBench and observe significant limitations in their ability to capture human preferences in Chinese scenarios. Additionally, based on CheemsPreference, we construct an RM that achieves state-of-the-art performance on CheemsBench, demonstrating the necessity of human supervision in RM training. Our findings reveal that scaled AI-generated data struggles to fully capture human preferences, emphasizing the importance of high-quality human supervision in RM development.

[Arxiv](https://arxiv.org/abs/2502.17173)