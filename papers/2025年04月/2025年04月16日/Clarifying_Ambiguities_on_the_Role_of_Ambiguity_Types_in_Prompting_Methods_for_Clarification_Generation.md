# 澄清歧义：探讨提示方法中歧义类型对澄清生成的影响

发布时间：2025年04月16日

`LLM应用

摘要中的论文探讨了如何利用大型语言模型（LLMs）生成澄清以解决信息检索中的歧义问题。通过提出一种新的提示方案（AT-CoT），研究旨在提高LLMs在处理用户查询时的推理能力。这属于LLM的应用层面，因为它关注于如何在实际应用中优化LLMs的表现，而不是探讨模型本身的理论或结构。` `信息检索` `对话系统`

> Clarifying Ambiguities: on the Role of Ambiguity Types in Prompting Methods for Clarification Generation

# 摘要

> 在信息检索（IR）领域，提供适当的澄清以更好地理解用户的信息需求，对于构建主动的搜索导向对话系统至关重要。由于大型语言模型（LLMs）具备强大的上下文学习能力，近期研究探讨了通过提示方法，利用少量样本或思维链（CoT）提示生成澄清。然而，传统的CoT提示方法未能区分不同信息需求的特征，使得理解LLMs如何解析用户查询中的歧义变得困难。本研究聚焦于澄清中的歧义概念，旨在在澄清过程中建模并整合歧义。为此，我们全面研究了基于推理和歧义的提示方案对澄清的影响。我们的思路是通过限制CoT首先预测可解释为澄清指令的第一类歧义类型，从而增强LLMs的推理能力，随后相应生成澄清。我们将这一新型提示方案命名为歧义类型-思维链（AT-CoT）。我们通过在包含人工标注澄清问题的多个数据集上进行实验，将AT-CoT与多个基线方法进行比较。此外，我们还进行了用户模拟，以隐式评估不同IR场景下生成澄清的质量。

> In information retrieval (IR), providing appropriate clarifications to better understand users' information needs is crucial for building a proactive search-oriented dialogue system. Due to the strong in-context learning ability of large language models (LLMs), recent studies investigate prompting methods to generate clarifications using few-shot or Chain of Thought (CoT) prompts. However, vanilla CoT prompting does not distinguish the characteristics of different information needs, making it difficult to understand how LLMs resolve ambiguities in user queries. In this work, we focus on the concept of ambiguity for clarification, seeking to model and integrate ambiguities in the clarification process. To this end, we comprehensively study the impact of prompting schemes based on reasoning and ambiguity for clarification. The idea is to enhance the reasoning abilities of LLMs by limiting CoT to predict first ambiguity types that can be interpreted as instructions to clarify, then correspondingly generate clarifications. We name this new prompting scheme Ambiguity Type-Chain of Thought (AT-CoT). Experiments are conducted on various datasets containing human-annotated clarifying questions to compare AT-CoT with multiple baselines. We also perform user simulations to implicitly measure the quality of generated clarifications under various IR scenarios.

[Arxiv](https://arxiv.org/abs/2504.12113)