# WarriorCoder：通过从专家对战中学习来增强代码大型语言模型

发布时间：2024年12月23日

`LLM应用` `模型训练`

> WarriorCoder: Learning from Expert Battles to Augment Code Large Language Models

# 摘要

> 尽管代码大型语言模型（LLMs）近来有所进步，但其出色的能力很大程度上依赖于对高质量数据的微调，这给数据收集和标注带来难题。为应对此问题，当下的方法常常设计各类数据飞轮来收集复杂的代码指令，让模型能够处理更繁杂的任务。然而，这些方法往往依赖现成的数据集以及来自有限的专有LLMs（如Claude、GPT4等）的数据增强，这限制了所构建数据的多样性，还容易产生系统性偏差。在本文中，我们提出了WarriorCoder以解决这些限制。具体而言，我们为当前的专家代码LLMs创建了一个竞技场，每个模型都相互挑战和回应，由不相关的裁判模型进行评估。这种竞争框架能从头生成新的训练数据，充分发挥所有参与者的优势。实验结果显示，即便不依赖专有LLMs，WarriorCoder与以往方法相比也能取得颇具竞争力的性能。

> Despite recent progress achieved by code large language models (LLMs), their remarkable abilities are largely dependent on fine-tuning on the high-quality data, posing challenges for data collection and annotation. To address this, current methods often design various data flywheels to gather complex code instructions, enabling models to handle more intricate tasks. However, these approaches typically rely on off-the-shelf datasets and data augmentation from the limited pool of proprietary LLMs (e.g., Claude, GPT4, and so on), which limits the diversity of the constructed data and makes it prone to systemic biases. In this paper, we propose WarriorCoder which learns from expert battles to address these limitations. Specifically, we create an arena for current expert code LLMs, where each model challenges and responds to others' challenges, with evaluations conducted by uninvolved judge models. This competitive framework generates novel training data constructed from scratch, harnessing the strengths of all participants. Experimental results demonstrate that WarriorCoder achieves competitive performance compared to previous methods, even without relying on proprietary LLMs.

[Arxiv](https://arxiv.org/abs/2412.17395)