# SEAL: 基于检索增强生成的语音大语言模型的语音嵌入对齐学习

发布时间：2025年01月26日

`RAG

理由：这篇论文主要讨论了在语音LLMs（SLLMs）中嵌入检索模型的改进，特别是针对RAG（Retrieval-Augmented Generation）技术的应用。论文提出了一种统一的嵌入框架，旨在解决现有方法中的延迟和错误传播问题，并展示了其在检索准确率和延迟方面的改进。因此，这篇论文应归类为RAG。` `语音处理` `多模态检索`

> SEAL: Speech Embedding Alignment Learning for Speech Large Language Model with Retrieval-Augmented Generation

# 摘要

> 嵌入检索模型在文本和多模态LLMs的RAG技术中取得了显著进展，但在语音LLMs（SLLMs）中，现有方法仍局限于两阶段流程：先进行语音识别（ASR），再进行文本检索。这种架构不仅延迟高，还容易导致错误传播。为此，我们提出了一种统一的嵌入框架，无需中间文本表示。该框架包含独立的语音和文本编码器，并通过共享缩放层将两种模态映射到同一嵌入空间。实验表明，我们的模型将延迟降低了50%，同时检索准确率优于传统两阶段方法。我们还从理论上分析了端到端语音检索的挑战，并提出了语音到文档匹配的架构设计原则。大量实验验证了该方法在不同声学条件和说话者变化下的鲁棒性，为多模态SLLMs检索系统开辟了新范式。

> Embedding-based retrieval models have made significant strides in retrieval-augmented generation (RAG) techniques for text and multimodal large language models (LLMs) applications. However, when it comes to speech larage language models (SLLMs), these methods are limited to a two-stage process, where automatic speech recognition (ASR) is combined with text-based retrieval. This sequential architecture suffers from high latency and error propagation. To address these limitations, we propose a unified embedding framework that eliminates the need for intermediate text representations. Specifically, the framework includes separate speech and text encoders, followed by a shared scaling layer that maps both modalities into a common embedding space. Our model reduces pipeline latency by 50\% while achieving higher retrieval accuracy compared to traditional two-stage methods. We also provide a theoretical analysis of the challenges inherent in end-to-end speech retrieval and introduce architectural principles for effective speech-to-document matching. Extensive experiments demonstrate the robustness of our approach across diverse acoustic conditions and speaker variations, paving the way for a new paradigm in multimodal SLLMs retrieval systems.

[Arxiv](https://arxiv.org/abs/2502.02603)