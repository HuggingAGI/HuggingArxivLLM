# QualityFM：基于自蒸馏的多模态生理信号基础模型——应对危重患者信号质量挑战

发布时间：2025年09月08日

`其他` `医疗健康`

> QualityFM: a Multimodal Physiological Signal Foundation Model with Self-Distillation for Signal Quality Challenges in Critically Ill Patients

# 摘要

> 光电容积脉搏波（PPG）与心电图（ECG）是重症监护室（ICU）和手术室（OR）中常规记录的生理信号。然而，信号质量差、不完整或不一致的情况频发，可能引发误报警或诊断偏差。目前已有的方法普遍存在泛化能力不足、依赖海量标记数据以及跨任务迁移效果不佳等局限。为解决这些难题，我们提出了QualityFM——一种针对这些生理信号的新型多模态基础模型，旨在习得对信号质量的通用理解能力。该模型在大规模数据集上预训练，涵盖超过2100万段30秒波形和179,757小时数据。我们的方法采用双轨架构处理不同质量的成对生理信号，并借助自蒸馏策略——由高质量信号编码器引导低质量信号编码器的训练。为高效处理长序列信号并捕捉关键的局部准周期模式，我们在基于Transformer的模型中融入了窗口化稀疏注意力机制。此外，复合损失函数将编码器输出的直接蒸馏损失与基于功率谱和相位谱的间接重建损失相结合，确保信号频域特征的保留。我们预训练了三个不同参数规模的模型（960万至3.19亿），并通过三个临床任务的迁移学习验证了其有效性与实用价值，具体包括：室性心动过速检测的误报警识别、心房颤动判别以及基于PPG和ECG信号的动脉血压（ABP）估计。

> Photoplethysmogram (PPG) and electrocardiogram (ECG) are commonly recorded in intesive care unit (ICU) and operating room (OR). However, the high incidence of poor, incomplete, and inconsistent signal quality, can lead to false alarms or diagnostic inaccuracies. The methods explored so far suffer from limited generalizability, reliance on extensive labeled data, and poor cross-task transferability. To overcome these challenges, we introduce QualityFM, a novel multimodal foundation model for these physiological signals, designed to acquire a general-purpose understanding of signal quality. Our model is pre-trained on an large-scale dataset comprising over 21 million 30-second waveforms and 179,757 hours of data. Our approach involves a dual-track architecture that processes paired physiological signals of differing quality, leveraging a self-distillation strategy where an encoder for high-quality signals is used to guide the training of an encoder for low-quality signals. To efficiently handle long sequential signals and capture essential local quasi-periodic patterns, we integrate a windowed sparse attention mechanism within our Transformer-based model. Furthermore, a composite loss function, which combines direct distillation loss on encoder outputs with indirect reconstruction loss based on power and phase spectra, ensures the preservation of frequency-domain characteristics of the signals. We pre-train three models with varying parameter counts (9.6 M to 319 M) and demonstrate their efficacy and practical value through transfer learning on three distinct clinical tasks: false alarm of ventricular tachycardia detection, the identification of atrial fibrillation and the estimation of arterial blood pressure (ABP) from PPG and ECG signals.

[Arxiv](https://arxiv.org/abs/2509.06516)