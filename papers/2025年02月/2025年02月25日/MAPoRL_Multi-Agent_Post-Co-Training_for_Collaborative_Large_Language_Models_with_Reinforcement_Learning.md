# MAPoRL: 一种用于强化学习驱动的协作大型语言模型的多智能体后协同训练方法

发布时间：2025年02月25日

`Agent` `多智能体协作`

> MAPoRL: Multi-Agent Post-Co-Training for Collaborative Large Language Models with Reinforcement Learning

# 摘要

> 多大型语言模型（LLMs）协作构建工作流程潜力巨大，但现有研究多依赖LLMs固有协作能力，效果有限。本文提出基于强化学习的MAPoRL范式，通过协作训练激发多智能体LLMs潜力。MAPoRL中，多个LLMs独立生成响应并展开多轮讨论，最终由验证器评分评估答案与讨论，激励改进。评分作为奖励，通过多智能体强化学习优化。实验表明，MAPoRL显著提升协作性能，实现跨领域泛化。

> Leveraging multiple large language models (LLMs) to build collaborative multi-agentic workflows has demonstrated significant potential. However, most previous studies focus on prompting the out-of-the-box LLMs, relying on their innate capability for collaboration, which may not improve LLMs' performance as shown recently. In this paper, we introduce a new post-training paradigm MAPoRL (Multi-Agent Post-co-training for collaborative LLMs with Reinforcement Learning), to explicitly elicit the collaborative behaviors and further unleash the power of multi-agentic LLM frameworks. In MAPoRL, multiple LLMs first generate their own responses independently and engage in a multi-turn discussion to collaboratively improve the final answer. In the end, a MAPoRL verifier evaluates both the answer and the discussion, by assigning a score that verifies the correctness of the answer, while adding incentives to encourage corrective and persuasive discussions. The score serves as the co-training reward, and is then maximized through multi-agent RL. Unlike existing LLM post-training paradigms, MAPoRL advocates the co-training of multiple LLMs together using RL for better generalization. Accompanied by analytical insights, our experiments demonstrate that training individual LLMs alone is insufficient to induce effective collaboration. In contrast, multi-agent co-training can boost the collaboration performance across benchmarks, with generalization to unseen domains.

[Arxiv](https://arxiv.org/abs/2502.18439)