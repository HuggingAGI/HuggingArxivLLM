# MGHFT: 多粒度层次化融合Transformer在跨模态表情包情感识别中的应用

发布时间：2025年07月24日

`LLM应用

理由：这篇论文提出了一种基于多模态大语言模型的多粒度分层融合Transformer（MGHFT），用于解决贴纸情感理解的挑战。通过结合文本和视觉信息，设计了分层融合策略和多视图解释器，展示了在实际应用中的有效性。这属于LLM的应用层面创新。` `情感分析` `计算机视觉`

> MGHFT: Multi-Granularity Hierarchical Fusion Transformer for Cross-Modal Sticker Emotion Recognition

# 摘要

> 尽管预训练的文本-视觉模型在视觉特征提取方面表现出色，但贴纸情感理解仍具挑战性，主要由于其依赖背景知识和风格线索等多视图信息。为解决这一难题，我们提出了一种基于多模态大语言模型的多粒度分层融合Transformer（MGHFT），并设计了多视图贴纸解释器。受人类从多角度解析贴纸情感的启发，我们首先利用多模态大语言模型通过多视图描述提供丰富文本上下文来解释贴纸。接着，我们设计了一种分层融合策略，结合金字塔视觉Transformer，在多个阶段提取全局和局部贴纸特征。通过对比学习和注意力机制，将文本特征注入视觉主干的不同阶段，增强文本指导下全局与局部视觉语义的融合。最后，引入文本引导的融合注意力机制，有效整合多模态特征，提升语义理解。在两个公开贴纸情感数据集上的大量实验表明，MGHFT显著超越现有方法，实现更高准确性和更细粒度情感识别。与最佳预训练视觉模型相比，我们的MGHFT在F1分数上提升了5.4%，准确率上提升了4.0%。代码已发布于https://github.com/cccccj-03/MGHFT_ACMMM2025。

> Although pre-trained visual models with text have demonstrated strong capabilities in visual feature extraction, sticker emotion understanding remains challenging due to its reliance on multi-view information, such as background knowledge and stylistic cues. To address this, we propose a novel multi-granularity hierarchical fusion transformer (MGHFT), with a multi-view sticker interpreter based on Multimodal Large Language Models. Specifically, inspired by the human ability to interpret sticker emotions from multiple views, we first use Multimodal Large Language Models to interpret stickers by providing rich textual context via multi-view descriptions. Then, we design a hierarchical fusion strategy to fuse the textual context into visual understanding, which builds upon a pyramid visual transformer to extract both global and local sticker features at multiple stages. Through contrastive learning and attention mechanisms, textual features are injected at different stages of the visual backbone, enhancing the fusion of global- and local-granularity visual semantics with textual guidance. Finally, we introduce a text-guided fusion attention mechanism to effectively integrate the overall multimodal features, enhancing semantic understanding. Extensive experiments on 2 public sticker emotion datasets demonstrate that MGHFT significantly outperforms existing sticker emotion recognition approaches, achieving higher accuracy and more fine-grained emotion recognition. Compared to the best pre-trained visual models, our MGHFT also obtains an obvious improvement, 5.4% on F1 and 4.0% on accuracy. The code is released at https://github.com/cccccj-03/MGHFT_ACMMM2025.

[Arxiv](https://arxiv.org/abs/2507.18929)