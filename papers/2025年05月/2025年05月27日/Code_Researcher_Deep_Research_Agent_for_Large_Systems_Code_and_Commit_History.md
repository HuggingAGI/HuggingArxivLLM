# 代码研究者：专注于大型系统代码与提交历史的深度智能体

发布时间：2025年05月27日

`Agent` `软件工程` `程序修复`

> Code Researcher: Deep Research Agent for Large Systems Code and Commit History

# 摘要

> 基于大型语言模型的编码代理在代码基准测试中表现优异，但其在系统代码上的实际效果仍有待进一步研究。由于系统代码的复杂性和规模，即使是经验丰富的开发人员，对其进行修改也是一项极具挑战性的任务。在做出任何更改之前，需要从庞大的代码库和海量的提交历史中研究大量上下文信息。受近期深度研究代理技术的启发，我们设计了首个专注于代码的深度研究代理——Code Researcher，并将其应用于解决系统代码中报告的崩溃问题的补丁生成任务。Code Researcher通过多步推理分析代码的语义、模式和提交历史，从而收集足够的上下文信息。这些上下文信息被存储在结构化记忆中，用于合成修复补丁。我们在kBenchSyz（一个Linux内核崩溃基准测试）上对Code Researcher进行了评估，结果显示它显著优于强大的基线模型，达到了58%的崩溃解决率，而SWE-agent仅为37.5%。平均而言，Code Researcher在每个轨迹中探索10个文件，而SWE-agent仅探索1.33个文件，这突显了Code Researcher对代码库的深入探索能力。通过在开源多媒体软件上的另一个实验，我们展示了Code Researcher的通用性。我们的实验结果强调了在大型代码库中收集全局上下文和进行多方面推理的重要性。

> Large Language Model (LLM)-based coding agents have shown promising results on coding benchmarks, but their effectiveness on systems code remains underexplored. Due to the size and complexities of systems code, making changes to a systems codebase is a daunting task, even for humans. It requires researching about many pieces of context, derived from the large codebase and its massive commit history, before making changes. Inspired by the recent progress on deep research agents, we design the first deep research agent for code, called Code Researcher, and apply it to the problem of generating patches for mitigating crashes reported in systems code. Code Researcher performs multi-step reasoning about semantics, patterns, and commit history of code to gather sufficient context. The context is stored in a structured memory which is used for synthesizing a patch. We evaluate Code Researcher on kBenchSyz, a benchmark of Linux kernel crashes, and show that it significantly outperforms strong baselines, achieving a crash-resolution rate of 58%, compared to 37.5% by SWE-agent. On an average, Code Researcher explores 10 files in each trajectory whereas SWE-agent explores only 1.33 files, highlighting Code Researcher's ability to deeply explore the codebase. Through another experiment on an open-source multimedia software, we show the generalizability of Code Researcher. Our experiments highlight the importance of global context gathering and multi-faceted reasoning for large codebases.

[Arxiv](https://arxiv.org/abs/2506.11060)