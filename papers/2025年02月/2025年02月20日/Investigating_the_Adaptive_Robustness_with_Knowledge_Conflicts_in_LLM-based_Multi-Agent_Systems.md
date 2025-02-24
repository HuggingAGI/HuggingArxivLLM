# 探究基于LLM的多智能体系统中知识冲突对自适应鲁棒性的影响

发布时间：2025年02月20日

`Agent` `多智能体系统`

> Investigating the Adaptive Robustness with Knowledge Conflicts in LLM-based Multi-Agent Systems

# 摘要

> 大型语言模型的最新进展使其从复杂的文本生成器升级为能够在多智能体系统中进行协作和工具使用的自主智能体。然而，这些基于LLMs的MAS在知识冲突下的稳健性仍不明朗。本文设计了四个全面指标来研究MAS在面对轻微或任务关键型知识冲突时的稳健性。我们首先分析了由异构智能体引入的轻微知识冲突，发现它们并不会损害系统稳健性，反而能提升协作决策。接着，我们通过合成知识冲突并将其嵌入其中一个智能体来研究任务关键型知识冲突。结果显示，这些冲突对MAS稳健性的影响微乎其微甚至完全没有影响。此外，我们发现MAS表现出一定的自我修复能力，通过减少对知识冲突的依赖并采用替代解决方案来维持稳定性。最后，我们在知识冲突数量、智能体数量和交互轮次上进行了消融研究，发现MAS的自我修复能力具有内在限制，且所有研究结果在各种因素下均保持一致。我们的代码已公开发布于https://github.com/wbw625/MultiAgentRobustness。

> Recent advances in Large Language Models (LLMs) have upgraded them from sophisticated text generators to autonomous agents capable of corporation and tool use in multi-agent systems (MASs). However, the robustness of these LLM-based MASs, especially under knowledge conflicts, remains unclear. In this paper, we design four comprehensive metrics to investigate the robustness of MASs when facing mild or task-critical knowledge conflicts. We first analyze mild knowledge conflicts introduced by heterogeneous agents and find that they do not harm system robustness but instead improve collaborative decision-making. Next, we investigate task-critical knowledge conflicts by synthesizing knowledge conflicts and embedding them into one of the agents. Our results show that these conflicts have surprisingly little to no impact on MAS robustness. Furthermore, we observe that MASs demonstrate certain self-repairing capabilities by reducing their reliance on knowledge conflicts and adopting alternative solution paths to maintain stability. Finally, we conduct ablation studies on the knowledge conflict number, agent number, and interaction rounds, finding that the self-repairing capability of MASs has intrinsic limits, and all findings hold consistently across various factors. Our code is publicly available at https://github.com/wbw625/MultiAgentRobustness.

[Arxiv](https://arxiv.org/abs/2502.15153)