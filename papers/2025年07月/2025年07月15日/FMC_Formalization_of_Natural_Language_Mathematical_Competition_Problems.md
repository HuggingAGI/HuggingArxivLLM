# FMC: 自然语言数学竞赛问题的形式化方法

发布时间：2025年07月15日

`LLM应用

理由：这篇论文探讨了大型语言模型在数学推理中的应用，具体涉及自动形式化方法和数据集构建，属于LLM的应用领域。` `计算机科学`

> FMC: Formalization of Natural Language Mathematical Competition Problems

# 摘要

> 高效的自动形式化方法是推动形式化数学推理发展的关键。这些方法利用大规模自然语言数学问题数据集构建形式化语言数据集。本文提出了一种基于大型语言模型且带有错误反馈的自动形式化流水线，实现了完全自动且无需训练的形式化方法。通过这一方法，我们整理了一个奥林匹克级别的数据集，包含$3,922$个自然语言数学问题和$9,787$个Lean形式化问题，其中$64.46\%$被评估为至少中等质量以上，适合作为自动化定理证明器的基准。此外，我们研究了不同大型语言模型的形式化和推理能力，实证表明少量样本学习、错误反馈和增加采样数量可以显著提升自动形式化过程。三种自动化定理证明器在\dataset\数据集上的实验结果进一步凸显了其挑战性及其作为形式化推理任务基准的重要价值。

> Efficient and accurate autoformalization methods, which leverage large-scale datasets of extensive natural language mathematical problems to construct formal language datasets, are key to advancing formal mathematical reasoning. In this paper, we propose an autoformalization pipeline based on large language models with error feedback, achieving a fully automatic and training-free formalization approach. Using this pipeline, we curate an Olympiad-level dataset aligning natural language problems with Lean formalizations. The dataset comprises $3,922$ mathematical problems in natural language and $9,787$ in Lean, of which $64.46\%$ were assessed as at least above-average quality, making it suitable as a benchmark for automated theorem provers. Additionally, we investigate the formalization and reasoning capabilities of various LLMs and empirically demonstrate that few-shot learning, error feedback, and increasing sampling numbers enhance the autoformalization process. Experiments of three automated theorem provers on the \dataset\ dataset also highlight its challenging nature and its value as a benchmark for formal reasoning tasks.

[Arxiv](https://arxiv.org/abs/2507.11275)