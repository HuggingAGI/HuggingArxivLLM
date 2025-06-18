# 基于大型语言模型的 Qiskit 代码自动重构

发布时间：2025年06月17日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在Qiskit代码重构中的应用，属于LLM的实际应用案例，因此归类为LLM应用。` `量子计算` `人工智能`

> Automatic Qiskit Code Refactoring Using Large Language Models

# 摘要

> 随着量子软件框架的演进，开发者在维护与快速变化的API兼容性方面面临日益严峻的挑战。本研究提出了一种基于大型语言模型（LLMs）的Qiskit代码重构新方法。我们从官方Qiskit文档（如发布说明）中提取迁移场景分类，捕捉常见模式，例如功能模块迁移及弃用用法。将该分类与原始Python代码一同输入LLM，使其识别代码中的迁移场景并推荐重构方案。我们的方法通过结构化输入和推理过程，有效应对当前LLMs的上下文长度限制。实验结果表明，结合领域特定迁移知识的LLMs能够有效协助Qiskit代码迁移。本研究贡献了一组经过验证的提示和分类，用于将Qiskit代码从早期版本迁移到版本0.46，并提供了一种评估LLMs在量子代码迁移中的能力的方法论。

> As quantum software frameworks evolve, developers face increasing challenges in maintaining compatibility with rapidly changing APIs. In this work, we present a novel methodology for refactoring Qiskit code using large language models (LLMs). We begin by extracting a taxonomy of migration scenarios from the different sources of official Qiskit documentation (such as release notes), capturing common patterns such as migration of functionality to different modules and deprecated usage. This taxonomy, along with the original Python source code, is provided as input to an LLM, which is then tasked with identifying instances of migration scenarios in the code and suggesting appropriate refactoring solutions. Our approach is designed to address the context length limitations of current LLMs by structuring the input and reasoning process in a targeted, efficient manner. The results demonstrate that LLMs, when guided by domain-specific migration knowledge, can effectively assist in automating Qiskit code migration. This work contributes both a set of proven prompts and taxonomy for Qiskit code migration from earlier versions to version 0.46 and a methodology to asses the capabilities of LLMs to assist in the migration of quantum code.

[Arxiv](https://arxiv.org/abs/2506.14535)