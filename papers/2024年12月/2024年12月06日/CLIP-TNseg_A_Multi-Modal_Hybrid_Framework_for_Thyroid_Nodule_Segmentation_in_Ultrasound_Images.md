# CLIP-TNseg：一种用于超声图像中甲状腺结节分割的多模态混合框架

发布时间：2024年12月06日

`其他` `图像分割`

> CLIP-TNseg: A Multi-Modal Hybrid Framework for Thyroid Nodule Segmentation in Ultrasound Images

# 摘要

> 在超声图像中对甲状腺结节进行分割对于准确诊断和制定治疗计划极为关键。然而，现有的方法在分割精准度、可解释性以及泛化能力方面遭遇挑战，从而影响了其性能表现。本文提出了一个新颖的框架——CLIP-TNseg，通过将多模态大型模型与神经网络架构相融合来应对这些问题。CLIP-TNseg 包含两个主要分支：粗粒度分支从冻结的 CLIP 模型中提取高级语义特征，细粒度分支利用 U-Net 风格的残差块捕捉细粒度特征。这些特征由预测头融合处理，从而生成精确的分割图。CLIP-TNseg 借助粗粒度分支通过文本和高级视觉特征增强语义理解，细粒度分支则细化空间细节，实现精准且稳健的分割。在公共数据集和我们新收集的数据集上开展的大量实验表明其性能卓越。我们的代码和原始数据集可在 https://github.com/jayxjsun/CLIP-TNseg 获取。

> Thyroid nodule segmentation in ultrasound images is crucial for accurate diagnosis and treatment planning. However, existing methods face challenges in segmentation accuracy, interpretability, and generalization, which hinder their performance. This letter proposes a novel framework, CLIP-TNseg, to address these issues by integrating a multimodal large model with a neural network architecture. CLIP-TNseg consists of two main branches: the Coarse-grained Branch, which extracts high-level semantic features from a frozen CLIP model, and the Fine-grained Branch, which captures fine-grained features using U-Net style residual blocks. These features are fused and processed by the prediction head to generate precise segmentation maps. CLIP-TNseg leverages the Coarse-grained Branch to enhance semantic understanding through textual and high-level visual features, while the Fine-grained Branch refines spatial details, enabling precise and robust segmentation. Extensive experiments on public and our newly collected datasets demonstrate its competitive performance. Our code and the original dataset are available at https://github.com/jayxjsun/CLIP-TNseg.

[Arxiv](https://arxiv.org/abs/2412.05530)