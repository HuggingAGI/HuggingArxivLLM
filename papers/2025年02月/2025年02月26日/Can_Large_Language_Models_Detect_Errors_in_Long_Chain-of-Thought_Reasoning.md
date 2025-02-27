# 长链式推理中的错误，大型语言模型能否检测？

发布时间：2025年02月26日

`LLM应用` `人工智能` `机器学习`

> Can Large Language Models Detect Errors in Long Chain-of-Thought Reasoning?

# 摘要

> 近期，类似o1的模型因其生成长链式思维（CoT）推理步骤的能力而备受关注，这些步骤显著提升了现有大型语言模型（LLMs）的推理性能。本文引入了DeltaBench，旨在深入理解长链式思维的特性，并评估现有LLMs对长链式思维的批判能力。DeltaBench涵盖了多种类似o1的模型（如QwQ、DeepSeek-R1）在不同推理任务（如数学、代码、通用推理）中生成的长链式思维，用于检测长链式推理中的错误。基于DeltaBench，我们首先对长链式思维进行了细致分析，以评估不同类似o1模型的有效性和效率。随后，我们对现有过程奖励模型（PRMs）和批判模型进行了全面测试，以检测标注过程中的错误，从而揭示现有模型的边界与局限。最终，我们希望DeltaBench能为开发者提供洞察，助其更好地理解模型的长链式推理能力。

> Recently, o1-like models have drawn significant attention, where these models produce the long Chain-of-Thought (CoT) reasoning steps to improve the reasoning abilities of existing Large Language Models (LLMs). In this paper, to understand the qualities of these long CoTs and measure the critique abilities of existing LLMs on these long CoTs, we introduce the DeltaBench, including the generated long CoTs from different o1-like models (e.g., QwQ, DeepSeek-R1) for different reasoning tasks (e.g., Math, Code, General Reasoning), to measure the ability to detect errors in long CoT reasoning. Based on DeltaBench, we first perform fine-grained analysis of the generated long CoTs to discover the effectiveness and efficiency of different o1-like models. Then, we conduct extensive evaluations of existing process reward models (PRMs) and critic models to detect the errors of each annotated process, which aims to investigate the boundaries and limitations of existing PRMs and critic models. Finally, we hope that DeltaBench could guide developers to better understand the long CoT reasoning abilities of their models.

[Arxiv](https://arxiv.org/abs/2502.19361)