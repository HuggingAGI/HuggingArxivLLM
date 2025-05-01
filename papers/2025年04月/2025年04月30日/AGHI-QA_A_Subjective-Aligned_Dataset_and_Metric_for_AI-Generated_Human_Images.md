# AGHI-QA：一个与主观体验高度契合的数据集及评估指标，专为AI生成的人类图像设计。

发布时间：2025年04月30日

`其他` `图像生成` `图像质量评估`

> AGHI-QA: A Subjective-Aligned Dataset and Metric for AI-Generated Human Images

# 摘要

> 文本到图像（T2I）生成技术的迅猛发展激发了人们对评估生成图像质量的浓厚兴趣，推动了多种通用T2I输出质量评估方法的诞生。然而，现有的图像质量评估（IQA）方法仅能提供全局质量评分，无法为结构复杂的目标（如人类形象）提供精细的感知评价。这一难题在AI生成的人类图像（AGHIs）中尤为突出，因其常出现解剖结构和纹理失真。为解决这一难题，我们推出了AGHI-QA，这是首个专为评估AGHI质量打造的大型基准数据集。该数据集包含400个精心设计的文本提示通过10个先进T2I模型生成的4,000张图像。我们开展了一项系统性主观研究，收集了多维度标注，涵盖感知质量评分、文本-图像对应评分、可见与失真身体部位标签。基于AGHI-QA，我们从多个维度剖析了当前T2I方法在生成人类图像方面的优势与不足。此外，我们提出了AGHI-Assessor，这一创新质量指标整合了大型多模态模型（LMM）与特定领域的人类特征，实现精准质量预测，并能识别AGHIs中可见与失真的身体部位。大量实验结果表明，AGHI-Assessor展现了卓越的性能，在多维度质量评估方面远超现有IQA方法，并在检测AGHIs中的结构失真方面超越了领先的LMMs。

> The rapid development of text-to-image (T2I) generation approaches has attracted extensive interest in evaluating the quality of generated images, leading to the development of various quality assessment methods for general-purpose T2I outputs. However, existing image quality assessment (IQA) methods are limited to providing global quality scores, failing to deliver fine-grained perceptual evaluations for structurally complex subjects like humans, which is a critical challenge considering the frequent anatomical and textural distortions in AI-generated human images (AGHIs). To address this gap, we introduce AGHI-QA, the first large-scale benchmark specifically designed for quality assessment of AGHIs. The dataset comprises 4,000 images generated from 400 carefully crafted text prompts using 10 state of-the-art T2I models. We conduct a systematic subjective study to collect multidimensional annotations, including perceptual quality scores, text-image correspondence scores, visible and distorted body part labels. Based on AGHI-QA, we evaluate the strengths and weaknesses of current T2I methods in generating human images from multiple dimensions. Furthermore, we propose AGHI-Assessor, a novel quality metric that integrates the large multimodal model (LMM) with domain-specific human features for precise quality prediction and identification of visible and distorted body parts in AGHIs. Extensive experimental results demonstrate that AGHI-Assessor showcases state-of-the-art performance, significantly outperforming existing IQA methods in multidimensional quality assessment and surpassing leading LMMs in detecting structural distortions in AGHIs.

[Arxiv](https://arxiv.org/abs/2504.21308)