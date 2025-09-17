# 超越人工错位：语义协同多模态操纵的检测与锚定

发布时间：2025年09月16日

`RAG` `媒体与娱乐`

> Beyond Artificial Misalignment: Detecting and Grounding Semantic-Coordinated Multimodal Manipulations

# 摘要

> 多模态数据中被篡改内容的检测与定位已成为媒体取证领域亟待解决的关键难题。现有基准虽展现了技术进展，却存在对齐偏差问题，难以真实反映现实世界的篡改模式：实际攻击通常会保持跨模态的语义一致性，而当前数据集反而人为破坏跨模态对齐，制造易于检测的异常。为弥合这一差距，我们率先提出语义协同篡改检测——即视觉编辑与语义一致的文本描述被系统地配对。我们的方法首先构建首个语义对齐多模态篡改（SAMM）数据集，通过两阶段流程构建而成：1）先应用最先进的图像篡改技术，再生成符合上下文逻辑的文本描述以强化视觉欺骗效果。在此基础上，我们提出检索增强型篡改检测与定位（RamDG）框架。该框架首先利用外部知识库检索上下文证据，将其作为辅助文本，与输入一同通过我们的图像伪造定位和深度篡改检测模块进行编码，以追踪所有篡改痕迹。大量实验表明，我们的框架性能显著优于现有方法，在SAMM数据集上的检测准确率较最先进方法提升了2.06%。相关数据集与代码已在https://github.com/shen8424/SAMM-RamDG-CAP公开。

> The detection and grounding of manipulated content in multimodal data has emerged as a critical challenge in media forensics. While existing benchmarks demonstrate technical progress, they suffer from misalignment artifacts that poorly reflect real-world manipulation patterns: practical attacks typically maintain semantic consistency across modalities, whereas current datasets artificially disrupt cross-modal alignment, creating easily detectable anomalies. To bridge this gap, we pioneer the detection of semantically-coordinated manipulations where visual edits are systematically paired with semantically consistent textual descriptions. Our approach begins with constructing the first Semantic-Aligned Multimodal Manipulation (SAMM) dataset, generated through a two-stage pipeline: 1) applying state-of-the-art image manipulations, followed by 2) generation of contextually-plausible textual narratives that reinforce the visual deception. Building on this foundation, we propose a Retrieval-Augmented Manipulation Detection and Grounding (RamDG) framework. RamDG commences by harnessing external knowledge repositories to retrieve contextual evidence, which serves as the auxiliary texts and encoded together with the inputs through our image forgery grounding and deep manipulation detection modules to trace all manipulations. Extensive experiments demonstrate our framework significantly outperforms existing methods, achieving 2.06\% higher detection accuracy on SAMM compared to state-of-the-art approaches. The dataset and code are publicly available at https://github.com/shen8424/SAMM-RamDG-CAP.

[Arxiv](https://arxiv.org/abs/2509.12653)