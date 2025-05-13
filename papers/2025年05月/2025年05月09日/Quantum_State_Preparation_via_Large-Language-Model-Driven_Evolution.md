# # 量子态制备：大型语言模型驱动的进化方法

发布时间：2025年05月09日

`LLM应用` `量子计算` `量子模拟`

> Quantum State Preparation via Large-Language-Model-Driven Evolution

# 摘要

> 我们提出了一种结合大型语言模型（LLMs）与进化优化的自动化量子电路设计框架，旨在解决传统变分量子算法中 rigidity、可扩展性限制以及对专家依赖的问题。我们的方法（FunSearch）能够从零开始自主发现具有新型可扩展性和系统规模无关的变分参数数量的硬件高效 ansätze。在包含9个量子比特的Ising和XY自旋链上的演示，成功生成了仅含4个参数的量子电路，并在不同系统规模下实现了近精确的能量外推。在量子硬件（Zuchongzhi芯片）上的实现验证了其实际可行性，其中通过零噪声外推技术，可以有效缓解两个量子比特门的噪声问题，从而实现对多达20个自旋位点的自旋链系统的有效控制。这一框架成功地连接了算法设计与实验约束，补充了现有的量子架构搜索框架，推动了可扩展量子模拟的发展。

> We propose an automated framework for quantum circuit design by integrating large-language models (LLMs) with evolutionary optimization to overcome the rigidity, scalability limitations, and expert dependence of traditional ones in variational quantum algorithms. Our approach (FunSearch) autonomously discovers hardware-efficient ansätze with new features of scalability and system-size-independent number of variational parameters entirely from scratch. Demonstrations on the Ising and XY spin chains with n = 9 qubits yield circuits containing 4 parameters, achieving near-exact energy extrapolation across system sizes. Implementations on quantum hardware (Zuchongzhi chip) validate practicality, where two-qubit quantum gate noises can be effectively mitigated via zero-noise extrapolations for a spin chain system as large as 20 sites. This framework bridges algorithmic design and experimental constraints, complementing contemporary quantum architecture search frameworks to advance scalable quantum simulations.

[Arxiv](https://arxiv.org/abs/2505.06347)