# 走向有效的 GenAI 多智能体协同：针对企业应用的设计与评估

发布时间：2024年12月06日

`Agent` `多代理协作`

> Towards Effective GenAI Multi-Agent Collaboration: Design and Evaluation for Enterprise Applications

# 摘要

> 由大型语言模型（LLMs）驱动的 AI 代理在解决问题方面展现出强大能力。众多智能代理相结合，多代理协作成为处理单个 AI 代理无法应对的复杂多面问题的有效途径。然而，设计协作协议以及评估这些系统的有效性仍是重大挑战，对企业应用而言尤甚。本报告针对新型多代理协作框架中的协调和路由能力展开全面评估，以应对上述挑战。我们评估了两种关键操作模式：（1）通过并行通信和有效负载引用完成复杂任务的协调模式；（2）实现代理间高效消息转发的路由模式。我们在来自三个企业领域的一组手工构建场景上进行基准测试，这些场景随报告一同公开。就协调能力而言，我们证明了代理间通信和有效负载引用机制的有效性，端到端目标成功率达 90%。分析得出了若干关键发现：在我们的基准测试中，多代理协作较单代理方法将目标成功率提高多达 70%；有效负载引用使代码密集型任务的性能提升 23%；借助有选择地绕过代理编排的路由机制，可大幅降低延迟。这些发现为多代理系统的企业部署提供了宝贵指导，推动了可扩展、高效的多代理协作框架的发展。

> AI agents powered by large language models (LLMs) have shown strong capabilities in problem solving. Through combining many intelligent agents, multi-agent collaboration has emerged as a promising approach to tackle complex, multi-faceted problems that exceed the capabilities of single AI agents. However, designing the collaboration protocols and evaluating the effectiveness of these systems remains a significant challenge, especially for enterprise applications. This report addresses these challenges by presenting a comprehensive evaluation of coordination and routing capabilities in a novel multi-agent collaboration framework. We evaluate two key operational modes: (1) a coordination mode enabling complex task completion through parallel communication and payload referencing, and (2) a routing mode for efficient message forwarding between agents. We benchmark on a set of handcrafted scenarios from three enterprise domains, which are publicly released with the report. For coordination capabilities, we demonstrate the effectiveness of inter-agent communication and payload referencing mechanisms, achieving end-to-end goal success rates of 90%. Our analysis yields several key findings: multi-agent collaboration enhances goal success rates by up to 70% compared to single-agent approaches in our benchmarks; payload referencing improves performance on code-intensive tasks by 23%; latency can be substantially reduced with a routing mechanism that selectively bypasses agent orchestration. These findings offer valuable guidance for enterprise deployments of multi-agent systems and advance the development of scalable, efficient multi-agent collaboration frameworks.

[Arxiv](https://arxiv.org/abs/2412.05449)