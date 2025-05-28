# 意图 concealment：基于博弈论的分析

发布时间：2025年05月27日

`LLM应用` `网络安全`

> Concealment of Intent: A Game-Theoretic Analysis

# 摘要

> 大型语言模型（LLMs）能力的提升带来了安全部署的担忧，尽管引入了对齐机制防止滥用，但精心设计的对抗性提示仍可能突破防线。本研究提出了一种可扩展的攻击策略：通过技能组合隐藏恶意意图的对抗性提示。我们构建了一个博弈论框架，用于分析此类攻击与基于提示和响应过滤的防御系统之间的互动。研究发现，攻击方在结构上具有显著优势，且攻击与防御的互动存在明确的均衡点。针对这一威胁，我们设计并验证了一种专门针对意图隐藏攻击的防御机制。实证结果显示，在多种恶意行为测试中，该攻击方法在多个真实世界LLMs上均展现出超越现有技术的优势。

> As large language models (LLMs) grow more capable, concerns about their safe deployment have also grown. Although alignment mechanisms have been introduced to deter misuse, they remain vulnerable to carefully designed adversarial prompts. In this work, we present a scalable attack strategy: intent-hiding adversarial prompting, which conceals malicious intent through the composition of skills. We develop a game-theoretic framework to model the interaction between such attacks and defense systems that apply both prompt and response filtering. Our analysis identifies equilibrium points and reveals structural advantages for the attacker. To counter these threats, we propose and analyze a defense mechanism tailored to intent-hiding attacks. Empirically, we validate the attack's effectiveness on multiple real-world LLMs across a range of malicious behaviors, demonstrating clear advantages over existing adversarial prompting techniques.

[Arxiv](https://arxiv.org/abs/2505.20841)