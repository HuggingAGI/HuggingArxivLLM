# MAKE: 基于多维度知识增强的视觉-语言预训练模型，实现零样本皮肤评估

发布时间：2025年05月14日

`LLM应用

理由：这篇论文探讨了视觉-语言预训练模型在皮肤病诊断中的应用，属于大型语言模型的实际应用。` `多模态`

> MAKE: Multi-Aspect Knowledge-Enhanced Vision-Language Pretraining for Zero-shot Dermatological Assessment

# 摘要

> 皮肤病诊断是一个多模态诊断难题，需要将视觉特征与专业临床知识相结合。尽管视觉-语言预训练（VLP）推动了医学AI的发展，但在皮肤病领域，其效果受限于文本长度限制和缺乏结构化文本的问题。本文提出了一种名为MAKE的多维度知识增强视觉-语言预训练框架，专为零样本皮肤病任务设计。考虑到全面的皮肤病描述需要多种知识维度的支持，而这些维度往往超出标准文本限制，我们的框架创新性地引入了以下三个关键组件：(1) 一种多维度对比学习策略，通过大型语言模型将临床叙述分解为知识增强的子文本；(2) 一种细粒度对齐机制，将子说明与诊断相关的图像特征精准连接；(3) 一种诊断引导的加权方案，根据临床意义优先级自适应地调整不同子说明的重要性。通过在403,563对皮肤病图像-文本数据上进行预训练，MAKE在零样本皮肤疾病分类、概念标注和跨模态检索任务的八个数据集上显著超越了现有的VLP模型。我们的代码将在https://github.com/SiyuanYan1/MAKE公开发布。
    

> Dermatological diagnosis represents a complex multimodal challenge that requires integrating visual features with specialized clinical knowledge. While vision-language pretraining (VLP) has advanced medical AI, its effectiveness in dermatology is limited by text length constraints and the lack of structured texts. In this paper, we introduce MAKE, a Multi-Aspect Knowledge-Enhanced vision-language pretraining framework for zero-shot dermatological tasks. Recognizing that comprehensive dermatological descriptions require multiple knowledge aspects that exceed standard text constraints, our framework introduces: (1) a multi-aspect contrastive learning strategy that decomposes clinical narratives into knowledge-enhanced sub-texts through large language models, (2) a fine-grained alignment mechanism that connects subcaptions with diagnostically relevant image features, and (3) a diagnosis-guided weighting scheme that adaptively prioritizes different sub-captions based on clinical significance prior. Through pretraining on 403,563 dermatological image-text pairs collected from education resources, MAKE significantly outperforms state-of-the-art VLP models on eight datasets across zero-shot skin disease classification, concept annotation, and cross-modal retrieval tasks. Our code will be made publicly available at https: //github.com/SiyuanYan1/MAKE.

[Arxiv](https://arxiv.org/abs/2505.09372)