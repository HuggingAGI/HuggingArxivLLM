# LLM增强器：融合向量嵌入，借助外部知识降低大模型幻觉

发布时间：2025年04月29日

`RAG

理由：这篇论文主要探讨了通过整合外部资源和使用向量嵌入检索来增强大型语言模型的能力，属于检索增强生成（RAG）技术的应用。` `对话系统` `信息检索`

> LLM Enhancer: Merged Approach using Vector Embedding for Reducing Large Language Model Hallucinations with External Knowledge

# 摘要

> 大型语言模型 (LLMs) 如 ChatGPT 在任务导向对话和问答等任务中展现了生成自然回应的能力。然而，它们在现实世界关键场景中的应用常因生成不准确信息和有限的外部知识利用能力而受限。本文介绍的 LLM ENHANCER 系统通过整合 Google、Wikipedia 和 DuckDuckGo 等在线资源，提升数据准确性。该系统采用开源 LLM，数据获取流程并行运行，借助定制的代理工具管理信息流动。通过向量嵌入识别最相关的信息，并将其提供给 LLM 用于用户交互。LLM ENHANCER 在基于聊天的 LLM 中有效缓解幻觉现象，同时保持回应的自然性和准确性。

> Large Language Models (LLMs), such as ChatGPT, have demonstrated the capability to generate human like, natural responses across a range of tasks, including task oriented dialogue and question answering. However, their application in real world, critical scenarios is often hindered by a tendency to produce inaccurate information and a limited ability to leverage external knowledge sources. This paper introduces the LLM ENHANCER system, designed to integrate multiple online sources such as Google, Wikipedia, and DuckDuckGo to enhance data accuracy. The LLMs employed within this system are open source. The data acquisition process for the LLM ENHANCER system operates in parallel, utilizing custom agent tools to manage the flow of information. Vector embeddings are used to identify the most pertinent information, which is subsequently supplied to the LLM for user interaction. The LLM ENHANCER system mitigates hallucinations in chat based LLMs while preserving response naturalness and accuracy.

[Arxiv](https://arxiv.org/abs/2504.21132)