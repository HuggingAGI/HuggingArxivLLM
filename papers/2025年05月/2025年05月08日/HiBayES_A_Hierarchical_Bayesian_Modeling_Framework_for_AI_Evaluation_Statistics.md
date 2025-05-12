# HiBayES：一个用于 AI 评估统计的分层贝叶斯建模框架

发布时间：2025年05月08日

`LLM理论` `AI评估` `统计学`

> HiBayES: A Hierarchical Bayesian Modeling Framework for AI Evaluation Statistics

# 摘要

> 随着大型语言模型 (LLMs) 与其他 AI 系统的不断发展，如何稳健地从本质上随机的输出中估计其能力，同时系统性地量化这些估计中的不确定性，变得越来越重要。此外，高级 AI 评估通常具有嵌套的层次结构，表现出高度的复杂性，并且在测试最先进的 AI 系统时伴随着高昂的测试成本。为了解决这些挑战，我们引入了 HiBayES，一个通用的分层贝叶斯建模框架，用于 AI 评估统计。HiBayES 在经典问答基准和高级智能体评估中支持稳健推断，特别是在小数据场景（例如，每个评估少于 20 个数据点）中表现尤为突出。基于广义线性模型 (GLMs)、贝叶斯数据分析和正式的模型比较，HiBayES 提供了原理性的不确定性量化和稳健的参数估计。本文对 HiBayES 进行了全面介绍，包括说明性示例、与传统统计方法的比较，以及实现多级贝叶斯 GLMs 的实用指南。此外，我们提供了一个 HiBayES 软件包 [4]（Beta 版），以便开箱即用的实现。

> As Large Language Models (LLMs) and other AI systems evolve, robustly estimating their capabilities from inherently stochastic outputs while systematically quantifying uncertainty in these estimates becomes increasingly important. Further, advanced AI evaluations often have a nested hierarchical structure, exhibit high levels of complexity, and come with high costs in testing the most advanced AI systems. To address these challenges, we introduce HiBayES, a generalizable Hierarchical Bayesian modeling framework for AI Evaluation Statistics. HiBayES supports robust inferences in classical question-answer benchmarks and advanced agentic evaluations, particularly in low-data scenarios (e.g., < 20 data points per evaluation). Built on Generalized Linear Models (GLMs), Bayesian data analysis, and formal model comparison, HiBayES provides principled uncertainty quantification and robust parameter estimation. This paper offers a comprehensive introduction to HiBayES, including illustrative examples, comparisons to conventional statistical methods, and practical guidance for implementing multilevel Bayesian GLMs. Additionally, we provide a HiBayES software package [4] (Beta version) for out-of-the-box implementation.

[Arxiv](https://arxiv.org/abs/2505.05602)