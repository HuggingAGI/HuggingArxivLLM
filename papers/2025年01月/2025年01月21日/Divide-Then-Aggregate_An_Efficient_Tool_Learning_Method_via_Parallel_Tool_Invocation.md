# 分而治之：并行工具调用的高效工具学习方法

发布时间：2025年01月21日

`Agent

理由：这篇论文提出了一种新的并行工具调用范式（DTA-Llama），旨在通过将任务划分为多个并行工具调用子任务并聚合结果来提升任务性能。这种方法涉及到与外部环境的交互和任务规划，符合Agent的定义，即能够感知环境、做出决策并执行动作的智能体。因此，这篇论文应归类为Agent。` `人工智能` `任务规划`

> Divide-Then-Aggregate: An Efficient Tool Learning Method via Parallel Tool Invocation

# 摘要

> 尽管当前的大型语言模型（LLMs）能力出众，但执行复杂现实任务仍需工具学习。主流方法如CoT/ReAct通过逐步调用工具与外部环境交互，但感知范围有限且任务规划能力不足。为解决这些问题，其他研究提出了首个基于搜索的决策树（DFSDT），但其计算成本高昂。本文提出了一种新颖的并行工具调用范式——DTA-Llama（Divide-Then-Aggregate Llama）。首先，我们将传统的树状工具搜索路径转换为有向无环图（DAG）结构，生成高质量的并行工具调用数据集。DTA-Llama在该数据集上训练，学习如何将任务迭代划分为多个并行工具调用子任务，并聚合结果以决定下一步行动。此外，我们借鉴进程/线程机制，为DTA-Llama设计了一个高效的推理框架。实验表明，该方法显著提升了任务性能，同时减少了令牌消耗和推理时间。使用该方法的Llama2-7B与GPT-3.5的官方并行函数调用方法表现相当。相关代码、数据集和模型权重可在https://corn0205.github.io/获取。

> Although current Large Language Models (LLMs) exhibit impressive capabilities, performing complex real-world tasks still requires tool learning. Mainstream methods, such as CoT/ReAct, rely on step-by-step tool invocation to interact with external environments, but they are limited in perceptual scope and lack adequate task-planning capability. To address these limitations, other studies introduce the first Search-based Decision Tree (DFSDT), which still suffers from the high computational cost. In this paper, we introduce a novel parallel tool invocation paradigm, DTA-Llama (Divide-Then-Aggregate Llama). First, we transform traditional tree-based tool search paths into Directed Acyclic Graph (DAG) structure, generating a high-quality parallel tool invocation dataset. The DTA-Llama is then trained on the dataset to learn to iteratively divide the current task into several parallel tool invocation sub-tasks and aggregate the invocation results to decide the next actions. Furthermore, we introduce an efficient inference framework inspired by the Process/Threads mechanism when applying the DTA-Llama to practical tasks. Experimental results show that our approach substantially enhances task performance while reducing token consumption and inference time. Llama2-7B, using our method, is comparable to the official parallel function calling method of GPT-3.5. The relevant code, dataset, and model weights are available at https://corn0205.github.io/

[Arxiv](https://arxiv.org/abs/2501.12432)