# 代码演化：基于交互驱动与混合迭代反馈的代码中心数据合成

发布时间：2025年07月25日

`LLM应用` `软件工程` `代码生成`

> CodeEvo: Interaction-Driven Synthesis of Code-centric Data through Hybrid and Iterative Feedback

# 摘要

> 训练用于代码生成的大型语言模型 (LLMs)，获取高质量的指令-代码对至关重要。然而，人工整理的数据成本高昂且规模有限，因此推动了以代码为中心的合成方法的发展。现有方法要么专注于增强现有代码，要么依赖预定义的启发式规则，这两种方式都缺乏严格的验证，导致合成数据出现不切实际、重复或过于简单的问题。受协作编程实践的启发，我们提出了 CodeEvo，一个通过两个 LLM 代理之间迭代交互来合成代码数据的框架：Coder 代理根据给定指令生成候选代码和测试用例，Reviewer 代理通过生成新指令和反馈来引导合成过程。我们还引入了一种结合编译器确定性和代理生成灵活性的混合反馈机制，从而在整个合成过程中实现自动质量控制。大量实验表明，基于 CodeEvo 数据进行微调的模型在不同难度的代码生成基准测试中显著超越了现有基线。深入分析进一步从多个角度揭示了有效的以代码为中心的数据合成方法。


> Acquiring high-quality instruction-code pairs is essential for training Large Language Models (LLMs) for code generation. Manually curated data is expensive and inherently limited in scale, motivating the development of code-centric synthesis methods. Yet, current approaches either focus on augmenting existing code or rely on predefined heuristics, both lacking rigorous data validation, which results in synthetic data that is ungrounded, repetitive, or overly simplistic. Inspired by collaborative programming practices, we propose CodeEvo, a framework that synthesizes code data through iterative interactions between two LLM agents: a Coder, which generates candidate code and test cases based on given instructions, and a Reviewer, which guides the synthesis process by producing new instructions and feedback. We further introduce a hybrid feedback mechanism that combines compiler determinism with the generative flexibility of agents, enabling automatic quality control throughout synthesis. Extensive experiments demonstrate that models fine-tuned on CodeEvo data significantly outperform established baselines across code generation benchmarks with various difficulties. In-depth analyses further provide insights from multiple perspectives into effective code-centric data synthesis.

[Arxiv](https://arxiv.org/abs/2507.22080)