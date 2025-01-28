# CLISC：利用增强CAM技术，将CLIP与SAM结合，实现无监督脑肿瘤分割

发布时间：2025年01月27日

`LLM应用

理由：这篇论文主要讨论了利用视觉语言模型（如CLIP）和Segment Anything Model（SAM）来进行脑肿瘤的无监督分割。虽然论文中提到的模型（如CLIP和SAM）可以被视为基础模型或大型语言模型（LLM）的应用，但整体研究重点在于如何利用这些模型来解决具体的医学图像分割问题。因此，这篇论文更适合归类为“LLM应用”，因为它展示了LLM在实际应用场景中的具体使用方法和效果。` `图像处理`

> CLISC: Bridging clip and sam by enhanced cam for unsupervised brain tumor segmentation

# 摘要

> # 摘要
脑肿瘤分割在肿瘤诊断中至关重要，但现有深度学习方法依赖大量标注图像，成本高昂。无监督分割虽能避免人工标注，但性能有限。本研究提出了一种基于基础模型的无监督分割方法，包含三个步骤：(1) 利用视觉语言模型（如CLIP）生成图像级伪标签，训练分类网络，并通过类激活映射（CAM）提取感兴趣区域（ROIs），结合自适应掩码增强ROI识别。(2) 使用ROIs生成边界框和点提示，供Segment Anything Model（SAM）生成分割伪标签。(3) 用SAM生成的伪标签训练3D分割网络，并通过SAM输出与网络预测的相似性自学习过滤低质量伪标签。在BraTS2020数据集上，我们的方法平均Dice相似性评分（DSC）达85.60%，比五种顶尖无监督方法高出10个百分点以上，且优于直接使用SAM进行零-shot推理，性能接近全监督学习。

> Brain tumor segmentation is important for diagnosis of the tumor, and current deep-learning methods rely on a large set of annotated images for training, with high annotation costs. Unsupervised segmentation is promising to avoid human annotations while the performance is often limited. In this study, we present a novel unsupervised segmentation approach that leverages the capabilities of foundation models, and it consists of three main steps: (1) A vision-language model (i.e., CLIP) is employed to obtain image-level pseudo-labels for training a classification network. Class Activation Mapping (CAM) is then employed to extract Regions of Interest (ROIs), where an adaptive masking-based data augmentation is used to enhance ROI identification.(2) The ROIs are used to generate bounding box and point prompts for the Segment Anything Model (SAM) to obtain segmentation pseudo-labels. (3) A 3D segmentation network is trained with the SAM-derived pseudo-labels, where low-quality pseudo-labels are filtered out in a self-learning process based on the similarity between the SAM's output and the network's prediction. Evaluation on the BraTS2020 dataset demonstrates that our approach obtained an average Dice Similarity Score (DSC) of 85.60%, outperforming five state-of-the-art unsupervised segmentation methods by more than 10 percentage points. Besides, our approach outperforms directly using SAM for zero-shot inference, and its performance is close to fully supervised learning.

[Arxiv](https://arxiv.org/abs/2501.16246)