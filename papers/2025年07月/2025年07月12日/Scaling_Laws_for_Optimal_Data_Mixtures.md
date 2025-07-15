# # 最优数据混合的缩放法则

发布时间：2025年07月12日

`LLM理论` `人工智能` `机器学习`

> Scaling Laws for Optimal Data Mixtures

# 摘要

> 大型基础模型通常在多领域数据上进行训练，数据混合——即每个领域所占的比例——在模型性能中起到决定性作用。目前选择这种数据混合比例的标准方法依赖于试错法，这在大规模预训练中变得不切实际。我们提出了一种基于缩放定律的系统方法，用于确定任何目标领域的最优数据混合比例。我们的方法能够准确预测使用大小为【数学公式】的模型、【数学公式】个令牌以及特定领域权重向量【数学公式】进行训练时的损失。通过在三个不同且大规模的场景中展示其预测能力，我们验证了这些缩放定律的普遍性：大型语言模型（LLM）、原生多模态模型（NMM）以及大型视觉模型（LVM）的预训练。我们进一步展示了这些缩放定律可以外推到新的数据混合比例和不同规模：其参数可以通过少量的小规模训练运行准确估计，并用于预测在更大规模和未见过的领域权重下的性能。这些缩放定律允许我们根据给定的训练预算（【数学公式】，【数学公式】）推导出任何目标领域的最优领域权重，从而为昂贵的试错法提供了原理性的替代方案。

> Large foundation models are typically trained on data from multiple domains, with the data mixture--the proportion of each domain used--playing a critical role in model performance. The standard approach to selecting this mixture relies on trial and error, which becomes impractical for large-scale pretraining. We propose a systematic method to determine the optimal data mixture for any target domain using scaling laws. Our approach accurately predicts the loss of a model of size $N$ trained with $D$ tokens and a specific domain weight vector $h$. We validate the universality of these scaling laws by demonstrating their predictive power in three distinct and large-scale settings: large language model (LLM), native multimodal model (NMM), and large vision models (LVM) pretraining. We further show that these scaling laws can extrapolate to new data mixtures and across scales: their parameters can be accurately estimated using a few small-scale training runs, and used to estimate the performance at larger scales and unseen domain weights. The scaling laws allow to derive the optimal domain weights for any target domain under a given training budget ($N$,$D$), providing a principled alternative to costly trial-and-error methods.

[Arxiv](https://arxiv.org/abs/2507.09404)