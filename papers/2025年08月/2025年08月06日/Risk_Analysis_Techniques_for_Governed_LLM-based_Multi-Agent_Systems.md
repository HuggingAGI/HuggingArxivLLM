# # 基于治理的大型语言模型多智能体系统风险分析方法

发布时间：2025年08月06日

`LLM应用` `系统管理`

> Risk Analysis Techniques for Governed LLM-based Multi-Agent Systems

# 摘要

> 组织正逐步采用基于LLM的AI代理，其部署从单一代理自然演进为互联的多代理网络。然而，个体安全的代理组合并不等同于整体安全，因代理间的长期交互会产生不可预测的行为模式和新的失效模式。因此，多代理系统需要一套全新的风险分析方法。

本报告聚焦于受控环境中多代理AI系统的早期风险识别与分析。在这一场景下，我们深入探讨了六种关键失效模式：级联可靠性失效、跨代理通信失效、单一文化崩溃、趋同偏见、心智理论缺失以及动机动态冲突。针对每种模式，我们为实践者提供了一套工具包，便于其扩展或整合到现有框架中，从而在组织环境中评估这些失效模式的影响。

鉴于当前对LLM行为理解的局限性，我们的方法以分析的有效性为核心。通过在不同抽象和部署阶段进行分阶段测试，逐步增加对潜在负向影响的暴露，从而提升分析的有效性。同时，我们结合模拟、观察分析、基准测试和红队测试等方法，收集趋同证据。这一系统化的方法为基于LLM的多代理系统在部署和运行过程中的稳健风险管理奠定了坚实基础。

> Organisations are starting to adopt LLM-based AI agents, with their deployments naturally evolving from single agents towards interconnected, multi-agent networks. Yet a collection of safe agents does not guarantee a safe collection of agents, as interactions between agents over time create emergent behaviours and induce novel failure modes. This means multi-agent systems require a fundamentally different risk analysis approach than that used for a single agent.
  This report addresses the early stages of risk identification and analysis for multi-agent AI systems operating within governed environments where organisations control their agent configurations and deployment. In this setting, we examine six critical failure modes: cascading reliability failures, inter-agent communication failures, monoculture collapse, conformity bias, deficient theory of mind, and mixed motive dynamics. For each, we provide a toolkit for practitioners to extend or integrate into their existing frameworks to assess these failure modes within their organisational contexts.
  Given fundamental limitations in current LLM behavioural understanding, our approach centres on analysis validity, and advocates for progressively increasing validity through staged testing across stages of abstraction and deployment that gradually increases exposure to potential negative impacts, while collecting convergent evidence through simulation, observational analysis, benchmarking, and red teaming. This methodology establishes the groundwork for robust organisational risk management as these LLM-based multi-agent systems are deployed and operated.

[Arxiv](https://arxiv.org/abs/2508.05687)