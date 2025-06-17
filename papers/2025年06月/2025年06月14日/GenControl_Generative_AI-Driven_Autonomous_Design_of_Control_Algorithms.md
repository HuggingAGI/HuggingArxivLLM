# GenControl：生成式AI驱动的自主控制算法设计

发布时间：2025年06月14日

`LLM应用` `工业自动化` `控制系统`

> GenControl: Generative AI-Driven Autonomous Design of Control Algorithms

# 摘要

> 设计复杂工业电子系统的控制器充满挑战，原因在于非线性和参数不确定性，而传统方法往往速度慢且成本高。为了解决这一问题，我们提出了一种由大型语言模型 (LLMs) 驱动的新型自主设计框架。我们的方法采用了一种双层优化策略：LLM 智能地探索并迭代改进控制算法的结构，同时粒子群优化 (PSO) 算法高效地优化给定结构的参数。这种方法实现了端到端的自动化设计。通过在 DC-DC Boost 转换器的仿真中验证，我们的框架成功地将一个基本控制器演进为高性能自适应版本，满足了快速响应、低误差和鲁棒性等严格的设计规范。这项工作为控制设计提出了一个全新的范式，显著提升了自动化和效率。

> Designing controllers for complex industrial electronic systems is challenging due to nonlinearities and parameter uncertainties, and traditional methods are often slow and costly. To address this, we propose a novel autonomous design framework driven by Large Language Models (LLMs). Our approach employs a bi-level optimization strategy: an LLM intelligently explores and iteratively improves the control algorithm's structure, while a Particle Swarm Optimization (PSO) algorithm efficiently refines the parameters for any given structure. This method achieves end-to-end automated design. Validated through a simulation of a DC-DC Boost converter, our framework successfully evolved a basic controller into a high-performance adaptive version that met all stringent design specifications for fast response, low error, and robustness. This work presents a new paradigm for control design that significantly enhances automation and efficiency.

[Arxiv](https://arxiv.org/abs/2506.12554)