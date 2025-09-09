# 深度研究系统的强化学习基础：综述

发布时间：2025年09月08日

`Agent` `基础理论`

> Reinforcement Learning Foundations for Deep Research Systems: A Survey

# 摘要

> 深度研究系统是一类能解决复杂多步骤任务的智能体AI，它们通过协调推理、跨开放网络与用户文件搜索及工具使用来完成任务，目前正朝着包含规划器、协调器和执行器的分层部署架构演进。但在实际应用中，端到端训练整个系统栈仍不现实，因此多数研究仅训练一个连接搜索、浏览、代码等核心工具的单一规划器。监督微调（SFT）虽能保证协议遵循的准确性，却存在模仿偏差与暴露偏差问题，还会浪费环境反馈信息。而偏好对齐方法（如DPO）则依赖模式与代理，采用离策略训练，在长程信用分配和多目标权衡上效果欠佳。SFT和DPO的另一大局限在于，它们需通过模式设计和标记比较来依赖人类定义的决策点与子技能。相比之下，强化学习通过优化轨迹级策略，天然适配闭环工具交互研究，不仅能实现探索、恢复行为及合理的信用分配，还能降低对人类先验和评分者偏差的依赖。
  据我们所知，本文是首篇聚焦深度研究系统强化学习基础的综述。本文从三个维度系统梳理了DeepSeek-R1之后的相关研究：（i）数据合成与整理；（ii）智能体研究的强化学习方法，涵盖稳定性、样本效率、长上下文处理、奖励与信用设计、多目标优化及多模态集成；（iii）智能体强化学习训练系统与框架。此外，本文还涉及智能体架构与协调机制、评估方法与基准测试，包括最新的问答（QA）、视觉问答（VQA）、长文本合成及领域特定的工具交互任务。我们总结了研究中的常见模式，指出了基础设施瓶颈，并为利用强化学习训练稳健、透明的深度研究智能体提供了实用建议。

> Deep research systems, agentic AI that solve complex, multi-step tasks by coordinating reasoning, search across the open web and user files, and tool use, are moving toward hierarchical deployments with a Planner, Coordinator, and Executors. In practice, training entire stacks end-to-end remains impractical, so most work trains a single planner connected to core tools such as search, browsing, and code. While SFT imparts protocol fidelity, it suffers from imitation and exposure biases and underuses environment feedback. Preference alignment methods such as DPO are schema and proxy-dependent, off-policy, and weak for long-horizon credit assignment and multi-objective trade-offs. A further limitation of SFT and DPO is their reliance on human defined decision points and subskills through schema design and labeled comparisons. Reinforcement learning aligns with closed-loop, tool-interaction research by optimizing trajectory-level policies, enabling exploration, recovery behaviors, and principled credit assignment, and it reduces dependence on such human priors and rater biases.
  This survey is, to our knowledge, the first dedicated to the RL foundations of deep research systems. It systematizes work after DeepSeek-R1 along three axes: (i) data synthesis and curation; (ii) RL methods for agentic research covering stability, sample efficiency, long context handling, reward and credit design, multi-objective optimization, and multimodal integration; and (iii) agentic RL training systems and frameworks. We also cover agent architecture and coordination, as well as evaluation and benchmarks, including recent QA, VQA, long-form synthesis, and domain-grounded, tool-interaction tasks. We distill recurring patterns, surface infrastructure bottlenecks, and offer practical guidance for training robust, transparent deep research agents with RL.

[Arxiv](https://arxiv.org/abs/2509.06733)