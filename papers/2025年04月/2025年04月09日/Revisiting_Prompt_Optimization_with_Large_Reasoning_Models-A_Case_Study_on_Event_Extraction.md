# # 再探大推理模型的提示优化——以事件抽取为案例研究

发布时间：2025年04月09日

`LLM应用` `信息抽取`

> Revisiting Prompt Optimization with Large Reasoning Models-A Case Study on Event Extraction

# 摘要

> 大型推理模型（LRMs）如DeepSeek-R1和OpenAI o1在多种推理任务中展现了卓越的能力。它们生成和推理中间思想的强大能力也引发了一些争论，认为它们可能不再需要复杂的提示工程或优化来理解人类指令并生成准确的输出。本研究以事件抽取任务为案例，系统性地探讨这一问题。我们实验了两种LRMs（DeepSeek-R1和o1）以及两种通用大型语言模型（LLMs）（GPT-4o和GPT-4.5），分别作为任务模型和提示优化器进行测试。结果显示，即使在复杂如事件抽取的任务中，LRMs作为任务模型仍能从提示优化中获益，而将LRMs用作提示优化器能够生成更有效的提示。最后，我们对LRMs常见的错误进行了分析，并强调了LRMs在细化任务指令和事件指南方面的稳定性和一致性。

> Large Reasoning Models (LRMs) such as DeepSeek-R1 and OpenAI o1 have demonstrated remarkable capabilities in various reasoning tasks. Their strong capability to generate and reason over intermediate thoughts has also led to arguments that they may no longer require extensive prompt engineering or optimization to interpret human instructions and produce accurate outputs. In this work, we aim to systematically study this open question, using the structured task of event extraction for a case study. We experimented with two LRMs (DeepSeek-R1 and o1) and two general-purpose Large Language Models (LLMs) (GPT-4o and GPT-4.5), when they were used as task models or prompt optimizers. Our results show that on tasks as complicated as event extraction, LRMs as task models still benefit from prompt optimization, and that using LRMs as prompt optimizers yields more effective prompts. Finally, we provide an error analysis of common errors made by LRMs and highlight the stability and consistency of LRMs in refining task instructions and event guidelines.

[Arxiv](https://arxiv.org/abs/2504.07357)