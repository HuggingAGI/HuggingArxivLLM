# AgentMesh：协作式多智能体生成式AI框架，助力软件开发自动化

发布时间：2025年07月26日

`Agent` `软件开发` `软件工程`

> AgentMesh: A Cooperative Multi-Agent Generative AI Framework for Software Development Automation

# 摘要

> 软件开发传统上是一个复杂且多阶段的过程，通常需要不同领域专家的紧密合作。我们提出了AgentMesh，一个基于Python的框架，利用多个协同工作的LLM驱动代理，实现软件开发任务的自动化。在AgentMesh中，规划者、编码者、调试者和审查者这四个专门代理协同工作，将高层次需求转化为完整的代码实现。规划者首先将用户需求分解为具体子任务；编码者实现每个子任务的代码；调试者测试并修复代码；审查者验证最终输出的正确性和质量。我们详细介绍了这些代理的架构设计、通信机制，以及包括提示策略和工作流编排在内的实现细节。案例研究展示了AgentMesh如何通过任务规划、代码生成、迭代调试和最终审查来处理复杂开发请求。通过协作代理之间的职责分配，我们探讨了如何充分发挥大型语言模型的优势，同时克服单一代理的限制。最后，我们分析了当前的挑战，如错误传播和上下文扩展，并展望了未来的工作，旨在构建更健壮、可扩展的多代理AI系统，推动软件工程自动化的发展。

> Software development is a complex, multi-phase process traditionally requiring collaboration among individuals with diverse expertise. We propose AgentMesh, a Python-based framework that uses multiple cooperating LLM-powered agents to automate software development tasks. In AgentMesh, specialized agents - a Planner, Coder, Debugger, and Reviewer - work in concert to transform a high-level requirement into fully realized code. The Planner agent first decomposes user requests into concrete subtasks; the Coder agent implements each subtask in code; the Debugger agent tests and fixes the code; and the Reviewer agent validates the final output for correctness and quality. We describe the architecture and design of these agents and their communication, and provide implementation details including prompt strategies and workflow orchestration. A case study illustrates AgentMesh handling a non-trivial development request via sequential task planning, code generation, iterative debugging, and final code review. We discuss how dividing responsibilities among cooperative agents leverages the strengths of large language models while mitigating single-agent limitations. Finally, we examine current limitations - such as error propagation and context scaling - and outline future work toward more robust, scalable multi-agent AI systems for software engineering automation.

[Arxiv](https://arxiv.org/abs/2507.19902)