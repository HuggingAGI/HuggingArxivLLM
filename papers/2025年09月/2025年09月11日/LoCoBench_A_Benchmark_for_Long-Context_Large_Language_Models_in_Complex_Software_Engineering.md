# LoCoBench：面向复杂软件工程的长上下文大语言模型基准测试

发布时间：2025年09月11日

`LLM应用` `基础理论`

> LoCoBench: A Benchmark for Long-Context Large Language Models in Complex Software Engineering

# 摘要

> 长上下文语言模型的问世（其上下文窗口可扩展至数百万token）为复杂代码理解与软件开发评估开辟了新可能。为此，我们提出LoCoBench——一个专为在真实复杂软件开发场景中评估长上下文大型语言模型（LLMs）而设计的综合基准。不同于现有代码评估基准多聚焦于单函数补全或短上下文任务，LoCoBench填补了长上下文能力评估的关键空白，这类能力要求模型理解整个代码库、跨文件推理，并在大型软件系统中保持架构一致性。该基准包含8000个评估场景，覆盖10种编程语言，上下文长度从10K到1M token不等，100倍的跨度可精准衡量真实开发场景下长上下文性能的衰减情况。LoCoBench设计了8个任务类别，全面考察核心长上下文能力：架构理解、跨文件重构、多会话开发、漏洞排查、功能实现、代码理解、集成测试及安全分析。通过5阶段生成流程，我们构建了多样化、高质量的场景，要求模型在前所未有的规模上对复杂代码库进行推理。我们还提出综合评估框架，涵盖4个维度的17个指标（含8个新指标），并将其整合为LoCoBench分数（LCBS）。对最先进长上下文模型的评估显示，它们存在显著性能差距，这表明复杂软件开发中的长上下文理解仍是亟待解决的重大挑战，值得更多关注。LoCoBench已开源：https://github.com/SalesforceAIResearch/LoCoBench。

> The emergence of long-context language models with context windows extending to millions of tokens has created new opportunities for sophisticated code understanding and software development evaluation. We propose LoCoBench, a comprehensive benchmark specifically designed to evaluate long-context LLMs in realistic, complex software development scenarios. Unlike existing code evaluation benchmarks that focus on single-function completion or short-context tasks, LoCoBench addresses the critical evaluation gap for long-context capabilities that require understanding entire codebases, reasoning across multiple files, and maintaining architectural consistency across large-scale software systems. Our benchmark provides 8,000 evaluation scenarios systematically generated across 10 programming languages, with context lengths spanning 10K to 1M tokens, a 100x variation that enables precise assessment of long-context performance degradation in realistic software development settings. LoCoBench introduces 8 task categories that capture essential long-context capabilities: architectural understanding, cross-file refactoring, multi-session development, bug investigation, feature implementation, code comprehension, integration testing, and security analysis. Through a 5-phase pipeline, we create diverse, high-quality scenarios that challenge LLMs to reason about complex codebases at unprecedented scale. We introduce a comprehensive evaluation framework with 17 metrics across 4 dimensions, including 8 new evaluation metrics, combined in a LoCoBench Score (LCBS). Our evaluation of state-of-the-art long-context models reveals substantial performance gaps, demonstrating that long-context understanding in complex software development represents a significant unsolved challenge that demands more attention. LoCoBench is released at: https://github.com/SalesforceAIResearch/LoCoBench.

[Arxiv](https://arxiv.org/abs/2509.09614)