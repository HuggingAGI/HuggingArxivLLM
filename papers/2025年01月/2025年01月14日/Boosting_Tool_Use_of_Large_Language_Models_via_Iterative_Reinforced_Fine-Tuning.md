# 通过迭代强化微调，提升大型语言模型的工具使用能力

发布时间：2025年01月14日

`Agent

理由：这篇论文主要讨论了通过外部工具增强大型语言模型（LLMs）的能力，并提出了迭代强化微调策略来提升模型在复杂任务中的表现。这涉及到模型与外部工具的交互和协作，属于Agent（智能体）的范畴，因为Agent通常指的是能够感知环境、做出决策并执行动作的智能系统。论文中的方法旨在提升模型使用工具的能力，这与Agent的研究方向高度相关。` `人工智能` `工具增强`

> Boosting Tool Use of Large Language Models via Iterative Reinforced Fine-Tuning

# 摘要

> 通过外部工具增强大型语言模型（LLMs）的能力是一种极具潜力的方法。要有效利用这一潜力完成复杂任务，关键在于提升模型使用工具的能力。通过模拟现实世界合成工具使用数据是一种有效途径。然而，研究发现，随着数据规模的增加，训练收益显著下降，主要原因是模型在复杂场景中的表现不佳（即缺陷），阻碍了通过SFT从数据中学习。为此，我们提出了一种迭代强化微调策略，持续引导模型缓解这一问题。具体而言，我们首先根据策略模型的反馈识别与缺陷相关的数据，然后通过蒙特卡洛树搜索收集细粒度偏好对，精确定位缺陷。接着，使用偏好优化更新策略模型，使其与真实情况对齐，并与缺陷不对齐。这一过程可迭代进行。此外，在迭代前，我们提出了一种从易到难的预热SFT策略，帮助模型更好地从挑战性数据中学习。实验表明，我们的模型超越了同参数规模的模型，优于许多更大的开源和闭源模型，并在复杂工具使用场景中取得了显著的训练收益。

> Augmenting large language models (LLMs) with external tools is a promising approach to enhance their capabilities. Effectively leveraging this potential for complex tasks hinges crucially on improving their ability to use tools. Synthesizing tool use data by simulating the real world is an effective approach. Nevertheless, our investigation reveals that training gains significantly decay as the scale of these data increases. The primary factor is the model's poor performance (a.k.a deficiency) in complex scenarios, which hinders learning from data using SFT. Driven by this objective, we propose an iterative reinforced fine-tuning strategy to continually guide the model to alleviate it. Specifically, we first identify deficiency-related data based on feedback from the policy model, then perform a Monte Carlo Tree Search to collect fine-grained preference pairs to pinpoint deficiencies. Subsequently, we update the policy model using preference optimization to align with ground truth and misalign with deficiencies. This process can be iterated. Moreover, before the iteration, we propose an easy-to-hard warm-up SFT strategy to facilitate learning from challenging data. The experiments demonstrate our models go beyond the same parametric models, outperforming many larger open-source and closed-source models. Additionally, it has achieved notable training gains in complex tool use scenarios.

[Arxiv](https://arxiv.org/abs/2501.09766)