# # 人类对齐基准
评估多语言大模型与人类推理能力的细致差异

发布时间：2025年05月16日

`LLM应用` `人工智能` `多模态推理`

> Human-Aligned Bench: Fine-Grained Assessment of Reasoning Ability in MLLMs vs. Humans

# 摘要

> 实现人工通用智能（AGI）的目标，就是要让模型不仅能够模仿人类，还能超越人类。OpenAI的o1、o3以及DeepSeek的R1等模型已经证明，具备类人推理能力的大语言模型（LLMs）表现优异，并且正在逐渐被整合到多模态大语言模型（MLLMs）中。然而，这些模型在处理推理任务时是否能够达到与人类相当的水平，目前尚不明确。本文中，我们提出了Human-Aligned Bench，这是一个用于多模态推理与人类表现精细对齐的基准测试。具体而言，我们收集了9,794个多模态问题，这些问题仅依赖于上下文推理，包括双语（中文和英文）的多模态问题以及纯文本问题，涵盖四种问题类型：视觉推理、定义判断、类比推理和逻辑判断。更重要的是，每个问题都附带了人类的成功率以及人类容易误选的选项。在Human-Aligned Bench上进行的大量实验表明，当前MLLMs在多模态推理方面的表现与人类表现之间存在显著差异。我们基准测试的结果为下一代模型的发展提供了重要启示。

> The goal of achieving Artificial General Intelligence (AGI) is to imitate humans and surpass them. Models such as OpenAI's o1, o3, and DeepSeek's R1 have demonstrated that large language models (LLMs) with human-like reasoning capabilities exhibit exceptional performance and are being gradually integrated into multimodal large language models (MLLMs). However, whether these models possess capabilities comparable to humans in handling reasoning tasks remains unclear at present. In this paper, we propose Human-Aligned Bench, a benchmark for fine-grained alignment of multimodal reasoning with human performance. Specifically, we collected 9,794 multimodal questions that solely rely on contextual reasoning, including bilingual (Chinese and English) multimodal questions and pure text-based questions, encompassing four question types: visual reasoning, definition judgment, analogical reasoning, and logical judgment. More importantly, each question is accompanied by human success rates and options that humans are prone to choosing incorrectly. Extensive experiments on the Human-Aligned Bench reveal notable differences between the performance of current MLLMs in multimodal reasoning and human performance. The findings on our benchmark provide insights into the development of the next-generation models.

[Arxiv](https://arxiv.org/abs/2505.11141)