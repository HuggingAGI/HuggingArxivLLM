# # 微调大型语言模型用于量子优化问题中的电路生成

发布时间：2025年04月15日

`LLM应用` `量子计算` `量子优化`

> Fine-Tuning Large Language Models on Quantum Optimization Problems for Circuit Generation

# 摘要

> 大型语言模型（LLM）在数学、编程和分析科学报告等复杂问题上表现出色，但在量子计算领域的潜力尚未得到充分挖掘。目前最大的难题是如何利用 LLM 自动生成大规模量子电路。本文通过微调 LLM 并融入量子计算专业知识，成功应对这一挑战。我们研究了训练数据集的生成机制，并构建了完整的微调流程，使 LLM 能够生成用于优化问题的参数化量子电路。我们准备了 14,000 个量子电路，覆盖了量子优化领域的重要场景：12 个优化问题实例及其优化后的 QAOA、VQE 和自适应 VQE 电路。微调后的 LLM 能够生成符合 OpenQASM 3.0 标准的语法正确参数化量子电路。通过对比优化后的期望值和分布，我们评估了参数质量。结果显示，微调后的 LLM 性能优于现有最佳模型，且生成的参数优于随机参数。这些参数化电路和初始参数可作为进一步优化的起点，例如用于量子机器学习的模板，或作为编译器和硬件的基准测试。

> Large language models (LLM) have achieved remarkable outcomes in addressing complex problems, including math, coding, and analyzing large amounts of scientific reports. Yet few works have explored the potential of LLM in quantum computing. The most challenging problem is how to leverage LLMs to automatically generate quantum circuits at a large scale. In this paper, we address such a challenge by fine-tuning LLMs and injecting the domain-specific knowledge of quantum computing. In particular, we investigate the mechanisms to generate training data sets and construct the end-to-end pipeline to fine-tune pre-trained LLMs that produce parameterized quantum circuits for optimization problems. We have prepared 14,000 quantum circuits covering a substantial part of the quantum optimization landscape: 12 optimization problem instances and their optimized QAOA, VQE, and adaptive VQE circuits. The fine-tuned LLMs can construct syntactically correct parametrized quantum circuits in the most recent OpenQASM 3.0. We have evaluated the quality of the parameters by comparing them to the optimized expectation values and distributions. Our evaluation shows that the fine-tuned LLM outperforms state-of-the-art models and that the parameters are better than random. The LLM-generated parametrized circuits and initial parameters can be used as a starting point for further optimization, \emph{e.g.,} templates in quantum machine learning and the benchmark for compilers and hardware.

[Arxiv](https://arxiv.org/abs/2504.11109)