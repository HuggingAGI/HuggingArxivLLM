# 时间序列预测中的隐私风险：用户级与记录级成员推理

发布时间：2025年09月04日

`其他`

> Privacy Risks in Time Series Forecasting: User- and Record-Level Membership Inference

# 摘要

> <翻译失败>

> Membership inference attacks (MIAs) aim to determine whether specific data were used to train a model. While extensively studied on classification models, their impact on time series forecasting remains largely unexplored. We address this gap by introducing two new attacks: (i) an adaptation of multivariate LiRA, a state-of-the-art MIA originally developed for classification models, to the time-series forecasting setting, and (ii) a novel end-to-end learning approach called Deep Time Series (DTS) attack. We benchmark these methods against adapted versions of other leading attacks from the classification setting.
  We evaluate all attacks in realistic settings on the TUH-EEG and ELD datasets, targeting two strong forecasting architectures, LSTM and the state-of-the-art N-HiTS, under both record- and user-level threat models. Our results show that forecasting models are vulnerable, with user-level attacks often achieving perfect detection. The proposed methods achieve the strongest performance in several settings, establishing new baselines for privacy risk assessment in time series forecasting. Furthermore, vulnerability increases with longer prediction horizons and smaller training populations, echoing trends observed in large language models.

[Arxiv](https://arxiv.org/abs/2509.04169)