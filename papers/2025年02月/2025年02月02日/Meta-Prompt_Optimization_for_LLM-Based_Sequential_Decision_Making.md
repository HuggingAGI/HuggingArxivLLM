# 基于LLM的序列决策元提示优化

发布时间：2025年02月02日

`Agent

理由：这篇论文主要讨论了如何通过自动优化元提示来提升基于大型语言模型（LLM）的代理在顺序决策任务中的性能。论文提出了EXPO算法及其扩展EXPO-ES，这些算法旨在优化代理的元提示，从而提高其在贝叶斯优化和多臂老虎机等任务中的表现。因此，这篇论文的核心内容与“Agent”相关，特别是如何通过优化提示来增强代理的决策能力。` `决策系统` `优化算法`

> Meta-Prompt Optimization for LLM-Based Sequential Decision Making

# 摘要

> 大型语言模型（LLMs）最近被用于解决贝叶斯优化和多臂老虎机（MAB）等顺序决策任务。这些研究通常通过为LLM提供固定的、手动设计的元提示来进行顺序动作选择。然而，许多研究表明，提示对LLM的性能有显著影响，因此需要一种自动优化基于LLM的代理的元提示的方法。由于基于LLM的顺序决策过程中奖励观察的非平稳性，元提示优化变得极具挑战性。为此，我们借鉴了对抗性老虎机算法，这些算法天生擅长处理非平稳的奖励观察。基于此，我们提出了EXPonential-weight algorithm for prompt Optimization（EXPO），用于自动优化基于LLM的代理的元提示中的任务描述和元指令。我们还扩展了EXPO，进一步优化元提示中的示例（即交互历史），从而引入了EXPO-ES算法。通过大量实验，我们证明了这些算法显著提升了基于LLM的顺序决策性能。

> Large language models (LLMs) have recently been employed as agents to solve sequential decision-making tasks such as Bayesian optimization and multi-armed bandits (MAB). These works usually adopt an LLM for sequential action selection by providing it with a fixed, manually designed meta-prompt. However, numerous previous works have found that the prompt has a significant impact on the performance of the LLM, which calls for a method to automatically optimize the meta-prompt for LLM-based agents. Unfortunately, the non-stationarity in the reward observations during LLM-based sequential decision-making makes meta-prompt optimization highly challenging. To address this challenge, we draw inspirations from adversarial bandit algorithms, which are inherently capable of handling non-stationary reward observations. Building on this foundation, we propose our EXPonential-weight algorithm for prompt Optimization} (EXPO) to automatically optimize the task description and meta-instruction in the meta-prompt for LLM-based agents. We also extend EXPO to additionally optimize the exemplars (i.e., history of interactions) in the meta-prompt to further enhance the performance, hence introducing our EXPO-ES algorithm. We use extensive experiments to show that our algorithms significantly improve the performance of LLM-based sequential decision-making.

[Arxiv](https://arxiv.org/abs/2502.00728)