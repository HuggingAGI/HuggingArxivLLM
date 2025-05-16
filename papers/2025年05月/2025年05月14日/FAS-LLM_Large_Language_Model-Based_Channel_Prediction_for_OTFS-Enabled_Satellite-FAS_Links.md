# FAS-LLM：基于大型语言模型的信道预测技术，应用于OTFS增强型卫星-FAS链路。

发布时间：2025年05月14日

`LLM应用` `卫星通信` `物联网`

> FAS-LLM: Large Language Model-Based Channel Prediction for OTFS-Enabled Satellite-FAS Links

# 摘要

> 本文提出了一种名为FAS-LLM的新型LLM架构，用于预测配备流体天线系统（FAS）的OTFS卫星下行链路中的未来信道状态。该方法采用一种结合参考端口选择和可分离主成分分析（PCA）的两阶段信道压缩策略，从高维OTFS信道中提取紧凑且具有延迟-多普勒感知的表示。这些表示随后被嵌入到适应LoRA的LLM中，从而实现信道系数的时间序列高效预测。性能评估表明，与包括GRU、LSTM和Transformer模型的经典基线相比，FAS-LLM表现更优，在预测时域内实现了高达10 dB的归一化均方误差（NMSE）提升和三次均方根误差（RMSE）的降低。此外，预测的信道保留了关键的物理层特性，在广泛的信噪比（SNR）范围内实现了遍历容量、频谱效率和中断概率的近最优性能。这些结果凸显了基于LLM的预测在未来的卫星物联网网络中实现延迟敏感和能量高效的链路自适应的潜力。

> This paper proposes FAS-LLM, a novel large language model (LLM)-based architecture for predicting future channel states in Orthogonal Time Frequency Space (OTFS)-enabled satellite downlinks equipped with fluid antenna systems (FAS). The proposed method introduces a two-stage channel compression strategy combining reference-port selection and separable principal component analysis (PCA) to extract compact, delay-Doppler-aware representations from high-dimensional OTFS channels. These representations are then embedded into a LoRA-adapted LLM, enabling efficient time-series forecasting of channel coefficients. Performance evaluations demonstrate that FAS-LLM outperforms classical baselines including GRU, LSTM, and Transformer models, achieving up to 10 dB normalized mean squared error (NMSE) improvement and threefold root mean squared error (RMSE) reduction across prediction horizons. Furthermore, the predicted channels preserve key physical-layer characteristics, enabling near-optimal performance in ergodic capacity, spectral efficiency, and outage probability across a wide range of signal-to-noise ratios (SNRs). These results highlight the potential of LLM-based forecasting for delay-sensitive and energy-efficient link adaptation in future satellite IoT networks.

[Arxiv](https://arxiv.org/abs/2505.09751)