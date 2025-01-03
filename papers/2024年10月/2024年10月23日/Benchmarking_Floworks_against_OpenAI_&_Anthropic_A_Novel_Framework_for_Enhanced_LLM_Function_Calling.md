# Floworks 与 OpenAI 和 Anthropic 的基准测试：一个提升 LLM 函数调用的创新框架

发布时间：2024年10月23日

`LLM应用

理由：这篇论文主要讨论了如何通过新的架构（ThorV2）提升大型语言模型（LLMs）在函数调用方面的能力，特别是在实际应用场景中的表现（如HubSpot CRM操作）。论文的重点在于优化LLMs在实际任务中的性能，如准确性、可靠性、延迟和成本效率，这些都是LLM在实际应用中的关键问题。因此，这篇论文应归类为LLM应用。` `客户关系管理` `人工智能`

> Benchmarking Floworks against OpenAI & Anthropic: A Novel Framework for Enhanced LLM Function Calling

# 摘要

> 大型语言模型（LLMs）在各领域表现出色，但其经济潜力因工具使用和函数调用的挑战而受限。本文推出ThorV2，一种大幅提升LLMs函数调用能力的新架构。我们构建了一个专注于HubSpot CRM操作的基准测试，评估ThorV2与OpenAI和Anthropic的顶尖模型。结果显示，ThorV2在单API和多API调用任务的准确性、可靠性、延迟和成本效率上均优于现有模型。此外，ThorV2在多步骤任务中的可靠性和扩展性远超传统模型。我们的研究展示了使用更小LLMs实现比当前最佳模型更精准函数调用的可能性，这对开发更强大的AI助手及LLMs在现实世界的广泛应用具有重要意义。

> Large Language Models (LLMs) have shown remarkable capabilities in various domains, yet their economic impact has been limited by challenges in tool use and function calling. This paper introduces ThorV2, a novel architecture that significantly enhances LLMs' function calling abilities. We develop a comprehensive benchmark focused on HubSpot CRM operations to evaluate ThorV2 against leading models from OpenAI and Anthropic. Our results demonstrate that ThorV2 outperforms existing models in accuracy, reliability, latency, and cost efficiency for both single and multi-API calling tasks. We also show that ThorV2 is far more reliable and scales better to multistep tasks compared to traditional models. Our work offers the tantalizing possibility of more accurate function-calling compared to today's best-performing models using significantly smaller LLMs. These advancements have significant implications for the development of more capable AI assistants and the broader application of LLMs in real-world scenarios.

[Arxiv](https://arxiv.org/abs/2410.17950)