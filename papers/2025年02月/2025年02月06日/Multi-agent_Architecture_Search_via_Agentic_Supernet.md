# 基于智能体超级网络的多智能体架构搜索

发布时间：2025年02月06日

`Agent

理由：这篇论文主要讨论了如何通过优化智能体超级网络（智能体架构的概率连续分布）来构建更高效的智能体系统。论文提出了MaAS框架，该框架能够根据查询的难度和领域动态分配推理资源，从而在多个基准测试中表现出色。虽然论文中提到了大型语言模型（LLM）的使用，但其核心关注点是智能体系统的设计和优化，因此应归类为Agent。` `智能体系统` `资源优化`

> Multi-agent Architecture Search via Agentic Supernet

# 摘要

> # 摘要
大型语言模型（LLM）赋能的智能体系统通过协作与互动扩展了个体智能体的认知边界，但构建这些系统往往依赖繁重的手动设计。尽管已有方法可自动化设计智能体工作流，但它们通常追求静态、复杂且通用的系统，无法根据查询难度和领域动态分配推理资源。为此，我们摒弃了单一智能体系统的思路，转而优化	extbf{智能体超级网络}——一种智能体架构的概率连续分布。我们提出了MaAS框架，它能从超级网络中采样出与查询相关的智能体系统，提供高质量解决方案并实现资源（如LLM调用、工具调用、令牌成本）的精准分配。在六个基准测试中，MaAS 	extbf{(I)} 仅需现有手工或自动化多智能体系统推理成本的$6\sim45\%$，	extbf{(II)} 性能超越它们$0.54\%\sim11.82\%$，	extbf{(III)} 并展现出卓越的跨数据集和跨LLM骨干的迁移能力。

> Large Language Model (LLM)-empowered multi-agent systems extend the cognitive boundaries of individual agents through disciplined collaboration and interaction, while constructing these systems often requires labor-intensive manual designs. Despite the availability of methods to automate the design of agentic workflows, they typically seek to identify a static, complex, one-size-fits-all system, which, however, fails to dynamically allocate inference resources based on the difficulty and domain of each query. To address this challenge, we shift away from the pursuit of a monolithic agentic system, instead optimizing the \textbf{agentic supernet}, a probabilistic and continuous distribution of agentic architectures. We introduce MaAS, an automated framework that samples query-dependent agentic systems from the supernet, delivering high-quality solutions and tailored resource allocation (\textit{e.g.}, LLM calls, tool calls, token cost). Comprehensive evaluation across six benchmarks demonstrates that MaAS \textbf{(I)} requires only $6\sim45\%$ of the inference costs of existing handcrafted or automated multi-agent systems, \textbf{(II)} surpasses them by $0.54\%\sim11.82\%$, and \textbf{(III)} enjoys superior cross-dataset and cross-LLM-backbone transferability.

[Arxiv](https://arxiv.org/abs/2502.04180)