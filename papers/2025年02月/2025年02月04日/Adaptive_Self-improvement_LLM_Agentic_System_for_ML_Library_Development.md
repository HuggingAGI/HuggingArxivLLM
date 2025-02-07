# 用于机器学习库开发的自适应自我改进LLM智能体系统

发布时间：2025年02月04日

`Agent

**理由**：这篇论文提出了一种自适应自我改进的智能体系统，用于生成基于特定领域架构的编程语言（ASPLs）的机器学习库代码。智能体系统通过自我改进和自适应机制，解决了在数据有限的情况下进行复杂推理的挑战。因此，这篇论文的核心内容与智能体（Agent）相关，属于Agent分类。` `机器学习` `编程语言`

> Adaptive Self-improvement LLM Agentic System for ML Library Development

# 摘要

> ML 库通常采用针对特定领域架构的架构特定编程语言（ASPLs）编写，是高效 ML 系统的核心。然而，编写这些高性能 ML 库颇具挑战，因为它需要 ML 算法和 ASPL 的深厚知识。另一方面，大型语言模型（LLMs）展现了强大的通用编码能力。然而，使用 LLMs 生成基于 ASPLs 的 ML 库仍面临两大挑战：1) 即使对经验丰富的程序员来说，这项任务也相当复杂；2) 由于 ASPLs 的深奥性和不断演进，相关代码示例稀缺。因此，LLMs 需要在数据有限的情况下进行复杂推理才能完成任务。为此，我们提出了一种自适应自我改进的智能体系统。为验证其有效性，我们构建了一个典型 ML 库的基准，并在该基准上使用开源和闭源 LLMs 生成 ASPL 代码。结果显示，与单一 LLM 基线相比，性能提升高达 $3.9\times$。

> ML libraries, often written in architecture-specific programming languages (ASPLs) that target domain-specific architectures, are key to efficient ML systems. However, writing these high-performance ML libraries is challenging because it requires expert knowledge of ML algorithms and the ASPL. Large language models (LLMs), on the other hand, have shown general coding capabilities. However, challenges remain when using LLMs for generating ML libraries using ASPLs because 1) this task is complicated even for experienced human programmers and 2) there are limited code examples because of the esoteric and evolving nature of ASPLs. Therefore, LLMs need complex reasoning with limited data in order to complete this task. To address these challenges, we introduce an adaptive self-improvement agentic system. In order to evaluate the effectiveness of our system, we construct a benchmark of a typical ML library and generate ASPL code with both open and closed-source LLMs on this benchmark. Our results show improvements of up to $3.9\times$ over a baseline single LLM.

[Arxiv](https://arxiv.org/abs/2502.02534)