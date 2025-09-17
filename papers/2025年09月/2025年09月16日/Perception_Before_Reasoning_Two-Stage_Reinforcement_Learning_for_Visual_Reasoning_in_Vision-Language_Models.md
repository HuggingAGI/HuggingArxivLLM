# 先感知后推理：视觉-语言模型视觉推理的两阶段强化学习

发布时间：2025年09月16日

`强化学习` `基础理论`

> Perception Before Reasoning: Two-Stage Reinforcement Learning for Visual Reasoning in Vision-Language Models

# 摘要

> 强化学习（RL）已被证实能有效激发大型语言模型（LLMs）的推理能力。受此启发，近期研究尝试将类似技术应用于视觉-语言模型（VLMs），以增强其推理表现。然而，将RL方法从LLMs直接迁移到VLMs效果欠佳，因为VLMs的任务本质上更为复杂——VLMs在有效推理前，必须先准确感知并理解视觉输入。为解决这一难题，我们提出了两阶段强化学习框架，旨在同时提升VLMs的感知与推理能力。为缓解RL训练中常见的优势消失问题，我们首先进行数据集级采样，利用不同数据源有针对性地强化特定能力。训练时，第一阶段通过粗粒度与细粒度视觉理解提升模型的视觉感知能力，第二阶段则专注于增强推理能力。经过上述两阶段强化学习后，我们得到了PeBR-R1——一个感知与推理能力显著提升的视觉-语言模型。在七个基准数据集上的实验结果证实了我们方法的有效性，并验证了PeBR-R1在各类视觉推理任务中的卓越表现。

> Reinforcement learning (RL) has proven highly effective in eliciting the reasoning capabilities of large language models (LLMs). Inspired by this success, recent studies have explored applying similar techniques to vision-language models (VLMs), aiming to enhance their reasoning performance. However, directly transplanting RL methods from LLMs to VLMs is suboptimal, as the tasks faced by VLMs are inherently more complex. Specifically, VLMs must first accurately perceive and understand visual inputs before reasoning can be effectively performed. To address this challenge, we propose a two-stage reinforcement learning framework designed to jointly enhance both the perceptual and reasoning capabilities of VLMs. To mitigate the vanishing advantage issue commonly observed in RL training, we first perform dataset-level sampling to selectively strengthen specific capabilities using distinct data sources. During training, the first stage focuses on improving the model's visual perception through coarse- and fine-grained visual understanding, while the second stage targets the enhancement of reasoning abilities. After the proposed two-stage reinforcement learning process, we obtain PeBR-R1, a vision-language model with significantly enhanced perceptual and reasoning capabilities. Experimental results on seven benchmark datasets demonstrate the effectiveness of our approach and validate the superior performance of PeBR-R1 across diverse visual reasoning tasks.

[Arxiv](https://arxiv.org/abs/2509.13031)