# SwiftEval：为LLM生成代码评估打造语言专属基准

发布时间：2025年05月30日

`LLM应用` `代码生成` `基准测试`

> SwiftEval: Developing a Language-Specific Benchmark for LLM-generated Code Evaluation

# 摘要

> 近年来，大型语言模型（LLMs）在代码生成领域取得了显著进展。然而，现有评估基准多专注于Python，难以高质量评估其他语言如Swift。通过分析HumanEval-XL和MultiPL-E等多语言基准测试，我们发现其Swift组件存在关键问题，难以有效评估LLM在Swift中的编码能力。与现有方法不同，我们不依赖LLM自动翻译Python基准测试，而是采用质量优先的方法。我们推出了首个专注于Swift的基准测试SwiftEval，包含28个精心设计的问题，并评估了44个流行的代码生成LLMs。结果显示，涉及Swift语言特性的任务中，LLM得分显著下降，这一趋势在小型模型中尤为明显。

> In recent years, large language models (LLMs) have showcased significant advancements in code generation. However, most evaluation benchmarks are primarily oriented towards Python, making it difficult to evaluate other programming languages, such as Swift, with high quality. By examining widely established multilingual benchmarks like HumanEval-XL and MultiPL-E, we identified critical issues specific to their Swift components, making them insufficient or even irrelevant for assessing LLM coding capabilities on Swift. Unlike these existing approaches, which prioritize rapid scaling and generalization by automatically translating Python-centric benchmarks with LLMs, we adopt a quality-over-quantity methodology. We present SwiftEval, the first Swift-oriented benchmark consisting of 28 carefully hand-crafted problems, and evaluate 44 popular Code LLMs on it. Our results show significant LLM scores drop for problems requiring language-specific features, most noticeable in the models of smaller sizes.

[Arxiv](https://arxiv.org/abs/2505.24324)