# 利用动态笔记增强LLM推理，提升复杂问答能力

发布时间：2025年05月22日

`RAG` `问答系统` `信息检索`

> Augmenting LLM Reasoning with Dynamic Notes Writing for Complex QA

# 摘要

> 在多跳问答任务中，迭代式RAG方法面临着长上下文和无关信息积累带来的挑战。这限制了模型处理和推理检索内容的能力，进而影响整体性能。尽管近期的方法致力于压缩检索到的信息，但它们要么仅限于单轮RAG，要么需要微调，或者在迭代式RAG中缺乏可扩展性。为了解决这些问题，我们提出了一种名为Notes Writing的方法，该方法在每一步从检索到的文档中生成简洁且相关的笔记，从而减少噪声并保留关键信息。这间接增加了大型语言模型（LLMs）的有效上下文长度，使它们在处理更多输入文本时能够更有效地推理和规划。Notes Writing方法具有框架无关性，可与不同的迭代式RAG方法相结合。我们通过三种迭代式RAG方法、两种模型以及四个评估数据集展示了其有效性。Notes Writing方法整体平均提升了15.6个百分点的性能，同时仅带来极小的输出令牌增加。

> Iterative RAG for multi-hop question answering faces challenges with lengthy contexts and the buildup of irrelevant information. This hinders a model's capacity to process and reason over retrieved content and limits performance. While recent methods focus on compressing retrieved information, they are either restricted to single-round RAG, require finetuning or lack scalability in iterative RAG. To address these challenges, we propose Notes Writing, a method that generates concise and relevant notes from retrieved documents at each step, thereby reducing noise and retaining only essential information. This indirectly increases the effective context length of Large Language Models (LLMs), enabling them to reason and plan more effectively while processing larger volumes of input text. Notes Writing is framework agnostic and can be integrated with different iterative RAG methods. We demonstrate its effectiveness with three iterative RAG methods, across two models and four evaluation datasets. Notes writing yields an average improvement of 15.6 percentage points overall, with minimal increase in output tokens.

[Arxiv](https://arxiv.org/abs/2505.16293)