# 从纯文本到诗歌形式，生成具有节奏约束的梵文诗歌

发布时间：2025年05月31日

`LLM应用` `文学艺术` `诗歌创作`

> From Plain Text to Poetic Form: Generating Metrically-Constrained Sanskrit Verses

# 摘要

> 大型语言模型（LLMs）的最新进展显著提升了自然语言生成能力，尤其在诗歌创作等创造性任务中表现突出。然而，目前的研究主要集中在高资源语言上。这引发了一个重要问题：能否将LLMs应用于低资源、形态丰富的语言（如梵文）的结构化诗歌生成？在本研究中，我们提出了一项旨在将英文散文翻译为遵循古典韵律模式（尤其是Anushtub诗律）的结构化梵文诗歌的数据集。我们评估了多种生成模型（开源与专有）在不同设置下的表现。具体而言，我们探索了针对韵律和语义忠实性的约束解码策略与指令微调方法。我们的解码方法在生成句法有效的诗歌形式方面达到了超过99%的准确率，显著优于通用模型的韵律一致性。同时，经指令微调的模型变体在保持与原意和诗歌风格的对齐方面表现更佳，尽管在韵律精度上有所微小妥协，但这一结论得到了人工评估的支持。


> Recent advances in large language models (LLMs) have significantly improved natural language generation, including creative tasks like poetry composition. However, most progress remains concentrated in high-resource languages. This raises an important question: Can LLMs be adapted for structured poetic generation in a low-resource, morphologically rich language such as Sanskrit? In this work, we introduce a dataset designed for translating English prose into structured Sanskrit verse, with strict adherence to classical metrical patterns, particularly the Anushtub meter. We evaluate a range of generative models-both open-source and proprietary-under multiple settings. Specifically, we explore constrained decoding strategies and instruction-based fine-tuning tailored to metrical and semantic fidelity. Our decoding approach achieves over 99% accuracy in producing syntactically valid poetic forms, substantially outperforming general-purpose models in meter conformity. Meanwhile, instruction-tuned variants show improved alignment with source meaning and poetic style, as supported by human assessments, albeit with marginal trade-offs in metrical precision.

[Arxiv](https://arxiv.org/abs/2506.00815)