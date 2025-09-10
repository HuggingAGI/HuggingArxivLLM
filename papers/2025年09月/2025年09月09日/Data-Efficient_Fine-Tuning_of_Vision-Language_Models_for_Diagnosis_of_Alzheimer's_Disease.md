# 面向阿尔茨海默病诊断的视觉语言模型数据高效微调

发布时间：2025年09月09日

`LLM应用` `医疗健康`

> Data-Efficient Fine-Tuning of Vision-Language Models for Diagnosis of Alzheimer's Disease

# 摘要

> 医学视觉语言模型（Med-VLMs）在报告生成、视觉问答等任务中表现亮眼，但仍存在诸多局限。其中最突出的问题是：未充分利用患者元数据，且缺乏临床诊断知识的融合。此外，现有模型大多需基于大规模2D图文对从头训练或微调，耗费大量计算资源；同时，因缺乏结构信息，它们在3D医学影像上的效果也常受限制。为填补这些空白，我们提出一种数据高效的微调流程，将基于3D CT的Med-VLMs适配于3D MRI，并验证其在阿尔茨海默病（AD）诊断中的应用。该系统包含两项核心创新：其一，将结构化元数据转化为合成报告，通过丰富文本输入提升图文对齐效果；其二，新增一个辅助token，经训练用于预测简易精神状态检查（MMSE）评分——这是衡量认知功能的常用临床指标，与AD严重程度密切相关——从而为微调提供额外监督信号。我们对图像和文本模态均采用轻量级提示调优，仅用1500张训练图像就在两个AD数据集上取得了当前最优性能，超越了使用10000张图像微调的现有方法。相关代码将在论文发表后公开。

> Medical vision-language models (Med-VLMs) have shown impressive results in tasks such as report generation and visual question answering, but they still face several limitations. Most notably, they underutilize patient metadata and lack integration of clinical diagnostic knowledge. Moreover, most existing models are typically trained from scratch or fine-tuned on large-scale 2D image-text pairs, requiring extensive computational resources, and their effectiveness on 3D medical imaging is often limited due to the absence of structural information. To address these gaps, we propose a data-efficient fine-tuning pipeline to adapt 3D CT-based Med-VLMs for 3D MRI and demonstrate its application in Alzheimer's disease (AD) diagnosis. Our system introduces two key innovations. First, we convert structured metadata into synthetic reports, enriching textual input for improved image-text alignment. Second, we add an auxiliary token trained to predict the mini-mental state examination (MMSE) score, a widely used clinical measure of cognitive function that correlates with AD severity. This provides additional supervision for fine-tuning. Applying lightweight prompt tuning to both image and text modalities, our approach achieves state-of-the-art performance on two AD datasets using 1,500 training images, outperforming existing methods fine-tuned on 10,000 images. Code will be released upon publication.

[Arxiv](https://arxiv.org/abs/2509.07613)