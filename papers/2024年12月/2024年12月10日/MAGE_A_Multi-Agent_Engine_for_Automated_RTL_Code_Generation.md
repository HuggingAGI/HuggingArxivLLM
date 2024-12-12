# MAGE：一款用于自动生成 RTL 代码的多智能体引擎

发布时间：2024年12月10日

`LLM应用` `芯片设计` `软件开发`

> MAGE: A Multi-Agent Engine for Automated RTL Code Generation

# 摘要

> 随着大型语言模型（LLMs）的发展，通过自然语言指令自动生成 RTL 代码（比如 Verilog）已成为颇具前景的方向。然而，生成语法和功能皆正确的 RTL 代码仍是重大挑战。现有的单 LLM 代理方法存在诸多限制，因其必须在多种编程语言间穿梭，并处理繁杂的生成、验证及修改任务。为应对这些难题，本文引入了 MAGE，这是首个专为强大且精准的 Verilog RTL 代码生成而设计的开源多代理 AI 系统。我们提出了新颖的高温 RTL 候选采样与调试系统，能有效探索代码候选空间，大幅提升候选质量。此外，我们还设计了全新的 Verilog 状态检查点检查机制，可早期检测功能错误，并为有针对性的修复提供精准反馈，显著增强了生成的 RTL 代码的功能正确性。MAGE 在 VerilogEval-Human 2 基准测试中实现了 95.7%的语法和功能正确性代码生成率，比最先进的 Claude-3.5-sonnet 高出 23.3%，展现了一种强大且可靠的 AI 驱动 RTL 设计工作流程方法。

> The automatic generation of RTL code (e.g., Verilog) through natural language instructions has emerged as a promising direction with the advancement of large language models (LLMs). However, producing RTL code that is both syntactically and functionally correct remains a significant challenge. Existing single-LLM-agent approaches face substantial limitations because they must navigate between various programming languages and handle intricate generation, verification, and modification tasks. To address these challenges, this paper introduces MAGE, the first open-source multi-agent AI system designed for robust and accurate Verilog RTL code generation. We propose a novel high-temperature RTL candidate sampling and debugging system that effectively explores the space of code candidates and significantly improves the quality of the candidates. Furthermore, we design a novel Verilog-state checkpoint checking mechanism that enables early detection of functional errors and delivers precise feedback for targeted fixes, significantly enhancing the functional correctness of the generated RTL code. MAGE achieves a 95.7% rate of syntactic and functional correctness code generation on VerilogEval-Human 2 benchmark, surpassing the state-of-the-art Claude-3.5-sonnet by 23.3 %, demonstrating a robust and reliable approach for AI-driven RTL design workflows.

[Arxiv](https://arxiv.org/abs/2412.07822)