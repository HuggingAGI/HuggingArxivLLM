# M-Ped：用于大型语言模型的多提示集成解码

发布时间：2024年12月24日

`LLM应用` `机器翻译`

> M-Ped: Multi-Prompt Ensemble Decoding for Large Language Models

# 摘要

> 随着大型语言模型（LLMs）在自然语言处理（NLP）领域的广泛运用，提升其性能已成为研究热点。本文呈现了一种新颖的多提示集成解码方法，意在借助多个提示结果的聚合来增强LLMs的生成质量。给定唯一输入$X$，我们以批处理模式向LLMs提交带有$X$的$n$种不同提示进行解码并获取概率分布。对于每个标记预测，我们通过在批处理内对$n$个概率分布求平均来计算集成概率，并利用此聚合概率生成标记。该技术被称为内批集成。为助力高效的批处理推理，我们采用了左填充策略，以在$n$个提示中保持输入长度的统一。通过在机器翻译、代码生成和文本简化等各类NLP任务上开展广泛实验，我们证实了该方法在提升LLM性能方面的有效性。结果表明，与传统方法相比，BLEU分数、pass@$k$率和LENS指标均有显著提升。

> With the widespread application of Large Language Models (LLMs) in the field of Natural Language Processing (NLP), enhancing their performance has become a research hotspot. This paper presents a novel multi-prompt ensemble decoding approach designed to bolster the generation quality of LLMs by leveraging the aggregation of outcomes from multiple prompts. Given a unique input $X$, we submit $n$ variations of prompts with $X$ to LLMs in batch mode to decode and derive probability distributions. For each token prediction, we calculate the ensemble probability by averaging the $n$ probability distributions within the batch, utilizing this aggregated probability to generate the token. This technique is dubbed Inner-Batch Ensemble. To facilitate efficient batch inference, we implement a Left-Padding strategy to maintain uniform input lengths across the n prompts. Through extensive experimentation on diverse NLP tasks, including machine translation, code generation, and text simplification, we demonstrate the efficacy of our method in enhancing LLM performance. The results show substantial improvements in BLEU scores, pass@$k$ rates, and LENS metrics over conventional methods.

[Arxiv](https://arxiv.org/abs/2412.18299)