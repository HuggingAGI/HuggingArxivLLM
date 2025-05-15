# 基于测试驱动开发的LLM代码生成基准：测试作为提示

发布时间：2025年05月13日

`LLM应用` `软件开发` `应用开发`

> Tests as Prompt: A Test-Driven-Development Benchmark for LLM Code Generation

# 摘要

> 我们推出了 WebApp1K，一个用于评估大型语言模型（LLMs）在测试驱动开发（TDD）任务中表现的全新基准测试。该测试中，测试用例既是代码生成的提示，也是验证依据。与传统依赖自然语言提示的方法不同，我们的基准测试专注于 LLMs 从测试用例中直接理解和实现功能的能力，更贴近真实世界中的软件开发实践。该基准测试包含 20 个应用领域的 1000 个多样化挑战，旨在评估 LLMs 在上下文长度和多特征复杂性限制下生成简洁、功能性代码的能力。研究发现，遵循指令和上下文学习能力是 TDD 成功的关键，其重要性远超一般的编码熟练度或预训练知识。通过对 19 个前沿模型的全面评估，我们发现性能瓶颈如长提示中的指令丢失问题，并提供了涵盖多种根本原因的详细错误分析。这项工作凸显了 TDD 专用基准测试的实际价值，并为提升 LLM 在严格、应用驱动的编码场景中的能力奠定了基础。

> We introduce WebApp1K, a novel benchmark for evaluating large language models (LLMs) in test-driven development (TDD) tasks, where test cases serve as both prompt and verification for code generation. Unlike traditional approaches relying on natural language prompts, our benchmark emphasizes the ability of LLMs to interpret and implement functionality directly from test cases, reflecting real-world software development practices. Comprising 1000 diverse challenges across 20 application domains, the benchmark evaluates LLMs on their ability to generate compact, functional code under the constraints of context length and multi-feature complexity. Our findings highlight instruction following and in-context learning as critical capabilities for TDD success, surpassing the importance of general coding proficiency or pretraining knowledge. Through comprehensive evaluation of 19 frontier models, we reveal performance bottlenecks, such as instruction loss in long prompts, and provide a detailed error analysis spanning multiple root causes. This work underscores the practical value of TDD-specific benchmarks and lays the foundation for advancing LLM capabilities in rigorous, application-driven coding scenarios.

[Arxiv](https://arxiv.org/abs/2505.09027)