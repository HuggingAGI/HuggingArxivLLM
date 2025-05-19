# 通过再利用预训练语言模型实现语义感知的跨语言线性迁移

发布时间：2025年05月16日

`LLM应用`

> Semantic Aware Linear Transfer by Recycling Pre-trained Language Models for Cross-lingual Transfer

# 摘要

> 大型语言模型（LLMs）的多语言能力日益增强，推动了将其应用于目标语言特定模型的需求。然而，现有的大多数方法通过替换源模型的词表为目标语言特定词表来融合源模型的嵌入，这可能限制目标语言的表达能力，因为源模型主要基于英语数据训练。本文提出了一种名为语义感知线性转移（SALT）的新型跨语言转移技术。SALT从目标语言的预训练语言模型（PLMs）中回收嵌入，将PLM衍生嵌入的深层表示优势传递给LLMs。通过分析源和目标词表的重叠部分，SALT推导出独特的回归线，以处理每个非重叠标记的嵌入空间。实验结果表明，SALT显著优于其他转移方法，在语言适应过程中不仅实现更低的损失，还以更快的收敛速度脱颖而出。特别值得一提的是，SALT在跨语言理解任务中表现优异，超越了现有方法。此外，通过不同架构的实验，我们展示了PLMs在增强当代LLMs功能方面的广泛应用潜力。

> Large Language Models (LLMs) increasingly incorporate multilingual capabilities, fueling the demand to transfer them into target language-specific models. However, most approaches, which blend the source model's embedding by replacing the source vocabulary with the target language-specific vocabulary, may constrain expressive capacity in the target language since the source model is predominantly trained on English data. In this paper, we propose Semantic Aware Linear Transfer (SALT), a novel cross-lingual transfer technique that recycles embeddings from target language Pre-trained Language Models (PLMs) to transmit the deep representational strengths of PLM-derived embedding to LLMs. SALT derives unique regression lines based on the similarity in the overlap of the source and target vocabularies, to handle each non-overlapping token's embedding space. Our extensive experiments show that SALT significantly outperforms other transfer methods and achieves lower loss with accelerating faster convergence during language adaptation. Notably, SALT obtains remarkable performance in cross-lingual understanding setups compared to other methods. Furthermore, we highlight the scalable use of PLMs to enhance the functionality of contemporary LLMs by conducting experiments with varying architectures.

[Arxiv](https://arxiv.org/abs/2505.10945)