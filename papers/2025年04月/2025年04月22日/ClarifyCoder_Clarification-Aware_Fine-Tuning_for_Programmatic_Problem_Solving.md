# ClarifyCoder：为编程问题解决而优化的澄清感知微调方法

发布时间：2025年04月22日

`LLM应用` `软件工程`

> ClarifyCoder: Clarification-Aware Fine-Tuning for Programmatic Problem Solving

# 摘要

> 大型语言模型（LLMs）在代码生成任务中展现出了卓越的能力，但与专业软件工程师相比仍有显著差距。关键区别在于，人类工程师在面对模糊需求时会主动寻求澄清，而LLM通常会直接生成代码，无视问题描述中的不确定性。我们提出了一种名为ClarifyCoder的新框架，它结合了合成数据生成和指令微调，使LLM能够识别模糊性并在生成代码前请求澄清。尽管近期研究集中于基于LLM的迭代代码生成代理，但我们主张，识别和查询模糊需求的能力应是模型本身的内在属性。我们的方法包含两个主要组件：（1）一种数据合成技术，通过补充需要澄清的场景来增强现有编程数据集，从而生成具有澄清意识的训练数据；（2）一种微调策略，教导模型在面对不完整或模糊需求时优先寻求澄清而非立即生成代码。我们进一步提供了一种将ClarifyCoder与标准微调相结合的实证分析，以实现澄清意识和编码能力的联合优化。实验结果表明，ClarifyCoder通过有意义的澄清对话显著提升了代码LLM的沟通能力，同时保持了代码生成能力。

> Large language models (LLMs) have demonstrated remarkable capabilities in code generation tasks. However, a significant gap remains between their current performance and that of expert software engineers. A key differentiator is that human engineers actively seek clarification when faced with ambiguous requirements, while LLMs typically generate code regardless of uncertainties in the problem description. We present ClarifyCoder, a novel framework with synthetic data generation and instruction-tuning that enables LLMs to identify ambiguities and request clarification before proceeding with code generation. While recent work has focused on LLM-based agents for iterative code generation, we argue that the fundamental ability to recognize and query ambiguous requirements should be intrinsic to the models themselves. Our approach consists of two main components: (1) a data synthesis technique that augments existing programming datasets with scenarios requiring clarification to generate clarification-aware training data, and (2) a fine-tuning strategy that teaches models to prioritize seeking clarification over immediate code generation when faced with incomplete or ambiguous requirements. We further provide an empirical analysis of integrating ClarifyCoder with standard fine-tuning for a joint optimization of both clarify-awareness and coding ability. Experimental results demonstrate that ClarifyCoder significantly improves the communication capabilities of Code LLMs through meaningful clarification dialogues while maintaining code generation capabilities.

[Arxiv](https://arxiv.org/abs/2504.16331)