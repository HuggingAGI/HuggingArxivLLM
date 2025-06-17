# 基于语义的LLM推理调度方案

发布时间：2025年06月13日

`LLM应用` `操作系统`

> Semantic Scheduling for LLM Inference

# 摘要

> 传统的操作系统调度算法大多对任务内容“视而不见”，它们仅根据延迟或公平性等因素做出决策，完全忽略了进程的实际意图或语义。因此，这些算法往往无法有效识别并优先处理那些需要紧急关注或具有更高重要性的任务，例如在应急管理等关键场景中。然而，语言模型的最新进展使我们能够对进程进行语义分析，从而做出更智能且上下文感知的调度决策。

在本文中，我们引入了大型语言模型（LLM）请求调度中的语义调度概念，其中进程的语义直接指导调度优先级。我们提出了一种具有最优时间复杂度的新调度算法，旨在最小化基于LLM提示调度的总体等待时间。为了展示其有效性，我们展示了一个医疗应急管理系统应用，强调语义调度对关键、时间敏感任务的潜在好处。

代码和数据可在https://github.com/Wenyueh/latency_optimization_with_priority_constraints获取。


> Conventional operating system scheduling algorithms are largely content-ignorant, making decisions based on factors such as latency or fairness without considering the actual intents or semantics of processes. Consequently, these algorithms often do not prioritize tasks that require urgent attention or carry higher importance, such as in emergency management scenarios. However, recent advances in language models enable semantic analysis of processes, allowing for more intelligent and context-aware scheduling decisions. In this paper, we introduce the concept of semantic scheduling in scheduling of requests from large language models (LLM), where the semantics of the process guide the scheduling priorities. We present a novel scheduling algorithm with optimal time complexity, designed to minimize the overall waiting time in LLM-based prompt scheduling. To illustrate its effectiveness, we present a medical emergency management application, underscoring the potential benefits of semantic scheduling for critical, time-sensitive tasks. The code and data are available at https://github.com/Wenyueh/latency_optimization_with_priority_constraints.

[Arxiv](https://arxiv.org/abs/2506.12204)