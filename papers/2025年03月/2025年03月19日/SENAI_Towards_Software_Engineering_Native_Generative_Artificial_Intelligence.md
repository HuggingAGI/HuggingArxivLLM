# SENAI：迈向软件工程原生生成式人工智能

发布时间：2025年03月19日

`LLM应用` `软件工程`

> SENAI: Towards Software Engineering Native Generative Artificial Intelligence

# 摘要

> 大型语言模型在代码生成领域取得了显著进展，能够生成功能正确的代码片段。然而，现有生成模型忽视了软件工程中的基本原则和概念，如模块化、单一职责、内聚和耦合，这些对于构建可维护、可扩展和健壮的软件系统至关重要。这些关键概念在从预训练到基于基准测试的评估的生成流程中被完全忽视。
    本文提出了一种将软件工程知识融入大型语言模型的方法，以增强其理解和分析代码以及生成符合软件工程知识的其他SE artifacts的能力。目标是提出一种新方向，使大型语言模型能够超越单纯的功能准确性，执行需要遵循软件工程原则和最佳实践的生成任务。此外，考虑到这些对话模型的交互性，我们提出使用布卢姆 taxonomy 作为评估框架，以衡量它们对软件工程知识的内化程度。与现有的方法（如线性探测）相比，所提出的评估框架提供了更全面和可靠的评估技术。原生的软件工程生成模型不仅能够克服现有模型的不足，还将为下一代能够处理真实世界软件工程的生成模型铺平道路。

> Large Language Models have significantly advanced the field of code generation, demonstrating the ability to produce functionally correct code snippets. However, advancements in generative AI for code overlook foundational Software Engineering (SE) principles such as modularity, and single responsibility, and concepts such as cohesion and coupling which are critical for creating maintainable, scalable, and robust software systems. These concepts are missing in pipelines that start with pre-training and end with the evaluation using benchmarks.
  This vision paper argues for the integration of SE knowledge into LLMs to enhance their capability to understand, analyze, and generate code and other SE artifacts following established SE knowledge. The aim is to propose a new direction where LLMs can move beyond mere functional accuracy to perform generative tasks that require adherence to SE principles and best practices. In addition, given the interactive nature of these conversational models, we propose using Bloom's Taxonomy as a framework to assess the extent to which they internalize SE knowledge. The proposed evaluation framework offers a sound and more comprehensive evaluation technique compared to existing approaches such as linear probing. Software engineering native generative models will not only overcome the shortcomings present in current models but also pave the way for the next generation of generative models capable of handling real-world software engineering.

[Arxiv](https://arxiv.org/abs/2503.15282)