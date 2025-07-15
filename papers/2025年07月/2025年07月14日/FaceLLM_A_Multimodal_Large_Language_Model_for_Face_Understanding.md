# FaceLLM：面向面部理解的多模态大型语言模型

发布时间：2025年07月14日

`LLM应用

理由：这篇论文专注于将多模态大语言模型应用于特定领域的视觉任务，特别是面部图像分析。通过提出新的学习方法和构建专用数据集，展示了LLM在特定任务中的应用潜力。因此，归类为LLM应用。` `面部图像分析` `多模态AI`

> FaceLLM: A Multimodal Large Language Model for Face Understanding

# 摘要

> 多模态大语言模型（MLLMs）在视觉-语言任务中表现优异，但现有模型主要基于通用数据集训练，难以有效处理特定领域的视觉线索，如面部图像分析。由于缺乏大规模标注的面部图像-文本数据，MLLMs在面部结构、表情、情感和人口统计特征等细节理解方面仍显不足。为解决这一问题，我们推出了FaceLLM——首个专注于面部图像理解的多模态大语言模型。我们创新性地提出了一种弱监督学习管道，借助ChatGPT的属性感知提示功能，基于FairFace数据集生成高质量的问题-答案对。由此构建的FairFaceGPT语料库涵盖了表情、姿势、皮肤纹理和法医信息等丰富属性。实验结果表明，FaceLLM显著提升了MLLMs在以面部为中心的任务上的性能，达到了当前最优水平。这项研究不仅展示了通过语言模型进行合成监督构建领域专用MLLMs的潜力，更为可信、以人为本的多模态AI系统树立了标杆。FairFaceGPT数据集和预训练的FaceLLM模型现已公开发布。

> Multimodal large language models (MLLMs) have shown remarkable performance in vision-language tasks. However, existing MLLMs are primarily trained on generic datasets, limiting their ability to reason on domain-specific visual cues such as those in facial images. In particular, tasks that require detailed understanding of facial structure, expression, emotion, and demographic features remain underexplored by MLLMs due to the lack of large-scale annotated face image-text datasets. In this work, we introduce FaceLLM, a multimodal large language model trained specifically for facial image understanding. To construct the training data, we propose a novel weakly supervised pipeline that uses ChatGPT with attribute-aware prompts to generate high-quality question-answer pairs based on images from the FairFace dataset. The resulting corpus, called FairFaceGPT, covers a diverse set of attributes including expression, pose, skin texture, and forensic information. Our experiments demonstrate that FaceLLM improves the performance of MLLMs on various face-centric tasks and achieves state-of-the-art performance. This work highlights the potential of synthetic supervision via language models for building domain-specialized MLLMs, and sets a precedent for trustworthy, human-centric multimodal AI systems. FairFaceGPT dataset and pretrained FaceLLM models are publicly available in the project page.

[Arxiv](https://arxiv.org/abs/2507.10300)