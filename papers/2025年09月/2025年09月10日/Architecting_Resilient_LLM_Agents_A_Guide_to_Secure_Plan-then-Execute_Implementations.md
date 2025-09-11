# 构建韧性LLM智能体：安全“先规划后执行”实现指南

发布时间：2025年09月10日

`Agent` `基础理论`

> Architecting Resilient LLM Agents: A Guide to Secure Plan-then-Execute Implementations

# 摘要

> 随着大型语言模型（LLM）智能体在自动化复杂多步骤任务上的能力愈发强大，稳健、安全且可预测的架构模式便成了重中之重。本文深入解析“先规划后执行”（P-t-E）模式，这是一种能实现战略规划与战术执行分离的智能体设计。我们不仅探讨了P-t-E的核心原理，还详细阐述其核心组件——规划器（Planner）与执行器（Executor）——以及相比ReAct（推理+行动）等反应式模式，P-t-E在可预测性、成本效益和推理质量上的架构优势。文章特别聚焦该设计的安全价值，尤其是通过构建控制流完整性，P-t-E天然具备抵御间接提示注入攻击的能力。我们认为，尽管P-t-E奠定了坚实基础，纵深防御策略仍不可或缺，并详细介绍了关键的补充控制措施，例如最小权限原则、任务级工具访问权限控制以及沙箱代码执行。为了让这些原则落地可执行，指南还提供了三个主流智能体框架的详细实现蓝图和可运行代码参考：LangChain（基于LangGraph）、CrewAI和AutoGen。我们分析了每个框架实现P-t-E模式的方法，并重点介绍其特色功能，如LangGraph用于重规划的有状态图、CrewAI面向安全的声明式工具范围控制，以及AutoGen内置的Docker沙箱机制。最后，我们还探讨了高级模式，包括动态重规划循环、基于有向无环图（DAGs）的并行执行，以及人机协作（HITL）验证的关键作用，为致力于构建生产级、高弹性且可信的LLM智能体的架构师、开发人员和安全工程师提供一份全面的战略蓝图。

> As Large Language Model (LLM) agents become increasingly capable of automating complex, multi-step tasks, the need for robust, secure, and predictable architectural patterns is paramount. This paper provides a comprehensive guide to the ``Plan-then-Execute'' (P-t-E) pattern, an agentic design that separates strategic planning from tactical execution. We explore the foundational principles of P-t-E, detailing its core components - the Planner and the Executor - and its architectural advantages in predictability, cost-efficiency, and reasoning quality over reactive patterns like ReAct (Reason + Act). A central focus is placed on the security implications of this design, particularly its inherent resilience to indirect prompt injection attacks by establishing control-flow integrity. We argue that while P-t-E provides a strong foundation, a defense-in-depth strategy is necessary, and we detail essential complementary controls such as the Principle of Least Privilege, task-scoped tool access, and sandboxed code execution. To make these principles actionable, this guide provides detailed implementation blueprints and working code references for three leading agentic frameworks: LangChain (via LangGraph), CrewAI, and AutoGen. Each framework's approach to implementing the P-t-E pattern is analyzed, highlighting unique features like LangGraph's stateful graphs for re-planning, CrewAI's declarative tool scoping for security, and AutoGen's built-in Docker sandboxing. Finally, we discuss advanced patterns, including dynamic re-planning loops, parallel execution with Directed Acyclic Graphs (DAGs), and the critical role of Human-in-the-Loop (HITL) verification, to offer a complete strategic blueprint for architects, developers, and security engineers aiming to build production-grade, resilient, and trustworthy LLM agents.

[Arxiv](https://arxiv.org/abs/2509.08646)