# ExCyTIn-Bench：针对网络安全威胁调查的 LLM 代理评估

发布时间：2025年07月14日

`LLM应用` `网络安全` `威胁情报`

> ExCyTIn-Bench: Evaluating LLM agents on Cyber Threat Investigation

# 摘要

> 我们提出 ExCyTIn-Bench，这是首个通过源自调查图的安全问题来评估 LLM 代理在网络安全威胁调查任务中表现的基准测试。现实中的安全分析师必须筛选大量异构的告警信号和安全日志，跟踪多跳的证据链，并编制事件报告。随着 LLMs 的发展，构建基于 LLM 的自动威胁调查代理成为可能。为了协助 LLM 代理的开发和评估，我们从一个受控的 Azure 租户中构建了一个数据集，涵盖了 8 个模拟的现实世界多步攻击、来自 Microsoft Sentinel 及相关服务的 57 个日志表以及 589 个自动生成的问题。我们利用专家编写的检测逻辑提取安全日志，构建威胁调查图，并使用图中的配对节点生成问题，将起始节点作为背景上下文，终点节点作为答案。将每个问题锚定到这些显式的节点和边，不仅提供了自动化的、可解释的 ground truth 答案，还使整个流程可复用且易于扩展到新的日志。这还实现了具有可验证奖励的程序化任务的自动生成，这些任务可以自然扩展到通过强化学习训练代理。我们使用不同模型进行的综合实验验证了任务的难度：在基础设置下，所有评估模型的平均奖励为 0.249，最佳表现达到 0.368，为未来研究留下了巨大的空间。代码和数据即将发布！

> We present ExCyTIn-Bench, the first benchmark to Evaluate an LLM agent x on the task of Cyber Threat Investigation through security questions derived from investigation graphs. Real-world security analysts must sift through a large number of heterogeneous alert signals and security logs, follow multi-hop chains of evidence, and compile an incident report. With the developments of LLMs, building LLM-based agents for automatic thread investigation is a promising direction. To assist the development and evaluation of LLM agents, we construct a dataset from a controlled Azure tenant that covers 8 simulated real-world multi-step attacks, 57 log tables from Microsoft Sentinel and related services, and 589 automatically generated questions. We leverage security logs extracted with expert-crafted detection logic to build threat investigation graphs, and then generate questions with LLMs using paired nodes on the graph, taking the start node as background context and the end node as answer. Anchoring each question to these explicit nodes and edges not only provides automatic, explainable ground truth answers but also makes the pipeline reusable and readily extensible to new logs. This also enables the automatic generation of procedural tasks with verifiable rewards, which can be naturally extended to training agents via reinforcement learning. Our comprehensive experiments with different models confirm the difficulty of the task: with the base setting, the average reward across all evaluated models is 0.249, and the best achieved is 0.368, leaving substantial headroom for future research. Code and data are coming soon!

[Arxiv](https://arxiv.org/abs/2507.14201)