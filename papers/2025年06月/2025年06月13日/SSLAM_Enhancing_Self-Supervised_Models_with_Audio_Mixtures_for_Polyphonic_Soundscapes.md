# SSLAM：利用音频混合提升自监督模型性能，针对多声部声音场景

发布时间：2025年06月13日

`其他` `音频处理` `多模态模型`

> SSLAM: Enhancing Self-Supervised Models with Audio Mixtures for Polyphonic Soundscapes

# 摘要

> 自监督预训练音频网络在多模态大语言模型等实际系统中得到了广泛应用。这些网络通常以冻结状态使用，假设自监督学习（SSL）预训练已充分赋予其处理真实世界音频的能力。然而，一个关键问题仍然存在：这些模型在现实条件下实际表现如何？在现实条件下，音频通常是多声音源的，涉及多个重叠的声音来源。目前的音频自监督学习方法通常在以单声音源为主的基准数据集上进行评估，例如环境声音和语音。因此，自监督模型在自然场景中常见特征的多声音源音频上的泛化能力仍未得到充分探索。这一限制引发了人们对自监督模型在更现实音频设置下实用稳健性的担忧。

为了解决这一差距，我们提出了从音频混合物进行自监督学习（SSLAM），这是音频自监督学习研究中的一个新方向。SSLAM旨在在保持对单声音源数据的强大性能的同时，提高模型从多声音源数据中学习的能力。我们在主要以单声音源为主的标准音频自监督学习基准数据集上对SSLAM进行了全面评估，并使用一系列高质量的公开可用的多声音源数据集对SSLAM与当前最优方法进行了全面的比较分析。SSLAM不仅提高了模型在多声音源音频上的性能，还在标准音频自监督学习基准上保持或超越了性能。值得注意的是，它在AudioSet-2M（AS-2M）上实现了高达3.9%的改进，达到了50.2的平均平均精度（mAP）。对于多声音源数据集，SSLAM在两种模式（线性评估和微调）下都达到了新的当前最优水平，性能提升高达9.1%（mAP）。


> Self-supervised pre-trained audio networks have seen widespread adoption in real-world systems, particularly in multi-modal large language models. These networks are often employed in a frozen state, under the assumption that the SSL pre-training has sufficiently equipped them to handle real-world audio. However, a critical question remains: how well do these models actually perform in real-world conditions, where audio is typically polyphonic and complex, involving multiple overlapping sound sources? Current audio SSL methods are often benchmarked on datasets predominantly featuring monophonic audio, such as environmental sounds, and speech. As a result, the ability of SSL models to generalize to polyphonic audio, a common characteristic in natural scenarios, remains underexplored. This limitation raises concerns about the practical robustness of SSL models in more realistic audio settings. To address this gap, we introduce Self-Supervised Learning from Audio Mixtures (SSLAM), a novel direction in audio SSL research, designed to improve, designed to improve the model's ability to learn from polyphonic data while maintaining strong performance on monophonic data. We thoroughly evaluate SSLAM on standard audio SSL benchmark datasets which are predominantly monophonic and conduct a comprehensive comparative analysis against SOTA methods using a range of high-quality, publicly available polyphonic datasets. SSLAM not only improves model performance on polyphonic audio, but also maintains or exceeds performance on standard audio SSL benchmarks. Notably, it achieves up to a 3.9\% improvement on the AudioSet-2M (AS-2M), reaching a mean average precision (mAP) of 50.2. For polyphonic datasets, SSLAM sets new SOTA in both linear evaluation and fine-tuning regimes with performance improvements of up to 9.1\% (mAP).

[Arxiv](https://arxiv.org/abs/2506.12222)