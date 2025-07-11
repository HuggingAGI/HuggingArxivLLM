# MAEBE：多智能体涌现行为框架

发布时间：2025年07月10日

`Agent` `AI安全` `多智能体系统`

> MAEBE: Multi-Agent Emergent Behavior Framework

# 摘要

> 随着多智能体AI系统日益普及，传统的LLM隔离式AI安全评估已显不足，因为它们无法应对由此带来的全新潜在风险。本文提出了一种多智能体涌现行为评估（MAEBE）框架，用于系统性地识别和评估这些新兴风险。通过结合最大效益基准测试（以及一种创新的双反转问题技术），我们利用MAEBE框架展示了以下几点：(1) LLM的道德偏好，特别是对工具性伤害的偏好，令人惊讶地脆弱，且会因问题表述方式的不同而发生显著变化，这种现象在单个智能体和智能体集群中都普遍存在。(2) LLM集群的道德推理无法直接从单个智能体的行为中预测，因为集群内部存在复杂的涌现性群体动态。(3) 特别地，集群会表现出同伴压力影响收敛等现象，即使在有监督指导下，也凸显出独特的安全与对齐挑战。我们的研究发现强调了在多智能体互动环境中评估AI系统的重要性。

> Traditional AI safety evaluations on isolated LLMs are insufficient as multi-agent AI ensembles become prevalent, introducing novel emergent risks. This paper introduces the Multi-Agent Emergent Behavior Evaluation (MAEBE) framework to systematically assess such risks. Using MAEBE with the Greatest Good Benchmark (and a novel double-inversion question technique), we demonstrate that: (1) LLM moral preferences, particularly for Instrumental Harm, are surprisingly brittle and shift significantly with question framing, both in single agents and ensembles. (2) The moral reasoning of LLM ensembles is not directly predictable from isolated agent behavior due to emergent group dynamics. (3) Specifically, ensembles exhibit phenomena like peer pressure influencing convergence, even when guided by a supervisor, highlighting distinct safety and alignment challenges. Our findings underscore the necessity of evaluating AI systems in their interactive, multi-agent contexts.

[Arxiv](https://arxiv.org/abs/2506.03053)