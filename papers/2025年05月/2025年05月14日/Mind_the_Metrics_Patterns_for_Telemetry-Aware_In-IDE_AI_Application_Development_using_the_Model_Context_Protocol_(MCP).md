# 关注指标：使用模型上下文协议 (MCP) 开发具备 telemetry 感知能力的 In-IDE AI 应用模式

发布时间：2025年05月14日

`LLM应用

理由：这篇论文主要探讨了AI开发环境的转型，特别是如何通过集成开发环境（IDE）和遥测数据来优化大型语言模型（LLM）的开发和使用。文中提到了提示优化、实时遥测数据、以及与多个框架的深度集成，这些都是围绕LLM应用的实际应用和工具改进，因此归类为LLM应用。` `AI开发工具` `软件工程`

> Mind the Metrics: Patterns for Telemetry-Aware In-IDE AI Application Development using the Model Context Protocol (MCP)

# 摘要

> AI 开发环境正在向以可观测性为核心的平台转型，实时遥测数据、提示追踪和评估反馈已无缝融入开发流程。本文介绍了由 Model Context Protocol (MCP) 驱动的遥测感知集成开发环境 (IDE)，该系统通过整合提示指标、追踪日志和版本控制，实现了开发过程的实时优化。我们提出了三种设计模式：本地提示迭代、基于 CI 的优化，以及利用遥测数据实现自适应行为的自主代理。我们的研究不局限于单一算法，而是构建了一个开放架构，支持与 DSPy、PromptWizard 和 Prompts as Programs 等框架的深度集成。通过 Opik——一个开源的 LLM 遥测 MCP 服务器——我们展示了这一理念的实际应用，并将其置于快速发展的 LLMOps 生态系统中。这项研究为未来在提示优化、IDE 代理工具以及数据丰富的 AI 开发工作流中的经验基准研究奠定了坚实的基础。

> AI development environments are evolving into observability first platforms that integrate real time telemetry, prompt traces, and evaluation feedback into the developer workflow. This paper introduces telemetry aware integrated development environments (IDEs) enabled by the Model Context Protocol (MCP), a system that connects IDEs with prompt metrics, trace logs, and versioned control for real time refinement. We present design patterns for local prompt iteration, CI based optimization, and autonomous agents that adapt behavior using telemetry. Rather than focusing on a single algorithm, we describe an architecture that supports integration with frameworks like DSPy, PromptWizard, and Prompts as Programs. We demonstrate this through Opik, an open source MCP server for LLM telemetry, and position our approach within the emerging LLMOps ecosystem. This work lays a foundation for future research on prompt optimization, IDE agent tooling, and empirical benchmarking in telemetry rich AI development workflows.

[Arxiv](https://arxiv.org/abs/2506.11019)