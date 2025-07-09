# # 解耦规划与执行：为深度搜索设计的分层推理框架

发布时间：2025年07月03日

`RAG` `信息检索` `搜索系统`

> Decoupled Planning and Execution: A Hierarchical Reasoning Framework for Deep Search

# 摘要

> 在现实世界搜索场景中，复杂的用户需求需要在多种来源之间进行深度推理和知识整合，这使得传统检索增强生成（RAG）管道难以有效应对。目前基于推理的方法存在一个根本性限制：它们使用单一模型来同时处理高层规划和详细执行，导致推理效率低下且扩展性有限。本文中，我们介绍了HiRA，一个将战略性规划与专门化执行分离的创新分层框架。我们的方法将复杂的搜索任务分解为专注的子任务，将每个子任务分配给配备外部工具和推理能力的领域特定代理，并通过结构化集成机制协调结果。这种分离不仅防止了执行细节干扰高层推理，还使系统能够充分利用不同类型信息处理的专门知识。在四个复杂跨模态深度搜索基准上的实验表明，HiRA显著优于现有的RAG和基于代理的系统。我们的结果显示，无论是答案质量还是系统效率都得到了显著提升，这充分证明了对多步骤信息检索任务中规划与执行分离的有效性。我们的代码可在GitHub仓库https://github.com/ignorejjj/HiRA获取。

> Complex information needs in real-world search scenarios demand deep reasoning and knowledge synthesis across diverse sources, which traditional retrieval-augmented generation (RAG) pipelines struggle to address effectively. Current reasoning-based approaches suffer from a fundamental limitation: they use a single model to handle both high-level planning and detailed execution, leading to inefficient reasoning and limited scalability. In this paper, we introduce HiRA, a hierarchical framework that separates strategic planning from specialized execution. Our approach decomposes complex search tasks into focused subtasks, assigns each subtask to domain-specific agents equipped with external tools and reasoning capabilities, and coordinates the results through a structured integration mechanism. This separation prevents execution details from disrupting high-level reasoning while enabling the system to leverage specialized expertise for different types of information processing. Experiments on four complex, cross-modal deep search benchmarks demonstrate that HiRA significantly outperforms state-of-the-art RAG and agent-based systems. Our results show improvements in both answer quality and system efficiency, highlighting the effectiveness of decoupled planning and execution for multi-step information seeking tasks. Our code is available at https://github.com/ignorejjj/HiRA.

[Arxiv](https://arxiv.org/abs/2507.02652)