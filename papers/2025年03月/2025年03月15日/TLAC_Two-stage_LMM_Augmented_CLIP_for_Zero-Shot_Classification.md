# TLAC：双阶段LMM增强CLIP实现零样本分类

发布时间：2025年03月15日

`LLM应用` `图像分类` `跨模态学习`

> TLAC: Two-stage LMM Augmented CLIP for Zero-Shot Classification

# 摘要

> 对比语言-图像预训练（CLIP）在图像分类任务中展现了令人瞩目的零样本性能。然而，现有最先进的方法通常依赖提示学习和基于适配器的微调等技术来优化CLIP的表现。微调的必要性极大限制了CLIP对新数据集和领域的适应能力，同时也带来了巨大的时间和计算资源消耗。为了解决这一限制，我们提出了两种简单而有效的无需训练方法：单阶段大跨模态模型增强CLIP（SLAC）和双阶段大跨模态模型增强CLIP（TLAC）。这些方法利用强大的大跨模态模型（LMM），如Gemini，来提升图像分类性能。

我们的方法充分利用了预训练LMM的能力，无需额外训练即可轻松适应多样化的数据集和领域。具体来说，我们通过提示LMM识别图像中的物体，然后利用CLIP文本编码器识别与LLM预测物体语义相似度最高的数据集类别来确定图像类别。我们在11个基准数据集到新数据集上进行了全面评估，其中9个数据集的准确率优于现有方法，包括ImageNet、SUN397和Caltech101等基准测试。同时，我们保持了严格的无需训练范式。

实验结果表明，我们的整体准确率达到83.44%，比之前的最先进少样本方法高出6.75%。在13个数据集上，我们的方法实现了83.6%的平均准确率，相比之前73.9%的无需训练方法最先进水平提升了9.7%。此外，我们的方法在领域泛化方面也取得了显著进步，在ImageNetV2上比之前少样本方法提升了3.6%，ImageNet-S提升了16.96%，ImageNet-R提升了12.59%。


> Contrastive Language-Image Pretraining (CLIP) has shown impressive zero-shot performance on image classification. However, state-of-the-art methods often rely on fine-tuning techniques like prompt learning and adapter-based tuning to optimize CLIP's performance. The necessity for fine-tuning significantly limits CLIP's adaptability to novel datasets and domains. This requirement mandates substantial time and computational resources for each new dataset. To overcome this limitation, we introduce simple yet effective training-free approaches, Single-stage LMM Augmented CLIP (SLAC) and Two-stage LMM Augmented CLIP (TLAC), that leverages powerful Large Multimodal Models (LMMs), such as Gemini, for image classification. The proposed methods leverages the capabilities of pre-trained LMMs, allowing for seamless adaptation to diverse datasets and domains without the need for additional training. Our approaches involve prompting the LMM to identify objects within an image. Subsequently, the CLIP text encoder determines the image class by identifying the dataset class with the highest semantic similarity to the LLM predicted object. We evaluated our models on 11 base-to-novel datasets and they achieved superior accuracy on 9 of these, including benchmarks like ImageNet, SUN397 and Caltech101, while maintaining a strictly training-free paradigm. Our overall accuracy of 83.44% surpasses the previous state-of-the-art few-shot methods by a margin of 6.75%. Our method achieved 83.6% average accuracy across 13 datasets, a 9.7% improvement over the previous 73.9% state-of-the-art for training-free approaches. Our method improves domain generalization, with a 3.6% gain on ImageNetV2, 16.96% on ImageNet-S, and 12.59% on ImageNet-R, over prior few-shot methods.

[Arxiv](https://arxiv.org/abs/2503.12206)