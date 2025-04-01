# FakeScope：大型多模态专家模型，助力透明的AI生成图像取证

发布时间：2025年03月31日

`LLM应用` `图像生成` `数字取证`

> FakeScope: Large Multimodal Expert Model for Transparent AI-Generated Image Forensics

# 摘要

> 生成式 AI 的快速发展如同一把双刃剑：它不仅激发了前所未有的创造力，同时也为生成极具迷惑性的虚假内容提供了便利，这对社会信任构成了威胁。随着图像生成技术的日益精进，辨别合成图像已不再仅仅是简单的二元判断：我们需要采用可解释且具备上下文感知能力的方法，以增强检测的可信度和透明度。然而，现有的检测模型大多专注于分类任务，对图像真实性的解释力十分有限。在本研究中，我们提出了 FakeScope，一个专为 AI 生成图像取证设计的专家级多模态模型 (LMM)，该模型不仅能够以高精度识别 AI 合成图像，还能提供丰富、可解释且基于查询的取证见解。我们首先构建了 FakeChain 数据集，其中包含了基于视觉线索的语言真实性推理，该数据集是通过一种全新的人机协作框架开发而成。以此为基础，我们进一步推出了 FakeInstruct，这是目前规模最大的多模态指令微调数据集，包含 200 万条专为提升 LMMs 取证意识而设计的视觉指令。FakeScope 在闭合域和开放域的取证场景中均达到了当前最优的性能水平。它不仅能精准识别合成图像，还能提供连贯且富有洞见的解释，支持对细粒度伪造属性的自由讨论，并提出切实可行的增强策略。值得注意的是，尽管 FakeScope 的训练仅基于定性硬标签，但它通过我们提出的基于令牌的概率估计策略，在检测任务中展现出了卓越的零样本定量能力。此外，FakeScope 还具备强大的泛化能力和实际场景适应性，确保其在现实世界中的广泛应用。

> The rapid and unrestrained advancement of generative artificial intelligence (AI) presents a double-edged sword: while enabling unprecedented creativity, it also facilitates the generation of highly convincing deceptive content, undermining societal trust. As image generation techniques become increasingly sophisticated, detecting synthetic images is no longer just a binary task: it necessitates interpretable, context-aware methodologies that enhance trustworthiness and transparency. However, existing detection models primarily focus on classification, offering limited explanatory insights into image authenticity. In this work, we propose FakeScope, an expert multimodal model (LMM) tailored for AI-generated image forensics, which not only identifies AI-synthetic images with high accuracy but also provides rich, interpretable, and query-driven forensic insights. We first construct FakeChain dataset that contains linguistic authenticity reasoning based on visual trace evidence, developed through a novel human-machine collaborative framework. Building upon it, we further present FakeInstruct, the largest multimodal instruction tuning dataset containing 2 million visual instructions tailored to enhance forensic awareness in LMMs. FakeScope achieves state-of-the-art performance in both closed-ended and open-ended forensic scenarios. It can distinguish synthetic images with high accuracy while offering coherent and insightful explanations, free-form discussions on fine-grained forgery attributes, and actionable enhancement strategies. Notably, despite being trained exclusively on qualitative hard labels, FakeScope demonstrates remarkable zero-shot quantitative capability on detection, enabled by our proposed token-based probability estimation strategy. Furthermore, FakeScope exhibits strong generalization and in-the-wild ability, ensuring its applicability in real-world scenarios.

[Arxiv](https://arxiv.org/abs/2503.24267)