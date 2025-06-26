# 利用属性测试连接LLM代码生成与验证

发布时间：2025年06月23日

`LLM应用` `软件工程` `测试方法`

> Use Property-Based Testing to Bridge LLM Code Generation and Validation

# 摘要

> 大型语言模型（LLMs）擅长代码生成，但在复杂编程任务中确保代码功能正确性仍是一个持续的难题。传统测试驱动开发（TDD）虽然为代码优化提供了一种方法，但与LLMs结合时，常因高质量测试用例的缺乏，或自动测试生成中的问题（如测试偏见或输出预测不准确）而效果受限。本文提出了一种名为“属性生成求解器”（Property-Generated Solver）的创新框架，该框架利用属性基测试（PBT）来验证程序的高层属性或不变式，而非依赖具体的输入-输出示例。这些属性通常比直接预测详尽的测试预言更简单定义和验证，从而打破了“自我欺骗的循环”，即测试可能与它们旨在验证的代码共享相同的缺陷。属性生成求解器采用了两个协作的基于LLM的代理：生成器专注于代码生成和迭代优化，以及测试器负责管理PBT生命周期并从属性违规中制定语义丰富的反馈。由此产生的全面且可操作的反馈随后指导生成器进行优化努力。通过将PBT确立为这一迭代闭环范式的核心验证引擎，属性生成求解器为引导LLMs生成更正确、更具通用性的代码提供了一个强大的机制。在多个代码生成基准上的广泛实验结果表明，属性生成求解器在pass@1指标上实现了显著提升，相对于 established TDD methods，相对增益从23.1%到37.3%不等。

> Large Language Models (LLMs) excel at code generation, but ensuring their outputs to be functionally correct, especially in complex programming tasks, is a persistent challenge. While traditional Test-Driven Development (TDD) offers a path for code refinement, its efficacy with LLMs is often undermined by the scarcity of high-quality test cases or the pitfalls of automated test generation, including biased tests or inaccurate output predictions that can misdirect the correction process. This paper introduces Property-Generated Solver, a novel framework that leverages Property-Based Testing (PBT) to validate high-level program properties or invariants, instead of relying on specific input-output examples. These properties are often simpler to define and verify than directly predicting exhaustive test oracles, breaking the "cycle of self-deception" where tests might share flaws with the code they are meant to validate. Property-Generated Solver employs two collaborative LLM-based agents: a Generator dedicated to code generation and iterative refinement, and a Tester that manages the PBT life-cycle and formulate semantically rich feedback from property violations. The resulting comprehensive and actionable feedback then guides the Generator in its refinement efforts. By establishing PBT as the core validation engine within this iterative, closed-loop paradigm, Property-Generated Solver provides a robust mechanism for steering LLMs towards more correct and generalizable code. Extensive experimental results on multiple code generation benchmarks demonstrate that Property-Generated Solver achieves substantial pass@1 improvements, ranging from 23.1% to 37.3% relative gains over established TDD methods.

[Arxiv](https://arxiv.org/abs/2506.18315)