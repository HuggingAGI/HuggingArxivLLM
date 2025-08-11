# 大型语言模型能否有效生成用于网络安全的博弈论场景？

发布时间：2025年08月04日

`LLM应用` `网络安全` `博弈论`

> Can LLMs effectively provide game-theoretic-based scenarios for cybersecurity?

# 摘要

> 博弈论一直是网络安全领域的重要工具，用于测试、预测和设计攻击者与防御者之间的战略互动。大型语言模型（LLMs）的最新发展为计算机系统的安全性提供了新的工具和挑战；在这项研究中，我们探讨了经典的博弈论框架是否能够有效捕捉由LLM驱动的参与者和 bots 的行为。通过一个可重复的博弈论LLM代理框架，我们研究了两个典型场景——一次性零和游戏和动态囚徒困境——并测试LLMs是否会收敛于预期的结果，或者由于嵌入的偏见而出现偏差。我们的实验涉及四个最先进的LLMs，并涵盖了五种自然语言：英语、法语、阿拉伯语、越南语和普通话，以评估语言敏感性。对于这两种游戏，我们观察到最终收益受到代理特性的影响，例如个性特征或对重复轮次的知识。此外，我们发现最终收益对语言选择的意外敏感性，这应该警告不要在网络安全应用中不加选择地使用LLMs，并呼吁深入研究，因为LLMs在不同国家部署时可能会表现出不同的行为。我们还采用定量指标来评估LLM代理的内部一致性和跨语言稳定性，以帮助选择最稳定的LLMs并优化模型，以确保安全应用。

> Game theory has long served as a foundational tool in cybersecurity to test, predict, and design strategic interactions between attackers and defenders. The recent advent of Large Language Models (LLMs) offers new tools and challenges for the security of computer systems; In this work, we investigate whether classical game-theoretic frameworks can effectively capture the behaviours of LLM-driven actors and bots. Using a reproducible framework for game-theoretic LLM agents, we investigate two canonical scenarios -- the one-shot zero-sum game and the dynamic Prisoner's Dilemma -- and we test whether LLMs converge to expected outcomes or exhibit deviations due to embedded biases. Our experiments involve four state-of-the-art LLMs and span five natural languages, English, French, Arabic, Vietnamese, and Mandarin Chinese, to assess linguistic sensitivity. For both games, we observe that the final payoffs are influenced by agents characteristics such as personality traits or knowledge of repeated rounds. Moreover, we uncover an unexpected sensitivity of the final payoffs to the choice of languages, which should warn against indiscriminate application of LLMs in cybersecurity applications and call for in-depth studies, as LLMs may behave differently when deployed in different countries. We also employ quantitative metrics to evaluate the internal consistency and cross-language stability of LLM agents, to help guide the selection of the most stable LLMs and optimising models for secure applications.

[Arxiv](https://arxiv.org/abs/2508.05670)