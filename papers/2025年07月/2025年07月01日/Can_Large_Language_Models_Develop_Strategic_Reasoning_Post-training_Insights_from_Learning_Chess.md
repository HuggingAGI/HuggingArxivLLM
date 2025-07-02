# 大型语言模型能否发展出战略推理能力？从学习国际象棋的训练后见解

发布时间：2025年07月01日

`LLM应用`

> Can Large Language Models Develop Strategic Reasoning? Post-training Insights from Learning Chess

# 摘要

> 虽然强化学习（RL）在大型语言模型（LLMs）的数学推理方面展现出潜力，但利用RL实现LLMs的战略推理能力仍鲜有探索。我们研究了LLMs是否能通过强化学习在国际象棋中发展出战略推理能力。为此，我们采用了一个预训练的国际象棋动作-值网络，为LLMs输出的走子质量提供密集奖励，这可以视为一种知识蒸馏。实验结果表明，基于蒸馏的密集奖励通常优于稀疏二元奖励。然而，令人惊讶的是，所有模型的表现远低于专家水平。我们对国际象棋推理训练进行了SFT和RL的消融实验，发现这一限制源于预训练模型对国际象棋内部理解的不足——而仅靠强化学习可能无法完全克服这一缺陷。

> While reinforcement learning (RL) for large language models (LLMs) has shown promise in mathematical reasoning, strategic reasoning for LLMs using RL remains largely unexplored. We investigate whether LLMs can develop strategic reasoning capabilities through RL in chess. To this end, we leverage a chess-pretrained action-value network to provide dense reward on the LLM's output move quality, which can be seen as a form of knowledge distillation. Our experiments show that our distillation-based dense rewards often outperform sparse binary rewards. However, surprisingly, all models plateau far below expert levels. We provide SFT and RL ablations on chess reasoning training and find evidence that this limitation stems from a deficit in the pretrained models' internal understanding of chess--a deficit which RL alone may not be able to fully overcome.

[Arxiv](https://arxiv.org/abs/2507.00726)