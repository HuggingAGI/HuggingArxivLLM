# 数学表达式文本到语音系统的清晰度

发布时间：2025年06月05日

`LLM应用

理由：这篇论文主要探讨了大型语言模型（LLMs）在文本转语音（TTS）中的应用，特别是处理数学表达式（MX）的输入。虽然论文中提到了LLMs被用来将LaTeX格式的MX转换为英文发音，但研究的核心在于评估TTS模型在处理MX时的音质和可懂度，以及比较不同模型和MX类别之间的表现差异。因此，论文的重点在于LLMs的实际应用，属于LLM应用类别。` `语音合成` `数学表达式生成`

> Intelligibility of Text-to-Speech Systems for Mathematical Expressions

# 摘要

> 目前对以数学表达式（MX）为输入的高级文本转语音（TTS）模型的评估十分有限。本研究设计了一系列实验，通过听力测试和转录测试，对五种TTS模型在不同类别MX下的音质和可懂度进行评估。我们采用了两种大型语言模型（LLMs）将LaTeX格式的MX转换为英文发音，因为TTS模型无法直接处理LaTeX格式。我们通过用户的平均评分来衡量音质，并通过转录正确率的三个指标来量化可懂度。同时，我们还将TTS输出与人类专家对相同MX的发音进行了比较。研究结果表明，TTS模型对MX的输出并非总是清晰易懂，不同TTS模型和MX类别之间的可懂度差距显著。对于大多数类别，TTS模型的表现明显劣于专家发音。大型语言模型的选择对结果的影响有限。这表明，提升TTS模型在MX处理方面的能力迫在眉睫。

> There has been limited evaluation of advanced Text-to-Speech (TTS) models with Mathematical eXpressions (MX) as inputs. In this work, we design experiments to evaluate quality and intelligibility of five TTS models through listening and transcribing tests for various categories of MX. We use two Large Language Models (LLMs) to generate English pronunciation from LaTeX MX as TTS models cannot process LaTeX directly. We use Mean Opinion Score from user ratings and quantify intelligibility through transcription correctness using three metrics. We also compare listener preference of TTS outputs with respect to human expert rendition of same MX. Results establish that output of TTS models for MX is not necessarily intelligible, the gap in intelligibility varies across TTS models and MX category. For most categories, performance of TTS models is significantly worse than that of expert rendition. The effect of choice of LLM is limited. This establishes the need to improve TTS models for MX.

[Arxiv](https://arxiv.org/abs/2506.11086)