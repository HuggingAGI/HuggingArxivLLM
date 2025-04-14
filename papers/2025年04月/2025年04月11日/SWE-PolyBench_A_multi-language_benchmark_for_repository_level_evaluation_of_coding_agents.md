# SWE-PolyBench：一个多语言基准，针对代码代理的仓库级别评估

发布时间：2025年04月11日

`LLM应用` `软件工程` `编码代理`

> SWE-PolyBench: A multi-language benchmark for repository level evaluation of coding agents

# 摘要

> 大型语言模型驱动的编码代理在软件工程领域展现了出色的能力，然而在多种编程语言和实际场景中全面评估其性能仍具挑战。我们推出SWE-PolyBench，一个全新的多语言基准测试，用于从仓库级别基于执行进行编码代理的评估。该基准包含来自21个仓库的2110个实例，涵盖Java（165个）、JavaScript（1017个）、TypeScript（729个）和Python（199个）的任务，包括错误修复、功能添加和代码重构。我们提供了一个任务和仓库分层的子样本（SWE-PolyBench500），并发布了一个支持完全自动化评估的框架。为了更全面地比较编码代理，本研究提出了一套基于语法树分析的新指标。我们在SWE-PolyBench上评估了领先的开源编码代理，揭示了它们在语言、任务类型和复杂度类别上的优势与局限。实验表明，当前代理在不同语言中的表现参差不齐，难以应对复杂问题，但在简单任务上表现更佳。SWE-PolyBench旨在推动开发更通用和健壮的AI编码助手，以应对现实世界的软件工程挑战。我们的数据集和代码可在以下链接获取：https://github.com/amazon-science/SWE-PolyBench

> Coding agents powered by large language models have shown impressive capabilities in software engineering tasks, but evaluating their performance across diverse programming languages and real-world scenarios remains challenging. We introduce SWE-PolyBench, a new multi-language benchmark for repository-level, execution-based evaluation of coding agents. SWE-PolyBench contains 2110 instances from 21 repositories and includes tasks in Java (165), JavaScript (1017), TypeScript (729) and Python (199), covering bug fixes, feature additions, and code refactoring. We provide a task and repository-stratified subsample (SWE-PolyBench500) and release an evaluation harness allowing for fully automated evaluation. To enable a more comprehensive comparison of coding agents, this work also presents a novel set of metrics rooted in syntax tree analysis. We evaluate leading open source coding agents on SWE-PolyBench, revealing their strengths and limitations across languages, task types, and complexity classes. Our experiments show that current agents exhibit uneven performances across languages and struggle with complex problems while showing higher performance on simpler tasks. SWE-PolyBench aims to drive progress in developing more versatile and robust AI coding assistants for real-world software engineering. Our datasets and code are available at: https://github.com/amazon-science/SWE-PolyBench

[Arxiv](https://arxiv.org/abs/2504.08703)