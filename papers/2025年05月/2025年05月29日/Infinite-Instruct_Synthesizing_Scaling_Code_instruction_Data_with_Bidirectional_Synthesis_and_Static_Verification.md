# # 无限指令：基于双向合成与静态验证的扩展代码指令数据合成

发布时间：2025年05月29日

`LLM应用` `知识图谱`

> Infinite-Instruct: Synthesizing Scaling Code instruction Data with Bidirectional Synthesis and Static Verification

# 摘要

> 传统的代码指令数据合成方法存在多样性和逻辑性上的明显缺陷。为解决这一问题，我们推出了Infinite-Instruct——一个专注于生成高质量问答对的自动化框架，旨在显著提升大型语言模型（LLMs）的代码生成能力。该框架通过三个核心步骤实现这一目标：首先，"逆向构造"技术将代码片段转化为形式多样的编程问题；其次，"反馈构造"方法将问题中的关键词结构化为知识图谱，从而生成逻辑性更强的编程问题；最后，通过跨语言静态代码分析流水线过滤低质量样本，确保数据整体质量。实验结果表明，与现有方法相比，我们的微调模型在70亿参数模型上平均性能提升了21.70%，在320亿参数模型上更是达到了36.95%的提升。值得一提的是，仅使用十分之一的指令微调数据，我们便实现了与Qwen-2.5-Coder-Instruct相当的性能表现。Infinite-Instruct不仅为编程领域的LLM训练提供了一个高效可扩展的解决方案，还开源了完整的实验数据集，包括未经筛选的原始版本和通过静态分析优化的版本。如需获取数据，请访问https://github.com/xingwenjing417/Infinite-Instruct-dataset。

> Traditional code instruction data synthesis methods suffer from limited diversity and poor logic. We introduce Infinite-Instruct, an automated framework for synthesizing high-quality question-answer pairs, designed to enhance the code generation capabilities of large language models (LLMs). The framework focuses on improving the internal logic of synthesized problems and the quality of synthesized code. First, "Reverse Construction" transforms code snippets into diverse programming problems. Then, through "Backfeeding Construction," keywords in programming problems are structured into a knowledge graph to reconstruct them into programming problems with stronger internal logic. Finally, a cross-lingual static code analysis pipeline filters invalid samples to ensure data quality. Experiments show that on mainstream code generation benchmarks, our fine-tuned models achieve an average performance improvement of 21.70% on 7B-parameter models and 36.95% on 32B-parameter models. Using less than one-tenth of the instruction fine-tuning data, we achieved performance comparable to the Qwen-2.5-Coder-Instruct. Infinite-Instruct provides a scalable solution for LLM training in programming. We open-source the datasets used in the experiments, including both unfiltered versions and filtered versions via static analysis. The data are available at https://github.com/xingwenjing417/Infinite-Instruct-dataset

[Arxiv](https://arxiv.org/abs/2505.23177)