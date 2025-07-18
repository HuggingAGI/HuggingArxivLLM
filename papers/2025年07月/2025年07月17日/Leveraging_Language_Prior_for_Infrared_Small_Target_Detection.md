# 基于语言先验的红外小目标检测

发布时间：2025年07月17日

`LLM应用` `军事侦察` `航空航天`

> Leveraging Language Prior for Infrared Small Target Detection

# 摘要

> # 红外小目标检测新突破：多模态框架提升检测精度  
IRSTD（红外小目标检测）技术在复杂红外背景下精准识别微小目标，对军事侦察、航空航天等领域具有重要意义。然而，由于目标尺寸微小且在数据集中分布稀疏，检测任务极具挑战性。尽管现有方法在IRSTD领域取得显著进展，但其局限性在于仅依赖单一图像模态。  
近年来，深度学习和大型视觉-语言模型在视觉识别领域表现出色。本研究提出了一种创新的多模态IRSTD框架，通过引入语言先验知识，有效提升小目标检测性能。我们利用语言引导注意力机制，结合文本描述与图像数据，为模型提供更丰富的信息支持。  
借助先进的GPT-4视觉模型，我们生成高质量的文本描述，精准定位红外图像中的小目标。通过精心设计的提示工程，进一步提升检测准确性。针对现有IRSTD数据集缺乏多模态信息的不足，我们构建了一个全新的多模态红外数据集，扩展了IRSTD-1k和NUDT-SIRST等流行数据集。  
通过广泛实验和全面消融研究，我们验证了所提方法的有效性。实验结果表明，与现有最优方法相比，我们的方法在NUAA-SIRST子集上IoU、nIoU、Pd和Fa指标分别提升9.74%、13.02%、1.25%和67.87%，在LangIR数据集的IRSTD-1k子集上分别提升4.41%、2.04%、2.01%和113.43%，实现了显著性能提升。


> IRSTD (InfraRed Small Target Detection) detects small targets in infrared blurry backgrounds and is essential for various applications. The detection task is challenging due to the small size of the targets and their sparse distribution in infrared small target datasets. Although existing IRSTD methods and datasets have led to significant advancements, they are limited by their reliance solely on the image modality. Recent advances in deep learning and large vision-language models have shown remarkable performance in various visual recognition tasks. In this work, we propose a novel multimodal IRSTD framework that incorporates language priors to guide small target detection. We leverage language-guided attention weights derived from the language prior to enhance the model's ability for IRSTD, presenting a novel approach that combines textual information with image data to improve IRSTD capabilities. Utilizing the state-of-the-art GPT-4 vision model, we generate text descriptions that provide the locations of small targets in infrared images, employing careful prompt engineering to ensure improved accuracy. Due to the absence of multimodal IR datasets, existing IRSTD methods rely solely on image data. To address this shortcoming, we have curated a multimodal infrared dataset that includes both image and text modalities for small target detection, expanding upon the popular IRSTD-1k and NUDT-SIRST datasets. We validate the effectiveness of our approach through extensive experiments and comprehensive ablation studies. The results demonstrate significant improvements over the state-of-the-art method, with relative percentage differences of 9.74%, 13.02%, 1.25%, and 67.87% in IoU, nIoU, Pd, and Fa on the NUAA-SIRST subset, and 4.41%, 2.04%, 2.01%, and 113.43% on the IRSTD-1k subset of the LangIR dataset, respectively.

[Arxiv](https://arxiv.org/abs/2507.13113)