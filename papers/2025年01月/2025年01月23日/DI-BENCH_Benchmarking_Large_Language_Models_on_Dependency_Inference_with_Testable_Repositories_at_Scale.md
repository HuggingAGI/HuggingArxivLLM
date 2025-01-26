# DI-BENCH：大规模可测试仓库中大型语言模型的依赖推断基准测试

发布时间：2025年01月23日

`LLM应用

理由：这篇论文讨论了大型语言模型（LLM）在自动化软件开发中的应用，特别是依赖推断能力的评估。论文提出了一个基准和评估框架（DI-BENCH），用于评估LLMs在仓库上的性能。这属于LLM在实际应用中的具体使用场景，因此分类为“LLM应用”。` `软件开发` `依赖管理`

> DI-BENCH: Benchmarking Large Language Models on Dependency Inference with Testable Repositories at Scale

# 摘要

> 大型语言模型推动了自动化软件开发的进步，但正确推断依赖关系——即识别仓库运行所需的内部组件和外部包——仍是一大挑战。研究表明，依赖问题导致了超过40%的生成仓库运行时错误。为此，我们推出了DI-BENCH，一个专门评估LLMs依赖推断能力的大规模基准和评估框架。该基准包含581个仓库，覆盖Python、C#、Rust和JavaScript的测试环境。实验结果显示，当前最佳模型的执行通过率仅为42.9%，表明仍有巨大改进空间。DI-BENCH为评估LLMs在仓库上的性能提供了新视角，为更健壮的端到端软件合成奠定了基础。

> Large Language Models have advanced automated software development, however, it remains a challenge to correctly infer dependencies, namely, identifying the internal components and external packages required for a repository to successfully run. Existing studies highlight that dependency-related issues cause over 40\% of observed runtime errors on the generated repository. To address this, we introduce DI-BENCH, a large-scale benchmark and evaluation framework specifically designed to assess LLMs' capability on dependency inference. The benchmark features 581 repositories with testing environments across Python, C#, Rust, and JavaScript. Extensive experiments with textual and execution-based metrics reveal that the current best-performing model achieves only a 42.9% execution pass rate, indicating significant room for improvement. DI-BENCH establishes a new viewpoint for evaluating LLM performance on repositories, paving the way for more robust end-to-end software synthesis.

[Arxiv](https://arxiv.org/abs/2501.13699)