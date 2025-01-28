# 失落的依赖项探索者：用LLMs解决Python依赖冲突

发布时间：2025年01月27日

`RAG

理由：这篇论文主要探讨了利用大型语言模型（LLMs）和检索增强生成（RAG）技术来自动修复 Python 依赖问题。PLLM 通过 RAG 技术帮助 LLM 推断 Python 文件的版本和所需模块，并通过迭代的反馈循环优化修复过程。因此，这篇论文的核心技术是 RAG，应归类为 RAG。` `软件开发`

> Raiders of the Lost Dependency: Fixing Dependency Conflicts in Python using LLMs

# 摘要

> # 摘要
修复 Python 依赖问题对开发者来说既繁琐又容易出错，他们需要手动处理第三方模块和 Python 解释器的环境依赖和版本约束。尽管研究人员尝试通过大型知识图谱和数据库查找表来自动化这一过程，但传统方法因依赖错误类型多样、模块版本繁多以及传递依赖冲突而受限。本研究探索了利用大型语言模型（LLMs）自动修复 Python 依赖问题的潜力，并提出了 PLLM（发音为“plum”）。PLLM 采用检索增强生成（RAG）技术，帮助 LLM 推断 Python 文件的版本和所需模块。它通过构建测试环境，迭代地（1）提示 LLM 生成模块组合，（2）测试建议的更改，并（3）将错误反馈给 LLM 以优化修复。这一反馈循环利用自然语言处理（NLP）智能解析构建错误信息。我们在 Gistable HG2.9K 数据集上对 PLLM 进行了基准测试，结果显示 PLLM 比 PyEGo 和 ReadPyE 两种基线方法修复了更多的依赖问题，分别多修复了 +218（+15.97%）和 +281（+21.58%）个问题。深入分析表明，PLLM 对依赖项较多的项目以及特定数值和机器学习模块尤为有效。我们的研究证明了基于 LLM 的方法在迭代解决 Python 依赖问题方面的巨大潜力。

> Fixing Python dependency issues is a tedious and error-prone task for developers, who must manually identify and resolve environment dependencies and version constraints of third-party modules and Python interpreters. Researchers have attempted to automate this process by relying on large knowledge graphs and database lookup tables. However, these traditional approaches face limitations due to the variety of dependency error types, large sets of possible module versions, and conflicts among transitive dependencies. This study explores the potential of using large language models (LLMs) to automatically fix dependency issues in Python programs. We introduce PLLM (pronounced "plum"), a novel technique that employs retrieval-augmented generation (RAG) to help an LLM infer Python versions and required modules for a given Python file. PLLM builds a testing environment that iteratively (1) prompts the LLM for module combinations, (2) tests the suggested changes, and (3) provides feedback (error messages) to the LLM to refine the fix. This feedback cycle leverages natural language processing (NLP) to intelligently parse and interpret build error messages. We benchmark PLLM on the Gistable HG2.9K dataset, a collection of challenging single-file Python gists. We compare PLLM against two state-of-the-art automatic dependency inference approaches, namely PyEGo and ReadPyE, w.r.t. the ability to resolve dependency issues. Our results indicate that PLLM can fix more dependency issues than the two baselines, with +218 (+15.97%) more fixes over ReadPyE and +281 (+21.58%) over PyEGo. Our deeper analyses suggest that PLLM is particularly beneficial for projects with many dependencies and for specific third-party numerical and machine-learning modules. Our findings demonstrate the potential of LLM-based approaches to iteratively resolve Python dependency issues.

[Arxiv](https://arxiv.org/abs/2501.16191)