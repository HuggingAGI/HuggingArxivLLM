# MARS：迈向更高效的多智能体协作，助力LLM推理

发布时间：2025年09月24日

`Agent` `基础理论`

> MARS: toward more efficient multi-agent collaboration for LLM reasoning

# 摘要

> 大型语言模型（LLMs）在自然语言理解领域成绩斐然，然而作为单一智能体时，其推理能力仍有局限。多智能体辩论（MAD）应运而生，通过让多个模型以圆桌辩论形式协作推理来弥补这一短板。尽管MAD效果显著，但因其涉及智能体数量众多且通信频繁，导致计算开销巨大。本文提出MARS（多智能体评审系统）——一个受评审流程启发的基于角色的协作框架。在MARS中，作者智能体生成初步方案，评审智能体独立给出决策与意见，元评审者则整合反馈，做出最终决策并指导后续修订。该设计在提升推理质量的同时，避免了评审者间的高昂交互成本，进而有效控制了token消耗与推理时间。我们在多个基准测试中，将MARS与MAD及其他最先进的推理策略展开对比。在不同LLM上进行的大量实验显示，MARS在准确率上与MAD持平，同时将token用量和推理时间均降低约50%。代码已开源，地址为https://github.com/xwang97/MARS。

> Large language models (LLMs) have achieved impressive results in natural language understanding, yet their reasoning capabilities remain limited when operating as single agents. Multi-Agent Debate (MAD) has been proposed to address this limitation by enabling collaborative reasoning among multiple models in a round-table debate manner. While effective, MAD introduces substantial computational overhead due to the number of agents involved and the frequent communication required. In this paper, we propose MARS (Multi-Agent Review System), a role-based collaboration framework inspired by the review process. In MARS, an author agent generates an initial solution, reviewer agents provide decisions and comments independently, and a meta-reviewer integrates the feedback to make the final decision and guide further revision. This design enhances reasoning quality while avoiding costly reviewer-to-reviewer interactions, thereby controlling token consumption and inference time. We compared MARS with both MAD and other state-of-the-art reasoning strategies across multiple benchmarks. Extensive experiments with different LLMs show that MARS matches the accuracy of MAD while reducing both token usage and inference time by approximately 50\%. Code is available at https://github.com/xwang97/MARS.

[Arxiv](https://arxiv.org/abs/2509.20502)