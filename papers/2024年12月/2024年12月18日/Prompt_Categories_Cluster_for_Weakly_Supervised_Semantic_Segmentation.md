# 用于弱监督语义分割的提示类别簇

发布时间：2024年12月18日

`LLM应用` `计算机视觉` `图像分割`

> Prompt Categories Cluster for Weakly Supervised Semantic Segmentation

# 摘要

> 弱监督语义分割（WSSS）借助图像级标签，因其成本效益显著而备受瞩目。以往的方法主要强化类间差异，以规避可能引发错误激活的类语义模糊。然而，它们却忽视了相似类别间某些共享信息的积极作用。同一簇内的类别存在一些相似特征。让模型识别这些特征，能进一步化解这些类别间的语义模糊。为有效识别和利用这一共享信息，本文引入了一种新颖的 WSSS 框架——提示类别聚类（PCC）。具体来说，我们探究了大型语言模型（LLMs）通过提示获取类别聚类的能力。这些聚类有效地体现了类别之间的内在联系。将这种关系信息融入训练网络，我们的模型能够更好地学习类别间的隐藏关联。实验结果表明了我们方法的有效性，显示其能提升在 PASCAL VOC 2012 数据集上的性能，并超越 WSSS 中现有的先进方法。

> Weakly Supervised Semantic Segmentation (WSSS), which leverages image-level labels, has garnered significant attention due to its cost-effectiveness. The previous methods mainly strengthen the inter-class differences to avoid class semantic ambiguity which may lead to erroneous activation. However, they overlook the positive function of some shared information between similar classes. Categories within the same cluster share some similar features. Allowing the model to recognize these features can further relieve the semantic ambiguity between these classes. To effectively identify and utilize this shared information, in this paper, we introduce a novel WSSS framework called Prompt Categories Clustering (PCC). Specifically, we explore the ability of Large Language Models (LLMs) to derive category clusters through prompts. These clusters effectively represent the intrinsic relationships between categories. By integrating this relational information into the training network, our model is able to better learn the hidden connections between categories. Experimental results demonstrate the effectiveness of our approach, showing its ability to enhance performance on the PASCAL VOC 2012 dataset and surpass existing state-of-the-art methods in WSSS.

[Arxiv](https://arxiv.org/abs/2412.13823)