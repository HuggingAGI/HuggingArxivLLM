# 基于一致性感知的短视频平台虚假视频检测

发布时间：2025年04月30日

`LLM应用

理由：该论文主要讨论了如何应用大型语言模型（LLM）来解决短视频平台上的虚假新闻检测问题。论文中提到使用多模态大型语言模型生成伪标签，并结合跨模态一致性诊断和多模态协作诊断等方法，这些都属于LLM的应用层面。因此，该论文应归类为LLM应用。` `短视频` `人工智能`

> Consistency-aware Fake Videos Detection on Short Video Platforms

# 摘要

> 本文致力于解决短视频平台上的虚假新闻检测问题。尽管近年来在这一领域投入了大量研究并取得了显著进展，但由于内容 manipulation 和生成技术的快速发展，现有检测方法的精度仍有待提升。目前主流的跨模态融合策略直接结合原始视频数据与元数据进行分类，但我们的研究发现了一个关键问题：虚假内容中普遍存在的跨模态不一致现象尚未被充分利用作为判别特征。基于这一发现，我们提出了一种全新的检测框架，专注于识别和利用跨模态矛盾作为判别依据。我们的方法由两大核心模块组成：跨模态一致性学习 (CMCL) 和多模态协作诊断 (MMCD)。CMCL 包括伪标签生成 (PLG) 和跨模态一致性诊断 (CMCD)。在 PLG 阶段，我们采用多模态大型语言模型生成伪标签，用于评估跨模态语义一致性。随后，CMCD 通过提取 [CLS] tokens 和计算余弦损失来量化跨模态不一致。MMCD 进一步通过多模态特征融合 (MFF) 和概率分数融合 (PSF) 整合多模态信息。MFF 采用协同注意力机制增强不同模态间的语义交互，同时利用 Transformer 实现全面特征融合。PSF 则进一步整合前一步获得的虚假新闻概率分数。在 FakeSV 和 FakeTT 这两个 established benchmarks 上的大量实验表明，我们的模型在虚假视频检测任务中表现优异。

> This paper focuses to detect the fake news on the short video platforms. While significant research efforts have been devoted to this task with notable progress in recent years, current detection accuracy remains suboptimal due to the rapid evolution of content manipulation and generation technologies. Existing approaches typically employ a cross-modal fusion strategy that directly combines raw video data with metadata inputs before applying a classification layer. However, our empirical observations reveal a critical oversight: manipulated content frequently exhibits inter-modal inconsistencies that could serve as valuable discriminative features, yet remain underutilized in contemporary detection frameworks. Motivated by this insight, we propose a novel detection paradigm that explicitly identifies and leverages cross-modal contradictions as discriminative cues. Our approach consists of two core modules: Cross-modal Consistency Learning (CMCL) and Multi-modal Collaborative Diagnosis (MMCD). CMCL includes Pseudo-label Generation (PLG) and Cross-modal Consistency Diagnosis (CMCD). In PLG, a Multimodal Large Language Model is used to generate pseudo-labels for evaluating cross-modal semantic consistency. Then, CMCD extracts [CLS] tokens and computes cosine loss to quantify cross-modal inconsistencies. MMCD further integrates multimodal features through Multimodal Feature Fusion (MFF) and Probability Scores Fusion (PSF). MFF employs a co-attention mechanism to enhance semantic interactions across different modalities, while a Transformer is utilized for comprehensive feature fusion. Meanwhile, PSF further integrates the fake news probability scores obtained in the previous step. Extensive experiments on established benchmarks (FakeSV and FakeTT) demonstrate our model exhibits outstanding performance in Fake videos detection.

[Arxiv](https://arxiv.org/abs/2504.21495)