# 揭秘工业推荐系统中的规模法则：基于大型用户模型的三步式方法

发布时间：2025年02月12日

`LLM应用` `推荐系统` `工业应用`

> Unlocking Scaling Law in Industrial Recommendation Systems with a Three-step Paradigm based Large User Model

# 摘要

> 自回归大型语言模型（LLMs）近期取得了重大进展，这些成就主要归功于其可扩展性，这一特性常被称为“缩放法则”。受到这些成果的启发，人们逐渐开始尝试将LLMs应用于推荐系统（RecSys），通过将RecSys任务重新表述为生成问题来实现。然而，这些端到端生成推荐（E2E-GR）方法往往过于追求理想化的目标，常常忽视了传统基于深度学习的推荐模型（DLRMs）在特征、架构和实践中所提供的实际优势。这种理想化目标与实际需求之间的差距带来了诸多挑战和限制，使得缩放法则在工业级推荐系统中难以应用。本文中，我们引入了一种大型用户模型（LUM），通过一个三步范式来解决这些限制，旨在满足工业环境中的严格要求，同时释放可扩展推荐的潜力。我们进行了广泛的实验评估，结果表明LUM在性能上优于现有的DLRMs和E2E-GR方法。值得注意的是，LUM表现出色的可扩展性，随着模型参数规模扩展至70亿级别，性能得到了显著提升。此外，我们成功地将LUM部署到工业应用中，在A/B测试中取得了显著的增益，进一步验证了其有效性和实用性。
    

> Recent advancements in autoregressive Large Language Models (LLMs) have achieved significant milestones, largely attributed to their scalability, often referred to as the "scaling law". Inspired by these achievements, there has been a growing interest in adapting LLMs for Recommendation Systems (RecSys) by reformulating RecSys tasks into generative problems. However, these End-to-End Generative Recommendation (E2E-GR) methods tend to prioritize idealized goals, often at the expense of the practical advantages offered by traditional Deep Learning based Recommendation Models (DLRMs) in terms of in features, architecture, and practices. This disparity between idealized goals and practical needs introduces several challenges and limitations, locking the scaling law in industrial RecSys. In this paper, we introduce a large user model (LUM) that addresses these limitations through a three-step paradigm, designed to meet the stringent requirements of industrial settings while unlocking the potential for scalable recommendations. Our extensive experimental evaluations demonstrate that LUM outperforms both state-of-the-art DLRMs and E2E-GR approaches. Notably, LUM exhibits excellent scalability, with performance improvements observed as the model scales up to 7 billion parameters. Additionally, we have successfully deployed LUM in an industrial application, where it achieved significant gains in an A/B test, further validating its effectiveness and practicality.

[Arxiv](https://arxiv.org/abs/2502.08309)