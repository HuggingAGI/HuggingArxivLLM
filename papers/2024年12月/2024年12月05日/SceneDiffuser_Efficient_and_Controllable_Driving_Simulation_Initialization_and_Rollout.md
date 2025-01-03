# SceneDiffuser: 高效可控的驾驶模拟初始化和展开

发布时间：2024年12月05日

`LLM应用

理由：这篇论文主要讨论了使用扩散模型和大型语言模型（LLM）来提升自动驾驶车辆开发中的场景模拟。虽然论文的核心技术是扩散模型，但它也提到了使用LLM进行少样本提示生成约束场景，这表明LLM在场景模拟中的应用。因此，这篇论文应归类为LLM应用。` `自动驾驶` `交通模拟`

> SceneDiffuser: Efficient and Controllable Driving Simulation Initialization and Rollout

# 摘要

> # 摘要
逼真且交互式的场景模拟是自动驾驶车辆（AV）开发的关键前提。本文提出SceneDiffuser，一种专为交通模拟设计的场景级扩散先验模型。该模型提供了一个统一的框架，涵盖模拟的两个核心阶段：场景初始化（生成初始交通布局）和场景展开（代理行为的闭环模拟）。尽管扩散模型在学习逼真且多模态的代理分布方面表现出色，但仍面临可控性、闭环模拟的逼真度以及推理效率等挑战。为此，我们引入了分摊扩散技术，将去噪计算成本分摊到未来的模拟步骤中，显著降低了每次展开步骤的成本（推理步骤减少16倍），同时有效减少了闭环误差。我们还通过广义硬约束（一种简单但高效的推理时间约束机制）和基于大型语言模型（LLM）的少样本提示生成约束场景，进一步提升了可控性。模型扩展研究表明，增加计算资源能显著提升模拟的逼真度。在Waymo Open Sim Agents Challenge中，我们的方法展现了卓越的开放环性能，并在扩散模型中实现了最佳的闭环性能。

> Realistic and interactive scene simulation is a key prerequisite for autonomous vehicle (AV) development. In this work, we present SceneDiffuser, a scene-level diffusion prior designed for traffic simulation. It offers a unified framework that addresses two key stages of simulation: scene initialization, which involves generating initial traffic layouts, and scene rollout, which encompasses the closed-loop simulation of agent behaviors. While diffusion models have been proven effective in learning realistic and multimodal agent distributions, several challenges remain, including controllability, maintaining realism in closed-loop simulations, and ensuring inference efficiency. To address these issues, we introduce amortized diffusion for simulation. This novel diffusion denoising paradigm amortizes the computational cost of denoising over future simulation steps, significantly reducing the cost per rollout step (16x less inference steps) while also mitigating closed-loop errors. We further enhance controllability through the introduction of generalized hard constraints, a simple yet effective inference-time constraint mechanism, as well as language-based constrained scene generation via few-shot prompting of a large language model (LLM). Our investigations into model scaling reveal that increased computational resources significantly improve overall simulation realism. We demonstrate the effectiveness of our approach on the Waymo Open Sim Agents Challenge, achieving top open-loop performance and the best closed-loop performance among diffusion models.

[Arxiv](https://arxiv.org/abs/2412.12129)