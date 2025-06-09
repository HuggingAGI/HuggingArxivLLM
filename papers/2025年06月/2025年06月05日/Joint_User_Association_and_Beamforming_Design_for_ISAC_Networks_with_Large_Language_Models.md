# 联合用户关联与波束成形设计：基于大型语言模型的ISAC网络研究

发布时间：2025年06月05日

`LLM应用

理由：这篇论文将大型语言模型（LLMs）应用于集成感知与通信网络的优化设计中，探讨了LLMs在解决复杂的网络优化问题中的应用。论文中提到使用LLMs来解决用户关联优化问题，并结合凸优化方法处理波束成形优化问题，这些都是LLMs在实际应用中的具体体现。因此，这篇论文属于LLM应用类别。` `通信网络` `人工智能`

> Joint User Association and Beamforming Design for ISAC Networks with Large Language Models

# 摘要

> # 集成感知与通信网络的优化设计

集成感知与通信（ISAC）在未来的无线网络中被期望发挥更加重要的作用。然而，设计ISAC网络极具挑战性，尤其是在存在多个通信与感知（C\&S）节点和多个感知目标的情况下。

我们研究了一个多基站（BS）的ISAC网络，其中多个配备多天线的BS同时为多个地面通信用户（CUs）和目标提供C\&S服务。为了提升C\&S的整体性能，我们制定了一个联合用户关联（UA）和多BS发射波束成形优化问题，目标是在满足最小目标检测和参数估计要求的同时，最大化所有CUs的总和速率。

为了高效解决这个高度非凸的混合整数非线性规划（MINLP）优化问题，我们提出了一种基于交替优化（AO）的算法，将问题分解为两个子问题，即UA优化和多BS发射波束成形优化。

受大型语言模型（LLMs）在预测和推理方面的启发，我们提出了一种将LLMs与基于凸优化的方法相结合的统一框架。首先，我们提出了一个全面的提示工程设计，包括少量样本学习、思维链和自我反思等技术，以引导LLMs解决二进制整数规划的UA优化问题。

其次，我们利用基于凸优化的方法，结合分数规划（FP）、主要化最小化（MM）和交替方向乘子法（ADMM），基于LLMs优化的UA，来处理非凸的波束成形优化问题。

数值结果表明，我们提出的基于LLM增强的AO算法在GPT-o1模型下实现了快速收敛和接近上界性能，优于各种基准方案。

> Integrated sensing and communication (ISAC) has been envisioned to play a more important role in future wireless networks. However, the design of ISAC networks is challenging, especially when there are multiple communication and sensing (C\&S) nodes and multiple sensing targets. We investigate a multi-base station (BS) ISAC network in which multiple BSs equipped with multiple antennas simultaneously provide C\&S services for multiple ground communication users (CUs) and targets. To enhance the overall performance of C\&S, we formulate a joint user association (UA) and multi-BS transmit beamforming optimization problem with the objective of maximizing the total sum rate of all CUs while ensuring both the minimum target detection and parameter estimation requirements. To efficiently solve the highly non-convex mixed integer nonlinear programming (MINLP) optimization problem, we propose an alternating optimization (AO)-based algorithm that decomposes the problem into two sub-problems, i.e., UA optimization and multi-BS transmit beamforming optimization. Inspired by large language models (LLMs) for prediction and inference, we propose a unified framework integrating LLMs with convex-based optimization methods. First, we propose a comprehensive design of prompt engineering, including few-shot, chain of thought, and self-reflection techniques to guide LLMs in solving the binary integer programming UA optimization problem. Second, we utilize convex-based optimization methods to handle the non-convex beamforming optimization problem based on fractional programming (FP), majorization minimization (MM), and the alternating direction method of multipliers (ADMM) with an optimized UA from LLMs. Numerical results demonstrate that our proposed LLM-enabled AO-based algorithm achieves fast convergence and near upper-bound performance with the GPT-o1 model, outperforming various benchmark schemes.

[Arxiv](https://arxiv.org/abs/2506.05637)