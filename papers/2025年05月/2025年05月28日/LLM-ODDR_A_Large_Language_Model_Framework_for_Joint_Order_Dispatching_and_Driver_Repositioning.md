# 基于大型语言模型的联合订单调度与司机重定位框架：LLM-ODDR

发布时间：2025年05月28日

`LLM应用

理由：这篇论文探讨了将大型语言模型（LLMs）应用于叫车平台的订单分发和司机重新定位问题。它介绍了LLM-ODDR框架及其组成部分，并展示了该方法在实际数据中的有效性。这属于将LLMs应用于特定领域的实际问题，因此归类为LLM应用。` `智能交通系统` `叫车平台`

> LLM-ODDR: A Large Language Model Framework for Joint Order Dispatching and Driver Repositioning

# 摘要

> 叫车平台在动态城市环境中优化订单分发和司机重新定位面临诸多挑战。传统方法如组合优化、规则启发式和强化学习常忽视司机收入公平性、可解释性及现实适应性。为此，我们提出LLM-ODDR框架，利用大型语言模型（LLMs）实现联合订单分发与司机重新定位（ODDR）。该框架由三大核心组成：多目标引导的订单价值精炼，公平意识的订单分发，以及时空需求感知的司机重新定位。我们还开发了针对ODDR任务优化的JointDR-GPT模型。基于曼哈顿出租车数据的实验证明，LLM-ODDR在效果、异常适应性和决策可解释性上显著优于传统方法。这是首次将LLMs应用于叫车ODDR决策，为智能交通系统中整合语言模型提供了重要见解。

> Ride-hailing platforms face significant challenges in optimizing order dispatching and driver repositioning operations in dynamic urban environments. Traditional approaches based on combinatorial optimization, rule-based heuristics, and reinforcement learning often overlook driver income fairness, interpretability, and adaptability to real-world dynamics. To address these gaps, we propose LLM-ODDR, a novel framework leveraging Large Language Models (LLMs) for joint Order Dispatching and Driver Repositioning (ODDR) in ride-hailing services. LLM-ODDR framework comprises three key components: (1) Multi-objective-guided Order Value Refinement, which evaluates orders by considering multiple objectives to determine their overall value; (2) Fairness-aware Order Dispatching, which balances platform revenue with driver income fairness; and (3) Spatiotemporal Demand-Aware Driver Repositioning, which optimizes idle vehicle placement based on historical patterns and projected supply. We also develop JointDR-GPT, a fine-tuned model optimized for ODDR tasks with domain knowledge. Extensive experiments on real-world datasets from Manhattan taxi operations demonstrate that our framework significantly outperforms traditional methods in terms of effectiveness, adaptability to anomalous conditions, and decision interpretability. To our knowledge, this is the first exploration of LLMs as decision-making agents in ride-hailing ODDR tasks, establishing foundational insights for integrating advanced language models within intelligent transportation systems.

[Arxiv](https://arxiv.org/abs/2505.22695)