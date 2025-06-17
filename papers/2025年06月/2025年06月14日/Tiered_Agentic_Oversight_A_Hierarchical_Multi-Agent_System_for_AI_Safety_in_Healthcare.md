# 分层代理监督：保障医疗AI安全的分层多智能体系统

发布时间：2025年06月14日

`LLM应用`

> Tiered Agentic Oversight: A Hierarchical Multi-Agent System for AI Safety in Healthcare

# 摘要

> 尽管大型语言模型 (LLMs) 功能强大，但在临床环境中可能因错误检测能力有限和单点故障等问题带来安全隐患。为解决这一问题，我们提出了一种名为分层代理监督 (TAO) 的创新框架。TAO 是一种分层多代理系统，通过自动化、分层的监督机制显著提升了 AI 的安全性。受临床等级制度（如护士、医生、专科医师）的启发，TAO 能够根据任务复杂度和代理角色进行智能路由分配。通过跨层和层内自动化协作以及角色扮演机制，TAO 构建了一个高效的安全防护体系。实验结果表明，TAO 的优越性能主要得益于其自适应的分层架构，与传统单层配置相比，安全性能提升了超过 3.2%；其较低层级（尤其是第一层）的关键作用，移除这些层级会对安全性产生最显著的影响；以及将更先进的 LLM 战略性分配到初始层级，与次优分配方式相比，性能提升了超过 2%，同时实现了接近峰值的安全性。在 5 个医疗安全基准测试中，TAO 在 4 个测试中表现优于单代理和多代理框架，相比其他方法在评估中提升了高达 8.2% 的性能。最后，我们通过一项临床医生参与的实验验证了 TAO，整合专家反馈使 TAO 在医学分诊中的准确率显著提升，从 40% 提升至 60%。

> Current large language models (LLMs), despite their power, can introduce safety risks in clinical settings due to limitations such as poor error detection and single point of failure. To address this, we propose Tiered Agentic Oversight (TAO), a hierarchical multi-agent framework that enhances AI safety through layered, automated supervision. Inspired by clinical hierarchies (e.g., nurse, physician, specialist), TAO conducts agent routing based on task complexity and agent roles. Leveraging automated inter- and intra-tier collaboration and role-playing, TAO creates a robust safety framework. Ablation studies reveal that TAO's superior performance is driven by its adaptive tiered architecture, which improves safety by over 3.2% compared to static single-tier configurations; the critical role of its lower tiers, particularly tier 1, whose removal most significantly impacts safety; and the strategic assignment of more advanced LLM to these initial tiers, which boosts performance by over 2% compared to less optimal allocations while achieving near-peak safety efficiently. These mechanisms enable TAO to outperform single-agent and multi-agent frameworks in 4 out of 5 healthcare safety benchmarks, showing up to an 8.2% improvement over the next-best methods in these evaluations. Finally, we validate TAO via an auxiliary clinician-in-the-loop study where integrating expert feedback improved TAO's accuracy in medical triage from 40% to 60%.

[Arxiv](https://arxiv.org/abs/2506.12482)