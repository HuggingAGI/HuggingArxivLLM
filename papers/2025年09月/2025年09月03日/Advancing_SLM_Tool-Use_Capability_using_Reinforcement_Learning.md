# 通过强化学习增强小型语言模型（SLM）的工具使用能力

发布时间：2025年09月03日

`强化学习` `基础理论`

> Advancing SLM Tool-Use Capability using Reinforcement Learning

# 摘要

> 大型语言模型（LLMs）已不再局限于简单的文本生成，工具使用对于复杂的现实世界任务而言，重要性日益凸显。LLMs的工具使用能力，指的是它们借助API、数据库或软件函数等外部资源，突破文本生成的局限，拓展自身功能的能力。这些工具可用于执行计算、调用API获取实时时间日期等任务。这种能力让模型能够获取实时数据、执行命令或解决需动态交互的问题，因此在虚拟助手的AI智能体、机器人控制或自动化工作流等应用中变得不可或缺。
  然而，尽管LLMs通常擅长工具使用，但其巨大的资源需求和计算复杂性限制了它们在所有场景中的应用。因此，对更紧凑高效的小型语言模型（SLMs）的需求日益增长。与LLMs相比，SLMs在工具使用方面表现欠佳（如表1所示）。SLMs通常在更小、更特定的数据集上训练，因此与LLMs相比，它们的知识库更窄，上下文理解能力也更有限。
  本研究通过强化学习（RL）——特别是群体相对策略优化（GRPO）——来应对这些挑战，以提升SLMs的工具使用能力。传统微调方法不仅计算量大，还常常缺乏适应性；与之不同，我们的方法提供了一种高效且有效的解决方案，能显著提高SLM的工具使用准确率，增强其实用价值。

> Large Language Models (LLMs) have progressed beyond simple text creation, and tool use has become increasingly important for complex, real-world tasks. Tool use in LLMs refers to their ability to utilize external resources such as APIs, databases, or software functions to extend their functionality beyond generating text.Tools are used for tasks such as performing calculations, making API calls to retrieve the current time and date, and more. This capability enables models to fetch real-time data, execute commands, or solve problems requiring dynamic interaction, making it indispensable for applications like AI agents in virtual assistants, robotic control, or automated workflows.
  However, while LLMs are usually adept tool use, their vast resource requirements and computation complexity restrict their use in every use case.As a result, there is an increasing need for more compact and efficient Small Language Models (SLMs). Small language models (SLMs) struggle in tool use compared to large language models (LLMs). As soon in Table 1. SLMs are typically trained on smaller, more specific datasets, resulting in a narrower knowledge base and limited contextual understanding compared to LLMs.
  This research addresses these challenges by using Reinforcement Learning (RL), specifically Group Relative Policy Optimization (GRPO), to enhance tool-use proficiency in SLMs. Unlike conventional fine-tuning approaches that require heavy computation and often lack adaptability, our method provides an efficient, effective solution that significantly boosts SLM tool-use accuracy, increasing their practical utility.

[Arxiv](https://arxiv.org/abs/2509.04518)