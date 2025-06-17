# CHILL 在 SemEval-2025 任务2中：别以为随便丢弃实体就能让模型正确处理，得让您的 LLM 准确识别它们。

发布时间：2025年06月15日

`RAG` `机器翻译`

> CHILL at SemEval-2025 Task 2: You Can't Just Throw Entities and Hope -- Make Your LLM to Get Them Right

# 摘要

> 本文介绍了我们在 SemEval 2025 任务 2 中的实体感知机器翻译（EA-MT）方法。我们的系统通过结合检索增强生成（RAG）和基于大型语言模型（LLMs）的迭代自我完善技术，显著提升了专有名实体的翻译准确性。系统还具备独特的自我评估功能，LLM 能根据实体翻译的准确性和整体翻译质量两个维度对自身输出进行评估。通过这些方法的协同作用，我们在保持翻译质量的同时，显著提升了实体处理能力。

> In this paper, we describe our approach for the SemEval 2025 Task 2 on Entity-Aware Machine Translation (EA-MT). Our system aims to improve the accuracy of translating named entities by combining two key approaches: Retrieval Augmented Generation (RAG) and iterative self-refinement techniques using Large Language Models (LLMs). A distinctive feature of our system is its self-evaluation mechanism, where the LLM assesses its own translations based on two key criteria: the accuracy of entity translations and overall translation quality. We demonstrate how these methods work together and effectively improve entity handling while maintaining high-quality translations.

[Arxiv](https://arxiv.org/abs/2506.13070)