# 用于评估生成式语言模型的参数化论辩推理任务

发布时间：2025年05月02日

`LLM应用

理由：这篇论文探讨了生成式大型语言模型在法律推理中的应用，特别是评估其推理能力的局限性。论文提出了一种动态、可扩展的基准方法，用于测试模型在不同复杂度下的表现，属于LLM在特定领域的应用研究。`

> Parameterized Argumentation-based Reasoning Tasks for Benchmarking Generative Language Models

# 摘要

> 生成式大型语言模型在法律领域有潜力改善司法体系，但当前模型的推理行为脆弱且难以理解，难以在法律和证据领域负责任地应用。本文提出了一种创建基准的方法，用于评估生成语言模型的推理能力。这些基准具有动态变化、复杂性可扩展和解释明确的特点。我们以证人证词为例，重点分析其背后的论证攻击结构。通过动态生成不同复杂度的线性和非线性论证攻击图，并将其转化为自然语言推理难题，我们发现：即使是先进大型语言模型在低复杂度下也常犯错误，表现出脆弱的推理能力。在高复杂度下，即使专门用于推理的模型也难以避免错误。这表明使用复杂性可变的参数化基准评估生成模型的推理能力是可行的。这些发现有助于我们更好地理解生成模型推理能力的局限性，这对于设计负责任的法律领域AI系统至关重要。

> Generative large language models as tools in the legal domain have the potential to improve the justice system. However, the reasoning behavior of current generative models is brittle and poorly understood, hence cannot be responsibly applied in the domains of law and evidence. In this paper, we introduce an approach for creating benchmarks that can be used to evaluate the reasoning capabilities of generative language models. These benchmarks are dynamically varied, scalable in their complexity, and have formally unambiguous interpretations. In this study, we illustrate the approach on the basis of witness testimony, focusing on the underlying argument attack structure. We dynamically generate both linear and non-linear argument attack graphs of varying complexity and translate these into reasoning puzzles about witness testimony expressed in natural language. We show that state-of-the-art large language models often fail in these reasoning puzzles, already at low complexity. Obvious mistakes are made by the models, and their inconsistent performance indicates that their reasoning capabilities are brittle. Furthermore, at higher complexity, even state-of-the-art models specifically presented for reasoning capabilities make mistakes. We show the viability of using a parametrized benchmark with varying complexity to evaluate the reasoning capabilities of generative language models. As such, the findings contribute to a better understanding of the limitations of the reasoning capabilities of generative models, which is essential when designing responsible AI systems in the legal domain.

[Arxiv](https://arxiv.org/abs/2505.01539)