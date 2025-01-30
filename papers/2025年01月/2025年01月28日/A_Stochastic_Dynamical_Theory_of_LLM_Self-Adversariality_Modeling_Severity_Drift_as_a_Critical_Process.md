# LLM 自对抗性的随机动力学理论：严重性漂移的关键过程建模

发布时间：2025年01月28日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLMs）在链式思维推理过程中如何自我放大潜在的偏见或毒性，并通过随机微分方程（SDE）和Fokker-Planck方法进行理论分析。论文的核心在于理论推导和模型分析，涉及LLMs的内部机制和潜在行为，属于对LLM的理论研究，因此应归类为LLM理论。` `人工智能` `语言模型`

> A Stochastic Dynamical Theory of LLM Self-Adversariality: Modeling Severity Drift as a Critical Process

# 摘要

> 本文提出了一个连续时间随机动力学框架，用于研究大型语言模型（LLMs）如何通过链式思维推理自我放大潜在的偏见或毒性。模型假设一个瞬时“严重性”变量 $x(t) \in [0,1]$ 在带有漂移项 $μ(x)$ 和扩散 $σ(x)$ 的随机微分方程（SDE）下演化。关键的是，若每个增量步骤在严重性空间中近似马尔可夫，则可通过 Fokker--Planck 方法一致分析该过程。研究揭示了临界现象，表明某些参数区域会引发从亚临界（自我纠正）到超临界（失控严重性）的相变。本文推导了稳态分布、达到有害阈值的首次通过时间以及临界点附近的标度律。最后，讨论了其对代理和扩展 LLM 推理模型的影响：这些方程或可作为形式验证的基础，判断模型在重复推理中是否保持稳定或传播偏见。

> This paper introduces a continuous-time stochastic dynamical framework for understanding how large language models (LLMs) may self-amplify latent biases or toxicity through their own chain-of-thought reasoning. The model posits an instantaneous "severity" variable $x(t) \in [0,1]$ evolving under a stochastic differential equation (SDE) with a drift term $μ(x)$ and diffusion $σ(x)$. Crucially, such a process can be consistently analyzed via the Fokker--Planck approach if each incremental step behaves nearly Markovian in severity space. The analysis investigates critical phenomena, showing that certain parameter regimes create phase transitions from subcritical (self-correcting) to supercritical (runaway severity). The paper derives stationary distributions, first-passage times to harmful thresholds, and scaling laws near critical points. Finally, it highlights implications for agents and extended LLM reasoning models: in principle, these equations might serve as a basis for formal verification of whether a model remains stable or propagates bias over repeated inferences.

[Arxiv](https://arxiv.org/abs/2501.16783)