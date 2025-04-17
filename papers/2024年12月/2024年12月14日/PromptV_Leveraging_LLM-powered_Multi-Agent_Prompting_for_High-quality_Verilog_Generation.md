# PromptV：借助LLM驱动的多智能体提示，实现高质量Verilog代码生成

发布时间：2024年12月14日

`Agent` `电子设计自动化` `人工智能`

> PromptV: Leveraging LLM-powered Multi-Agent Prompting for High-quality Verilog Generation

# 摘要

> 智能体大型语言模型（agentic LLMs）的最新进展展示了卓越的自动化Verilog代码生成能力。然而，现有方法要么需要大量计算资源，要么依赖LLM辅助的单智能体提示学习技术。我们首次发现，单智能体方法存在性能退化的问题，表现为生成质量下降和错误修复能力减弱。本文提出了一种创新的多智能体提示学习框架，以克服这些限制并提升代码生成质量。我们首次证明，多智能体架构不仅能有效降低性能退化风险，还能显著提升代码错误修复能力，从而生成更高质量的Verilog代码。实验结果表明，该方法在VerilogEval Machine和Human基准测试中分别达到了96.4%和96.5%的@10通过率，同时在RTLLM基准测试中实现了100%的语法和99.9%的功能@5通过率。

> Recent advances in agentic LLMs have demonstrated remarkable automated Verilog code generation capabilities. However, existing approaches either demand substantial computational resources or rely on LLM-assisted single-agent prompt learning techniques, which we observe for the first time has a degeneration issue - characterized by deteriorating generative performance and diminished error detection and correction capabilities. This paper proposes a novel multi-agent prompt learning framework to address these limitations and enhance code generation quality. We show for the first time that multi-agent architectures can effectively mitigate the degeneration risk while improving code error correction capabilities, resulting in higher-quality Verilog code generation. Experimental results show that the proposed method could achieve 96.4% and 96.5% pass@10 scores on VerilogEval Machine and Human benchmarks, respectively while attaining 100% Syntax and 99.9% Functionality pass@5 metrics on the RTLLM benchmark.

[Arxiv](https://arxiv.org/abs/2412.11014)