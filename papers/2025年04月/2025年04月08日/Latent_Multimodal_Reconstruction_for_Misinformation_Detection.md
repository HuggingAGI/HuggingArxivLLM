# 潜在多模态重构助力虚假信息检测

发布时间：2025年04月08日

`LLM应用` `虚假信息检测` `视觉-语言模型`

> Latent Multimodal Reconstruction for Misinformation Detection

# 摘要

> 多模态虚假信息，如错误描述的图片，正为数字时代带来日益严峻的挑战。这些虚假信息通过误导图片的来源、背景或含义，给社会带来诸多困扰。为了应对这一问题，研究人员致力于开发多模态虚假信息检测（MMD）方法和相关数据集。然而，受限于大规模标注数据的稀缺性，现有研究多依赖合成数据进行训练，例如通过无上下文的图片-说明配对或对命名实体进行修改（如更改姓名、日期和地点）。但这些方法生成的虚假信息过于简单，无法真实反映现实世界的复杂性，导致检测模型的鲁棒性受到限制。

与此同时，大型视觉-语言模型（LVLMs）在生成多模态合成数据方面的潜力尚未得到充分挖掘。为解决这一问题，我们推出了“MisCaption This!”，一个由LVLM生成的错误描述图片数据集。此外，我们还引入了“潜在多模态重构”（LAMAR），这一网络通过重构真实说明的嵌入，为检测过程提供强有力的辅助信号。为了优化LAMAR，我们尝试了多种训练策略（包括端到端训练和大规模预训练）和集成方法（如直接、掩码、门控和注意力）。实验结果表明，“MisCaption This!”训练出的模型在真实世界虚假信息检测中表现更佳，而LAMAR在NewsCLIPpings和VERITE基准测试中均达到了新的技术水平，充分展现了基于LVLM生成数据和重构方法在多模态虚假信息检测领域的巨大潜力。我们的代码已开源，地址为：https://github.com/stevejpapad/miscaptioned-image-reconstruction

> Multimodal misinformation, such as miscaptioned images, where captions misrepresent an image's origin, context, or meaning, poses a growing challenge in the digital age. To support fact-checkers, researchers have been focusing on creating datasets and developing methods for multimodal misinformation detection (MMD). Due to the scarcity of large-scale annotated MMD datasets, recent studies leverage synthetic training data via out-of-context image-caption pairs or named entity manipulations; altering names, dates, and locations. However, these approaches often produce simplistic misinformation that fails to reflect real-world complexity, limiting the robustness of detection models trained on them. Meanwhile, despite recent advancements, Large Vision-Language Models (LVLMs) remain underutilized for generating diverse, realistic synthetic training data for MMD. To address this gap, we introduce "MisCaption This!", a training dataset comprising LVLM-generated miscaptioned images. Additionally, we introduce "Latent Multimodal Reconstruction" (LAMAR), a network trained to reconstruct the embeddings of truthful captions, providing a strong auxiliary signal to the detection process. To optimize LAMAR, we explore different training strategies (end-to-end training and large-scale pre-training) and integration approaches (direct, mask, gate, and attention). Extensive experiments show that models trained on "MisCaption This!" generalize better on real-world misinformation, while LAMAR sets new state-of-the-art on both NewsCLIPpings and VERITE benchmarks; highlighting the potential of LVLM-generated data and reconstruction-based approaches for advancing MMD. We release our code at: https://github.com/stevejpapad/miscaptioned-image-reconstruction

[Arxiv](https://arxiv.org/abs/2504.06010)