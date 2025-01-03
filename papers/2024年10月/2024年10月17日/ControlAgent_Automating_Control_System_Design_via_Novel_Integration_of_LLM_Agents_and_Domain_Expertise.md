# ControlAgent: 通过LLM代理与领域专业知识的创新融合，实现控制系统设计的自动化

发布时间：2024年10月17日

`Agent

理由：这篇论文主要介绍了一种名为ControlAgent的系统，该系统通过结合LLM代理和领域专业知识来自动化控制系统设计。ControlAgent包含多个协作的LLM代理，每个代理负责不同的任务，如任务分配、详细设计、复杂计算和控制器评估等。这些代理通过协作和迭代优化来模拟人类工程师的设计流程，并最终实现端到端的自动化控制系统设计。因此，这篇论文的核心内容是关于Agent的设计和应用，属于Agent分类。` `航空航天` `机器人`

> ControlAgent: Automating Control System Design via Novel Integration of LLM Agents and Domain Expertise

# 摘要

> # 控制系统设计
控制系统设计是现代工程的核心，广泛应用于航空航天、汽车、电网和机器人等领域。尽管大型语言模型（LLMs）在多个领域取得了显著进展，但由于控制理论的复杂性和特殊性，其在控制系统设计中的应用仍有限。为此，我们提出了ControlAgent，这是一种通过LLM代理与领域专业知识相结合的新范式，旨在自动化控制系统设计。ControlAgent不仅编码了专家控制知识，还通过逐步调整控制器参数来模拟人类的设计迭代过程，以满足用户对稳定性、性能和鲁棒性的要求。ControlAgent集成了多个协作的LLM代理，包括一个负责任务分配的中心代理和多个针对不同系统及需求进行详细设计的任务特定代理。此外，ControlAgent还配备了一个Python计算代理，用于执行复杂计算和控制器评估，这些计算基于任务特定LLM代理提供的标准设计信息。结合历史和反馈模块，任务特定LLM代理能够根据先前设计的实时反馈迭代优化控制器参数。总体而言，ControlAgent不仅模仿了人类工程师的设计流程，还完全自动化了这一过程，为用户指定的控制系统设计提供了端到端的解决方案。为了验证ControlAgent的有效性，我们开发了ControlEval评估数据集，其中包含500个具有不同设计目标的控制任务。通过与传统人类参与的基于工具箱的基线进行广泛比较，ControlAgent的有效性得到了充分验证。

> Control system design is a crucial aspect of modern engineering with far-reaching applications across diverse sectors including aerospace, automotive systems, power grids, and robotics. Despite advances made by Large Language Models (LLMs) in various domains, their application in control system design remains limited due to the complexity and specificity of control theory. To bridge this gap, we introduce ControlAgent, a new paradigm that automates control system design via novel integration of LLM agents and control-oriented domain expertise. ControlAgent encodes expert control knowledge and emulates human iterative design processes by gradually tuning controller parameters to meet user-specified requirements for stability, performance, and robustness. ControlAgent integrates multiple collaborative LLM agents, including a central agent responsible for task distribution and task-specific agents dedicated to detailed controller design for various types of systems and requirements. ControlAgent also employs a Python computation agent that performs complex calculations and controller evaluations based on standard design information provided by task-specified LLM agents. Combined with a history and feedback module, the task-specific LLM agents iteratively refine controller parameters based on real-time feedback from prior designs. Overall, ControlAgent mimics the design processes used by (human) practicing engineers, but removes all the human efforts and can be run in a fully automated way to give end-to-end solutions for control system design with user-specified requirements. To validate ControlAgent's effectiveness, we develop ControlEval, an evaluation dataset that comprises 500 control tasks with various specific design goals. The effectiveness of ControlAgent is demonstrated via extensive comparative evaluations between LLM-based and traditional human-involved toolbox-based baselines.

[Arxiv](https://arxiv.org/abs/2410.19811)