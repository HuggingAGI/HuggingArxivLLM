# Mosaic3D: 开放词汇3D分割的基础数据集与模型

发布时间：2025年02月04日

`其他

理由：这篇论文主要讨论的是3D场景理解和开放词汇的3D语义和实例分割问题，涉及数据生成管道、训练框架、3D编码器和掩码解码器等技术。虽然论文中提到了视觉-语言模型，但整体内容与Agent、RAG、LLM应用或LLM理论没有直接关联。因此，将其分类为“其他”更为合适。` `计算机视觉` `3D建模`

> Mosaic3D: Foundation Dataset and Model for Open-Vocabulary 3D Segmentation

# 摘要

> 我们提出了一种创新的数据生成管道和训练框架，用于解决开放词汇的3D场景理解问题。该方法聚焦于三个关键训练需求：精确的3D区域分割、详尽的文本描述以及大规模数据集。通过整合先进的开放词汇图像分割模型和区域感知的视觉-语言模型，我们构建了一个自动化管道，能够生成高质量的3D掩码-文本对。将该管道应用于多个3D场景数据集后，我们创建了Mosaic3D-5.6M，这是一个包含超过30K标注场景和5.6M掩码-文本对的数据集，规模远超现有数据集。在此基础上，我们提出了Mosaic3D，这是一个结合了对比学习训练的3D编码器和轻量级掩码解码器的基础模型，专为开放词汇的3D语义和实例分割设计。我们的方法在ScanNet200、Matterport3D和ScanNet++等开放词汇3D语义和实例分割任务中取得了领先成果，并通过消融研究验证了大规模训练数据的显著效果。

> We tackle open-vocabulary 3D scene understanding by introducing a novel data generation pipeline and training framework. Our method addresses three critical requirements for effective training: precise 3D region segmentation, comprehensive textual descriptions, and sufficient dataset scale. By leveraging state-of-the-art open-vocabulary image segmentation models and region-aware Vision-Language Models, we develop an automatic pipeline that generates high-quality 3D mask-text pairs. Applying this pipeline to multiple 3D scene datasets, we create Mosaic3D-5.6M, a dataset of over 30K annotated scenes with 5.6M mask-text pairs, significantly larger than existing datasets. Building upon this data, we propose Mosaic3D, a foundation model combining a 3D encoder trained with contrastive learning and a lightweight mask decoder for open-vocabulary 3D semantic and instance segmentation. Our approach achieves state-of-the-art results on open-vocabulary 3D semantic and instance segmentation tasks including ScanNet200, Matterport3D, and ScanNet++, with ablation studies validating the effectiveness of our large-scale training data.

[Arxiv](https://arxiv.org/abs/2502.02548)