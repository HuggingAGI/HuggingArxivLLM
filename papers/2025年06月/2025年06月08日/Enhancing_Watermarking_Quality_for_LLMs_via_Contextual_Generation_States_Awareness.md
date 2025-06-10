# # 提升大型语言模型水印质量的上下文生成状态感知方法
通过感知上下文生成状态，提升大型语言模型的水印质量。

发布时间：2025年06月08日

`LLM应用

摘要中讨论了水印技术在AI生成文本中的应用，特别是针对大型语言模型（LLMs）。该论文提出了一种新的水印框架，旨在提高生成文本的质量和检测率，属于对LLM应用的改进和优化，因此归类为LLM应用。` `信息安全` `内容安全`

> Enhancing Watermarking Quality for LLMs via Contextual Generation States Awareness

# 摘要

> # 摘要
近期水印技术的突破性进展使在AI生成文本（AIGT）中嵌入秘密信息成为可能，这一技术作为检测AIGT的重要手段。现有方法通常通过干扰大型语言模型（LLMs）的生成过程，在生成文本中嵌入信号。然而，这些方法往往依赖启发式规则，可能导致次优的令牌选择，并引发生成内容质量下降。本文提出了一种即插即用的上下文生成状态感知水印框架（CAW），该框架能够动态调整嵌入过程，并可与现有多种水印方法无缝集成，从而提升生成质量。首先，CAW集成了一个水印容量评估器，通过分析上下文生成状态，评估在不同令牌位置嵌入消息的影响。此外，我们引入了多分支预生成机制，以避免所提水印策略带来的延迟。在此基础上，CAW可根据每个令牌的评估水印容量动态调整水印过程，从而最大限度地减少内容质量下降的可能性。在多领域数据集上进行的广泛实验验证了我们方法的有效性，无论是在检测率还是生成质量方面，与各种基线方法相比，我们的方法都表现更优。


> Recent advancements in watermarking techniques have enabled the embedding of secret messages into AI-generated text (AIGT), serving as an important mechanism for AIGT detection. Existing methods typically interfere with the generation processes of large language models (LLMs) to embed signals within the generated text. However, these methods often rely on heuristic rules, which can result in suboptimal token selection and a subsequent decline in the quality of the generated content. In this paper, we introduce a plug-and-play contextual generation states-aware watermarking framework (CAW) that dynamically adjusts the embedding process. It can be seamlessly integrated with various existing watermarking methods to enhance generation quality. First, CAW incorporates a watermarking capacity evaluator, which can assess the impact of embedding messages at different token positions by analyzing the contextual generation states. Furthermore, we introduce a multi-branch pre-generation mechanism to avoid the latency caused by the proposed watermarking strategy. Building on this, CAW can dynamically adjust the watermarking process based on the evaluated watermark capacity of each token, thereby minimizing potential degradation in content quality. Extensive experiments conducted on datasets across multiple domains have verified the effectiveness of our method, demonstrating superior performance compared to various baselines in terms of both detection rate and generation quality.

[Arxiv](https://arxiv.org/abs/2506.07403)