# BanglaByT5：孟加拉语字节级建模新方案

发布时间：2025年05月21日

`LLM应用

理由：该论文主要探讨了大型语言模型在孟加拉语处理中的应用，特别是针对传统分词器在形态丰富的孟加拉语上的不足，提出了一种专门设计的字节级编解码模型。这属于将大型语言模型应用于特定语言和任务的范畴，因此归类为LLM应用。` `孟加拉语`

> BanglaByT5: Byte-Level Modelling for Bangla

# 摘要

> 大型语言模型 (LLMs) 在自然语言处理领域取得了显著成功，但传统分词器如 BPE 和 SentencePiece 在处理形态丰富的孟加拉语时存在不足。为此，我们推出了 BanglaByT5，首个专为孟加拉语设计的字节级编解码模型。该模型基于 Google ByT5 架构的小型变体，经过 14GB 高质量文学和新闻语料库的预训练。在生成和分类任务的零样本及监督评估中，BanglaByT5 表现出色，超越了多个跨语言和更大规模的模型。研究结果表明，字节级建模对形态丰富语言的有效性，BanglaByT5 有望成为孟加拉语 NLP 的轻量级强大工具，尤其适用于资源受限和可扩展环境。

> Large language models (LLMs) have achieved remarkable success across various natural language processing tasks. However, most LLM models use traditional tokenizers like BPE and SentencePiece, which fail to capture the finer nuances of a morphologically rich language like Bangla (Bengali). In this work, we introduce BanglaByT5, the first byte-level encoder-decoder model explicitly tailored for Bangla. Built upon a small variant of Googles ByT5 architecture, BanglaByT5 is pre-trained on a 14GB curated corpus combining high-quality literary and newspaper articles. Through zeroshot and supervised evaluations across generative and classification tasks, BanglaByT5 demonstrates competitive performance, surpassing several multilingual and larger models. Our findings highlight the efficacy of byte-level modelling for morphologically rich languages and highlight BanglaByT5 potential as a lightweight yet powerful tool for Bangla NLP, particularly in both resource-constrained and scalable environments.

[Arxiv](https://arxiv.org/abs/2505.17102)