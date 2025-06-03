# NTPP：双通道语音对话的生成式语言建模新方法——基于预测下一个词对

发布时间：2025年06月01日

`LLM应用` `对话系统` `语音技术`

> NTPP: Generative Speech Language Modeling for Dual-Channel Spoken Dialogue via Next-Token-Pair Prediction

# 摘要

> 受到 GPT-4o 的启发，研究者们日益关注赋予语音语言模型 (SLMs) 与人类进行自然流畅对话的能力。尽管近期已有几种 SLMs 在这一领域展现出潜力，但现有方法尚未充分利用双通道语音数据的独特优势——这种数据天然捕捉了人类对话的结构与动态。本文首次系统性地探索了双通道语音数据在现代大型语言模型中的应用，并创新性地提出了一种全新生成建模范式——Next-Token-Pair Prediction (NTPP)，成功实现了基于解码器架构的无说话人依赖双通道对话学习。在标准基准测试中，我们的 NTPP 方法在对话轮次预测、响应连贯性与自然度方面均显著优于现有方法。更值得一提的是，NTPP 的推理延迟大幅降低，充分展现了其在实时应用中的高效实用价值。

> Inspired by the impressive capabilities of GPT-4o, there is growing interest in enabling speech language models (SLMs) to engage in natural, fluid spoken interactions with humans. Recent advancements have led to the development of several SLMs that demonstrate promising results in this area. However, current approaches have yet to fully exploit dual-channel speech data, which inherently captures the structure and dynamics of human conversation. In this work, we systematically explore the use of dual-channel speech data in the context of modern large language models, and introduce a novel generative modeling paradigm, Next-Token-Pair Prediction (NTPP), to enable speaker-independent dual-channel spoken dialogue learning using decoder-only architectures for the first time. We evaluate our approach on standard benchmarks, and empirical results show that our proposed method, NTPP, significantly improves the conversational abilities of SLMs in terms of turn-taking prediction, response coherence, and naturalness. Moreover, compared to existing methods, NTPP achieves substantially lower inference latency, highlighting its practical efficiency for real-time applications.

[Arxiv](https://arxiv.org/abs/2506.00975)