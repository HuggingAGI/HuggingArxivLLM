# LLMigrate: 唤醒“懒惰”的大型语言模型，打造高效的源代码迁移工具

发布时间：2025年03月31日

`LLM应用

理由：这篇论文探讨了利用大型语言模型（LLM）进行C到Rust代码迁移的应用，属于将LLM技术应用于实际编程任务的范畴，因此归类为LLM应用。` `软件开发` `编译器`

> LLMigrate: Transforming "Lazy" Large Language Models into Efficient Source Code Migrators

# 摘要

> 将C代码迁移到Rust虽然能显著提升内存安全性，但面对像Linux内核这样庞大的代码库（拥有3200万行代码），这一过程依然充满挑战。现有的基于规则的翻译工具，如C2Rust，虽然能够生成准确的Rust代码，但这些代码大多不够安全。近期的大型语言模型（LLM）方法虽然生成的Rust代码更符合语言习惯且更安全，但它们往往“偷工减料”，遗漏大量关键代码。为解决这一难题，我们提出了LLMigrate——一个基于LLM的C到Rust翻译工具。该工具通过将模块拆分为独立的函数进行分别翻译，再重新整合。LLMigrate借助静态分析保留必要上下文，结合GPT-4o（一款顶尖的LLM）与编译器驱动的翻译及程序修复技术，专注于处理复杂的核心函数，并采用调用图引导的翻译策略，确保接口的一致性。在对math、sort和ramfs这三个典型的Linux内核模块进行评估后发现，LLMigrate仅需修改不到15%的目标代码，相较于纯GPT-4o迁移方法，性能有了显著提升。

> Rewriting C code in Rust provides stronger memory safety, yet migrating large codebases such as the 32-million-line Linux kernel remains challenging. While rule-based translators (e.g., C2Rust) provide accurate yet largely unsafe Rust programs, recent Large Language Model (LLM) approaches produce more idiomatic, safe Rust programs but frequently exhibit "laziness", omitting significant portions of the target code. To address the issue, in this paper, we present LLMigrate, an LLM-based C-to-Rust translation tool that splits modules into discrete functions, translating them individually, and then reintegrating them. LLMigrate uses static analysis to retain necessary context, pairs GPT-4o (a state-of-the-art LLM) with compiler-driven translation and program-repair techniques for complex core functions, and leverages call-graph-guided translation to ensure consistent interfaces. Evaluations on three representative Linux kernel modules (math, sort, and ramfs) show that LLMigrate requires modifying less than 15\% of the target code, significantly outperforming a pure GPT-4o-based migration.

[Arxiv](https://arxiv.org/abs/2503.23791)