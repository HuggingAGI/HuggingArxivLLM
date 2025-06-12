# G-Sim：利用大型语言模型实现生成式模拟与无梯度校准

发布时间：2025年06月10日

`LLM应用

理由：这篇论文探讨了如何将大型语言模型（LLM）应用于构建稳健的模拟器，特别是在医疗保健和物流等关键领域。它提出了一个结合LLM驱动的结构设计与实证校准的混合框架G-Sim，用于自动化构建可靠且具有因果解释的模拟器。因此，它属于LLM应用类别。` `医疗保健`

> G-Sim: Generative Simulations with Large Language Models and Gradient-Free Calibration

# 摘要

> 构建稳健的模拟器对于医疗保健和物流等关键领域的决策支持至关重要，但现有方法在面对超越历史数据的泛化能力和基于LLM的模拟器准确性方面存在明显局限。为此，我们提出了G-Sim，一个结合LLM驱动的结构设计与实证校准的混合框架。G-Sim通过迭代优化模拟器的核心结构和因果关系，并结合灵活的参数校准技术，实现模拟器的自动化构建。它能够支持似然自由和梯度自由的校准方法，从而处理不可微分和随机的模拟器。通过整合领域知识与实证数据，G-Sim生成可靠且具有因果解释的模拟器，为复杂决策提供稳健的系统级干预支持。

> Constructing robust simulators is essential for asking "what if?" questions and guiding policy in critical domains like healthcare and logistics. However, existing methods often struggle, either failing to generalize beyond historical data or, when using Large Language Models (LLMs), suffering from inaccuracies and poor empirical alignment. We introduce G-Sim, a hybrid framework that automates simulator construction by synergizing LLM-driven structural design with rigorous empirical calibration. G-Sim employs an LLM in an iterative loop to propose and refine a simulator's core components and causal relationships, guided by domain knowledge. This structure is then grounded in reality by estimating its parameters using flexible calibration techniques. Specifically, G-Sim can leverage methods that are both likelihood-free and gradient-free with respect to the simulator, such as gradient-free optimization for direct parameter estimation or simulation-based inference for obtaining a posterior distribution over parameters. This allows it to handle non-differentiable and stochastic simulators. By integrating domain priors with empirical evidence, G-Sim produces reliable, causally-informed simulators, mitigating data-inefficiency and enabling robust system-level interventions for complex decision-making.

[Arxiv](https://arxiv.org/abs/2506.09272)