# 通过视觉人类偏好与 VLMs 和软奖励进行推理测试探索

发布时间：2025年03月25日

`LLM应用` `计算机视觉` `图像处理`

> Test-Time Reasoning Through Visual Human Preferences with VLMs and Soft Rewards

# 摘要

> 视觉语言模型（VLMs）能否有效捕捉人类视觉偏好？本研究通过训练VLMs在测试时思考偏好，采用受DeepSeek R1和OpenAI O1启发的强化学习方法，探讨这一问题。基于ImageReward和HPSv2数据集，我们的模型在ImageReward测试集（基于官方划分训练）上达到了64.9%的准确率，在HPSv2（基于约25%的数据训练）上达到了65.4%的准确率。这些结果与传统基于编码器的模型相当，同时提供了透明的推理和增强的泛化能力。这种方法不仅能够利用丰富的VLM世界知识，还能利用其潜在的推理能力，产生可解释的结果，从而辅助决策过程。通过证明当前VLMs能够合理解释人类视觉偏好，我们引入了高效的软奖励策略用于图像排序，超越了简单的选择或评分方法。这种推理能力使VLMs能够对任意图像进行排序——无论其宽高比或复杂性如何——从而有望增强视觉偏好优化的效果。通过减少对大量标注的需求，同时提升奖励的泛化性和可解释性，我们的发现可以成为一个强有力的里程碑，进一步提升文本到视觉模型的性能。


> Can Visual Language Models (VLMs) effectively capture human visual preferences? This work addresses this question by training VLMs to think about preferences at test time, employing reinforcement learning methods inspired by DeepSeek R1 and OpenAI O1. Using datasets such as ImageReward and Human Preference Score v2 (HPSv2), our models achieve accuracies of 64.9% on the ImageReward test set (trained on ImageReward official split) and 65.4% on HPSv2 (trained on approximately 25% of its data). These results match traditional encoder-based models while providing transparent reasoning and enhanced generalization. This approach allows to use not only rich VLM world knowledge, but also its potential to think, yielding interpretable outcomes that help decision-making processes. By demonstrating that human visual preferences reasonable by current VLMs, we introduce efficient soft-reward strategies for image ranking, outperforming simplistic selection or scoring methods. This reasoning capability enables VLMs to rank arbitrary images-regardless of aspect ratio or complexity-thereby potentially amplifying the effectiveness of visual Preference Optimization. By reducing the need for extensive markup while improving reward generalization and explainability, our findings can be a strong mile-stone that will enhance text-to-vision models even further.

[Arxiv](https://arxiv.org/abs/2503.19948)