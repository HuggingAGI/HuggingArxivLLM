# 嵌入即可满足需求！借助免训练嵌入分析达成高性能医学图像分类

发布时间：2024年12月12日

`LLM应用` `医学成像`

> Embeddings are all you need! Achieving High Performance Medical Image Classification through Training-Free Embedding Analysis

# 摘要

> 开发用于医学成像的人工智能（AI）和机器学习（ML）模型，往往要在大型数据集上开展大量训练和测试，会耗费大量计算时间、能源及资源。因此，需要更高效的方法，既能达成相当甚至更优的诊断性能，又不会带来资源负担。我们探究了用基于嵌入的方法替代传统训练流程的可行性，这种方法借助了医学图像简洁且语义丰富的表示。运用预训练的基础模型——具体来说，像 ResNet 这样的卷积神经网络（CNN）以及像对比语言 - 图像预训练（CLIP）这样的多模态模型——我们为多类别分类任务生成了图像嵌入。接着对这些嵌入应用简单的线性分类器。该方法在视网膜图像、乳腺 X 光摄影、皮肤镜图像和胸部 X 光片等多种医学成像模式中得到评估。并将其性能与通过传统方法训练和测试的基准模型作比较。在各种医学成像模式的多类别分类任务中，基于嵌入的模型在接收者操作特征曲线（AUC-ROC）下的面积得分比基准高出多达 87%。特别要指出的是，CLIP 嵌入模型取得了最高的 AUC-ROC 得分，在大幅降低计算需求的同时展现出卓越的分类性能。我们的研究表明，利用预训练基础模型的嵌入能够有效取代医学图像分析中传统的、资源密集型的训练和测试流程。这种基于嵌入的方法为图像分割、分类和预测提供了更高效的选择，有望加快 AI 技术在临床实践中的融合。

> Developing artificial intelligence (AI) and machine learning (ML) models for medical imaging typically involves extensive training and testing on large datasets, consuming significant computational time, energy, and resources. There is a need for more efficient methods that can achieve comparable or superior diagnostic performance without the associated resource burden. We investigated the feasibility of replacing conventional training procedures with an embedding-based approach that leverages concise and semantically meaningful representations of medical images. Using pre-trained foundational models-specifically, convolutional neural networks (CNN) like ResNet and multimodal models like Contrastive Language-Image Pre-training (CLIP)-we generated image embeddings for multi-class classification tasks. Simple linear classifiers were then applied to these embeddings. The approach was evaluated across diverse medical imaging modalities, including retinal images, mammography, dermatoscopic images, and chest radiographs. Performance was compared to benchmark models trained and tested using traditional methods. The embedding-based models surpassed the benchmark area under the receiver operating characteristic curve (AUC-ROC) scores by up to 87 percentage in multi-class classification tasks across the various medical imaging modalities. Notably, CLIP embedding models achieved the highest AUC-ROC scores, demonstrating superior classification performance while significantly reducing computational demands. Our study indicates that leveraging embeddings from pre-trained foundational models can effectively replace conventional, resource-intensive training and testing procedures in medical image analysis. This embedding-based approach offers a more efficient alternative for image segmentation, classification, and prediction, potentially accelerating AI technology integration into clinical practice.

[Arxiv](https://arxiv.org/abs/2412.09445)