# 大规模细粒度视觉-语言预训练助力CT图像理解提升

发布时间：2025年01月24日

`LLM应用

理由：这篇论文主要讨论了如何利用对比语言-图像预训练（CLIP）技术来开发一个细粒度的视觉-语言模型（fVLM），用于医学图像解读。虽然论文中提到了对比学习等技术，但其核心应用场景是利用语言模型（CLIP）来提升医学图像解读的效率和准确性。因此，这篇论文属于LLM应用领域，特别是将LLM技术应用于医学图像解读的场景。` `放射学`

> Large-scale and Fine-grained Vision-language Pre-training for Enhanced CT Image Understanding

# 摘要

> # 摘要
人工智能（AI）在提升医学图像解读和诊断的效率和准确性方面展现出巨大潜力。然而，构建通用的AI模型需要大规模数据和全面标注，这在医疗环境中往往难以实现。最近的研究利用放射学报告作为医学图像的高质量监督，通过对比语言-图像预训练（CLIP）开发了语言信息模型用于放射学图像解读。然而，这些方法通常将整个图像与报告进行对比，忽略了图像区域与报告句子之间的局部关联，可能影响模型性能和互操作性。本文提出了一种细粒度的视觉-语言模型（fVLM），用于解剖级别的CT图像解读。具体而言，我们明确地将CT图像的解剖区域与放射学报告中的相应描述进行匹配，并对每个解剖结构单独进行对比预训练。细粒度对齐面临的主要挑战是假阴性问题，主要源于大量解剖级别的健康样本和相似的病变异常。为此，我们提出识别正常和异常样本的假阴性，并从患者级别到疾病感知配对校准对比学习。我们整理了迄今为止最大的CT数据集，包含69,086名患者的影像和报告数据，并对15个主要解剖结构的54个重要疾病诊断任务进行了全面评估。实验结果表明，fVLM在通用医学图像解读方面具有显著潜力。在零样本分类任务中，我们在54个诊断任务中平均AUC达到81.3%，分别比CLIP和监督方法高出12.9%和8.0%。

> Artificial intelligence (AI) shows great potential in assisting radiologists to improve the efficiency and accuracy of medical image interpretation and diagnosis. However, a versatile AI model requires large-scale data and comprehensive annotations, which are often impractical in medical settings. Recent studies leverage radiology reports as a naturally high-quality supervision for medical images, using contrastive language-image pre-training (CLIP) to develop language-informed models for radiological image interpretation. Nonetheless, these approaches typically contrast entire images with reports, neglecting the local associations between imaging regions and report sentences, which may undermine model performance and interoperability. In this paper, we propose a fine-grained vision-language model (fVLM) for anatomy-level CT image interpretation. Specifically, we explicitly match anatomical regions of CT images with corresponding descriptions in radiology reports and perform contrastive pre-training for each anatomy individually. Fine-grained alignment, however, faces considerable false-negative challenges, mainly from the abundance of anatomy-level healthy samples and similarly diseased abnormalities. To tackle this issue, we propose identifying false negatives of both normal and abnormal samples and calibrating contrastive learning from patient-level to disease-aware pairing. We curated the largest CT dataset to date, comprising imaging and report data from 69,086 patients, and conducted a comprehensive evaluation of 54 major and important disease diagnosis tasks across 15 main anatomies. Experimental results demonstrate the substantial potential of fVLM in versatile medical image interpretation. In the zero-shot classification task, we achieved an average AUC of 81.3% on 54 diagnosis tasks, surpassing CLIP and supervised methods by 12.9% and 8.0%, respectively.

[Arxiv](https://arxiv.org/abs/2501.14548)