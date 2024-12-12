# 利用大型语言模型实现参数化形状优化

发布时间：2024年12月10日

`LLM应用` `优化算法`

> Using Large Language Models for Parametric Shape Optimization

# 摘要

> 近期先进的大型语言模型（LLMs）展现出了其上下文学习的新兴能力，能够借助自然语言提示，无需重新训练，就能促进智能决策。这种新的机器学习范式在包括一般控制和优化问题等诸多领域都展现出良好前景。受此启发，我们针对一项特定且关键的工程任务——参数化形状优化（PSO），探索了LLMs的潜力。我们构建了一个优化框架——LLM-PSO，它借助LLM，以进化策略的思路来确定参数化工程设计的最优形状。运用“Claude 3.5 Sonnet”LLM，我们在两个基准流优化问题上对LLM-PSO进行了评估，具体旨在找出1）层流中二维机翼的减阻轮廓，以及2）Stokes流中三维轴对称体的减阻轮廓。在这两种情形下，LLM-PSO都成功找出了与基准解相符的最优形状。而且，它通常比其他经典优化算法收敛速度更快。我们的初步探索或许能激发对利用LLMs进行形状优化以及更广泛的工程设计的进一步研究。

> Recent advanced large language models (LLMs) have showcased their emergent capability of in-context learning, facilitating intelligent decision-making through natural language prompts without retraining. This new machine learning paradigm has shown promise in various fields, including general control and optimization problems. Inspired by these advancements, we explore the potential of LLMs for a specific and essential engineering task: parametric shape optimization (PSO). We develop an optimization framework, LLM-PSO, that leverages an LLM to determine the optimal shape of parameterized engineering designs in the spirit of evolutionary strategies. Utilizing the ``Claude 3.5 Sonnet'' LLM, we evaluate LLM-PSO on two benchmark flow optimization problems, specifically aiming to identify drag-minimizing profiles for 1) a two-dimensional airfoil in laminar flow, and 2) a three-dimensional axisymmetric body in Stokes flow. In both cases, LLM-PSO successfully identifies optimal shapes in agreement with benchmark solutions. Besides, it generally converges faster than other classical optimization algorithms. Our preliminary exploration may inspire further investigations into harnessing LLMs for shape optimization and engineering design more broadly.

[Arxiv](https://arxiv.org/abs/2412.08072)