# # 停止过度思考：大型语言模型高效推理综述
停止过度思考：大型语言模型高效推理的综述

发布时间：2025年03月20日

`LLM应用` `计算机科学` `人工智能`

> Stop Overthinking: A Survey on Efficient Reasoning for Large Language Models

# 摘要

> 大型语言模型（LLMs）在复杂任务中展现出卓越的能力。近期，大型推理模型（LRMs）如 OpenAI o1 和 DeepSeek-R1 的进展，通过监督微调（SFT）和强化学习（RL）等技术进一步提升了系统2推理领域（如数学和编程）中的链式推理（CoT）能力。然而，尽管更长的 CoT 推理序列能够提升性能，但冗长且重复的输出也带来了显著的计算开销，这一现象被称为“过度思考现象”。本文将提供首个结构化的综述，系统性地探究和梳理实现大型语言模型高效推理的当前进展。总体而言，基于大型语言模型的内在机制，我们将现有工作归纳为几个关键方向：（1）模型层面的高效推理，旨在通过优化全长度推理模型为更简洁的推理模型，或直接训练高效推理模型；（2）推理输出层面的高效推理，目标是在推理过程中动态减少推理步骤和长度；（3）输入提示层面的高效推理，寻求根据输入提示的属性（如难度或长度控制）来提升推理效率。此外，我们还将介绍高效数据在训练推理模型中的应用，探索小型语言模型的推理能力，并讨论评估方法和基准测试。

> Large Language Models (LLMs) have demonstrated remarkable capabilities in complex tasks. Recent advancements in Large Reasoning Models (LRMs), such as OpenAI o1 and DeepSeek-R1, have further improved performance in System-2 reasoning domains like mathematics and programming by harnessing supervised fine-tuning (SFT) and reinforcement learning (RL) techniques to enhance the Chain-of-Thought (CoT) reasoning. However, while longer CoT reasoning sequences improve performance, they also introduce significant computational overhead due to verbose and redundant outputs, known as the "overthinking phenomenon". In this paper, we provide the first structured survey to systematically investigate and explore the current progress toward achieving efficient reasoning in LLMs. Overall, relying on the inherent mechanism of LLMs, we categorize existing works into several key directions: (1) model-based efficient reasoning, which considers optimizing full-length reasoning models into more concise reasoning models or directly training efficient reasoning models; (2) reasoning output-based efficient reasoning, which aims to dynamically reduce reasoning steps and length during inference; (3) input prompts-based efficient reasoning, which seeks to enhance reasoning efficiency based on input prompt properties such as difficulty or length control. Additionally, we introduce the use of efficient data for training reasoning models, explore the reasoning capabilities of small language models, and discuss evaluation methods and benchmarking.

[Arxiv](https://arxiv.org/abs/2503.16419)