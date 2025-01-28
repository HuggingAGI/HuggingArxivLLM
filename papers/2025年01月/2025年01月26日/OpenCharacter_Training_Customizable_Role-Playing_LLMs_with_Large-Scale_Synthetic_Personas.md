# OpenCharacter: 利用大规模合成角色训练可定制的角色扮演LLM

发布时间：2025年01月26日

`Agent

理由：这篇论文主要讨论了如何通过大规模数据合成方法赋予大型语言模型（LLMs）角色泛化能力，并用于开发和部署角色扮演对话代理。这涉及到对话代理（Agent）的设计和优化，因此应归类为Agent。` `对话系统` `角色扮演`

> OpenCharacter: Training Customizable Role-Playing LLMs with Large-Scale Synthetic Personas

# 摘要

> # 可定制的角色扮演
在大型语言模型（LLMs）中，角色泛化因其在开发和部署角色扮演对话代理中的多功能性和成本效益而备受关注。本研究采用大规模数据合成方法，赋予LLMs角色泛化能力。我们首先利用Persona Hub中的角色合成大规模角色配置文件，随后探索响应重写和响应生成两种策略，以生成与角色一致的教学响应。为验证合成指令调优数据对角色泛化的有效性，我们使用LLaMA-3 8B模型进行监督微调（SFT）。最终，我们的最佳模型不仅增强了LLaMA-3 8B Instruct模型，还在角色扮演对话中达到了与GPT-4o模型相当的性能。我们公开了合成角色和指令调优对话，以支持公共研究。

> Customizable role-playing in large language models (LLMs), also known as character generalization, is gaining increasing attention for its versatility and cost-efficiency in developing and deploying role-playing dialogue agents. This study explores a large-scale data synthesis approach to equip LLMs with character generalization capabilities. We begin by synthesizing large-scale character profiles using personas from Persona Hub and then explore two strategies: response rewriting and response generation, to create character-aligned instructional responses. To validate the effectiveness of our synthetic instruction tuning data for character generalization, we perform supervised fine-tuning (SFT) using the LLaMA-3 8B model. Our best-performing model strengthens the original LLaMA-3 8B Instruct model and achieves performance comparable to GPT-4o models on role-playing dialogue. We release our synthetic characters and instruction-tuning dialogues to support public research.

[Arxiv](https://arxiv.org/abs/2501.15427)