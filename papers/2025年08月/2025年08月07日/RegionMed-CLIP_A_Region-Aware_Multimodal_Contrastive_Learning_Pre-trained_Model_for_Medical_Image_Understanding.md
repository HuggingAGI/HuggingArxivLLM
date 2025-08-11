# RegionMed-CLIP: 区域感知多模态对比学习预训练模型，专为医学图像理解而设计

发布时间：2025年08月07日

`LLM应用` `计算机视觉`

> RegionMed-CLIP: A Region-Aware Multimodal Contrastive Learning Pre-trained Model for Medical Image Understanding

# 摘要

> 医学图像理解在实现自动化诊断和数据驱动的临床决策支持方面具有重要作用。然而，其发展面临两大核心挑战：高质量标注医学数据的稀缺性，以及对全局图像特征的过度依赖，这往往会忽视一些细微却具有临床意义的病理性区域。为了解决这些问题，我们提出了RegionMed-CLIP，一个基于区域感知的多模态对比学习框架，它巧妙地结合了局部病理信号和整体语义表征。该方法的核心是一个创新的感兴趣区域（ROI）处理器，它能够自适应地融合细粒度区域特征与全局上下文，并通过一种渐进式训练策略来优化多模态对齐效果。为了实现大规模的区域级表征学习，我们构建了MedRegion-500k，一个包含丰富区域标注和多层级临床描述的综合医学图像-文本语料库。在图像-文本检索、零样本分类和视觉问答等任务上的大量实验表明，RegionMed-CLIP在性能上显著超越了现有的先进视觉语言模型。我们的研究结果突显了区域感知对比预训练的重要性，并将RegionMed-CLIP定位为推动多模态医学图像理解发展的坚实基础。

> Medical image understanding plays a crucial role in enabling automated diagnosis and data-driven clinical decision support. However, its progress is impeded by two primary challenges: the limited availability of high-quality annotated medical data and an overreliance on global image features, which often miss subtle but clinically significant pathological regions. To address these issues, we introduce RegionMed-CLIP, a region-aware multimodal contrastive learning framework that explicitly incorporates localized pathological signals along with holistic semantic representations. The core of our method is an innovative region-of-interest (ROI) processor that adaptively integrates fine-grained regional features with the global context, supported by a progressive training strategy that enhances hierarchical multimodal alignment. To enable large-scale region-level representation learning, we construct MedRegion-500k, a comprehensive medical image-text corpus that features extensive regional annotations and multilevel clinical descriptions. Extensive experiments on image-text retrieval, zero-shot classification, and visual question answering tasks demonstrate that RegionMed-CLIP consistently exceeds state-of-the-art vision language models by a wide margin. Our results highlight the critical importance of region-aware contrastive pre-training and position RegionMed-CLIP as a robust foundation for advancing multimodal medical image understanding.

[Arxiv](https://arxiv.org/abs/2508.05244)