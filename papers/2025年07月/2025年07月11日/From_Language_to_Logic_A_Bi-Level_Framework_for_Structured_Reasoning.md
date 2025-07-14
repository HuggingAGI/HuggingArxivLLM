# 语言到逻辑：结构化推理的双层框架

发布时间：2025年07月11日

`LLM应用` `人工智能` `推理系统`

> From Language to Logic: A Bi-Level Framework for Structured Reasoning

# 摘要

> 在自然语言处理中，结构化推理依然是核心挑战，因为它需要弥合非结构化语言表达与形式化逻辑表示之间的鸿沟。本文提出了一种创新的双层框架，通过两阶段过程实现语言到逻辑的映射：高层任务抽象与低层逻辑生成。在高层，大型语言模型（LLM）将自然语言查询解析为中间结构化表示，明确问题类型、目标、决策变量及符号约束。在低层，LLM 利用这些表示生成符号工作流或可执行推理程序，以实现准确且可解释的决策。该框架支持模块化推理，强制执行显式约束，并在数学问题求解、问答及逻辑推理等领域具有良好的跨域泛化能力。我们进一步采用端到端双层优化方法优化框架，同时精调高层抽象与低层逻辑生成阶段。在多个现实推理基准上的实验表明，我们的方法在准确性方面显著超越现有基线，准确率提升高达40%。此外，双层设计增强了透明度与错误可追溯性，为实现可信且系统的LLM推理迈出了重要一步。

> Structured reasoning over natural language inputs remains a core challenge in artificial intelligence, as it requires bridging the gap between unstructured linguistic expressions and formal logical representations. In this paper, we propose a novel \textbf{bi-level framework} that maps language to logic through a two-stage process: high-level task abstraction and low-level logic generation. At the upper level, a large language model (LLM) parses natural language queries into intermediate structured representations specifying the problem type, objectives, decision variables, and symbolic constraints. At the lower level, the LLM uses these representations to generate symbolic workflows or executable reasoning programs for accurate and interpretable decision making. The framework supports modular reasoning, enforces explicit constraints, and generalizes across domains such as mathematical problem solving, question answering, and logical inference. We further optimize the framework with an end-to-end {bi-level} optimization approach that jointly refines both the high-level abstraction and low-level logic generation stages. Experiments on multiple realistic reasoning benchmarks demonstrate that our approach significantly outperforms existing baselines in accuracy, with accuracy gains reaching as high as 40\%. Moreover, the bi-level design enhances transparency and error traceability, offering a promising step toward trustworthy and systematic reasoning with LLMs.

[Arxiv](https://arxiv.org/abs/2507.08501)