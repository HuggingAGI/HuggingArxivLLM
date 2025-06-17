# AgentOrchestra：面向通用任务解决的分层多智能体框架

发布时间：2025年06月14日

`Agent` `智能体协作` `通用任务解决`

> AgentOrchestra: A Hierarchical Multi-Agent Framework for General-Purpose Task Solving

# 摘要

> 基于大型语言模型（LLMs）的智能体系统在解决复杂任务方面展现出强大能力，但现有方法在协调专业智能体和跨领域扩展方面仍显不足。为此，我们提出了\projectname，一个结合高层规划与模块化协作的分层多智能体框架，专为通用任务解决而设计。受指挥家指挥交响乐的启发，并遵循可扩展性、多模态性、模块化和协调性原则，\projectname框架配备了一个中央规划智能体，能够将复杂目标分解为子任务并分配给专业智能体团队。每个子智能体都配备了通用编程与分析工具，并具备处理广泛现实任务的能力，包括数据分析、文件操作、网络导航以及在动态多模态环境中进行交互式推理。通过明确的子目标制定、智能体间通信和自适应角色分配，\projectname实现了灵活的任务编排。我们在涵盖网页搜索、异质模态推理等多样化现实任务的三个基准数据集上评估了该框架。实验结果表明，\projectname在任务成功率和适应性方面均显著优于平面智能体和单体基线。这一发现凸显了分层组织和角色专业化在构建可扩展和通用LLM智能体系统中的有效性。

> Recent advances in agent systems based on large language models (LLMs) have demonstrated strong capabilities in solving complex tasks. However, most current methods lack mechanisms for coordinating specialized agents and have limited ability to generalize to new or diverse domains. We introduce \projectname, a hierarchical multi-agent framework for general-purpose task solving that integrates high-level planning with modular agent collaboration. Inspired by the way a conductor orchestrates a symphony and guided by the principles of \textit{extensibility}, \textit{multimodality}, \textit{modularity}, and \textit{coordination}, \projectname features a central planning agent that decomposes complex objectives and delegates sub-tasks to a team of specialized agents. Each sub-agent is equipped with general programming and analytical tools, as well as abilities to tackle a wide range of real-world specific tasks, including data analysis, file operations, web navigation, and interactive reasoning in dynamic multimodal environments. \projectname supports flexible orchestration through explicit sub-goal formulation, inter-agent communication, and adaptive role allocation. We evaluate the framework on three widely used benchmark datasets covering various real-world tasks, searching web pages, reasoning over heterogeneous modalities, etc. Experimental results demonstrate that \projectname consistently outperforms flat-agent and monolithic baselines in task success rate and adaptability. These findings highlight the effectiveness of hierarchical organization and role specialization in building scalable and general-purpose LLM-based agent systems.

[Arxiv](https://arxiv.org/abs/2506.12508)