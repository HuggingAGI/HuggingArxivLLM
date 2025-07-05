# 通过语言引导和表示对齐实现领域泛化的提示解耦

发布时间：2025年07月02日

`LLM应用` `计算机视觉` `人工智能`

> Prompt Disentanglement via Language Guidance and Representation Alignment for Domain Generalization

# 摘要

> 领域泛化（DG）的目标是开发一个通用性强的模型，使其能够有效应对未见过的目标领域。值得注意的是，近期预训练视觉基础模型（VFM）如CLIP的进展，已显示出显著提升深度学习模型泛化能力的潜力。尽管基于VFM的领域提示调优在DG中受到越来越多的关注，但如何有效设计能够解耦不同领域间不变特征的提示，仍然是一个关键挑战。本文提出利用VFM的可控且灵活的语言提示来应对这一挑战。由于VFM的文本模态在本质上更容易解耦，我们引入了一种基于文本特征引导的视觉提示调优新框架。该框架首先通过大型语言模型（LLM）自动解耦文本提示，然后在解耦的文本特征指导下学习领域不变的视觉表征。然而，仅依赖语言来引导视觉特征解耦存在局限性，因为视觉特征有时可能过于复杂或微妙，无法完全通过描述性文本捕捉。为了解决这一问题，我们引入了最显式表征对齐（WERA），它通过引入一组额外的抽象提示来扩展文本引导的视觉提示。这些提示通过风格化图像增强增加源域的多样性，同时对齐约束确保视觉表征在原始和增强分布之间保持一致。在PACS、VLCS、OfficeHome、DomainNet和TerraInc等主要DG数据集上的实验表明，我们提出的方法优于现有的DG方法。

> Domain Generalization (DG) seeks to develop a versatile model capable of performing effectively on unseen target domains. Notably, recent advances in pre-trained Visual Foundation Models (VFMs), such as CLIP, have demonstrated considerable potential in enhancing the generalization capabilities of deep learning models. Despite the increasing attention toward VFM-based domain prompt tuning within DG, the effective design of prompts capable of disentangling invariant features across diverse domains remains a critical challenge. In this paper, we propose addressing this challenge by leveraging the controllable and flexible language prompt of the VFM. Noting that the text modality of VFMs is naturally easier to disentangle, we introduce a novel framework for text feature-guided visual prompt tuning. This framework first automatically disentangles the text prompt using a large language model (LLM) and then learns domain-invariant visual representation guided by the disentangled text feature. However, relying solely on language to guide visual feature disentanglement has limitations, as visual features can sometimes be too complex or nuanced to be fully captured by descriptive text. To address this, we introduce Worst Explicit Representation Alignment (WERA), which extends text-guided visual prompts by incorporating an additional set of abstract prompts. These prompts enhance source domain diversity through stylized image augmentations, while alignment constraints ensure that visual representations remain consistent across both the original and augmented distributions. Experiments conducted on major DG datasets, including PACS, VLCS, OfficeHome, DomainNet, and TerraInc, demonstrate that our proposed method outperforms state-of-the-art DG methods.

[Arxiv](https://arxiv.org/abs/2507.02288)