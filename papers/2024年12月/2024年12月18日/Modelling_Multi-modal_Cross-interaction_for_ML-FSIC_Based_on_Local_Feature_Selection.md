# 基于局部特征选择为 ML-FSIC 构建多模态交叉交互模型

发布时间：2024年12月18日

`其他` `图像分类` `计算机视觉`

> Modelling Multi-modal Cross-interaction for ML-FSIC Based on Local Feature Selection

# 摘要

> 多标签少样本图像分类（ML-FSIC）旨在为图像分配语义标签，其场景是每个标签仅有少量训练示例可用。多标签的关键特点在于图像往往具有多个标签，通常指的是出现在图像不同区域的对象。在基于度量的设定中估计标签原型时，确定哪些区域与哪些标签相关至关重要，然而有限的训练数据和局部特征的噪声特性让这极具挑战。为此，我们提出一种逐步优化标签原型的策略。首先，利用词嵌入来初始化原型，借此利用关于标签含义的先验知识。其次，凭借这些初始原型，运用损失变化测量（LCM）策略从训练图像（即支持集）中选取最有可能代表给定标签的局部特征。最后，通过多模态交叉交互机制聚合这些有代表性的局部特征，构建标签的最终原型，这依然依赖于基于初始词嵌入的原型。在 COCO、PASCAL VOC、NUS-WIDE 和 iMaterialist 上的实验表明，我们的模型显著提升了当前的最优水平。

> The aim of multi-label few-shot image classification (ML-FSIC) is to assign semantic labels to images, in settings where only a small number of training examples are available for each label. A key feature of the multi-label setting is that images often have several labels, which typically refer to objects appearing in different regions of the image. When estimating label prototypes, in a metric-based setting, it is thus important to determine which regions are relevant for which labels, but the limited amount of training data and the noisy nature of local features make this highly challenging. As a solution, we propose a strategy in which label prototypes are gradually refined. First, we initialize the prototypes using word embeddings, which allows us to leverage prior knowledge about the meaning of the labels. Second, taking advantage of these initial prototypes, we then use a Loss Change Measurement~(LCM) strategy to select the local features from the training images (i.e.\ the support set) that are most likely to be representative of a given label. Third, we construct the final prototype of the label by aggregating these representative local features using a multi-modal cross-interaction mechanism, which again relies on the initial word embedding-based prototypes. Experiments on COCO, PASCAL VOC, NUS-WIDE, and iMaterialist show that our model substantially improves the current state-of-the-art.

[Arxiv](https://arxiv.org/abs/2412.13732)