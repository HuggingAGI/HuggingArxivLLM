# CTRLS：基于潜在状态转换的链式推理方法

发布时间：2025年07月10日

`LLM理论`

> CTRLS: Chain-of-Thought Reasoning via Latent State-Transition

# 摘要

> 思维链推理 (CoT) 赋予大型语言模型 (LLMs) 将复杂问题分解为可解释中间步骤的能力，显著提升了模型在推理任务中的透明度和性能表现。然而，传统 CoT 方法依赖启发式采样，缺乏对推理过程的结构化建模，限制了其系统性探索多样化有效推理路径的能力。本研究提出 CTRLS 框架，将 CoT 推理建模为带有潜在状态转移的马尔可夫决策过程 (MDP)，通过分布强化学习实现原理化和基于状态的探索。通过将推理动作建模为潜在空间中的显式概率分布，我们的方法显式建模了知识不确定性，促进对推理空间的健壮探索。框架中采用结合 epsilon-greedy 探索和基于熵的正则化的在策略强化学习策略，迭代精炼潜在状态转移，无需额外微调底层 LLM。理论分析提供证据下界 (ELBO)，为潜在推理动力学建模提供理论依据。实验结果表明，我们的方法在基准推理任务中显著提升了推理准确性和多样性，同时优化了探索效率。

> Chain-of-thought (CoT) reasoning enables large language models (LLMs) to break down complex problems into interpretable intermediate steps, significantly enhancing model transparency and performance in reasoning tasks. However, conventional CoT methods rely on heuristic sampling without structured modeling of reasoning transitions, constraining their ability to systematically explore and discover diverse and effective reasoning trajectories. In this work, we introduce CTRLS, a framework that formulates CoT reasoning as a Markov decision process (MDP) with latent state transitions, enabling principled and state-aware exploration via distributional reinforcement learning. By modelling reasoning actions as explicit probability distributions in latent space, our approach explicitly models epistemic uncertainty, facilitating robust exploration of the reasoning space. As part of our framework, we introduce an on-policy reinforcement learning strategy incorporating epsilon-greedy exploration and entropy-based regularization to iteratively refine latent state transitions without requiring additional fine-tuning of the underlying LLM. Theoretical analyses provide evidence lower bounds (ELBO), theoretically grounding our transition-aware modeling of latent reasoning dynamics. Further experiments demonstrate improvements in reasoning accuracy, diversity, and exploration efficiency across benchmark reasoning tasks.

[Arxiv](https://arxiv.org/abs/2507.08182)