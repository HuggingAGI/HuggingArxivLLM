# HalluSearch 在 SemEval-2025 任务 3 中：一个用于幻觉检测的搜索增强型 RAG 流水线

发布时间：2025年04月14日

`LLM应用

理由：这篇论文提出了一种多语言管道（HalluSearch），用于检测大型语言模型（LLM）输出中的虚构文本片段。它结合了检索增强验证（RAG）和细粒度事实分割，属于对LLM的应用研究，因此归类为LLM应用。` `幻觉检测`

> HalluSearch at SemEval-2025 Task 3: A Search-Enhanced RAG Pipeline for Hallucination Detection

# 摘要

> 本文提出了一种名为 HalluSearch 的多语言管道，用于检测大型语言模型（LLM）输出中的虚构文本片段。作为多语言共享任务 Mu-SHROOM 的一部分，HalluSearch 通过结合检索增强验证与细粒度事实分割，在十四种不同语言中实现了幻觉现象的识别与定位。实证评估结果显示，HalluSearch 的表现十分出色，在英语（排名前十分位）和捷克语中均位列第四。尽管该系统的检索策略通常表现出色，但在在线资源有限的语言中仍面临挑战，这凸显了进一步研究的必要性，以确保在各种语言背景下实现一致的幻觉检测。

> In this paper, we present HalluSearch, a multilingual pipeline designed to detect fabricated text spans in Large Language Model (LLM) outputs. Developed as part of Mu-SHROOM, the Multilingual Shared-task on Hallucinations and Related Observable Overgeneration Mistakes, HalluSearch couples retrieval-augmented verification with fine-grained factual splitting to identify and localize hallucinations in fourteen different languages. Empirical evaluations show that HalluSearch performs competitively, placing fourth in both English (within the top ten percent) and Czech. While the system's retrieval-based strategy generally proves robust, it faces challenges in languages with limited online coverage, underscoring the need for further research to ensure consistent hallucination detection across diverse linguistic contexts.

[Arxiv](https://arxiv.org/abs/2504.10168)