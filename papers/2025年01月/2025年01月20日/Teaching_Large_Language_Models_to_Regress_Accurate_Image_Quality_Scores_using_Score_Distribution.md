# 利用分数分布训练大型语言模型，精准回归图像质量评分

发布时间：2025年01月20日

`LLM应用

理由：这篇论文主要讨论了如何利用多模态大型语言模型（MLLMs）来实现精准的图像质量评分回归。虽然涉及到图像质量评估（IQA），但其核心在于利用MLLMs的能力来解决评分回归问题，属于LLM在实际应用中的具体应用场景。因此，将其分类为LLM应用是合适的。` `图像处理` `质量评估`

> Teaching Large Language Models to Regress Accurate Image Quality Scores using Score Distribution

# 摘要

> 随着多模态大型语言模型（MLLMs）的飞速发展，基于MLLM的图像质量评估（IQA）方法在语言描述方面表现亮眼。然而，现有方法在图像质量评分上仍有不足。本研究旨在利用MLLMs实现精准的图像质量评分回归。一个核心挑战在于，质量评分本质上是连续的，通常建模为高斯分布，而MLLMs生成的是离散的标记输出，这种不匹配需要评分离散化。以往方法将平均评分离散化为独热标签，导致信息丢失，无法捕捉图像间关系。我们提出了一种基于分布的方法，将评分分布离散化为软标签，保留了评分分布的特性，实现了高准确性并保持了图像间关系。此外，针对不同IQA数据集分布各异的问题，我们引入了基于Thurstone模型的保真度损失，捕捉数据集内部关系，促进跨数据集联合训练。通过这些设计，我们开发了基于分布的图像质量评分回归模型（DeQA-Score）。多个基准测试表明，DeQA-Score在评分回归上稳定优于基线，且能预测与人类注释高度一致的评分分布。代码和模型权重已在https://depictqa.github.io/deqa-score/发布。

> With the rapid advancement of Multi-modal Large Language Models (MLLMs), MLLM-based Image Quality Assessment (IQA) methods have shown promising performance in linguistic quality description. However, current methods still fall short in accurately scoring image quality. In this work, we aim to leverage MLLMs to regress accurate quality scores. A key challenge is that the quality score is inherently continuous, typically modeled as a Gaussian distribution, whereas MLLMs generate discrete token outputs. This mismatch necessitates score discretization. Previous approaches discretize the mean score into a one-hot label, resulting in information loss and failing to capture inter-image relationships. We propose a distribution-based approach that discretizes the score distribution into a soft label. This method preserves the characteristics of the score distribution, achieving high accuracy and maintaining inter-image relationships. Moreover, to address dataset variation, where different IQA datasets exhibit various distributions, we introduce a fidelity loss based on Thurstone's model. This loss captures intra-dataset relationships, facilitating co-training across multiple IQA datasets. With these designs, we develop the distribution-based Depicted image Quality Assessment model for Score regression (DeQA-Score). Experiments across multiple benchmarks show that DeQA-Score stably outperforms baselines in score regression. Also, DeQA-Score can predict the score distribution that closely aligns with human annotations. Codes and model weights have been released in https://depictqa.github.io/deqa-score/.

[Arxiv](https://arxiv.org/abs/2501.11561)