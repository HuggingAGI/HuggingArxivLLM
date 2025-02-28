# # 摘要
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年02月27日

`LLM应用` `机器学习`

> Efficient Machine Learning Approach for Yield Prediction in Chemical Reactions

# 摘要

> 近年来，机器学习（ML）在化学反应产率预测中的应用已成为一个备受关注的前沿领域。然而，反应数据集的不平衡与稀疏性问题为这一领域的研究带来了诸多挑战。我们提出了一种创新方法，通过化学反应的化学语言表示，结合自然语言处理模型ULMFiT的潜力，为产率预测提供了一种定制化解决方案。

为支持这一研究，我们构建了一个全新的反应数据集，包含从过去十年文献中精选的860多个反应，这些反应均属于一类具有重要当代意义的催化meta-C(sp2)-H键活化反应。针对数据集规模较小、高产率分布偏态及稀疏性等特性，我们开发了两项关键创新：

(i) 一种时间与资源高效的预训练策略，为下游迁移学习提供强有力支持；

(ii) 一种创新的CFR（分类后回归）模型，其预测精度超越传统直接回归方法，达到了行业领先水平。

在预训练策略方面，我们突破了传统做法，未采用ChEMBL数据集中140万个未标记分子，而是构建了一个11万规模的SSP1数据集，通过PubChem数据库的子结构挖掘而成，不仅性能相当，且大幅提升了训练效率。

实验结果表明，ULMFiT-SSP1回归器的CFR模型在产率预测中表现优异：在标题反应中，CFR主要类别的RMSE为8.40，次要类别为6.48，以53%的产率作为分类边界。此外，该模型展现出强大的泛化能力，在多个基准数据集上均实现了显著性能提升。


> Developing machine learning (ML) models for yield prediction of chemical reactions has emerged as an important use case scenario in very recent years. In this space, reaction datasets present a range of challenges mostly stemming from imbalance and sparsity. Herein, we consider chemical language representations for reactions to tap into the potential of natural language processing models such as the ULMFiT (Universal Language Model Fine Tuning) for yield prediction, which is customized to work across such distribution settings. We contribute a new reaction dataset with more than 860 manually curated reactions collected from literature spanning over a decade, belonging to a family of catalytic meta-C(sp2)-H bond activation reactions of high contemporary importance. Taking cognizance of the dataset size, skewness toward the higher yields, and the sparse distribution characteristics, we developed a new (i) time- and resource-efficient pre-training strategy for downstream transfer learning, and (ii) the CFR (classification followed by regression) model that offers state-of-the-art yield predictions, surpassing conventional direct regression (DR) approaches. Instead of the prevailing pre-training practice of using a large number of unlabeled molecules (1.4 million) from the ChEMBL dataset, we first created a pre-training dataset SSP1 (0.11 million), by using a substructure-based mining from the PubChem database, which is found to be equally effective and more time-efficient in offering enhanced performance. The CFR model with the ULMFiT-SSP1 regressor achieved an impressive RMSE of 8.40 for the CFR-major and 6.48 for the CFR-minor class in yield prediction on the title reaction, with a class boundary of yield at 53 %. Furthermore, the CFR model is highly generalizable as evidenced by the significant improvement over the previous benchmark reaction datasets.

[Arxiv](https://arxiv.org/abs/2502.19976)