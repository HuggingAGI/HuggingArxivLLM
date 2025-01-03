# ExecRepoBench: 多层次可执行代码补全评估

发布时间：2024年12月16日

`LLM应用

理由：这篇论文主要讨论了如何通过构建仓库级基准和指令语料库来提升开源大型语言模型（LLMs）在代码补全任务中的表现。论文还提出了一个基于多级语法的补全方法，并在微调后的LLM上进行了实验。这些内容都属于LLM在实际应用中的优化和改进，因此应归类为LLM应用。` `软件开发` `代码补全`

> ExecRepoBench: Multi-level Executable Code Completion Evaluation

# 摘要

> # 摘要
代码补全已成为软件开发中的必备工具。然而，现有评估基准多采用静态方法，难以全面反映真实编码环境的动态特性，且面临上下文长度有限、评估指标表面化及对训练数据过拟合等挑战。为此，我们提出了一个创新框架，通过构建仓库级基准ExecRepoBench和指令语料库Repo-Instruct，旨在提升开源大型语言模型（LLMs）在跨文件复杂依赖的真实编码场景中的表现。ExecRepoBench包含1.2K个活跃Python仓库样本。我们还提出了一种基于多级语法的补全方法，利用抽象语法树在语句、表达式和函数等逻辑单元上屏蔽代码片段。随后，我们在Repo-Instruct上微调了7B参数的开源LLM，生成了强大的代码补全基线模型Qwen2.5-Coder-Instruct-C。该模型在MultiPL-E和ExecRepoBench等基准测试中表现优异，全面超越现有基线。\ourmethod{}可作为高性能本地服务，助力编程开发ootnote{url{https://execrepobench.github.io/}}。

> Code completion has become an essential tool for daily software development. Existing evaluation benchmarks often employ static methods that do not fully capture the dynamic nature of real-world coding environments and face significant challenges, including limited context length, reliance on superficial evaluation metrics, and potential overfitting to training datasets. In this work, we introduce a novel framework for enhancing code completion in software development through the creation of a repository-level benchmark ExecRepoBench and the instruction corpora Repo-Instruct, aim at improving the functionality of open-source large language models (LLMs) in real-world coding scenarios that involve complex interdependencies across multiple files. ExecRepoBench includes 1.2K samples from active Python repositories. Plus, we present a multi-level grammar-based completion methodology conditioned on the abstract syntax tree to mask code fragments at various logical units (e.g. statements, expressions, and functions). Then, we fine-tune the open-source LLM with 7B parameters on Repo-Instruct to produce a strong code completion baseline model Qwen2.5-Coder-Instruct-C based on the open-source model. Qwen2.5-Coder-Instruct-C is rigorously evaluated against existing benchmarks, including MultiPL-E and ExecRepoBench, which consistently outperforms prior baselines across all programming languages. The deployment of \ourmethod{} can be used as a high-performance, local service for programming development\footnote{url{https://execrepobench.github.io/}}.

[Arxiv](https://arxiv.org/abs/2412.11990)