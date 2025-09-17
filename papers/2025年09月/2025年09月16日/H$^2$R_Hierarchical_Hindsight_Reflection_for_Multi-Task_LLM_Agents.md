# H²R：面向多任务LLM智能体的分层事后反思（Hierarchical Hindsight Reflection for Multi-Task LLM Agents）

发布时间：2025年09月16日

`Agent` `基础理论`

> H$^2$R: Hierarchical Hindsight Reflection for Multi-Task LLM Agents

# 摘要

> 基于大型语言模型（LLM）的智能体凭借跨任务知识迁移能力，在多任务场景中展现出巨大潜力。然而，现有方法常将过往经验与知识视作整体单元，造成知识迁移效率低下且粒度粗糙。为此，本研究提出一种新型分层记忆架构，通过分离高层规划记忆与低层执行记忆，实现细粒度知识迁移。为构建并优化此类分层记忆，我们提出分层后见反思机制（H²R），该机制能从智能体与环境的历史交互中提取可复用的分层知识。测试阶段，H²R会分别检索高层与低层记忆，让基于LLM的智能体能够高效获取并运用新任务的相关知识。两项基准测试的实验结果显示，H²R可提升泛化能力与决策性能，表现优于Expel等现有基线方法。

> Large language model (LLM)-based agents have shown strong potential in multi-task scenarios, owing to their ability to transfer knowledge across diverse tasks. However, existing approaches often treat prior experiences and knowledge as monolithic units, leading to inefficient and coarse-grained knowledge transfer. In this work, we propose a novel hierarchical memory architecture that enables fine-grained knowledge transfer by decoupling high-level planning memory from low-level execution memory. To construct and refine these hierarchical memories, we introduce Hierarchical Hindsight Reflection (H$^2$R), a mechanism that distills reusable and hierarchical knowledge from past agent-environment interactions. At test time, H$^2$R performs retrievals of high-level and low-level memories separately, allowing LLM-based agents to efficiently access and utilize task-relevant knowledge for new tasks.Experimental results across two benchmarks demonstrate that H$^2$R can improve generalization and decision-making performance, outperforming prior baselines such as Expel.

[Arxiv](https://arxiv.org/abs/2509.12810)