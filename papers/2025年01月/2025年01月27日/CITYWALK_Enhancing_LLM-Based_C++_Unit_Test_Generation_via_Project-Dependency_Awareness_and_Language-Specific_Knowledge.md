# CITYWALK: 利用项目依赖感知与语言特定知识，提升基于LLM的C++单元测试生成

发布时间：2025年01月27日

`LLM应用

**理由**：这篇论文主要讨论了如何利用大型语言模型（LLMs）来自动生成C++单元测试，并提出了一个基于LLM的框架CITYWALK。这属于LLM在实际应用中的具体使用场景，因此归类为LLM应用。` `软件开发` `C++`

> CITYWALK: Enhancing LLM-Based C++ Unit Test Generation via Project-Dependency Awareness and Language-Specific Knowledge

# 摘要

> # 摘要
单元测试在软件开发中至关重要，它确保了代码质量。然而，编写高质量的单元测试对开发者来说仍然耗时。最近，大型语言模型（LLMs）在自动生成单元测试方面取得了显著进展。现有方法主要针对解释型语言（如Java），而针对编译型语言如C++的成熟解决方案尚待探索。C++的复杂特性（如指针、模板和虚函数）对LLMs生成可执行且高覆盖率的单元测试提出了挑战。为此，本文提出了CITYWALK，一个基于LLM的C++单元测试生成框架。CITYWALK通过程序分析全面理解项目依赖关系，并结合C++特定知识，显著提升了LLM生成单元测试的准确性。我们使用GPT-4o实现了CITYWALK，实验结果表明，它在八个流行C++项目上优于现有方法，证明了其在生成高质量C++单元测试方面的有效性。

> Unit testing plays a pivotal role in the software development lifecycle, as it ensures code quality. However, writing high-quality unit tests remains a time-consuming task for developers in practice. More recently, the application of large language models (LLMs) in automated unit test generation has demonstrated promising results. Existing approaches primarily focus on interpreted programming languages (e.g., Java), while mature solutions tailored to compiled programming languages like C++ are yet to be explored. The intricate language features of C++, such as pointers, templates, and virtual functions, pose particular challenges for LLMs in generating both executable and high-coverage unit tests. To tackle the aforementioned problems, this paper introduces CITYWALK, a novel LLM-based framework for C++ unit test generation. CITYWALK enhances LLMs by providing a comprehensive understanding of the dependency relationships within the project under test via program analysis. Furthermore, CITYWALK incorporates language-specific knowledge about C++ derived from project documentation and empirical observations, significantly improving the correctness of the LLM-generated unit tests. We implement CITYWALK by employing the widely popular LLM GPT-4o. The experimental results show that CITYWALK outperforms current state-of-the-art approaches on a collection of eight popular C++ projects. Our findings demonstrate the effectiveness of CITYWALK in generating high-quality C++ unit tests.

[Arxiv](https://arxiv.org/abs/2501.16155)