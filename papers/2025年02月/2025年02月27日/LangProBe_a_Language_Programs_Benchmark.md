# # LangProBe：语言程序评测基准

发布时间：2025年02月27日

`LLM应用` `人工智能` `基准测试`

> LangProBe: a Language Programs Benchmark

# 摘要

> 将语言模型 (LMs) 组合成多步语言程序并自动优化其模块化提示，已成为构建 AI 系统的主要方法，但这一领域的权衡问题此前研究极少。我们引入 LangProBe，这是首个用于评估语言程序架构与优化策略的大型基准测试，涵盖超过 2000 种任务、架构、优化器和语言模型的组合。借助 LangProBe，我们首次研究了程序架构和优化器（及其与不同模型的组合）对质量和成本权衡的影响。我们发现，经过优化的语言程序在质量和成本上比直接调用模型有显著的帕累托改进，但同时也证明，关于哪些组合值得追求，仍需人类判断（或经验决策）才能取得最佳效果。我们将开源 LangProBe 的代码和评估数据。

> Composing language models (LMs) into multi-step language programs and automatically optimizing their modular prompts is now a mainstream paradigm for building AI systems, but the tradeoffs in this space have only scarcely been studied before. We introduce LangProBe, the first large-scale benchmark for evaluating the architectures and optimization strategies for language programs, with over 2000 combinations of tasks, architectures, optimizers, and choices of LMs. Using LangProBe, we are the first to study the impact of program architectures and optimizers (and their compositions together and with different models) on tradeoffs of quality and cost. We find that optimized language programs offer strong cost--quality Pareto improvement over raw calls to models, but simultaneously demonstrate that human judgment (or empirical decisions) about which compositions to pursue is still necessary for best performance. We will open source the code and evaluation data for LangProBe.

[Arxiv](https://arxiv.org/abs/2502.20315)