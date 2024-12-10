# 用于开放词汇多标签识别的类别自适应跨模态语义细化与转移

发布时间：2024年12月08日

`LLM应用` `计算机视觉` `多标签识别`

> Category-Adaptive Cross-Modal Semantic Refinement and Transfer for Open-Vocabulary Multi-Label Recognition

# 摘要

> 得益于 CLIP 的泛化能力，近期的视觉语言预训练（VLP）模型在捕捉日常图像中的几乎任何视觉概念方面表现出色。然而，在开放词汇设定中存在未见过的类别，现有算法难以有效捕捉类别间强烈的语义关联，致使在开放词汇多标签识别（OV-MLR）中表现欠佳。另外，不同对象类别中判别区域数量的显著差异与当前方法采用的固定数量补丁匹配不匹配，引入了干扰视觉线索，阻碍了对目标语义的准确捕捉。为应对这些挑战，我们提出了新颖的类别自适应跨模态语义细化和转移（C$^2$SRT）框架，以类别自适应的方式探寻每个类别内以及不同类别间的语义关联。该框架由两个互补模块构成，即类别内语义细化（ISR）模块和类别间语义转移（IST）模块。具体来说，ISR 模块借助 VLP 模型的跨模态知识，自适应地找出最能代表目标类别语义的一组局部判别区域。IST 模块利用 LLMs 的常识能力，为目标类别自适应地发现一组最相关的类别，构建类别自适应相关图，并将语义知识从相关的已见类别转移至未见类别。在 OV-MLR 基准上的大量实验清晰表明，所提出的 C$^2$SRT 框架优于当前的先进算法。

> Benefiting from the generalization capability of CLIP, recent vision language pre-training (VLP) models have demonstrated an impressive ability to capture virtually any visual concept in daily images. However, due to the presence of unseen categories in open-vocabulary settings, existing algorithms struggle to effectively capture strong semantic correlations between categories, resulting in sub-optimal performance on the open-vocabulary multi-label recognition (OV-MLR). Furthermore, the substantial variation in the number of discriminative areas across diverse object categories is misaligned with the fixed-number patch matching used in current methods, introducing noisy visual cues that hinder the accurate capture of target semantics. To tackle these challenges, we propose a novel category-adaptive cross-modal semantic refinement and transfer (C$^2$SRT) framework to explore the semantic correlation both within each category and across different categories, in a category-adaptive manner. The proposed framework consists of two complementary modules, i.e., intra-category semantic refinement (ISR) module and inter-category semantic transfer (IST) module. Specifically, the ISR module leverages the cross-modal knowledge of the VLP model to adaptively find a set of local discriminative regions that best represent the semantics of the target category. The IST module adaptively discovers a set of most correlated categories for a target category by utilizing the commonsense capabilities of LLMs to construct a category-adaptive correlation graph and transfers semantic knowledge from the correlated seen categories to unseen ones. Extensive experiments on OV-MLR benchmarks clearly demonstrate that the proposed C$^2$SRT framework outperforms current state-of-the-art algorithms.

[Arxiv](https://arxiv.org/abs/2412.06190)