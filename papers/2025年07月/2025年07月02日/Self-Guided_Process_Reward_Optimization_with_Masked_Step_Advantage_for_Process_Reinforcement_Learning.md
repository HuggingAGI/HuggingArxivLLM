# 自我引导过程奖励优化，利用遮蔽步优势，应用于过程强化学习

发布时间：2025年07月02日

`LLM理论` `工业应用`

> Self-Guided Process Reward Optimization with Masked Step Advantage for Process Reinforcement Learning

# 摘要

> 流程强化学习（PRL）在提升大型语言模型（LLMs）的推理能力方面展现出巨大潜力。然而，引入额外的流程奖励模型会带来巨大的计算开销，而且在流程级别的优势估计方面缺乏统一的理论框架。为了解决这些问题，我们提出了**自引导流程奖励优化（SPRO）**这一创新框架，通过两大关键创新实现流程感知的强化学习：(1) 首先，我们从理论上证明，流程奖励可以内在地从策略模型本身中推导出来；(2) 我们引入了明确的累积流程奖励和**遮蔽步优势（MSA）**，这有助于在共享提示采样组内进行严格的分步动作优势估计。实验结果表明，与传统的GRPO相比，SPRO的训练效率提升了3.4倍，测试准确率提高了17.5%。此外，SPRO在整个训练过程中保持了稳定且较高的策略熵，同时将平均响应长度减少了约三分之一，这表明它在探索和防止奖励欺骗方面表现优异。值得注意的是，与传统的监督式强化学习方法（如GRPO）相比，SPRO不会带来额外的计算开销，这对工业应用非常有利。

> Process Reinforcement Learning~(PRL) has demonstrated considerable potential in enhancing the reasoning capabilities of Large Language Models~(LLMs). However, introducing additional process reward models incurs substantial computational overhead, and there is no unified theoretical framework for process-level advantage estimation. To bridge this gap, we propose \textbf{S}elf-Guided \textbf{P}rocess \textbf{R}eward \textbf{O}ptimization~(\textbf{SPRO}), a novel framework that enables process-aware RL through two key innovations: (1) we first theoretically demonstrate that process rewards can be derived intrinsically from the policy model itself, and (2) we introduce well-defined cumulative process rewards and \textbf{M}asked \textbf{S}tep \textbf{A}dvantage (\textbf{MSA}), which facilitates rigorous step-wise action advantage estimation within shared-prompt sampling groups. Our experimental results demonstrate that SPRO outperforms vaniila GRPO with 3.4x higher training efficiency and a 17.5\% test accuracy improvement. Furthermore, SPRO maintains a stable and elevated policy entropy throughout training while reducing the average response length by approximately $1/3$, evidencing sufficient exploration and prevention of reward hacking. Notably, SPRO incurs no additional computational overhead compared to outcome-supervised RL methods such as GRPO, which benefit industrial implementation.

[Arxiv](https://arxiv.org/abs/2507.01551)