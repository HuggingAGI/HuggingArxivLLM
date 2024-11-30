# MUSE-VL：借助语义离散编码构建统一的 VLM 模型

发布时间：2024年11月25日

`LLM应用` `视觉语言` `多模态`

> MUSE-VL: Modeling Unified VLM through Semantic Discrete Encoding

# 摘要

> 我们推出 MUSE-VL，这是一款借助语义离散编码来实现多模态理解与生成的统一视觉语言模型。近来，研究领域已着手探索用于视觉生成与理解的统一模型。然而，现有的视觉标记器（如 VQGAN）只考虑低级信息，难以与纹理语义特征匹配。这致使训练复杂度颇高，且需要大量训练数据才能达至最优性能。另外，它们的表现仍远不及专用的理解模型。本文提出语义离散编码（SDE），给视觉标记器添加语义约束，从而有效对齐视觉标记和语言标记的信息。这极大地降低了训练难度，提升了统一模型的性能。所提模型在各类视觉语言基准测试中大幅超越先前的最先进水平，且性能优于专用理解模型。

> We introduce MUSE-VL, a Unified Vision-Language Model through Semantic discrete Encoding for multimodal understanding and generation. Recently, the research community has begun exploring unified models for visual generation and understanding. However, existing vision tokenizers (e.g., VQGAN) only consider low-level information, which makes it difficult to align with texture semantic features. This results in high training complexity and necessitates a large amount of training data to achieve optimal performance. Additionally, their performance is still far from dedicated understanding models. This paper proposes Semantic Discrete Encoding (SDE), which effectively aligns the information of visual tokens and language tokens by adding semantic constraints to the visual tokenizer. This greatly reduces training difficulty and improves the performance of the unified model. The proposed model significantly surpasses the previous state-of-the-art in various vision-language benchmarks and achieves better performance than dedicated understanding models.

[Arxiv](https://arxiv.org/abs/2411.17762)