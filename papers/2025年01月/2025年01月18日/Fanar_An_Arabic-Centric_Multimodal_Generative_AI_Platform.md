# Fanar: 一个专注于阿拉伯语的多模态生成式AI平台

发布时间：2025年01月18日

`LLM应用

理由：这篇论文主要介绍了一个名为Fanar的多模态生成AI平台，该平台专注于阿拉伯语，并包含多个大型语言模型（LLMs）和其他功能，如检索增强生成（RAG）系统、语音识别、语音和图像生成等。这些内容主要涉及LLM在实际应用中的开发和部署，因此将其分类为“LLM应用”。` `人工智能`

> Fanar: An Arabic-Centric Multimodal Generative AI Platform

# 摘要

> 我们推出了Fanar，一个专注于阿拉伯语的多模态生成AI平台，支持语言、语音和图像生成任务。Fanar的核心是Fanar Star和Fanar Prime，这两个阿拉伯语大型语言模型（LLMs）在同类模型中表现卓越。Fanar Star是一个70亿参数的模型，从头训练，使用了近1万亿个干净且去重的阿拉伯语、英语和代码标记。Fanar Prime是一个90亿参数的模型，基于Gemma-2 9B基础模型在同一1万亿标记集上持续训练。这两个模型同时部署，通过定制编排器透明地处理不同类型的提示。Fanar平台还提供了许多其他功能，包括一个定制的伊斯兰检索增强生成（RAG）系统，用于处理宗教提示，以及一个用于总结预训练数据截止日期后发生的当前或近期事件的Recency RAG。该平台还具备额外的认知能力，如支持多种阿拉伯方言的内部双语语音识别，以及经过微调以更好地反映区域特征的语音和图像生成。最后，Fanar提供了一个归属服务，用于验证基于事实生成内容的真实性。
    Fanar的设计、开发和实施完全由哈马德·本·哈利法大学的卡塔尔计算研究所（QCRI）承担，并由卡塔尔通信和信息技术部赞助，以支持主权AI技术的发展。

> We present Fanar, a platform for Arabic-centric multimodal generative AI systems, that supports language, speech and image generation tasks. At the heart of Fanar are Fanar Star and Fanar Prime, two highly capable Arabic Large Language Models (LLMs) that are best in the class on well established benchmarks for similar sized models. Fanar Star is a 7B (billion) parameter model that was trained from scratch on nearly 1 trillion clean and deduplicated Arabic, English and Code tokens. Fanar Prime is a 9B parameter model continually trained on the Gemma-2 9B base model on the same 1 trillion token set. Both models are concurrently deployed and designed to address different types of prompts transparently routed through a custom-built orchestrator. The Fanar platform provides many other capabilities including a customized Islamic Retrieval Augmented Generation (RAG) system for handling religious prompts, a Recency RAG for summarizing information about current or recent events that have occurred after the pre-training data cut-off date. The platform provides additional cognitive capabilities including in-house bilingual speech recognition that supports multiple Arabic dialects, voice and image generation that is fine-tuned to better reflect regional characteristics. Finally, Fanar provides an attribution service that can be used to verify the authenticity of fact based generated content.
  The design, development, and implementation of Fanar was entirely undertaken at Hamad Bin Khalifa University's Qatar Computing Research Institute (QCRI) and was sponsored by Qatar's Ministry of Communications and Information Technology to enable sovereign AI technology development.

[Arxiv](https://arxiv.org/abs/2501.13944)