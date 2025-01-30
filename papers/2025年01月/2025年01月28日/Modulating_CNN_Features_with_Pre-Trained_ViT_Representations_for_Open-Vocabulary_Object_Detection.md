# 利用预训练的ViT表示来增强CNN特征，实现开放词汇对象检测

发布时间：2025年01月28日

`其他

理由：这篇论文主要讨论的是视觉语言模型（VLM）和开放词汇目标检测器的设计，特别是通过双分支骨干网络（VMCNet）来提升检测性能。虽然涉及了预训练模型（如ViT），但核心内容并不直接涉及大型语言模型（LLM）的应用、理论、RAG（Retrieval-Augmented Generation）或Agent技术。因此，将其分类为“其他”更为合适。` `计算机视觉` `目标检测`

> Modulating CNN Features with Pre-Trained ViT Representations for Open-Vocabulary Object Detection

# 摘要

> 得益于大规模图像-文本对比训练，CLIP等预训练视觉语言模型（VLM）展现出强大的开放词汇识别能力。现有的大多数开放词汇目标检测器都试图利用预训练的VLM来获取生成性表示。F-ViT采用预训练的视觉编码器作为骨干网络，并在训练过程中冻结它。然而，冻结的骨干网络无法通过标注数据增强表示能力。为此，我们提出了一种新颖的双分支骨干网络设计——ViT-特征调制多尺度卷积网络（VMCNet）。VMCNet包含一个可训练的卷积分支、一个冻结的预训练ViT分支和一个特征调制模块。可训练的CNN分支可以通过标注数据进行优化，而冻结的ViT分支则保留了大规模预训练带来的表示能力。特征调制模块则利用ViT分支的表示来调制多尺度CNN特征。通过这种混合结构，检测器更容易发现新类别。在两个主流基准测试中，我们的方法显著提升了新类别的检测性能，超越了基线模型。在OV-COCO数据集上，使用ViT-B/16和ViT-L/14的VMCNet分别达到了44.3 AP$_{50}^{\mathrm{novel}}$和48.5 AP$_{50}^{\mathrm{novel}}$。在OV-LVIS数据集上，VMCNet使用ViT-B/16和ViT-L/14分别取得了27.8和38.4 mAP$_{r}$的成绩。

> Owing to large-scale image-text contrastive training, pre-trained vision language model (VLM) like CLIP shows superior open-vocabulary recognition ability. Most existing open-vocabulary object detectors attempt to utilize the pre-trained VLM to attain generative representation. F-ViT uses the pre-trained visual encoder as the backbone network and freezes it during training. However, the frozen backbone doesn't benefit from the labeled data to strengthen the representation. Therefore, we propose a novel two-branch backbone network design, named as ViT-Feature-Modulated Multi-Scale Convolutional network (VMCNet). VMCNet consists of a trainable convolutional branch, a frozen pre-trained ViT branch and a feature modulation module. The trainable CNN branch could be optimized with labeled data while the frozen pre-trained ViT branch could keep the representation ability derived from large-scale pre-training. Then, the proposed feature modulation module could modulate the multi-scale CNN features with the representations from ViT branch. With the proposed mixed structure, detector is more likely to discover novel categories. Evaluated on two popular benchmarks, our method boosts the detection performance on novel category and outperforms the baseline. On OV-COCO, the proposed method achieves 44.3 AP$_{50}^{\mathrm{novel}}$ with ViT-B/16 and 48.5 AP$_{50}^{\mathrm{novel}}$ with ViT-L/14. On OV-LVIS, VMCNet with ViT-B/16 and ViT-L/14 reaches 27.8 and 38.4 mAP$_{r}$.

[Arxiv](https://arxiv.org/abs/2501.16981)