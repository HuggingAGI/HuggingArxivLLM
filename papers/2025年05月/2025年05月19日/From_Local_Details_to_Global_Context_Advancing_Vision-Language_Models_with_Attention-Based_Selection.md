# 从局部细节迈向全局上下文：基于注意力机制的选择推动视觉语言模型的发展

发布时间：2025年05月19日

`LLM应用

理由：这篇论文探讨了视觉语言模型（VLMs）在零样本任务中的应用，特别是如何通过视觉增强技术和注意力引导选择方法（ABS）来提升模型的性能。虽然涉及模型改进，但核心是实际应用中的优化，属于应用层面的创新。` `计算机视觉` `图像分类`

> From Local Details to Global Context: Advancing Vision-Language Models with Attention-Based Selection

# 摘要

> 预训练的视觉语言模型（VLMs），如CLIP，在零样本任务中表现卓越。先前研究表明，视觉增强技术（如随机裁剪）在与LLM生成的细粒度描述对齐时发挥关键作用，通过多视图信息显著提升零样本性能。然而，随机增强带来的背景噪声和局部细节过关注问题，影响了全局语义理解。为解决这一难题，我们提出了一种从局部到全局的注意力引导选择方法（ABS）。该方法通过注意力引导的裁剪在图像和特征空间中进行特征选择，补充全局语义信息。同时，我们引入软匹配技术，优化描述对齐效果。ABS在分布外泛化和零样本分类任务中表现优异，且无需训练，甚至可与微调和测试时适应方法相媲美。我们的代码已在GitHub上开源，欢迎访问\href{https://github.com/BIT-DA/ABS}{	extcolor{darkgreen}{https://github.com/BIT-DA/ABS}}获取。

> Pretrained vision-language models (VLMs), e.g., CLIP, demonstrate impressive zero-shot capabilities on downstream tasks. Prior research highlights the crucial role of visual augmentation techniques, like random cropping, in alignment with fine-grained class descriptions generated by large language models (LLMs), significantly enhancing zero-shot performance by incorporating multi-view information. However, the inherent randomness of these augmentations can inevitably introduce background artifacts and cause models to overly focus on local details, compromising global semantic understanding. To address these issues, we propose an \textbf{A}ttention-\textbf{B}ased \textbf{S}election (\textbf{ABS}) method from local details to global context, which applies attention-guided cropping in both raw images and feature space, supplement global semantic information through strategic feature selection. Additionally, we introduce a soft matching technique to effectively filter LLM descriptions for better alignment. \textbf{ABS} achieves state-of-the-art performance on out-of-distribution generalization and zero-shot classification tasks. Notably, \textbf{ABS} is training-free and even rivals few-shot and test-time adaptation methods. Our code is available at \href{https://github.com/BIT-DA/ABS}{\textcolor{darkgreen}{https://github.com/BIT-DA/ABS}}.

[Arxiv](https://arxiv.org/abs/2505.13233)