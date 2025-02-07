# 视觉与语言参考提示融入SAM，实现少样本分割

发布时间：2025年02月02日

`LLM应用

理由：这篇论文主要讨论了如何通过结合视觉和语言信息来改进少样本分割模型（VLP-SAM），并利用多模态视觉语言模型将带有视觉语言信息的提示嵌入输入到 SAM 中。虽然 SAM 本身是一个分割模型，但论文的核心在于如何利用语言信息（文本标签）来增强模型的性能，这与大型语言模型（LLM）在多模态任务中的应用密切相关。因此，这篇论文应归类为 **LLM应用**。` `计算机视觉` `图像分割`

> Vision and Language Reference Prompt into SAM for Few-shot Segmentation

# 摘要

> # 摘要
Segment Anything Model (SAM) 是一个强大的大规模分割模型，能够通过灵活的提示实现零-shot 分割。然而，SAM 需要用户为每个目标图像提供提示，并且不会为分割结果附加标签信息。少样本分割模型通过将标注的参考图像作为提示输入到 SAM 中，解决了这些问题，能够在无需用户提示的情况下分割目标图像中的特定对象。然而，之前的基于 SAM 的少样本分割模型仅使用标注的参考图像作为提示，由于缺乏足够的参考信息，导致准确性受限。本文提出了一种新颖的少样本分割模型 VLP-SAM，它不仅输入图像，还输入语言作为参考信息，从而充分利用参考图像的视觉信息和文本标签的语义信息。VLP-SAM 结构简单且可扩展，具有最少的可学习参数，通过多模态视觉语言模型将带有视觉语言信息的提示嵌入输入到 SAM 中。我们在 PASCAL-5i 和 COCO-20i 数据集上进行了实验，结果表明 VLP-SAM 在少样本分割任务中表现出色，大幅超越了之前的最先进模型（在 mIoU 上分别提高了 6.3% 和 9.5%）。此外，VLP-SAM 在未见对象上也展示了强大的泛化能力。代码已开源：https://github.com/kosukesakurai1/VLP-SAM。

> Segment Anything Model (SAM) represents a large-scale segmentation model that enables powerful zero-shot capabilities with flexible prompts. While SAM can segment any object in zero-shot, it requires user-provided prompts for each target image and does not attach any label information to masks. Few-shot segmentation models addressed these issues by inputting annotated reference images as prompts to SAM and can segment specific objects in target images without user-provided prompts. Previous SAM-based few-shot segmentation models only use annotated reference images as prompts, resulting in limited accuracy due to a lack of reference information. In this paper, we propose a novel few-shot segmentation model, Vision and Language reference Prompt into SAM (VLP-SAM), that utilizes the visual information of the reference images and the semantic information of the text labels by inputting not only images but also language as reference information. In particular, VLP-SAM is a simple and scalable structure with minimal learnable parameters, which inputs prompt embeddings with vision-language information into SAM using a multimodal vision-language model. To demonstrate the effectiveness of VLP-SAM, we conducted experiments on the PASCAL-5i and COCO-20i datasets, and achieved high performance in the few-shot segmentation task, outperforming the previous state-of-the-art model by a large margin (6.3% and 9.5% in mIoU, respectively). Furthermore, VLP-SAM demonstrates its generality in unseen objects that are not included in the training data. Our code is available at https://github.com/kosukesakurai1/VLP-SAM.

[Arxiv](https://arxiv.org/abs/2502.00719)