# Bi'an: 一个双语基准与模型，用于检索增强生成中的幻觉检测

发布时间：2025年02月26日

`RAG` `问答系统` `信息检索`

> Bi'an: A Bilingual Benchmark and Model for Hallucination Detection in Retrieval-Augmented Generation

# 摘要

> 检索增强生成（RAG）显著降低了大型语言模型（LLMs）中的幻觉现象，但仍然存在生成不一致或无支持内容的问题。尽管LLM-as-a-Judge因其简单易行而被广泛用于RAG幻觉检测，但它面临两大挑战：缺乏全面的评估基准和领域优化的判断模型。为了解决这些问题，我们推出了	extbf{Bi'an}——一个创新框架，包含双语基准数据集和轻量级判断模型。该数据集支持在多个RAG场景下进行严格评估，而判断模型则基于开源LLMs进行了优化微调。在Bi'anBench的全面实验中，我们的140亿参数模型不仅超越了参数规模大五倍的基线模型，更与先进的闭源LLMs相媲美。我们即将在https://github.com/OpenSPG/KAG上发布相关数据和模型。

> Retrieval-Augmented Generation (RAG) effectively reduces hallucinations in Large Language Models (LLMs) but can still produce inconsistent or unsupported content. Although LLM-as-a-Judge is widely used for RAG hallucination detection due to its implementation simplicity, it faces two main challenges: the absence of comprehensive evaluation benchmarks and the lack of domain-optimized judge models. To bridge these gaps, we introduce \textbf{Bi'an}, a novel framework featuring a bilingual benchmark dataset and lightweight judge models. The dataset supports rigorous evaluation across multiple RAG scenarios, while the judge models are fine-tuned from compact open-source LLMs. Extensive experimental evaluations on Bi'anBench show our 14B model outperforms baseline models with over five times larger parameter scales and rivals state-of-the-art closed-source LLMs. We will release our data and models soon at https://github.com/OpenSPG/KAG.

[Arxiv](https://arxiv.org/abs/2502.19209)