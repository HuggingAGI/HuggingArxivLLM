# 一张图片，即可致命：用单图投毒视觉文档检索增强生成

发布时间：2025年04月02日

`RAG` `计算机视觉` `系统安全`

> One Pic is All it Takes: Poisoning Visual Document Retrieval Augmented Generation with a Single Image

# 摘要

> 多模态检索增强生成（M-RAG）作为一种新兴方法，通过事实知识库（KB）抑制大型多模态模型（LMMs）的幻觉现象。然而，M-RAG也为攻击者提供了新的攻击途径，他们可通过向KB注入恶意条目来破坏系统。本研究针对视觉文档检索应用，提出了一种针对M-RAG的中毒攻击，其中KB包含文档页面的图像。我们的目标是精心构造一张图片，使其能被多种不同的用户查询检索到，并持续影响生成模型的输出，从而对M-RAG系统发起一种通用的拒绝服务（DoS）攻击。我们证明，尽管该攻击对广泛使用的多种先进检索器（嵌入模型）和生成器（LMMs）均有效，但对鲁棒嵌入模型则可能无效。此次攻击不仅揭示了M-RAG流水线易受中毒攻击的脆弱性，还揭示了一个潜在的根本性弱点，这可能在良性环境下也会影响其性能表现。

> Multimodal retrieval augmented generation (M-RAG) has recently emerged as a method to inhibit hallucinations of large multimodal models (LMMs) through a factual knowledge base (KB). However, M-RAG also introduces new attack vectors for adversaries that aim to disrupt the system by injecting malicious entries into the KB. In this work, we present a poisoning attack against M-RAG targeting visual document retrieval applications, where the KB contains images of document pages. Our objective is to craft a single image that is retrieved for a variety of different user queries, and consistently influences the output produced by the generative model, thus creating a universal denial-of-service (DoS) attack against the M-RAG system. We demonstrate that while our attack is effective against a diverse range of widely-used, state-of-the-art retrievers (embedding models) and generators (LMMs), it can also be ineffective against robust embedding models. Our attack not only highlights the vulnerability of M-RAG pipelines to poisoning attacks, but also sheds light on a fundamental weakness that potentially hinders their performance even in benign settings.

[Arxiv](https://arxiv.org/abs/2504.02132)