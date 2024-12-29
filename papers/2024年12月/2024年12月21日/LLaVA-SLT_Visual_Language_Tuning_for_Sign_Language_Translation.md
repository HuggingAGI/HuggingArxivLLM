# LLaVA-SLT：针对手语翻译的视觉语言调优

发布时间：2024年12月21日

`LLM应用` `手语翻译` `多模态模型`

> LLaVA-SLT: Visual Language Tuning for Sign Language Translation

# 摘要

> 在手语翻译（SLT）领域，依赖昂贵的标注数据集形成了显著阻碍。无标注的 SLT 方法虽有新进展，但在翻译精准度方面常大幅落后于基于标注的方法。为缩小这一性能差距，我们推出了 LLaVA-SLT，这一开创性的大型多模态模型（LMM）框架，旨在借助有效学习的视觉语言嵌入来发挥大型语言模型（LLM）的威力。我们的模型通过三部曲加以训练。首先是语言持续预训练，我们扩展 LLM，并利用大规模语料库数据集使其适应手语领域，切实增强其有关手语的文本语言知识。接着进行视觉对比预训练，让视觉编码器与大规模预训练的文本编码器达成对齐。我们提出分层视觉编码器，它能学习与 LLM 标记嵌入兼容的强大的单词级中间表征。最后是视觉语言调整，我们冻结预训练模型，采用轻量级可训练的 MLP 连接器，将预训练的视觉语言嵌入有效映射至 LLM 标记嵌入空间，以完成下游的 SLT 任务。我们的综合实验显示，LLaVA-SLT 优于前沿方法。借助额外的无标注数据，它甚至接近基于标注的精准度。

> In the realm of Sign Language Translation (SLT), reliance on costly gloss-annotated datasets has posed a significant barrier. Recent advancements in gloss-free SLT methods have shown promise, yet they often largely lag behind gloss-based approaches in terms of translation accuracy. To narrow this performance gap, we introduce LLaVA-SLT, a pioneering Large Multimodal Model (LMM) framework designed to leverage the power of Large Language Models (LLMs) through effectively learned visual language embeddings. Our model is trained through a trilogy. First, we propose linguistic continued pretraining. We scale up the LLM and adapt it to the sign language domain using an extensive corpus dataset, effectively enhancing its textual linguistic knowledge about sign language. Then, we adopt visual contrastive pretraining to align the visual encoder with a large-scale pretrained text encoder. We propose hierarchical visual encoder that learns a robust word-level intermediate representation that is compatible with LLM token embeddings. Finally, we propose visual language tuning. We freeze pretrained models and employ a lightweight trainable MLP connector. It efficiently maps the pretrained visual language embeddings into the LLM token embedding space, enabling downstream SLT task. Our comprehensive experiments demonstrate that LLaVA-SLT outperforms the state-of-the-art methods. By using extra annotation-free data, it even closes to the gloss-based accuracy.

[Arxiv](https://arxiv.org/abs/2412.16524)