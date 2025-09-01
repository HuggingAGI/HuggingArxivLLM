# Aegis：LLM智能体中智能体-环境故障的分类体系与优化策略

发布时间：2025年08月26日

`Agent` `零售与电商`

> Aegis: Taxonomy and Optimizations for Overcoming Agent-Environment Failures in LLM Agents

# 摘要

> 配备领域工具的大型语言模型（LLMs）智能体，有望自主完成客服、数字助理等需人类级智能的复杂任务。但在复杂的现实环境中，其成功率偏低，严重制约了实际部署。此前研究多聚焦于改进智能体本身（如开发更强的智能体LLM），却忽略了智能体运行的系统环境所扮演的角色。
  本文则探索了一个互补方向：通过优化智能体运行的系统环境来提升其成功率。我们在5个最先进的智能体基准测试中，收集了142条智能体轨迹（包含3656轮智能体-环境交互）。通过分析这些智能体失败案例，我们提出了包含6种失败模式的智能体-环境交互失败分类法。基于这些发现，我们设计了Aegis——一套针对性的环境优化方案，包括：1）环境可观测性增强、2）通用计算卸载、3）推测性智能体行动。这些技术在不修改智能体及底层LLM的情况下，将智能体成功率平均提升了6.7-12.5%。

> Large Language Models (LLMs) agents augmented with domain tools promise to autonomously execute complex tasks requiring human-level intelligence, such as customer service and digital assistance. However, their practical deployment is often limited by their low success rates under complex real-world environments. To tackle this, prior research has primarily focused on improving the agents themselves, such as developing strong agentic LLMs, while overlooking the role of the system environment in which the agent operates.
  In this paper, we study a complementary direction: improving agent success rates by optimizing the system environment in which the agent operates. We collect 142 agent traces (3,656 turns of agent-environment interactions) across 5 state-of-the-art agentic benchmarks. By analyzing these agent failures, we propose a taxonomy for agent-environment interaction failures that includes 6 failure modes. Guided by these findings, we design Aegis, a set of targeted environment optimizations: 1) environment observability enhancement, 2) common computation offloading, and 3) speculative agentic actions. These techniques improve agent success rates on average by 6.7-12.5%, without any modifications to the agent and underlying LLM.

[Arxiv](https://arxiv.org/abs/2508.19504)