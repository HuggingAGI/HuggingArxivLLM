# PDL：声明式提示编程语言

发布时间：2024年10月24日

`LLM应用

**理由**：这篇论文主要讨论的是如何通过提示框架（如PDL）来简化基于大型语言模型（LLM）的应用开发，特别是针对聊天机器人、RAG或代理等常见用例。这属于LLM在实际应用中的优化和工具开发，因此归类为LLM应用。` `软件开发`

> PDL: A Declarative Prompt Programming Language

# 摘要

> 大型语言模型（LLMs）凭借其强大的文本处理能力，使得许多曾经难以实现的AI应用成为可能。然而，非结构化的文本输入和输出使得基于LLM的应用显得脆弱。为此，提示框架应运而生，它们在LLMs与外部世界之间架起桥梁。但现有框架要么学习门槛高，要么剥夺了开发者对提示的精确控制。为解决这一难题，本文推出了提示声明语言（PDL）。PDL是一种基于YAML的简洁声明性语言，将提示置于核心位置。它与众多LLM平台和模型兼容，支持开发调用LLMs和工具的交互式应用，并简化了聊天机器人、RAG或代理等常见用例的实现。我们期待PDL能让提示编程变得更简单、更稳定、更富乐趣。

> Large language models (LLMs) have taken the world by storm by making many previously difficult uses of AI feasible. LLMs are controlled via highly expressive textual prompts and return textual answers. Unfortunately, this unstructured text as input and output makes LLM-based applications brittle. This motivates the rise of prompting frameworks, which mediate between LLMs and the external world. However, existing prompting frameworks either have a high learning curve or take away control over the exact prompts from the developer. To overcome this dilemma, this paper introduces the Prompt Declaration Language (PDL). PDL is a simple declarative data-oriented language that puts prompts at the forefront, based on YAML. PDL works well with many LLM platforms and LLMs. It supports writing interactive applications that call LLMs and tools, and makes it easy to implement common use-cases such as chatbots, RAG, or agents. We hope PDL will make prompt programming simpler, less brittle, and more enjoyable.

[Arxiv](https://arxiv.org/abs/2410.19135)