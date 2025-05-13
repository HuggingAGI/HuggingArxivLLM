# # 基于单模态微调的批量扩增方法在多模态学习中的应用

发布时间：2025年05月10日

`LLM应用` `医学成像`

> Batch Augmentation with Unimodal Fine-tuning for Multimodal Learning

# 摘要

> 本文提出了一种结合批量增强技术和单模态微调的方法，用于从超声图像及其相关临床文本信息中检测胎儿器官。我们还建议在多模态训练前，通过研究过的医学数据对初始层进行预训练。首先，我们采用单模态图像数据集部分进行批量增强的迁移初始化。这一步调整了医学数据的初始层权重。然后，我们对图像进行批量增强处理，利用具有微调初始层的神经网络（NNs）提取特征。同时，我们从图像描述中提取信息，并将其与从图像中获得的特征结合，用于训练头部层。我们编写了一个数据加载器脚本，用于加载多模态数据，并结合现有的单模态图像增强技术和批量增强技术处理多模态数据。数据加载器为每个批次引入新的随机增强，以获得良好的泛化性能。我们研究了FPU23超声和UPMC Food-101多模态数据集。采用所提方法训练的多模态大型语言模型（LLM）在研究的方法中表现最佳。在UPMC Food-101数据集上，我们达到了接近最先进（SOTA）的性能。我们将在以下仓库中分享所提方法与传统方法的脚本：github.com/dipuk0506/multimodal

> This paper proposes batch augmentation with unimodal fine-tuning to detect the fetus's organs from ultrasound images and associated clinical textual information. We also prescribe pre-training initial layers with investigated medical data before the multimodal training. At first, we apply a transferred initialization with the unimodal image portion of the dataset with batch augmentation. This step adjusts the initial layer weights for medical data. Then, we apply neural networks (NNs) with fine-tuned initial layers to images in batches with batch augmentation to obtain features. We also extract information from descriptions of images. We combine this information with features obtained from images to train the head layer. We write a dataloader script to load the multimodal data and use existing unimodal image augmentation techniques with batch augmentation for the multimodal data. The dataloader brings a new random augmentation for each batch to get a good generalization. We investigate the FPU23 ultrasound and UPMC Food-101 multimodal datasets. The multimodal large language model (LLM) with the proposed training provides the best results among the investigated methods. We receive near state-of-the-art (SOTA) performance on the UPMC Food-101 dataset. We share the scripts of the proposed method with traditional counterparts at the following repository: github.com/dipuk0506/multimodal

[Arxiv](https://arxiv.org/abs/2505.06592)