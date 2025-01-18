# OptiChat: 用大型语言模型架起优化模型与实践者之间的桥梁

发布时间：2025年01月14日

`LLM应用

理由：这篇论文介绍了一个名为OptiChat的自然语言对话系统，该系统利用大型语言模型（LLMs）来帮助非优化专业的从业者与优化模型进行交互。OptiChat通过功能调用和代码生成来增强LLMs的能力，使其能够解释模型、诊断问题、分析敏感性等。这属于LLM在实际应用中的使用，因此分类为“LLM应用”。` `决策支持`

> OptiChat: Bridging Optimization Models and Practitioners with Large Language Models

# 摘要

> 优化模型广泛应用于各类决策问题，通常由优化专家开发，但使用者多为非优化专业的从业者。这导致从业者难以独立与模型互动并获取有用结论。为此，我们推出了OptiChat，一个自然语言对话系统，帮助从业者解读模型、诊断问题、分析敏感性、检索信息、评估修改并提供反事实解释。通过为优化模型定制的功能调用和代码生成，OptiChat增强了LLMs的能力，实现了无缝交互并降低了幻觉风险。我们还开发了新数据集来评估OptiChat在解释优化模型方面的表现。实验证明，OptiChat成功弥合了优化模型与从业者之间的鸿沟，提供了自主、准确且即时的响应。

> Optimization models have been applied to solve a wide variety of decision-making problems. These models are usually developed by optimization experts but are used by practitioners without optimization expertise in various application domains. As a result, practitioners often struggle to interact with and draw useful conclusions from optimization models independently. To fill this gap, we introduce OptiChat, a natural language dialogue system designed to help practitioners interpret model formulation, diagnose infeasibility, analyze sensitivity, retrieve information, evaluate modifications, and provide counterfactual explanations. By augmenting large language models (LLMs) with functional calls and code generation tailored for optimization models, we enable seamless interaction and minimize the risk of hallucinations in OptiChat. We develop a new dataset to evaluate OptiChat's performance in explaining optimization models. Experiments demonstrate that OptiChat effectively bridges the gap between optimization models and practitioners, delivering autonomous, accurate, and instant responses.

[Arxiv](https://arxiv.org/abs/2501.08406)