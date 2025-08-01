# 语义信任链：借助超图增强的智能体AI技术实现协作选择的自主信任编排机制

发布时间：2025年07月31日

`Agent

摘要中提到的智能体AI用于自主感知设备状态、任务分解和语义推理，结合超图技术进行信任评估和资源管理，属于智能体的应用场景。` `物联网` `分布式系统`

> Semantic Chain-of-Trust: Autonomous Trust Orchestration for Collaborator Selection via Hypergraph-Aided Agentic AI

# 摘要

> 在协作系统中，任务的高效完成依赖于对潜在设备进行任务特定的信任评估。然而，任务复杂性、设备资源的时空动态性以及评估开销的增加，使得信任评估过程变得复杂且耗资源。不恰当的或过于频繁的信任评估会降低资源利用率，进而影响协作任务执行。为解决这一问题，本文提出了一种基于语义信任链的自主信任编排方法。我们的方法结合智能体AI和超图技术，用于建立和维护设备间的信任关系。智能体AI通过自主感知设备状态、任务分解和语义推理，在设备空闲时基于历史数据自主执行信任评估，从而优化资源利用。此外，智能体AI通过分析资源与任务需求的匹配度，进行任务特定的信任评估。通过维护嵌入信任语义的超图，智能体AI实现了协作方的分层管理，并基于语义识别需要评估的协作方，在开销与准确性之间取得平衡。多设备的信任超图可链式连接，支持大规模协作系统的高效协调。实验结果表明，本方法在资源效率方面实现了高效信任评估。

> In collaborative systems, the effective completion of tasks hinges on task-specific trust evaluations of potential devices for distributed collaboration. However, the complexity of tasks, the spatiotemporal dynamism of distributed device resources, and the inevitable assessment overhead dramatically increase the complexity and resource consumption of the trust evaluation process. As a result, ill-timed or overly frequent trust evaluations can reduce utilization rate of constrained resources, negatively affecting collaborative task execution. To address this challenge, this paper proposes an autonomous trust orchestration method based on a new concept of semantic chain-of-trust. Our technique employs agentic AI and hypergraph to establish and maintain trust relationships among devices. By leveraging its strengths in autonomous perception, task decomposition, and semantic reasoning, we propose agentic AI to perceive device states and autonomously perform trust evaluations of collaborators based on historical performance data only during device idle periods, thereby enabling efficient utilization of distributed resources. In addition, agentic AI performs task-specific trust evaluations on collaborator resources by analyzing the alignment between resource capabilities and task requirements. Moreover, by maintaining a trust hypergraph embedded with trust semantics for each device, agentic AI enables hierarchical management of collaborators and identifies collaborators requiring trust evaluation based on trust semantics, thereby achieving a balance between overhead and trust accuracy. Furthermore, local trust hypergraphs from multiple devices can be chained together to support multi-hop collaboration, enabling efficient coordination in large-scale systems. Experimental results demonstrate that the proposed method achieves resource-efficient trust evaluation.

[Arxiv](https://arxiv.org/abs/2507.23565)