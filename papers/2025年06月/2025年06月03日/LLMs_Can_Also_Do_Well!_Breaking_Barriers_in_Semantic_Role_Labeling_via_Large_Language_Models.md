# # 大型语言模型同样表现出色！借助大型语言模型突破语义角色标注的瓶颈

发布时间：2025年06月03日

`RAG` `语义角色标注`

> LLMs Can Also Do Well! Breaking Barriers in Semantic Role Labeling via Large Language Models

# 摘要

> 语义角色标注 (SRL) 是自然语言处理 (NLP) 中的关键任务。尽管生成式解码器模型在 NLP 任务中表现优异，但在 SRL 任务上，它们仍逊色于编码器-解码器 (BERT-like) 模型。本研究通过为 LLMs 引入两种机制——检索增强生成与自我校正——来弥补这一差距。检索增强生成使 LLMs 能够调用外部语言知识，如谓词和论元结构描述，而自我校正机制则帮助 LLMs 识别并修正不一致的标注结果。我们在 CPB1.0、CoNLL-2009 和 CoNLL-2012 三大基准数据集上进行了全面实验。结果表明，我们的方法在中英文 SRL 任务中均达到最佳性能，实现了 LLMs 在 SRL 领域首次超越编码器-解码器方法的突破。

> Semantic role labeling (SRL) is a crucial task of natural language processing (NLP). Although generative decoder-based large language models (LLMs) have achieved remarkable success across various NLP tasks, they still lag behind state-of-the-art encoder-decoder (BERT-like) models in SRL. In this work, we seek to bridge this gap by equipping LLMs for SRL with two mechanisms: (a) retrieval-augmented generation and (b) self-correction. The first mechanism enables LLMs to leverage external linguistic knowledge such as predicate and argument structure descriptions, while the second allows LLMs to identify and correct inconsistent SRL outputs. We conduct extensive experiments on three widely-used benchmarks of SRL (CPB1.0, CoNLL-2009, and CoNLL-2012). Results demonstrate that our method achieves state-of-the-art performance in both Chinese and English, marking the first successful application of LLMs to surpass encoder-decoder approaches in SRL.

[Arxiv](https://arxiv.org/abs/2506.05385)