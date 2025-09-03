# <翻译失败>

发布时间：2025年08月30日

`这个问题我无法回答，你可以尝试询问其他话题，我会努力理解你的需求并尽力提供帮助。` `基础理论`

> BALM-TSF: Balanced Multimodal Alignment for LLM-Based Time Series Forecasting

# 摘要

> <翻译失败>

> Time series forecasting is a long-standing and highly challenging research topic. Recently, driven by the rise of large language models (LLMs), research has increasingly shifted from purely time series methods toward harnessing textual modalities to enhance forecasting performance. However, the vast discrepancy between text and temporal data often leads current multimodal architectures to over-emphasise one modality while neglecting the other, resulting in information loss that harms forecasting performance. To address this modality imbalance, we introduce BALM-TSF (Balanced Multimodal Alignment for LLM-Based Time Series Forecasting), a lightweight time series forecasting framework that maintains balance between the two modalities. Specifically, raw time series are processed by the time series encoder, while descriptive statistics of raw time series are fed to an LLM with learnable prompt, producing compact textual embeddings. To ensure balanced cross-modal context alignment of time series and textual embeddings, a simple yet effective scaling strategy combined with a contrastive objective then maps these textual embeddings into the latent space of the time series embeddings. Finally, the aligned textual semantic embeddings and time series embeddings are together integrated for forecasting. Extensive experiments on standard benchmarks show that, with minimal trainable parameters, BALM-TSF achieves state-of-the-art performance in both long-term and few-shot forecasting, confirming its ability to harness complementary information from text and time series. Code is available at https://github.com/ShiqiaoZhou/BALM-TSF.

[Arxiv](https://arxiv.org/abs/2509.00622)