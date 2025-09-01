# Agri-Query：RAG与长上下文LLMs在跨语言技术问答中的案例研究

发布时间：2025年08月25日

`RAG` `农业科技`

> Agri-Query: A Case Study on RAG vs. Long-Context LLMs for Cross-Lingual Technical Question Answering

# 摘要

> 我们开展了一项案例研究，评估了具备128K token上下文窗口的大型语言模型（LLMs）在技术问答（QA）任务中的表现。研究基准测试集基于一本农业机械用户手册（含英、法、德三语版本），模拟了跨语言信息检索场景：以英文提问，对应手册的三种语言版本内容。评估不仅包含真实的“大海捞针”挑战，还加入了无法回答的问题以检测模型幻觉。我们对比了九种长上下文LLM的直接提示方式与三种检索增强生成（RAG）策略（关键词、语义、混合），并采用LLM作为评判器进行评估。结果显示，针对该手册，混合RAG的表现始终优于直接长上下文提示；而像Gemini 2.5 Flash和更小体量的Qwen 2.5 7B模型，结合RAG后在所有语言上均实现了85%以上的高准确率。本文不仅深入分析了LLM在特定工业领域的性能，还提供了用于类似评估的开放框架，同时点明了实际应用中的权衡与挑战。

> We present a case study evaluating large language models (LLMs) with 128K-token context windows on a technical question answering (QA) task. Our benchmark is built on a user manual for an agricultural machine, available in English, French, and German. It simulates a cross-lingual information retrieval scenario where questions are posed in English against all three language versions of the manual. The evaluation focuses on realistic "needle-in-a-haystack" challenges and includes unanswerable questions to test for hallucinations. We compare nine long-context LLMs using direct prompting against three Retrieval-Augmented Generation (RAG) strategies (keyword, semantic, hybrid), with an LLM-as-a-judge for evaluation. Our findings for this specific manual show that Hybrid RAG consistently outperforms direct long-context prompting. Models like Gemini 2.5 Flash and the smaller Qwen 2.5 7B achieve high accuracy (over 85%) across all languages with RAG. This paper contributes a detailed analysis of LLM performance in a specialized industrial domain and an open framework for similar evaluations, highlighting practical trade-offs and challenges.

[Arxiv](https://arxiv.org/abs/2508.18093)