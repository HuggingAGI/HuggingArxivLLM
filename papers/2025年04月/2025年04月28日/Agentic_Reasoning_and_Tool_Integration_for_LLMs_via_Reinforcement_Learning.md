# # 通过强化学习实现智能体推理与工具集成，提升大型语言模型的能力

发布时间：2025年04月28日

`Agent

理由：这篇论文提出了一种结合代理推理、强化学习和工具集成的框架ARTIST，旨在提升大型语言模型在动态推理和工具使用方面的能力。其核心贡献在于智能体设计和强化学习的应用，因此属于Agent类别。` `人工智能` `机器学习`

> Agentic Reasoning and Tool Integration for LLMs via Reinforcement Learning

# 摘要

> 大型语言模型 (LLMs) 在复杂推理任务中表现优异，但仍受制于静态知识和纯文本推理的局限。现实问题解决需要动态推理、自适应决策及与外部工具环境交互的能力。为此，我们推出 ARTIST（代理推理与工具集成的自我改进变换器），一个将代理推理、强化学习和工具集成于一体的框架。ARTIST 赋予模型在多轮推理中自主决策工具调用的能力，通过基于结果的强化学习，无需逐级监督即可掌握稳健的工具使用策略。实验表明，ARTIST 在数学推理和多轮函数调用任务中超越现有最优模型，提升幅度达 22%，尤其在高难度任务中表现突出。研究表明，代理强化学习训练显著提升了推理深度、工具使用效率和解决方案质量。ARTIST 树立了 LLMs 在稳健、可解释和通用问题解决领域的新标杆。

> Large language models (LLMs) have achieved remarkable progress in complex reasoning tasks, yet they remain fundamentally limited by their reliance on static internal knowledge and text-only reasoning. Real-world problem solving often demands dynamic, multi-step reasoning, adaptive decision making, and the ability to interact with external tools and environments. In this work, we introduce ARTIST (Agentic Reasoning and Tool Integration in Self-improving Transformers), a unified framework that tightly couples agentic reasoning, reinforcement learning, and tool integration for LLMs. ARTIST enables models to autonomously decide when, how, and which tools to invoke within multi-turn reasoning chains, leveraging outcome-based RL to learn robust strategies for tool use and environment interaction without requiring step-level supervision. Extensive experiments on mathematical reasoning and multi-turn function calling benchmarks show that ARTIST consistently outperforms state-of-the-art baselines, with up to 22% absolute improvement over base models and strong gains on the most challenging tasks. Detailed studies and metric analyses reveal that agentic RL training leads to deeper reasoning, more effective tool use, and higher-quality solutions. Our results establish agentic RL with tool integration as a powerful new frontier for robust, interpretable, and generalizable problem-solving in LLMs.

[Arxiv](https://arxiv.org/abs/2505.01441)