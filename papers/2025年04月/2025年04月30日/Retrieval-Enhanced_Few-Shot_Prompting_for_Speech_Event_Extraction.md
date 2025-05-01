# 基于检索增强的少样本提示方法，用于语音事件抽取

发布时间：2025年04月30日

`LLM应用` `语音处理`

> Retrieval-Enhanced Few-Shot Prompting for Speech Event Extraction

# 摘要

> 语音事件抽取（SpeechEE）是一项结合自动语音识别（ASR）和自然语言处理（NLP）的挑战性任务，旨在从口语中识别结构化的事件信息。本研究提出了一种模块化、基于管道的SpeechEE框架，将高性能ASR与语义搜索增强的大型语言模型（LLMs）提示相结合。我们的系统首先通过基于规则、BERT和LLM的混合过滤机制，识别可能包含事件的语音段。随后，利用语义相似度检索动态丰富内容，采用少量样本的LLM提示，精准识别事件触发词并提取相关参数。我们使用Llama3-8B、GPT-4o-mini和o1-mini等多个LLM对管道进行了评估，结果显示o1-mini表现尤为突出，实现了63.3%的触发词分类F1分数和27.8%的参数分类F1分数，超越了现有基准。研究结果表明，借助检索增强的LLM，管道方法不仅能够与端到端系统相媲美，甚至在某些方面超越，同时保持了良好的可解释性和模块化设计。这项工作为LLM驱动的事件抽取提供了宝贵的实践见解，并为未来结合文本和声学特征的混合模型开发指明了方向。

> Speech Event Extraction (SpeechEE) is a challenging task that lies at the intersection of Automatic Speech Recognition (ASR) and Natural Language Processing (NLP), requiring the identification of structured event information from spoken language. In this work, we present a modular, pipeline-based SpeechEE framework that integrates high-performance ASR with semantic search-enhanced prompting of Large Language Models (LLMs). Our system first classifies speech segments likely to contain events using a hybrid filtering mechanism including rule-based, BERT-based, and LLM-based models. It then employs few-shot LLM prompting, dynamically enriched via semantic similarity retrieval, to identify event triggers and extract corresponding arguments. We evaluate the pipeline using multiple LLMs (Llama3-8B, GPT-4o-mini, and o1-mini) highlighting significant performance gains with o1-mini, which achieves 63.3% F1 on trigger classification and 27.8% F1 on argument classification, outperforming prior benchmarks. Our results demonstrate that pipeline approaches, when empowered by retrieval-augmented LLMs, can rival or exceed end-to-end systems while maintaining interpretability and modularity. This work provides practical insights into LLM-driven event extraction and opens pathways for future hybrid models combining textual and acoustic features.

[Arxiv](https://arxiv.org/abs/2504.21372)