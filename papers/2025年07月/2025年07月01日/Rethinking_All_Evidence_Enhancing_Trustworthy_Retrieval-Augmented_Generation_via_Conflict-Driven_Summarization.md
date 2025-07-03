# 重新审视证据：通过冲突驱动的摘要增强生成的可信度

发布时间：2025年07月01日

`RAG` `问答系统` `信息检索`

> Rethinking All Evidence: Enhancing Trustworthy Retrieval-Augmented Generation via Conflict-Driven Summarization

# 摘要

> 检索增强生成 (RAG) 通过整合大型语言模型 (LLMs) 的参数化知识与外部检索内容，显著提升了模型性能。然而，由内部不一致或嘈杂的检索内容引发的知识冲突可能严重削弱 RAG 系统的生成可靠性。本研究提出，LLMs 应在生成响应前重新审视所有证据，包括检索内容和内部知识。为此，我们开发了 CARE-RAG（用于 RAG 的冲突感知和可靠证据），这是一个通过冲突驱动的证据汇总来增强可信度的创新框架。CARE-RAG 通过比较参数记录以识别不同内部视角，推导出参数感知的证据。随后，它细化检索到的证据，去除无关或误导性内容，生成上下文感知的证据。为了检测和汇总冲突，我们对一个 3B 的 LLaMA 3.2 模型进行了蒸馏，以实现冲突驱动的摘要，从而实现多来源之间的可靠合成。此外，我们引入了一个 QA 修复步骤，以纠正过时或模糊的基准答案，确保评估的完整性。在包含检索数据的修订 QA 数据集上的实验表明，CARE-RAG 一致优于强大的 RAG 基线，尤其在存在噪声或冲突证据的情况下表现突出。

> Retrieval-Augmented Generation (RAG) enhances large language models (LLMs) by integrating their parametric knowledge with external retrieved content. However, knowledge conflicts caused by internal inconsistencies or noisy retrieved content can severely undermine the generation reliability of RAG systems.In this work, we argue that LLMs should rethink all evidence, including both retrieved content and internal knowledge, before generating responses.We propose CARE-RAG (Conflict-Aware and Reliable Evidence for RAG), a novel framework that improves trustworthiness through Conflict-Driven Summarization of all available evidence.CARE-RAG first derives parameter-aware evidence by comparing parameter records to identify diverse internal perspectives. It then refines retrieved evidences to produce context-aware evidence, removing irrelevant or misleading content. To detect and summarize conflicts, we distill a 3B LLaMA3.2 model to perform conflict-driven summarization, enabling reliable synthesis across multiple sources.To further ensure evaluation integrity, we introduce a QA Repair step to correct outdated or ambiguous benchmark answers.Experiments on revised QA datasets with retrieval data show that CARE-RAG consistently outperforms strong RAG baselines, especially in scenarios with noisy or conflicting evidence.

[Arxiv](https://arxiv.org/abs/2507.01281)