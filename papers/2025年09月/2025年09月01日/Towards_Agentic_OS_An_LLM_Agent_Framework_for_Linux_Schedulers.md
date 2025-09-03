# 迈向智能体操作系统：针对Linux调度器的LLM智能体框架

发布时间：2025年09月01日

`Agent` `基础理论`

> Towards Agentic OS: An LLM Agent Framework for Linux Schedulers

# 摘要

> 操作系统调度器长期面临一个根本性的语义鸿沟：内核策略无法理解应用的特定需求，进而导致性能不理想。为此，我们推出了SchedCP——首个能让完全自主的大型语言模型（LLM）智能体在无需人工干预的情况下，安全高效地优化Linux调度器的框架。我们的核心洞见在于，这一挑战的关键并非简单应用更优的LLM，而是构建解耦的控制平面，将AI的语义推理角色（“优化什么”）与系统的执行角色（“如何观察和行动”）分离。SchedCP作为模型上下文协议（MCP）服务器实现，提供了稳定的接口并包含三项核心服务：工作负载分析引擎、持续演进的调度器策略库，以及执行验证器——后者会在部署前通过静态和动态分析验证所有AI生成的代码与配置。
  我们通过sched-agent验证了该架构的强大能力——这是一个多智能体系统，可自主分析工作负载、合成自定义eBPF调度策略，并通过sched_ext基础设施进行部署。评估结果显示，与基础智能体方案相比，SchedCP性能提升最高达1.79倍，成本降低13倍，且始终保持高成功率。通过弥合语义鸿沟，SchedCP让专家级系统优化触手可及，并为构建真正自优化、感知应用的操作系统奠定了基础。代码已开源至https://github.com/eunomia-bpf/schedcp

> Operating system schedulers suffer from a fundamental semantic gap, where kernel policies fail to understand application-specific needs, leading to suboptimal performance. We introduce SchedCP, the first framework that enables fully autonomous Large Language Model (LLM) agents to safely and efficiently optimize Linux schedulers without human involvement. Our core insight is that the challenge is not merely to apply a better LLM, but to architect a decoupled control plane that separates the AI's role of semantic reasoning ("what to optimize") from the system's role of execution ("how to observe and act"). Implemented as Model Context Protocol(MCP) server, SchedCP provides a stable interface with three key services: a Workload Analysis Engine, an evolving Scheduler Policy Repository, and an Execution Verifier that validates all AI-generated code and configure before deployment with static and dynamic analysis.
  We demonstrate this architecture's power with sched-agent, a multi-agent system that autonomously analyzes workloads, synthesizes custom eBPF scheduling policies, and deploys them via the sched\_ext infrastructure. Our evaluation shows that SchedCP achieves up to an 1.79x performance improvement, and a 13x cost reduction compared to naive agentic approaches, all while maintaining high success rate. By bridging the semantic gap, SchedCP democratizes expert-level system optimization and represents a step towards creating truly self-optimizing, application-aware operating systems. The code is open-sourced in https://github.com/eunomia-bpf/schedcp

[Arxiv](https://arxiv.org/abs/2509.01245)