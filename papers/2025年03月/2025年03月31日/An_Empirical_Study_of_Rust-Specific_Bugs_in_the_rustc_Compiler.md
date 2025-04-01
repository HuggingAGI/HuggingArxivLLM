# # 实证研究：Rust 编译器 rustc 中特定于 Rust 的缺陷的经验研究

发布时间：2025年03月31日

`其他` `安全关键系统` `编译器技术`

> An Empirical Study of Rust-Specific Bugs in the rustc Compiler

# 摘要

> Rust凭借其广为人知的内存安全性保证和高性能，正在迅速流行起来，这使其与C/C++和基于JVM的语言区分开来。其编译器rustc通过特征解决、借用检查和特定优化等专门机制来确保这些保证。然而，Rust独特的语言机制给其编译器带来了复杂性，导致了比传统编译器更少见的Rust特定编译器错误。随着Rust在安全关键领域中的采用日益增加，理解这些语言机制及其对编译器错误的影响，对于提高rustc和Rust程序的可靠性至关重要。然而，我们仍然缺乏对rustc中Rust特定错误的大规模、详细和深入研究。
    为了填补这一空白，本研究对rustc中的Rust特定错误进行了全面和系统的分析，特别关注支持其独特语言功能的组件。我们的分析检查了2022年至2024年间报告的问题和修复，并手动审查了301个有效问题。我们根据错误的原因、症状、受影响的编译阶段和测试用例的特征对这些错误进行了分类。此外，我们评估了现有的rustc测试工具，以评估其有效性和局限性。我们的主要发现包括：（1）rustc错误主要源于Rust的类型系统和生命周期模型，由于复杂的检查器和优化，HIR（高级中间表示）和MIR（中级中间表示）模块经常出现错误；（2）揭示错误的测试用例通常涉及不稳定功能、高级特征使用、生命周期注解、标准API和特定优化级别；（3）尽管有效和无效程序都可能触发错误，但现有测试工具难以检测非崩溃错误，这凸显了进一步改进rustc测试的必要性。

> Rust is gaining popularity for its well-known memory safety guarantees and high performance, distinguishing it from C/C++ and JVM-based languages. Its compiler, rustc, enforces these guarantees through specialized mechanisms such as trait solving, borrow checking, and specific optimizations. However, Rust's unique language mechanisms introduce complexity to its compiler, leading to Rust-specific compiler bugs that are less common in traditional compilers. With Rust's increasing adoption in safety-critical domains, understanding these language mechanisms and their impact on compiler bugs is essential for improving the reliability of both rustc and Rust programs. Yet, we still lack a large-scale, detailed, and in-depth study of Rust-specific bugs in rustc.
  To bridge this gap, this work conducts a comprehensive and systematic study of Rust-specific bugs in rustc, with a particular focus on the components that support its unique language features. Our analysis examines issues and fixes reported between 2022 and 2024, with a manual review of 301 valid issues. We categorize these bugs based on their causes, symptoms, affected compilation stages, and test case characteristics. Additionally, we evaluate existing rustc testing tools to assess their effectiveness and limitations. Our key findings include: (1) rustc bugs primarily arise from Rust's type system and lifetime model, with frequent errors in the High-Level Intermediate Representation (HIR) and Mid-Level Intermediate Representation (MIR) modules due to complex checkers and optimizations; (2) bug-revealing test cases often involve unstable features, advanced trait usages, lifetime annotations, standard APIs, and specific optimization levels; (3) while both valid and invalid programs can trigger bugs, existing testing tools struggle to detect non-crash errors, underscoring the need for further advancements in rustc testing.

[Arxiv](https://arxiv.org/abs/2503.23985)