# 基于智能体网络的智能体即服务模式

发布时间：2025年05月13日

`Agent` `多智能体系统` `人工智能`

> Agent-as-a-Service based on Agent Network

# 摘要

> 大型模型驱动的AI代理的兴起为多智能体系统（MAS）带来了新的可能性，这些系统在决策、协作和适应性方面展现出独特优势。尽管模型上下文协议（MCP）通过统一协议解决了工具调用和数据交换的挑战，但它在代理级别协作组织方面存在局限。为了解决这一问题，我们提出了基于代理网络的代理即服务（AaaS-AN），这是一种基于角色-目标-过程-服务（RGPS）标准的服务导向范式。AaaS-AN通过两个核心组件贯穿整个代理生命周期：（1）动态代理网络，将代理和代理组建模为顶点，根据任务和角色依赖关系实现自组织；（2）服务导向的代理，包含服务发现、注册和互操作性协议。这些组件由服务调度器编排，利用执行图实现分布式协调、上下文跟踪和运行时任务管理。我们在数学推理和应用级代码生成任务上验证了AaaS-AN，其性能优于现有最先进基线。值得注意的是，我们基于AaaS-AN构建了一个包含代理组、机器人流程自动化（RPA）工作流和MCP服务器的MAS，涉及超过100个代理服务。我们还发布了一个包含10,000个长周期多智能体工作流的数据集，以促进未来关于MAS中长链协作的研究。

> The rise of large model-based AI agents has spurred interest in Multi-Agent Systems (MAS) for their capabilities in decision-making, collaboration, and adaptability. While the Model Context Protocol (MCP) addresses tool invocation and data exchange challenges via a unified protocol, it lacks support for organizing agent-level collaboration. To bridge this gap, we propose Agent-as-a-Service based on Agent Network (AaaS-AN), a service-oriented paradigm grounded in the Role-Goal-Process-Service (RGPS) standard. AaaS-AN unifies the entire agent lifecycle, including construction, integration, interoperability, and networked collaboration, through two core components: (1) a dynamic Agent Network, which models agents and agent groups as vertexes that self-organize within the network based on task and role dependencies; (2) service-oriented agents, incorporating service discovery, registration, and interoperability protocols. These are orchestrated by a Service Scheduler, which leverages an Execution Graph to enable distributed coordination, context tracking, and runtime task management. We validate AaaS-AN on mathematical reasoning and application-level code generation tasks, which outperforms state-of-the-art baselines. Notably, we constructed a MAS based on AaaS-AN containing agent groups, Robotic Process Automation (RPA) workflows, and MCP servers over 100 agent services. We also release a dataset containing 10,000 long-horizon multi-agent workflows to facilitate future research on long-chain collaboration in MAS.

[Arxiv](https://arxiv.org/abs/2505.08446)