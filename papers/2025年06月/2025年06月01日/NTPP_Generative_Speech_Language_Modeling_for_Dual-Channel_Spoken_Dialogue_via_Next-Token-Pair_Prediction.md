# NTPP：基于预测下一个词对的双通道口语对话生成式语音语言建模

发布时间：2025年06月01日

`LLM应用` `语音对话` `对话系统`

> NTPP: Generative Speech Language Modeling for Dual-Channel Spoken Dialogue via Next-Token-Pair Prediction

# 摘要

> 受GPT-4o令人惊艳的能力启发，研究者们对赋予语音语言模型（SLMs）与人类进行自然流畅对话的能力产生了浓厚兴趣。近期进展已催生出数款在这一领域表现优异的SLMs。然而，现有方法尚未充分挖掘双通道语音数据的潜力，这种数据天然蕴含人类对话的结构与动态特征。本研究系统性地探索了双通道语音数据在现代大型语言模型中的应用，并首次提出了一种基于解码器-only架构的新型生成建模范式——Next-Token-Pair Prediction（NTPP），以实现说话人无关的双通道口语对话学习。我们在标准基准测试中评估了这一方法，实证结果表明，相较于现有技术，我们的NTPP方法在轮次预测、响应连贯性和自然度等关键对话能力方面均取得了显著提升。此外，NTPP的推理延迟大幅低于现有方案，凸显了其在实时应用中的实用效率优势。

> Inspired by the impressive capabilities of GPT-4o, there is growing interest in enabling speech language models (SLMs) to engage in natural, fluid spoken interactions with humans. Recent advancements have led to the development of several SLMs that demonstrate promising results in this area. However, current approaches have yet to fully exploit dual-channel speech data, which inherently captures the structure and dynamics of human conversation. In this work, we systematically explore the use of dual-channel speech data in the context of modern large language models, and introduce a novel generative modeling paradigm, Next-Token-Pair Prediction (NTPP), to enable speaker-independent dual-channel spoken dialogue learning using decoder-only architectures for the first time. We evaluate our approach on standard benchmarks, and empirical results show that our proposed method, NTPP, significantly improves the conversational abilities of SLMs in terms of turn-taking prediction, response coherence, and naturalness. Moreover, compared to existing methods, NTPP achieves substantially lower inference latency, highlighting its practical efficiency for real-time applications.

[Arxiv](https://arxiv.org/abs/2506.00975)