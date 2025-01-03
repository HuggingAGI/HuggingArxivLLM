# MiTREE: 多输入Transformer生态区编码器，专为物种分布建模设计

发布时间：2024年12月25日

`其他

理由：这篇论文主要讨论的是利用机器学习方法（特别是多输入视觉Transformer模型）来预测物种分布，尤其是鸟类物种的遭遇率。虽然涉及了机器学习和模型的应用，但其核心内容与Agent、RAG、LLM应用或LLM理论没有直接关联。因此，将其分类为“其他”更为合适。` `生态学`

> MiTREE: Multi-input Transformer Ecoregion Encoder for Species Distribution Modelling

# 摘要

> 气候变化对生物多样性构成严重威胁，高效建模物种地理分布范围变得至关重要。大规模遥感图像和环境数据的普及推动了机器学习在物种分布模型（SDMs）中的应用，旨在预测物种在特定位置的存在。传统SDMs依赖专家观察，费时费力，但遥感和公民科学数据的进步为机器学习方法在SDM开发中提供了便利。然而，这些模型常难以利用不同输入间的空间关系——例如，气候数据如何影响卫星图像数据——而无需上采样或扭曲原始输入。此外，位置信息和生态特征在物种分布预测中至关重要，但这些因素尚未纳入最先进的方法中。本文提出MiTREE：一种基于多输入视觉Transformer的模型，配备生态区编码器。MiTREE无需上采样即可计算空间跨模态关系，并整合位置和生态背景。我们在SatBird夏季和冬季数据集上评估了模型，目标是预测鸟类物种遭遇率，结果表明我们的方法优于现有基线。

> Climate change poses an extreme threat to biodiversity, making it imperative to efficiently model the geographical range of different species. The availability of large-scale remote sensing images and environmental data has facilitated the use of machine learning in Species Distribution Models (SDMs), which aim to predict the presence of a species at any given location. Traditional SDMs, reliant on expert observation, are labor-intensive, but advancements in remote sensing and citizen science data have facilitated machine learning approaches to SDM development. However, these models often struggle with leveraging spatial relationships between different inputs -- for instance, learning how climate data should inform the data present in satellite imagery -- without upsampling or distorting the original inputs. Additionally, location information and ecological characteristics at a location play a crucial role in predicting species distribution models, but these aspects have not yet been incorporated into state-of-the-art approaches. In this work, we introduce MiTREE: a multi-input Vision-Transformer-based model with an ecoregion encoder. MiTREE computes spatial cross-modal relationships without upsampling as well as integrates location and ecological context. We evaluate our model on the SatBird Summer and Winter datasets, the goal of which is to predict bird species encounter rates, and we find that our approach improves upon state-of-the-art baselines.

[Arxiv](https://arxiv.org/abs/2412.18995)