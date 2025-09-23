# 联邦学习在金融预测中的应用

发布时间：2025年09月19日

`其他` `金融科技`

> Federated Learning for Financial Forecasting

# 摘要

> 本文研究联邦学习（FL）在波动性金融市场趋势二分类中的应用。借助共享的长短期记忆（LSTM）分类器，我们对比了三种场景：(i) 基于所有数据联合训练的集中式模型，(ii) 仅用单个数据子集训练的单智能体模型，以及 (iii) 隐私保护型联邦学习协作——在此协作中，智能体仅交换模型更新，不共享原始数据。随后，我们通过增加市场特征扩展研究，刻意在智能体间引入非独立同分布数据（non-IID），并结合了个性化联邦学习与差分隐私。数值实验结果显示，联邦学习的准确性和泛化能力与集中式基线持平，且显著优于单智能体模型。结果表明，即便在真实的数据异质性和个性化需求场景中，协作式隐私保护学习也能为金融领域带来切实的集体价值。

> This paper studies Federated Learning (FL) for binary classification of volatile financial market trends. Using a shared Long Short-Term Memory (LSTM) classifier, we compare three scenarios: (i) a centralized model trained on the union of all data, (ii) a single-agent model trained on an individual data subset, and (iii) a privacy-preserving FL collaboration in which agents exchange only model updates, never raw data. We then extend the study with additional market features, deliberately introducing not independent and identically distributed data (non-IID) across agents, personalized FL and employing differential privacy. Our numerical experiments show that FL achieves accuracy and generalization on par with the centralized baseline, while significantly outperforming the single-agent model. The results show that collaborative, privacy-preserving learning provides collective tangible value in finance, even under realistic data heterogeneity and personalization requirements.

[Arxiv](https://arxiv.org/abs/2509.16393)