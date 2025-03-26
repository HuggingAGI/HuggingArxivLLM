# 当辩论失效：大型语言模型中的偏见强化机制

发布时间：2025年03月20日

`LLM应用` `人工智能` `战略决策`

> When Debate Fails: Bias Reinforcement in Large Language Models

# 摘要

> 大型语言模型（LLMs）利用无需训练的提示工程和上下文学习方法解决复杂问题，但确保推理的正确性仍具挑战。尽管自洽性与自完善等自我修正方法旨在提升可靠性，但因缺乏有效反馈机制，它们往往强化偏见。多智能体辩论（MAD）作为替代方案逐渐兴起，但存在两大局限：偏见强化（辩论放大而非纠正模型偏见）和观点单一（所有智能体共享同一模型与推理模式，限制了真正辩论效果）。为系统评估这些问题，我们推出了《MetaNIM Arena》，这是一个评估LLMs在对抗性战略决策中表现的基准，其中动态交互影响最优决策。为克服MAD的局限，我们提出《DReaMAD》（通过精炼提示实现多智能体辩论中的多样化推理），一个创新框架，可（1）优化LLM的战略先验知识以提升推理质量，以及（2）通过系统性修改提示，促进单一模型内的观点多样性，从而减少偏见。实证结果显示，《DReaMAD》在多个战略任务中显著提升了决策准确性、推理多样性和偏见缓解效果，确立了其作为基于LLM决策更有效方法的地位。


> Large Language Models $($LLMs$)$ solve complex problems using training-free methods like prompt engineering and in-context learning, yet ensuring reasoning correctness remains challenging. While self-correction methods such as self-consistency and self-refinement aim to improve reliability, they often reinforce biases due to the lack of effective feedback mechanisms. Multi-Agent Debate $($MAD$)$ has emerged as an alternative, but we identify two key limitations: bias reinforcement, where debate amplifies model biases instead of correcting them, and lack of perspective diversity, as all agents share the same model and reasoning patterns, limiting true debate effectiveness. To systematically evaluate these issues, we introduce $\textit{MetaNIM Arena}$, a benchmark designed to assess LLMs in adversarial strategic decision-making, where dynamic interactions influence optimal decisions. To overcome MAD's limitations, we propose $\textbf{DReaMAD}$ $($$\textbf{D}$iverse $\textbf{Rea}$soning via $\textbf{M}$ulti-$\textbf{A}$gent $\textbf{D}$ebate with Refined Prompt$)$, a novel framework that $(1)$ refines LLM's strategic prior knowledge to improve reasoning quality and $(2)$ promotes diverse viewpoints within a single model by systematically modifying prompts, reducing bias. Empirical results show that $\textbf{DReaMAD}$ significantly improves decision accuracy, reasoning diversity, and bias mitigation across multiple strategic tasks, establishing it as a more effective approach for LLM-based decision-making.

[Arxiv](https://arxiv.org/abs/2503.16814)