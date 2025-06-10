# LUCIFER：语言理解与上下文增强的探索与行为优化框架

发布时间：2025年06月09日

`Agent` `自主系统`

> LUCIFER: Language Understanding and Context-Infused Framework for Exploration and Behavior Refinement

# 摘要

> 在动态环境中，预存环境知识的快速过时导致智能体内部模型与现实环境之间产生差距，这种差异从根本上限制了自主决策的有效性。为了弥合这一差距，人类领域利益相关者的情境偏见变得不可或缺，他们通过直接观察积累见解。然而，将这些细致且情境丰富的输入转化为自主系统的可执行情报仍然是一个开放的挑战。为此，我们提出了LUCIFER框架，它将分层决策架构与强化学习（RL）和大型语言模型（LLMs）整合到一个统一系统中。该架构模拟了人类分解复杂任务的方式，使高层规划者能够协调专注于不同目标和时间相关动作的专门子智能体。与传统应用中LLMs仅限于单一角色不同，LUCIFER将它们整合到两个协同角色中：作为情境提取器，将言语利益相关者输入结构化为领域感知表示，通过注意力空间机制影响决策过程；以及作为零样本探索促进者，在探索过程中引导智能体的动作选择过程。我们在两个角色中对各种LLMs进行了基准测试，并证明LUCIFER提高了探索效率和决策质量，优于平坦的目标条件策略。我们的研究结果表明，基于情境的决策具有潜力，自主系统可以通过利用人类情境知识实现运营成功。

> In dynamic environments, the rapid obsolescence of pre-existing environmental knowledge creates a gap between an agent's internal model and the evolving reality of its operational context. This disparity between prior and updated environmental valuations fundamentally limits the effectiveness of autonomous decision-making. To bridge this gap, the contextual bias of human domain stakeholders, who naturally accumulate insights through direct, real-time observation, becomes indispensable. However, translating their nuanced, and context-rich input into actionable intelligence for autonomous systems remains an open challenge. To address this, we propose LUCIFER (Language Understanding and Context-Infused Framework for Exploration and Behavior Refinement), a domain-agnostic framework that integrates a hierarchical decision-making architecture with reinforcement learning (RL) and large language models (LLMs) into a unified system. This architecture mirrors how humans decompose complex tasks, enabling a high-level planner to coordinate specialised sub-agents, each focused on distinct objectives and temporally interdependent actions. Unlike traditional applications where LLMs are limited to single role, LUCIFER integrates them in two synergistic roles: as context extractors, structuring verbal stakeholder input into domain-aware representations that influence decision-making through an attention space mechanism aligning LLM-derived insights with the agent's learning process, and as zero-shot exploration facilitators guiding the agent's action selection process during exploration. We benchmark various LLMs in both roles and demonstrate that LUCIFER improves exploration efficiency and decision quality, outperforming flat, goal-conditioned policies. Our findings show the potential of context-driven decision-making, where autonomous systems leverage human contextual knowledge for operational success.

[Arxiv](https://arxiv.org/abs/2506.07915)