# SymAgent: 神经符号自学习代理框架，专为知识图谱的复杂推理而设计

发布时间：2025年02月05日

`Agent

理由：这篇论文提出了一种名为SymAgent的神经符号代理框架，旨在通过结合知识图谱（KGs）和大型语言模型（LLMs）来增强复杂推理任务的处理能力。论文的核心是设计了一个代理系统，该系统包含Agent-Planner和Agent-Executor两个模块，分别负责问题分解和执行动作工具。此外，论文还提到了自学习框架，使代理能够自动合成推理轨迹并提升性能。这些内容都符合“Agent”分类，因为论文主要关注的是代理系统的设计和实现，以及如何通过代理来增强LLMs的推理能力。` `知识图谱` `推理系统`

> SymAgent: A Neural-Symbolic Self-Learning Agent Framework for Complex Reasoning over Knowledge Graphs

# 摘要

> # 摘要
近期研究表明，大型语言模型（LLMs）在处理复杂推理问题时容易产生幻觉，导致错误结果。为解决这一问题，研究人员引入知识图谱（KGs）以增强LLMs的推理能力。然而，现有方法存在两大局限：1）通常假设所有问题答案均包含在KGs中，忽视了KGs的不完整性；2）将KG视为静态存储库，忽略了其内在的隐式逻辑推理结构。本文提出SymAgent，一种创新的神经符号代理框架，实现KGs与LLMs的协同增强。我们将KGs视为动态环境，将复杂推理任务转化为多步交互过程，使KGs深度参与推理。SymAgent包含两个模块：Agent-Planner和Agent-Executor。Agent-Planner利用LLM的归纳推理能力从KGs中提取符号规则，指导高效问题分解；Agent-Executor则自主调用预定义动作工具，整合KGs与外部文档信息，解决KGs不完整性问题。此外，我们设计了包含在线探索与离线迭代策略更新的自学习框架，使代理能够自动合成推理轨迹并提升性能。实验表明，使用弱LLM骨干（如7B系列）的SymAgent在多种强基线中表现优异或相当。进一步分析显示，该代理能识别缺失三元组，促进KGs自动更新。

> Recent advancements have highlighted that Large Language Models (LLMs) are prone to hallucinations when solving complex reasoning problems, leading to erroneous results. To tackle this issue, researchers incorporate Knowledge Graphs (KGs) to improve the reasoning ability of LLMs. However, existing methods face two limitations: 1) they typically assume that all answers to the questions are contained in KGs, neglecting the incompleteness issue of KGs, and 2) they treat the KG as a static repository and overlook the implicit logical reasoning structures inherent in KGs. In this paper, we introduce SymAgent, an innovative neural-symbolic agent framework that achieves collaborative augmentation between KGs and LLMs. We conceptualize KGs as dynamic environments and transform complex reasoning tasks into a multi-step interactive process, enabling KGs to participate deeply in the reasoning process. SymAgent consists of two modules: Agent-Planner and Agent-Executor. The Agent-Planner leverages LLM's inductive reasoning capability to extract symbolic rules from KGs, guiding efficient question decomposition. The Agent-Executor autonomously invokes predefined action tools to integrate information from KGs and external documents, addressing the issues of KG incompleteness. Furthermore, we design a self-learning framework comprising online exploration and offline iterative policy updating phases, enabling the agent to automatically synthesize reasoning trajectories and improve performance. Experimental results demonstrate that SymAgent with weak LLM backbones (i.e., 7B series) yields better or comparable performance compared to various strong baselines. Further analysis reveals that our agent can identify missing triples, facilitating automatic KG updates.

[Arxiv](https://arxiv.org/abs/2502.03283)