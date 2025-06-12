# PHRASED：基于短语词典偏向的语音翻译方法

发布时间：2025年06月10日

`LLM应用` `语音翻译`

> PHRASED: Phrase Dictionary Biasing for Speech Translation

# 摘要

> 短语是理解对话核心概念的关键，但由于其在训练数据中稀少，准确翻译颇具挑战。本文提出短语词典偏置方法，利用源语言到目标语言的短语映射对。该方法成功应用于两种主流模型：基于转录器的流式语音翻译模型和多模态大型语言模型。实验显示，相较于短语列表偏置，该方法使流式语音翻译模型性能提升21%。此外，短语词典偏置还让多模态大语言模型能有效利用外部短语信息，实现85%的召回率提升。

> Phrases are essential to understand the core concepts in conversations. However, due to their rare occurrence in training data, correct translation of phrases is challenging in speech translation tasks. In this paper, we propose a phrase dictionary biasing method to leverage pairs of phrases mapping from the source language to the target language. We apply the phrase dictionary biasing method to two types of widely adopted models, a transducer-based streaming speech translation model and a multimodal large language model. Experimental results show that the phrase dictionary biasing method outperforms phrase list biasing by 21% relatively for the streaming speech translation model. In addition, phrase dictionary biasing enables multimodal large language models to use external phrase information, achieving 85% relative improvement in phrase recall.

[Arxiv](https://arxiv.org/abs/2506.09175)