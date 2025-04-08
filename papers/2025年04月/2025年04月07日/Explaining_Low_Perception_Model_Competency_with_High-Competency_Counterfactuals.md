# Explaining Low Perception Model Competency with High-Competency Counterfactuals
用高能力反事实分析揭示低感知模型能力

发布时间：2025年04月07日

`LLM应用

这篇论文探讨了如何利用反事实图像来解释图像分类模型的低模型能力，并通过多模态大型语言模型（MLLMs）生成语言解释。研究展示了反事实图像在提升模型解释能力方面的实用性，属于LLM的应用领域。` `计算机视觉` `人工智能`

> Explaining Low Perception Model Competency with High-Competency Counterfactuals

# 摘要

> 目前，解释图像分类模型如何生成决策的方法层出不穷，但关于分类器为何对预测缺乏信心的研究却凤毛麟角。由于分类器可能失去信心的原因多种多样，因此该模型不仅要指示其不确定性的水平，还要解释其为何不确定，这一点非常有价值。反事实图像已被用于可视化可以对图像进行哪些更改以生成不同的分类决策。在这项工作中，我们探索了使用反事实来解释低模型能力——一种衡量信心的预测不确定性的一般形式。为此，我们开发了五种新颖的方法来生成高能力的反事实图像，分别是图像梯度下降（IGD）、特征梯度下降（FGD）、自动编码器重构（Reco）、潜在梯度下降（LGD）和潜在最近邻（LNN）。我们在包含六种已知导致低模型能力原因的图像的两个独特数据集上评估了这些方法，并发现Reco、LGD和LNN是最有前途的反事实生成方法。我们进一步评估了这三种方法如何被预训练的多模态大型语言模型（MLLMs）用于生成低模型能力的语言解释。我们发现，在语言模型查询中包含反事实图像极大地提高了模型生成准确解释的能力，从而证明了反事实图像在解释低感知模型能力方面的实用性。


> There exist many methods to explain how an image classification model generates its decision, but very little work has explored methods to explain why a classifier might lack confidence in its prediction. As there are various reasons the classifier might lose confidence, it would be valuable for this model to not only indicate its level of uncertainty but also explain why it is uncertain. Counterfactual images have been used to visualize changes that could be made to an image to generate a different classification decision. In this work, we explore the use of counterfactuals to offer an explanation for low model competency--a generalized form of predictive uncertainty that measures confidence. Toward this end, we develop five novel methods to generate high-competency counterfactual images, namely Image Gradient Descent (IGD), Feature Gradient Descent (FGD), Autoencoder Reconstruction (Reco), Latent Gradient Descent (LGD), and Latent Nearest Neighbors (LNN). We evaluate these methods across two unique datasets containing images with six known causes for low model competency and find Reco, LGD, and LNN to be the most promising methods for counterfactual generation. We further evaluate how these three methods can be utilized by pre-trained Multimodal Large Language Models (MLLMs) to generate language explanations for low model competency. We find that the inclusion of a counterfactual image in the language model query greatly increases the ability of the model to generate an accurate explanation for the cause of low model competency, thus demonstrating the utility of counterfactual images in explaining low perception model competency.

[Arxiv](https://arxiv.org/abs/2504.05254)