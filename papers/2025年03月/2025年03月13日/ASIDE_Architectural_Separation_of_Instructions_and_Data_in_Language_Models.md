# # ASIDE：语言模型中指令与数据的架构分离方法
在语言模型设计中，实现指令与数据的架构分离是一种全新的思路。

发布时间：2025年03月13日

`LLM理论` `人工智能`

> ASIDE: Architectural Separation of Instructions and Data in Language Models

# 摘要

> 大型语言模型虽然表现出色，但缺乏基本的安全特性，使其易受恶意攻击。尤其是，指令与数据间的分离不足被认为是提示注入攻击成功的关键原因。本研究提出了一种名为ASIDE的架构改动，通过为指令和数据使用独立嵌入，帮助模型实现清晰的区分。我们无需从头训练嵌入层，而是提出了一种方法，利用原模型嵌入层的两个副本，并对其中一个进行正交旋转，从而将现有模型转换为ASIDE形式。实验结果表明：(1) 在保持模型能力的同时，显著提升了指令与数据的分离度；(2) 即使没有专门的安全训练，ASIDE在提示注入攻击基准测试中也表现优异。此外，我们还通过分析模型表示，深入研究了该方法的工作机制。

> Despite their remarkable performance, large language models lack elementary safety features, and this makes them susceptible to numerous malicious attacks. In particular, previous work has identified the absence of an intrinsic separation between instructions and data as a root cause for the success of prompt injection attacks. In this work, we propose an architectural change, ASIDE, that allows the model to clearly separate between instructions and data by using separate embeddings for them. Instead of training the embeddings from scratch, we propose a method to convert an existing model to ASIDE form by using two copies of the original model's embeddings layer, and applying an orthogonal rotation to one of them. We demonstrate the effectiveness of our method by showing (1) highly increased instruction-data separation scores without a loss in model capabilities and (2) competitive results on prompt injection benchmarks, even without dedicated safety training. Additionally, we study the working mechanism behind our method through an analysis of model representations.

[Arxiv](https://arxiv.org/abs/2503.10566)