# PsyPlay: 个性驱动的角色扮演对话系统

发布时间：2025年02月06日

`Agent

理由：这篇论文主要讨论了如何通过LLM（大型语言模型）来创建具有个性化特征的角色扮演对话代理（RPCAs），并提出了一个名为PsyPlay的框架来促进多个LLM代理之间的个性表达。研究重点在于如何让LLM代理在对话中精准展现其指定的个性特征，这与Agent（智能代理）领域的研究密切相关，特别是关于如何设计和实现具有特定行为和个性特征的智能代理。因此，这篇论文应被分类为Agent。` `对话系统` `心理学`

> PsyPlay: Personality-Infused Role-Playing Conversational Agents

# 摘要

> 当前关于LLM角色扮演对话代理（RPCAs）的研究主要聚焦于模仿特定说话风格和利用角色背景，而忽略了对深层个性特征的刻画。本研究提出了一种基于个性的角色扮演方法，鼓励LLM代理在对话中精准展现其指定的个性特征。我们进一步推出了PsyPlay框架，旨在促进多个LLM代理之间丰富个性的表达。具体而言，PsyPlay让代理能够扮演具有鲜明个性特征的角色，围绕特定主题展开讨论，并在互动中始终如一地展现其个性。通过对生成对话数据的验证，PsyPlay在GPT-3.5上实现了80.31%的个性描绘成功率。值得注意的是，与负面个性角色相比，与正面价值观对齐的LLM在描绘正面个性角色时表现更佳。此外，我们还构建了PsyPlay-Bench对话语料库，包含4745个使用PsyPlay正确描绘的对话实例，旨在推动个性化角色扮演和对话个性检测的深入研究。

> The current research on Role-Playing Conversational Agents (RPCAs) with Large Language Models (LLMs) primarily focuses on imitating specific speaking styles and utilizing character backgrounds, neglecting the depiction of deeper personality traits.~In this study, we introduce personality-infused role-playing for LLM agents, which encourages agents to accurately portray their designated personality traits during dialogues. We then propose PsyPlay, a dialogue generation framework that facilitates the expression of rich personalities among multiple LLM agents. Specifically, PsyPlay enables agents to assume roles with distinct personality traits and engage in discussions centered around specific topics, consistently exhibiting their designated personality traits throughout the interactions. Validation on generated dialogue data demonstrates that PsyPlay can accurately portray the intended personality traits, achieving an overall success rate of 80.31% on GPT-3.5. Notably, we observe that LLMs aligned with positive values are more successful in portraying positive personality roles compared to negative ones. Moreover, we construct a dialogue corpus for personality-infused role-playing, called PsyPlay-Bench. The corpus, which consists of 4745 instances of correctly portrayed dialogues using PsyPlay, aims to further facilitate research in personalized role-playing and dialogue personality detection.

[Arxiv](https://arxiv.org/abs/2502.03821)