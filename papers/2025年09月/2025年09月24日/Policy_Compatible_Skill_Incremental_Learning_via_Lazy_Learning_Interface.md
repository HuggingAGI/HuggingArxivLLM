# 基于惰性学习接口的策略兼容技能增量学习

发布时间：2025年09月24日

`Agent` `工业与制造`

> Policy Compatible Skill Incremental Learning via Lazy Learning Interface

# 摘要

> 技能增量学习（SIL）指具身智能体通过与环境交互积累经验或整合额外数据，随时间逐步扩展并优化自身技能集的过程。SIL能够帮助智能体高效习得基于可重用技能的层级策略，从而服务于下游任务。但随着技能库的不断更新，可能会破坏与现有技能策略的兼容性，进而限制这些策略的复用性和泛化效果。为此，本研究提出一种新型框架SIL-C，它能确保技能与策略的兼容性，让增量学习中技能的提升直接增强下游策略性能，且无需对策略进行重新训练或结构调整。SIL-C采用基于双边懒惰学习的映射技术，动态匹配策略所涉及的子任务空间与解码为智能体行为的技能空间。这样一来，策略分解复杂任务后得到的每个子任务，都能根据轨迹分布的相似性选择恰当技能来执行。我们在多种SIL场景下对SIL-C进行评估，结果表明它在整个学习过程中既能维持演变技能与下游策略的兼容性，又能保证学习效率。

> Skill Incremental Learning (SIL) is the process by which an embodied agent expands and refines its skill set over time by leveraging experience gained through interaction with its environment or by the integration of additional data. SIL facilitates efficient acquisition of hierarchical policies grounded in reusable skills for downstream tasks. However, as the skill repertoire evolves, it can disrupt compatibility with existing skill-based policies, limiting their reusability and generalization. In this work, we propose SIL-C, a novel framework that ensures skill-policy compatibility, allowing improvements in incrementally learned skills to enhance the performance of downstream policies without requiring policy re-training or structural adaptation. SIL-C employs a bilateral lazy learning-based mapping technique to dynamically align the subtask space referenced by policies with the skill space decoded into agent behaviors. This enables each subtask, derived from the policy's decomposition of a complex task, to be executed by selecting an appropriate skill based on trajectory distribution similarity. We evaluate SIL-C across diverse SIL scenarios and demonstrate that it maintains compatibility between evolving skills and downstream policies while ensuring efficiency throughout the learning process.

[Arxiv](https://arxiv.org/abs/2509.20612)