# PRIMG：高效LLM驱动测试生成，基于变异体优先级排序

发布时间：2025年05月08日

`LLM应用

理由：这篇论文探讨了如何利用大型语言模型（LLMs）生成和优化测试用例，特别是在Solidity智能合约的变异测试中。它展示了LLMs在测试生成中的具体应用，属于LLM应用类别。` `软件工程` `区块链`

> PRIMG : Efficient LLM-driven Test Generation Using Mutant Prioritization

# 摘要

> 变异测试是一种广为人知的技术，通过引入故意的代码突变来评估和提升软件测试套件的有效性。然而，其应用常常导致测试套件过大，因为开发人员会生成大量测试用例以消灭特定突变体，从而增加了计算开销。本文介绍了PRIMG（优先级排序与优化相结合的变异驱动生成框架），一种用于Solidity智能合约的增量式和自适应测试用例生成的新颖框架。PRIMG整合了两个核心组件：一个变异体优先级排序模块，该模块使用基于突变体子集图训练的机器学习模型来预测存活突变体的有用性；以及一个测试用例生成模块，该模块利用大型语言模型（LLMs）生成并迭代优化测试用例，以实现语义和行为上的正确性。

我们通过评估PRIMG在Code4Arena的真实Solidity项目中的表现，验证了其在提升变异覆盖率和生成高质量测试用例方面的有效性。实验结果表明，PRIMG显著减少了测试套件的规模，同时保持了高变异覆盖度。优先级排序模块在随机突变体选择中表现更优，能够以更少的计算开销生成高影响力的测试用例。此外，优化过程提升了LLM生成测试用例的正确性和实用性，弥补了其在处理边界条件和复杂程序逻辑方面的固有局限性。

> Mutation testing is a widely recognized technique for assessing and enhancing the effectiveness of software test suites by introducing deliberate code mutations. However, its application often results in overly large test suites, as developers generate numerous tests to kill specific mutants, increasing computational overhead. This paper introduces PRIMG (Prioritization and Refinement Integrated Mutation-driven Generation), a novel framework for incremental and adaptive test case generation for Solidity smart contracts. PRIMG integrates two core components: a mutation prioritization module, which employs a machine learning model trained on mutant subsumption graphs to predict the usefulness of surviving mutants, and a test case generation module, which utilizes Large Language Models (LLMs) to generate and iteratively refine test cases to achieve syntactic and behavioral correctness.
  We evaluated PRIMG on real-world Solidity projects from Code4Arena to assess its effectiveness in improving mutation scores and generating high-quality test cases. The experimental results demonstrate that PRIMG significantly reduces test suite size while maintaining high mutation coverage. The prioritization module consistently outperformed random mutant selection, enabling the generation of high-impact tests with reduced computational effort. Furthermore, the refining process enhanced the correctness and utility of LLM-generated tests, addressing their inherent limitations in handling edge cases and complex program logic.

[Arxiv](https://arxiv.org/abs/2505.05584)