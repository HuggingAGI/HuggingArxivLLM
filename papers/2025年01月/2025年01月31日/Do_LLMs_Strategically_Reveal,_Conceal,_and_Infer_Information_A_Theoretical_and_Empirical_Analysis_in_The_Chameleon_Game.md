# LLMs 是否会策略性地揭示、隐藏和推断信息？——基于变色龙游戏的理论与实证分析

发布时间：2025年01月31日

`Agent

理由：这篇论文主要探讨了基于大型语言模型（LLM）的代理在非合作环境中的信息控制和决策能力，特别是通过参与隐藏身份游戏《变色龙》来评估代理的表现。论文的核心关注点是代理在战略互动中的行为和信息控制能力，这属于“Agent”领域的研究。虽然论文涉及LLM的应用，但其重点在于代理的行为和策略分析，而不是LLM的理论或应用本身。因此，将其分类为“Agent”更为合适。` `人工智能`

> Do LLMs Strategically Reveal, Conceal, and Infer Information? A Theoretical and Empirical Analysis in The Chameleon Game

# 摘要

> # 摘要
基于大型语言模型（LLM-based）的代理在非合作环境中已广泛应用。在此类环境中，代理需向对手隐藏信息、向合作者透露信息，并推断其他代理的特征。为探究LLMs是否具备这些信息控制与决策能力，我们让LLM代理参与基于语言的隐藏身份游戏《变色龙》。游戏中，一群互不相识的非变色龙代理需在不泄露秘密的前提下识别变色龙代理。游戏要求无论作为变色龙还是非变色龙，代理都需具备上述信息控制能力。实证结果显示，非变色龙LLM代理虽能识别变色龙，却未能向变色龙隐藏秘密，且其获胜概率远低于简单策略。为解释这一现象，我们对从隐藏到透露的一系列策略进行了理论分析，并给出了非变色龙获胜概率的界限。基于不同策略的实证与理论分析，我们推断LLM非变色龙代理向身份未知的代理透露了过多信息。这一结果揭示了当代LLMs（如GPT-4、GPT-4o、Gemini 1.5和Claude 3.5 Sonnet）在战略互动中的不足。

> Large language model-based (LLM-based) agents have become common in settings that include non-cooperative parties. In such settings, agents' decision-making needs to conceal information from their adversaries, reveal information to their cooperators, and infer information to identify the other agents' characteristics. To investigate whether LLMs have these information control and decision-making capabilities, we make LLM agents play the language-based hidden-identity game, The Chameleon. In the game, a group of non-chameleon agents who do not know each other aim to identify the chameleon agent without revealing a secret. The game requires the aforementioned information control capabilities both as a chameleon and a non-chameleon. The empirical results show that while non-chameleon LLM agents identify the chameleon, they fail to conceal the secret from the chameleon, and their winning probability is far from the levels of even trivial strategies. To formally explain this behavior, we give a theoretical analysis for a spectrum of strategies, from concealing to revealing, and provide bounds on the non-chameleons' winning probability. Based on the empirical results and theoretical analysis of different strategies, we deduce that LLM-based non-chameleon agents reveal excessive information to agents of unknown identities. Our results point to a weakness of contemporary LLMs, including GPT-4, GPT-4o, Gemini 1.5, and Claude 3.5 Sonnet, in strategic interactions.

[Arxiv](https://arxiv.org/abs/2501.19398)