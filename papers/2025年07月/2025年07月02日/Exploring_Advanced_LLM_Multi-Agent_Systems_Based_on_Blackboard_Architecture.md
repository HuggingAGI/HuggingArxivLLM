# 深入探索采用黑板架构的LLM多智能体系统

发布时间：2025年07月02日

`Agent` `人工智能`

> Exploring Advanced LLM Multi-Agent Systems Based on Blackboard Architecture

# 摘要

> 本文提出将黑板架构融入大型语言模型多智能体系统（MASs），实现以下功能：(1) 不同角色的智能体在整个问题解决过程中共享全部信息与消息，(2) 根据黑板当前内容选择行动智能体，(3) 重复选择与执行，直至黑板达成共识。我们实现了这一方案，并在常识知识、推理和数学数据集上进行实验。结果显示，我们的系统不仅在性能上达到最优，且在token使用上更为高效。这一方案有望在缺乏明确结构或工作流程的情况下，实现复杂动态的问题解决。

> In this paper, we propose to incorporate the blackboard architecture into LLM multi-agent systems (MASs) so that (1) agents with various roles can share all the information and others' messages during the whole problem-solving process, (2) agents that will take actions are selected based on the current content of the blackboard, and (3) the selection and execution round is repeated until a consensus is reached on the blackboard. We develop the first implementation of this proposal and conduct experiments on commonsense knowledge, reasoning and mathematical datasets. The results show that our system can be competitive with the SOTA static and dynamic MASs by achieving the best average performance, and at the same time manage to spend less tokens. Our proposal has the potential to enable complex and dynamic problem-solving where well-defined structures or workflows are unavailable.

[Arxiv](https://arxiv.org/abs/2507.01701)