# # Gradientsys：基于 ReAct 编排的多智能体 LLM 调度系统

发布时间：2025年07月08日

`Agent` `AI系统优化` `多智能体协作`

> Gradientsys: A Multi-Agent LLM Scheduler with ReAct Orchestration

# 摘要

> 我们推出了一款名为Gradientsys的下一代多智能体调度框架，它利用类型化的模型上下文协议（MCP）和基于ReAct的动态规划循环，协调各类专业的AI智能体协同工作。框架的核心是一个由大型语言模型（LLM）驱动的智能调度器，支持将任务分配给多个不同类型的智能体（如PDF解析器、网络搜索模块等）并行执行。Gradientsys不仅支持混合同步/异步任务处理，还内置了智能容量管理和故障恢复机制，确保系统运行的高效与稳定。为了增强系统的透明度和用户信任，我们特别设计了一个实时观测层，通过服务器发送事件（SSE）技术，让用户随时查看智能体的活动状态和中间推理过程。通过对现有框架在可扩展性、调度能力、工具复用性、并行执行和观测能力等多维度的对比分析，我们展示了Gradientsys的显著优势。在GAIA通用助手基准测试中，Gradientsys不仅任务成功率更高，而且在延迟和API成本方面均优于MinionS风格的基线系统，充分证明了其LLM驱动的多智能体编排技术的优越性。

> We present Gradientsys, a next-generation multi-agent scheduling framework that coordinates diverse specialized AI agents using a typed Model-Context Protocol (MCP) and a ReAct-based dynamic planning loop. At its core, Gradientsys employs an LLM-powered scheduler for intelligent one-to-many task dispatch, enabling parallel execution of heterogeneous agents such as PDF parsers, web search modules, GUI controllers, and web builders. The framework supports hybrid synchronous/asynchronous execution, respects agent capacity constraints, and incorporates a robust retry-and-replan mechanism to handle failures gracefully. To promote transparency and trust, Gradientsys includes an observability layer streaming real-time agent activity and intermediate reasoning via Server-Sent Events (SSE). We offer an architectural overview and evaluate Gradientsys against existing frameworks in terms of extensibility, scheduling topology, tool reusability, parallelism, and observability. Experiments on the GAIA general-assistant benchmark show that Gradientsys achieves higher task success rates with reduced latency and lower API costs compared to a MinionS-style baseline, demonstrating the strength of its LLM-driven multi-agent orchestration.

[Arxiv](https://arxiv.org/abs/2507.06520)