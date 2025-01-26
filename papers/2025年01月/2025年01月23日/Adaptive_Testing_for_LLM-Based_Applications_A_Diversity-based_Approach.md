# 基于LLM的应用的自适应测试：多样性驱动的方法

发布时间：2025年01月23日

`LLM应用

理由：这篇论文主要讨论了基于大型语言模型（LLMs）的软件系统的测试框架，特别是如何优化测试套件的策划。虽然涉及到了测试技术，但其核心关注点是如何在LLM应用的背景下进行有效的测试选择和优先级策略。因此，这篇论文应归类为LLM应用。` `软件测试` `人工智能`

> Adaptive Testing for LLM-Based Applications: A Diversity-based Approach

# 摘要

> 最近，基于大型语言模型（LLMs）的软件系统蓬勃发展，催生了多种测试框架，这些框架主要将提示模板作为测试单元。尽管测试输入执行和输出评估成本高昂，但这些工具中优化测试套件的策划仍被忽视，亟需定制化的测试选择或优先级策略。本文提出，基于多样性的测试技术，如采用适当字符串距离度量的自适应随机测试（ART），可有效应用于提示模板测试。我们提出的自适应测试方法通过根据现有测试套件及其标记结果得出的分数选择新测试输入，调整了传统ART过程以适应这一场景。通过探索多种基于字符串的距离实现，我们的结果表明，该方法能在减少测试预算的情况下发现故障，并促进生成更多样化的输出。

> The recent surge of building software systems powered by Large Language Models (LLMs) has led to the development of various testing frameworks, primarily focused on treating prompt templates as the unit of testing. Despite the significant costs associated with test input execution and output assessment, the curation of optimized test suites is yet overlooked in these tools, which calls for tailored test selection or prioritization strategies. In this paper, we show that diversity-based testing techniques, such as Adaptive Random Testing (ART) with appropriate string distance metrics, can be effectively applied to the testing of prompt templates. Our proposed adaptive testing approach adjusts the conventional ART process to this context by selecting new test inputs based on scores derived from existing test suite and their labelling results. Our results, obtained using various implementations that explore several string-based distances, confirm that our approach enables the discovery of failures with reduced testing budgets and promotes the generation of more varied outputs.

[Arxiv](https://arxiv.org/abs/2501.13480)