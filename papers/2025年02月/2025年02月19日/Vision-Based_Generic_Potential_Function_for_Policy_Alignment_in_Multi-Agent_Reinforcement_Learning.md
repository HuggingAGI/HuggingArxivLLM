# 基于视觉的通用势函数在多智能体强化学习中的策略对齐研究

发布时间：2025年02月19日

`Agent` `人工智能` `机器人`

> Vision-Based Generic Potential Function for Policy Alignment in Multi-Agent Reinforcement Learning

# 摘要

> 多智能体强化学习中，如何让策略与人类常识对齐是一个难题，这主要是因为将常识转化为奖励信号的复杂性，尤其在复杂的长期任务中。近期研究显示，通过奖励塑造（如基于势能的奖励）可以有效提升策略与人类常识的对齐效果。然而，现有方法主要依赖专家手动设计基于规则的奖励，这种方式不仅耗时耗力，还难以深入理解常识的语义内涵。为解决这一问题，我们提出了一种层次化的视觉奖励塑造方法。在底层，我们采用视觉语言模型（VLM）作为通用的势能函数，通过其内在的语义理解能力引导策略与人类常识对齐。为了帮助策略更好地适应长期任务中的不确定性和动态变化，我们在顶层设计了一个基于视觉大型语言模型（vLLM）的自适应技能选择模块。该模块通过分析指令、视频回放和训练记录，能够从预设的势能函数池中动态选择最适合当前任务的函数。此外，我们的方法在理论上被证明能够保持最优策略的特性。在Google Research Football环境中进行的大量实验表明，我们的方法不仅显著提高了胜率，还实现了策略与人类常识的有效对齐。

> Guiding the policy of multi-agent reinforcement learning to align with human common sense is a difficult problem, largely due to the complexity of modeling common sense as a reward, especially in complex and long-horizon multi-agent tasks. Recent works have shown the effectiveness of reward shaping, such as potential-based rewards, to enhance policy alignment. The existing works, however, primarily rely on experts to design rule-based rewards, which are often labor-intensive and lack a high-level semantic understanding of common sense. To solve this problem, we propose a hierarchical vision-based reward shaping method. At the bottom layer, a visual-language model (VLM) serves as a generic potential function, guiding the policy to align with human common sense through its intrinsic semantic understanding. To help the policy adapts to uncertainty and changes in long-horizon tasks, the top layer features an adaptive skill selection module based on a visual large language model (vLLM). The module uses instructions, video replays, and training records to dynamically select suitable potential function from a pre-designed pool. Besides, our method is theoretically proven to preserve the optimal policy. Extensive experiments conducted in the Google Research Football environment demonstrate that our method not only achieves a higher win rate but also effectively aligns the policy with human common sense.

[Arxiv](https://arxiv.org/abs/2502.13430)