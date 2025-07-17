# GitChameleon：评估 AI 代码生成在 Python 库版本不兼容性中的表现

发布时间：2025年07月16日

`LLM应用` `软件工程` `代码生成`

> GitChameleon: Evaluating AI Code Generation Against Python Library Version Incompatibilities

# 摘要

> 软件库的快速迭代给代码生成带来了巨大挑战，要求在保持兼容性的同时，持续适应频繁的版本更新。现有代码演化基准虽有帮助，却缺乏针对特定库版本的生成代码执行评估。为此，我们推出了GitChameleon——一个精心打造的数据集，包含328个Python代码补全问题，每个问题均基于特定库版本，并配有可执行单元测试。GitChameleon严格评估了当代大型语言模型（LLMs）、LLM驱动的代理、代码助手和RAG系统在特定版本条件下生成代码的能力，这些代码通过执行展现了功能准确性。我们的评估显示，最先进系统在该任务上面临重大挑战，企业模型的基线成功率在48-51%之间，凸显了问题的复杂性。通过提供一个基于执行的基准，强调代码库的动态特性，GitChameleon帮助我们更清晰地理解这一挑战，并为开发更具适应性和可靠性的AI代码生成方法提供了指引。我们已将数据集和评估代码公开发布，地址为https://github.com/mrcabbage972/GitChameleonBenchmark。


> The rapid evolution of software libraries poses a considerable hurdle for code generation, necessitating continuous adaptation to frequent version updates while preserving backward compatibility. While existing code evolution benchmarks provide valuable insights, they typically lack execution-based evaluation for generating code compliant with specific library versions. To address this, we introduce GitChameleon, a novel, meticulously curated dataset comprising 328 Python code completion problems, each conditioned on specific library versions and accompanied by executable unit tests. GitChameleon rigorously evaluates the capacity of contemporary large language models (LLMs), LLM-powered agents, code assistants, and RAG systems to perform version-conditioned code generation that demonstrates functional accuracy through execution. Our extensive evaluations indicate that state-of-the-art systems encounter significant challenges with this task; enterprise models achieving baseline success rates in the 48-51\% range, underscoring the intricacy of the problem. By offering an execution-based benchmark emphasizing the dynamic nature of code libraries, GitChameleon enables a clearer understanding of this challenge and helps guide the development of more adaptable and dependable AI code generation methods. We make the dataset and evaluation code publicly available at https://github.com/mrcabbage972/GitChameleonBenchmark.

[Arxiv](https://arxiv.org/abs/2507.12367)