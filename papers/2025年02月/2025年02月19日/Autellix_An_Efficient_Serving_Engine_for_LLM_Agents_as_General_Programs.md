# Autellix：高效LLM代理服务引擎，实现通用程序功能

发布时间：2025年02月19日

`LLM应用` `LLM服务` `智能体`

> Autellix: An Efficient Serving Engine for LLM Agents as General Programs

# 摘要

> 大型语言模型（LLM）的应用正在从简单的聊天机器人发展为动态的、通用的智能体程序，这些程序通过扩展LLM调用和输出令牌来帮助AI智能体进行推理、探索和解决复杂任务。然而，现有的LLM服务系统忽视了程序与调用之间的依赖关系，错失了重要的优化机会。我们的分析表明，提交到LLM服务引擎的程序会经历漫长的累积等待时间，这主要是由于在单个LLM请求和程序层面都存在队首阻塞现象。

为了解决这一问题，我们引入了Autellix，这是一个将程序作为第一公民对待的LLM服务系统，旨在最大限度地减少它们的端到端延迟。Autellix拦截程序提交的LLM调用，通过程序级别的上下文丰富调度器。我们提出了两种调度算法——针对单线程和分布式程序——它们根据程序之前完成的调用来抢先和优先调度LLM调用。

我们的评估表明，与现有的系统（如vLLM）相比，Autellix在相同的延迟下，将程序的吞吐量提高了4-15倍，适用于各种LLM和智能体工作负载。

> Large language model (LLM) applications are evolving beyond simple chatbots into dynamic, general-purpose agentic programs, which scale LLM calls and output tokens to help AI agents reason, explore, and solve complex tasks. However, existing LLM serving systems ignore dependencies between programs and calls, missing significant opportunities for optimization. Our analysis reveals that programs submitted to LLM serving engines experience long cumulative wait times, primarily due to head-of-line blocking at both the individual LLM request and the program. To address this, we introduce Autellix, an LLM serving system that treats programs as first-class citizens to minimize their end-to-end latencies. Autellix intercepts LLM calls submitted by programs, enriching schedulers with program-level context. We propose two scheduling algorithms-for single-threaded and distributed programs-that preempt and prioritize LLM calls based on their programs' previously completed calls. Our evaluation demonstrates that across diverse LLMs and agentic workloads, Autellix improves throughput of programs by 4-15x at the same latency compared to state-of-the-art systems, such as vLLM.

[Arxiv](https://arxiv.org/abs/2502.13965)