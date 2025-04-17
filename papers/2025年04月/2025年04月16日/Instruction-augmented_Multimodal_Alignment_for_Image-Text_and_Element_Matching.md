# 基于指令增强的多模态对齐，实现图像-文本与元素匹配

发布时间：2025年04月16日

`LLM应用

理由：这篇论文讨论了如何利用多模态大型语言模型来评估图像-文本对齐，属于大型语言模型的实际应用。` `计算机视觉` `人工智能`

> Instruction-augmented Multimodal Alignment for Image-Text and Element Matching

# 摘要

> 文本到图像（T2I）生成模型的快速发展使得评估生成图像与文本描述的语义对齐成为重要研究课题。现有方法，包括基于视觉问答（VQA）的方法，仍难以实现细粒度评估和图像-文本对齐的精确量化。本文提出了一种改进的评估方法——基于指令增强的多模态对齐评估方法（iMatch），通过微调多模态大型语言模型来评估图像-文本语义对齐。我们引入了四种创新的增强策略：首先，QAlign策略创建了一个精确的概率映射，将多模态大型语言模型的离散得分转换为连续的匹配得分。其次，验证集增强策略利用模型预测的伪标签扩展训练数据，提升模型的泛化性能。第三，元素增强策略整合了元素类别标签，以细化模型对图像-文本匹配的理解。第四，图像增强策略采用随机光照等技术，增强模型的鲁棒性。此外，我们还提出了提示类型增强和得分扰动策略，以进一步提升元素评估的准确性。实验结果表明，iMatch方法显著超越现有方法，证实了其有效性和实用价值。此外，我们的iMatch在CVPR NTIRE 2025文本到图像生成模型质量评估比赛的图像-文本对齐任务中荣获第一名。

> With the rapid advancement of text-to-image (T2I) generation models, assessing the semantic alignment between generated images and text descriptions has become a significant research challenge. Current methods, including those based on Visual Question Answering (VQA), still struggle with fine-grained assessments and precise quantification of image-text alignment. This paper presents an improved evaluation method named Instruction-augmented Multimodal Alignment for Image-Text and Element Matching (iMatch), which evaluates image-text semantic alignment by fine-tuning multimodal large language models. We introduce four innovative augmentation strategies: First, the QAlign strategy creates a precise probabilistic mapping to convert discrete scores from multimodal large language models into continuous matching scores. Second, a validation set augmentation strategy uses pseudo-labels from model predictions to expand training data, boosting the model's generalization performance. Third, an element augmentation strategy integrates element category labels to refine the model's understanding of image-text matching. Fourth, an image augmentation strategy employs techniques like random lighting to increase the model's robustness. Additionally, we propose prompt type augmentation and score perturbation strategies to further enhance the accuracy of element assessments. Our experimental results show that the iMatch method significantly surpasses existing methods, confirming its effectiveness and practical value. Furthermore, our iMatch won first place in the CVPR NTIRE 2025 Text to Image Generation Model Quality Assessment - Track 1 Image-Text Alignment.

[Arxiv](https://arxiv.org/abs/2504.12018)