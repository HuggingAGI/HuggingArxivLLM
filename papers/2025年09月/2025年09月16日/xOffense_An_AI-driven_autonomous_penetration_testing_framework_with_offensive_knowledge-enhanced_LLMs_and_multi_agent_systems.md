# xOffense：AI驱动的自主渗透测试框架——集成攻击知识增强的大型语言模型与多智能体系统

发布时间：2025年09月16日

`Agent` `基础理论`

> xOffense: An AI-driven autonomous penetration testing framework with offensive knowledge-enhanced LLMs and multi agent systems

# 摘要

> 本研究提出xOffense——一个AI驱动的多智能体渗透测试框架，它将渗透测试从劳动密集、依赖专家的手动流程转变为完全自动化、机器可执行的工作流，且能随计算基础设施无缝扩展。其核心采用经过微调的中等规模开源LLM（Qwen3-32B），负责驱动渗透测试的推理与决策。框架为侦察、漏洞扫描和漏洞利用分配专门智能体，并通过编排层实现各阶段的无缝协同。通过在思维链渗透测试数据上微调，模型还能生成精确的工具命令并进行连贯的多步骤推理。我们在AutoPenBench和AI-Pentest-Benchmark两个严格基准测试集上对xOffense进行了评估，结果显示其性能持续优于现有方法，子任务完成率达79.17%，明显超越VulnBot、PentestGPT等领先系统。这些发现表明，将领域适配的中等规模LLM嵌入结构化多智能体编排后，可为自主渗透测试提供性能卓越、成本高效且结果可复现的解决方案。

> This work introduces xOffense, an AI-driven, multi-agent penetration testing framework that shifts the process from labor-intensive, expert-driven manual efforts to fully automated, machine-executable workflows capable of scaling seamlessly with computational infrastructure. At its core, xOffense leverages a fine-tuned, mid-scale open-source LLM (Qwen3-32B) to drive reasoning and decision-making in penetration testing. The framework assigns specialized agents to reconnaissance, vulnerability scanning, and exploitation, with an orchestration layer ensuring seamless coordination across phases. Fine-tuning on Chain-of-Thought penetration testing data further enables the model to generate precise tool commands and perform consistent multi-step reasoning. We evaluate xOffense on two rigorous benchmarks: AutoPenBench and AI-Pentest-Benchmark. The results demonstrate that xOffense consistently outperforms contemporary methods, achieving a sub-task completion rate of 79.17%, decisively surpassing leading systems such as VulnBot and PentestGPT. These findings highlight the potential of domain-adapted mid-scale LLMs, when embedded within structured multi-agent orchestration, to deliver superior, cost-efficient, and reproducible solutions for autonomous penetration testing.

[Arxiv](https://arxiv.org/abs/2509.13021)