# EQ谈判者：用于信贷对话的情感推理大型语言模型代理

发布时间：2025年03月26日

`Agent` `金融谈判`

> EQ-Negotiator: An Emotion-Reasoning LLM Agent in Credit Dialogues

# 摘要

> 基于大型语言模型 (LLM) 的聊天机器人在信贷对话中的应用已见成效，但它们在动态情感表达方面的能力仍有待提升。当前的智能体主要依赖被动共情，而非情感推理。例如，面对客户持续的消极情绪时，智能体应通过表达适度的愤怒来引导对话走向解决，从而抑制不利行为。这种情境感知的情感调节对于模仿人类谈判者细致入微的决策至关重要。本文提出了一种结合预训练语言模型 (PLMs) 的情感感知与基于博弈论和隐马尔可夫模型的情感推理的 EQ-negotiator。它不仅关注客户当前的情绪，还考虑其历史情绪，以便更好地管理和应对互动中的负面情绪。通过在公开的情感数据集上对预训练语言模型 (PLMs) 进行微调，并在信贷对话数据集上进行验证，我们的方法使基于 LLM 的智能体能够有效捕捉客户情绪的变化，并根据我们的情感决策策略在现实的金融谈判中动态调整回应语气。这种 EQ-negotiator 还能帮助信贷机构培养积极的客户关系，从而提升信贷服务的满意度。

> While large language model (LLM)-based chatbots have been applied for effective engagement in credit dialogues, their capacity for dynamic emotional expression remains limited. Current agents primarily rely on passive empathy rather than affective reasoning. For instance, when faced with persistent client negativity, the agent should employ strategic emotional adaptation by expressing measured anger to discourage counterproductive behavior and guide the conversation toward resolution. This context-aware emotional modulation is essential for imitating the nuanced decision-making of human negotiators. This paper introduces an EQ-negotiator that combines emotion sensing from pre-trained language models (PLMs) with emotional reasoning based on Game Theory and Hidden Markov Models. It takes into account both the current and historical emotions of the client to better manage and address negative emotions during interactions. By fine-tuning pre-trained language models (PLMs) on public emotion datasets and validating them on the credit dialogue datasets, our approach enables LLM-based agents to effectively capture shifts in client emotions and dynamically adjust their response tone based on our emotion decision policies in real-world financial negotiations. This EQ-negotiator can also help credit agencies foster positive client relationships, enhancing satisfaction in credit services.

[Arxiv](https://arxiv.org/abs/2503.21080)