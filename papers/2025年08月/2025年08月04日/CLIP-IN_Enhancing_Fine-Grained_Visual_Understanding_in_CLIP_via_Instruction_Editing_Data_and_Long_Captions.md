# CLIP-IN：增强CLIP中的细致入微视觉理解，借助指令编辑数据与长描述

发布时间：2025年08月04日

`LLM应用` `计算机视觉` `多模态`

> CLIP-IN: Enhancing Fine-Grained Visual Understanding in CLIP via Instruction Editing Data and Long Captions

# 摘要

> 尽管像CLIP这样的视觉语言模型（VLM）在视觉与语言的对齐方面表现出色，但它们在细粒度视觉理解方面的潜力仍未完全释放。我们提出了一种名为CLIP-IN的创新框架，通过两大核心技术显著提升了CLIP的细粒度感知能力。首先，CLIP-IN巧妙地利用图像 manipulation 领域的 instruction-editing 数据集，将其转化为硬负图像-文本对的独特资源，并结合对称硬负对比损失，帮助模型精准捕捉细微的视觉语义差异。其次，CLIP-IN引入长描述性 captions，借助旋转位置编码技术，深入挖掘常被标准CLIP忽略的丰富语义上下文。实验结果表明，CLIP-IN在MMVP基准和多项细粒度视觉识别任务中表现优异，同时在更广泛的分类和检索任务中保持了稳健的零样本性能。更重要的是，将CLIP-IN的视觉表征融入多模态大语言模型，不仅显著降低了视觉幻觉的发生，还大幅提升了模型的推理能力。这项研究充分展现了将指令驱动的对比学习与详尽描述信息相结合的巨大潜力，为提升视觉语言模型的细粒度理解能力开辟了新的道路。

> Despite the success of Vision-Language Models (VLMs) like CLIP in aligning vision and language, their proficiency in detailed, fine-grained visual comprehension remains a key challenge. We present CLIP-IN, a novel framework that bolsters CLIP's fine-grained perception through two core innovations. Firstly, we leverage instruction-editing datasets, originally designed for image manipulation, as a unique source of hard negative image-text pairs. Coupled with a symmetric hard negative contrastive loss, this enables the model to effectively distinguish subtle visual-semantic differences. Secondly, CLIP-IN incorporates long descriptive captions, utilizing rotary positional encodings to capture rich semantic context often missed by standard CLIP. Our experiments demonstrate that CLIP-IN achieves substantial gains on the MMVP benchmark and various fine-grained visual recognition tasks, without compromising robust zero-shot performance on broader classification and retrieval tasks. Critically, integrating CLIP-IN's visual representations into Multimodal Large Language Models significantly reduces visual hallucinations and enhances reasoning abilities. This work underscores the considerable potential of synergizing targeted, instruction-based contrastive learning with comprehensive descriptive information to elevate the fine-grained understanding of VLMs.

[Arxiv](https://arxiv.org/abs/2508.02329)