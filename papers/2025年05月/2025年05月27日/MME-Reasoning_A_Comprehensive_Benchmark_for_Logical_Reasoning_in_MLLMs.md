# MME-推理：多模态大语言模型的综合性逻辑推理评测基准

发布时间：2025年05月27日

`LLM理论` `人工智能` `基准测试`

> MME-Reasoning: A Comprehensive Benchmark for Logical Reasoning in MLLMs

# 摘要

> 逻辑推理是人类智能的核心，也是多模态大语言模型 (MLLMs) 的关键能力。尽管多模态推理取得了显著进展，但现有基准测试未能全面评估推理能力，原因在于缺乏逻辑推理类型的明确分类以及对推理本质的模糊理解。为了解决这些问题，我们推出了 MME-Reasoning，这是一个全面设计的基准测试，旨在评估 MLLMs 的推理能力，其问题涵盖了归纳、演绎和溯因推理三种类型。我们精心整理数据，确保每个问题都能有效评估推理能力，而非感知技能或知识广度，并扩展了评估协议以涵盖多样化问题的评估。我们的评估揭示了在全面评估逻辑推理能力时，最先进 MLLMs 的重大局限性。即使是最先进的 MLLMs，在全面逻辑推理方面也表现出有限的性能，且在推理类型之间存在显著的性能不平衡。此外，我们深入分析了“思考模式”和基于规则的强化学习等方法，这些方法通常被认为能够增强推理能力。这些发现凸显了当前 MLLMs 在多样化逻辑推理场景中的关键限制和性能不平衡，为理解和评估推理能力提供了全面而系统的见解。

> Logical reasoning is a fundamental aspect of human intelligence and an essential capability for multimodal large language models (MLLMs). Despite the significant advancement in multimodal reasoning, existing benchmarks fail to comprehensively evaluate their reasoning abilities due to the lack of explicit categorization for logical reasoning types and an unclear understanding of reasoning. To address these issues, we introduce MME-Reasoning, a comprehensive benchmark designed to evaluate the reasoning ability of MLLMs, which covers all three types of reasoning (i.e., inductive, deductive, and abductive) in its questions. We carefully curate the data to ensure that each question effectively evaluates reasoning ability rather than perceptual skills or knowledge breadth, and extend the evaluation protocols to cover the evaluation of diverse questions. Our evaluation reveals substantial limitations of state-of-the-art MLLMs when subjected to holistic assessments of logical reasoning capabilities. Even the most advanced MLLMs show limited performance in comprehensive logical reasoning, with notable performance imbalances across reasoning types. In addition, we conducted an in-depth analysis of approaches such as ``thinking mode'' and Rule-based RL, which are commonly believed to enhance reasoning abilities. These findings highlight the critical limitations and performance imbalances of current MLLMs in diverse logical reasoning scenarios, providing comprehensive and systematic insights into the understanding and evaluation of reasoning capabilities.

[Arxiv](https://arxiv.org/abs/2505.21327)