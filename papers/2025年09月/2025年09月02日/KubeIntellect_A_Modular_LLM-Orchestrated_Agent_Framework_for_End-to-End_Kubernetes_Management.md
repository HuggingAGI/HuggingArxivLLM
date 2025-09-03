# KubeIntellect：面向端到端Kubernetes管理的模块化LLM编排智能体框架

发布时间：2025年09月02日

`Agent` `工业与制造`

> KubeIntellect: A Modular LLM-Orchestrated Agent Framework for End-to-End Kubernetes Management

# 摘要

> Kubernetes已成为现代云原生基础设施的基石，但其管理依旧复杂且分散。管理员必须应对庞大的API接口，管理异构工作负载，并在互不关联的工具间协调任务——往往需要精准的命令、YAML配置和上下文专业知识。
  本文提出KubeIntellect，这是一个由大型语言模型（LLM）驱动的智能端到端Kubernetes控制系统。与专注于可观测性或静态自动化的现有工具不同，KubeIntellect支持跨Kubernetes API全操作范围的自然语言交互，包括读取、写入、删除、执行、访问控制、生命周期及高级动词。该系统采用与功能领域（如日志、指标、RBAC）对齐的模块化智能体，由一个监督器进行编排——该监督器负责解析用户查询、维护工作流记忆、调用可重用工具，或通过安全代码生成智能体合成新工具。
  KubeIntellect将记忆检查点、人机协作澄清和动态任务排序集成到结构化编排框架中。评估结果显示，在200个自然语言查询中，工具合成成功率达93%，可靠性达100%，充分证明了系统在多样化工作负载下的高效运行能力。
  Azure上提供了自动化演示环境，并通过kind额外支持本地测试。这项工作引入了一类全新的可解释、可扩展且由LLM驱动的系统，专为管理复杂基础设施而设计。

> Kubernetes has become the foundation of modern cloud-native infrastructure, yet its management remains complex and fragmented. Administrators must navigate a vast API surface, manage heterogeneous workloads, and coordinate tasks across disconnected tools - often requiring precise commands, YAML configuration, and contextual expertise.
  This paper presents KubeIntellect, a Large Language Model (LLM)-powered system for intelligent, end-to-end Kubernetes control. Unlike existing tools that focus on observability or static automation, KubeIntellect supports natural language interaction across the full spectrum of Kubernetes API operations, including read, write, delete, exec, access control, lifecycle, and advanced verbs. The system uses modular agents aligned with functional domains (e.g., logs, metrics, RBAC), orchestrated by a supervisor that interprets user queries, maintains workflow memory, invokes reusable tools, or synthesizes new ones via a secure Code Generator Agent.
  KubeIntellect integrates memory checkpoints, human-in-the-loop clarification, and dynamic task sequencing into a structured orchestration framework. Evaluation results show a 93% tool synthesis success rate and 100% reliability across 200 natural language queries, demonstrating the system's ability to operate efficiently under diverse workloads. An automated demo environment is provided on Azure, with additional support for local testing via kind. This work introduces a new class of interpretable, extensible, and LLM-driven systems for managing complex infrastructure.

[Arxiv](https://arxiv.org/abs/2509.02449)