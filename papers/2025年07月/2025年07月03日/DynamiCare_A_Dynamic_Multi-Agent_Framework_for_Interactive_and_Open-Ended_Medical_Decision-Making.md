# DynamiCare：动态多智能体框架，助力交互式开放性医疗决策

发布时间：2025年07月03日

`Agent` `人工智能`

> DynamiCare: A Dynamic Multi-Agent Framework for Interactive and Open-Ended Medical Decision-Making

# 摘要

> 大型语言模型（LLMs）的崛起推动了专用AI代理的发展，尤其在医疗领域，这些代理具备领域特定的推理与交互能力。尽管近期的框架模拟了医疗决策过程，但它们主要集中在单轮任务上，即医生代理在一开始就获得完整的病例信息——这与现实世界中具有不确定性、交互性和迭代性的诊断过程大相径庭。本文中，我们推出了MIMIC-Patient，这是一个基于MIMIC-III电子健康记录（EHRs）构建的结构化数据集，旨在支持动态的、以患者为中心的模拟。在此基础上，我们提出了DynamiCare，这是一个新颖的动态多智能体框架，将临床诊断建模为一个多轮交互循环，其中一组专科医生代理会反复查询患者系统、整合新信息，并动态调整其组成和策略。通过广泛的实验，我们证明了DynamiCare的可行性和有效性，为基于LLM的代理在动态临床决策方面的研究奠定了首个基准。


> The rise of Large Language Models (LLMs) has enabled the development of specialized AI agents with domain-specific reasoning and interaction capabilities, particularly in healthcare. While recent frameworks simulate medical decision-making, they largely focus on single-turn tasks where a doctor agent receives full case information upfront -- diverging from the real-world diagnostic process, which is inherently uncertain, interactive, and iterative. In this paper, we introduce MIMIC-Patient, a structured dataset built from the MIMIC-III electronic health records (EHRs), designed to support dynamic, patient-level simulations. Building on this, we propose DynamiCare, a novel dynamic multi-agent framework that models clinical diagnosis as a multi-round, interactive loop, where a team of specialist agents iteratively queries the patient system, integrates new information, and dynamically adapts its composition and strategy. We demonstrate the feasibility and effectiveness of DynamiCare through extensive experiments, establishing the first benchmark for dynamic clinical decision-making with LLM-powered agents.

[Arxiv](https://arxiv.org/abs/2507.02616)