# DataSentinel: 一种基于博弈论的提示注入攻击检测方法

发布时间：2025年04月15日

`LLM应用

理由：这篇论文讨论了大型语言模型在实际应用中的安全问题，特别是提示注入攻击，并提出了一种基于博弈论的检测方法。它关注的是LLM在实际应用中的安全防护，属于应用层面的研究。` `网络安全` `模型安全`

> DataSentinel: A Game-Theoretic Detection of Prompt Injection Attacks

# 摘要

> 集成大型语言模型 (LLM) 的应用程序和智能体易受提示注入攻击。攻击者通过在输入中注入特定提示，诱导模型生成期望输出。现有检测方法对最新攻击的防护效果有限，更不用说自适应攻击了。本研究提出 DataSentinel，一种基于博弈论的检测方法。DataSentinel 通过微调 LLM 来检测被注入提示污染的输入，这些提示经过策略性调整以规避检测。我们将此问题建模为极小化极大优化问题，目标是通过微调 LLM 来检测强大的自适应攻击。我们提出了一种基于梯度的方法，通过交替求解内部最大值和外部最小值问题来解决该优化问题。在多个基准数据集和 LLM 上的评估结果表明，DataSentinel 能够有效检测现有和自适应的提示注入攻击。

> LLM-integrated applications and agents are vulnerable to prompt injection attacks, where an attacker injects prompts into their inputs to induce attacker-desired outputs. A detection method aims to determine whether a given input is contaminated by an injected prompt. However, existing detection methods have limited effectiveness against state-of-the-art attacks, let alone adaptive ones. In this work, we propose DataSentinel, a game-theoretic method to detect prompt injection attacks. Specifically, DataSentinel fine-tunes an LLM to detect inputs contaminated with injected prompts that are strategically adapted to evade detection. We formulate this as a minimax optimization problem, with the objective of fine-tuning the LLM to detect strong adaptive attacks. Furthermore, we propose a gradient-based method to solve the minimax optimization problem by alternating between the inner max and outer min problems. Our evaluation results on multiple benchmark datasets and LLMs show that DataSentinel effectively detects both existing and adaptive prompt injection attacks.

[Arxiv](https://arxiv.org/abs/2504.11358)