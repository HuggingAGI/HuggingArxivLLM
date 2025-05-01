# 迭代轨迹探索助力多模态智能体

发布时间：2025年04月30日

`Agent

理由：这篇论文主要探讨了多模态代理的开发与优化，提出了一种在线自我探索方法SPORT，用于提升代理在复杂任务中的表现。研究的核心在于代理的自主学习和优化，属于Agent领域。` `多模态` `人工智能`

> Iterative Trajectory Exploration for Multimodal Agents

# 摘要

> 多模态代理通过整合控制器（如大型语言模型）与外部工具，在处理复杂任务方面表现出色。然而，现有的代理需要大量专家数据进行微调以适应新环境。本文提出一种针对多模态代理的在线自我探索方法——SPORT，通过逐步偏好优化精炼代理轨迹，无需专家标注。SPORT通过四个迭代组件运行：任务合成、步骤采样、步骤验证和偏好调整。首先，利用语言模型合成多模态任务。然后，引入一种新颖的搜索方案，步骤采样与验证交替执行以解决生成任务。通过验证器提供AI反馈，构建逐步偏好数据。这些数据用于更新控制器策略，生成SPORT代理。通过与真实环境的交互，SPORT代理逐渐优化，变得更为强大。在GTA和GAIA基准测试中，SPORT代理分别提升了6.41%和3.64%，证明了方法的泛化与有效性。项目页面：https://SPORT-Agents.github.io。

> Multimodal agents, which integrate a controller (e.g., a large language model) with external tools, have demonstrated remarkable capabilities in tackling complex tasks. However, existing agents need to collect a large number of expert data for fine-tuning to adapt to new environments. In this paper, we propose an online self-exploration method for multimodal agents, namely SPORT, via step-wise preference optimization to refine the trajectories of agents, which automatically generates tasks and learns from solving the generated tasks, without any expert annotation. SPORT operates through four iterative components: task synthesis, step sampling, step verification, and preference tuning. First, we synthesize multi-modal tasks using language models. Then, we introduce a novel search scheme, where step sampling and step verification are executed alternately to solve each generated task. We employ a verifier to provide AI feedback to construct step-wise preference data. The data is subsequently used to update the controller's policy through preference tuning, producing a SPORT Agent. By interacting with real environments, the SPORT Agent evolves into a more refined and capable system. Evaluation in the GTA and GAIA benchmarks show that the SPORT Agent achieves 6.41\% and 3.64\% improvements, underscoring the generalization and effectiveness introduced by our method. The project page is https://SPORT-Agents.github.io.

[Arxiv](https://arxiv.org/abs/2504.21561)