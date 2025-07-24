# MultiNRC：一个多语言推理评估基准，专为大型语言模型设计，既具挑战性又符合母语水平

发布时间：2025年07月23日

`LLM应用` `语言模型`

> MultiNRC: A Challenging and Native Multilingual Reasoning Evaluation Benchmark for LLMs

# 摘要

> 尽管大型语言模型（LLMs）在英语推理基准上取得了显著进步，但对其多语言推理能力的跨语言跨文化评估仍显不足。现有的多语言推理基准往往基于英文推理基准的翻译构建，导致其更侧重于英语语言文化背景的推理问题。为此，我们推出了《多语言原生推理挑战》（MultiNRC），一个由法语、西班牙语和中文母语者编写的、涵盖1000多个原生语言文化背景推理问题的基准，旨在全面评估LLMs的推理能力。

MultiNRC涵盖四大核心推理领域：特定语言的语言推理、文字游戏与谜题、文化/传统推理以及具有文化相关性的数学推理。对于文化/传统推理和具有文化相关性的数学推理，我们还通过母语者的手动翻译提供了多语言问题的英文等效版本。这一组英文等效问题为在同一推理问题上比较LLMs在不同语言与英语之间的推理能力提供了直接依据。

我们系统性地评估了当前14个领先的LLMs（涵盖主要LLM家族）在MultiNRC及其英文等效集上的表现。结果显示：
1. 当前LLMs在多语言原生推理方面仍表现欠佳，无一模型在MultiNRC上的得分超过50%；
2. 不同LLMs在处理语言、文化和逻辑推理任务时表现出明显的优势和劣势；
3. 大部分模型在英语数学推理上的表现比在原生语言中高出约10%，这表明基于文化背景的知识仍是LLMs面临的重要挑战。


> Although recent Large Language Models (LLMs) have shown rapid improvement on reasoning benchmarks in English, the evaluation of such LLMs' multilingual reasoning capability across diverse languages and cultural contexts remains limited. Existing multilingual reasoning benchmarks are typically constructed by translating existing English reasoning benchmarks, biasing these benchmarks towards reasoning problems with context in English language/cultures. In this work, we introduce the Multilingual Native Reasoning Challenge (MultiNRC), a benchmark designed to assess LLMs on more than 1,000 native, linguistic and culturally grounded reasoning questions written by native speakers in French, Spanish, and Chinese. MultiNRC covers four core reasoning categories: language-specific linguistic reasoning, wordplay & riddles, cultural/tradition reasoning, and math reasoning with cultural relevance. For cultural/tradition reasoning and math reasoning with cultural relevance, we also provide English equivalent translations of the multilingual questions by manual translation from native speakers fluent in English. This set of English equivalents can provide a direct comparison of LLM reasoning capacity in other languages vs. English on the same reasoning questions. We systematically evaluate current 14 leading LLMs covering most LLM families on MultiNRC and its English equivalent set. The results show that (1) current LLMs are still not good at native multilingual reasoning, with none scoring above 50% on MultiNRC; (2) LLMs exhibit distinct strengths and weaknesses in handling linguistic, cultural, and logical reasoning tasks; (3) Most models perform substantially better in math reasoning in English compared to in original languages (+10%), indicating persistent challenges with culturally grounded knowledge.

[Arxiv](https://arxiv.org/abs/2507.17476)