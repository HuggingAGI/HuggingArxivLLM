# AI生成的跌倒数据：评估LLMs与扩散模型在可穿戴跌倒检测中的应用

发布时间：2025年05月06日

`LLM应用` `健康/医疗` `数据科学`

> AI-Generated Fall Data: Assessing LLMs and Diffusion Model for Wearable Fall Detection

# 摘要

> 训练跌倒检测系统面临现实世界数据稀缺的挑战，尤其是来自老年人的跌倒数据。本研究旨在探索大型语言模型（LLMs）生成合成跌倒数据的潜力，以应对这一挑战。我们评估了文本到动作（T2M、SATO、ParCo）和文本到文本模型（GPT4o、GPT4、Gemini）在模拟现实跌倒场景中的性能。通过生成合成数据集并与四个现实世界基准数据集结合，采用长短期记忆（LSTM）模型评估其对跌倒检测性能的影响。此外，我们将LLM生成的合成数据与基于扩散的方法进行对比，评估其与真实加速度计分布的对齐程度。研究发现，数据集特征显著影响合成数据的有效性。LLM生成的数据在低频设置（如20Hz）下表现最佳，但在高频数据集（如200Hz）中表现出不稳定性。文本到动作模型生成的生物力学数据比文本到文本模型更真实，但对跌倒检测的影响各不相同。基于扩散的合成数据最接近真实数据，但并不能始终提升模型性能。通过消融研究，我们进一步证实合成数据的有效性取决于传感器放置和跌倒表示。这些发现为优化跌倒检测模型的合成数据生成提供了重要见解。

> Training fall detection systems is challenging due to the scarcity of real-world fall data, particularly from elderly individuals. To address this, we explore the potential of Large Language Models (LLMs) for generating synthetic fall data. This study evaluates text-to-motion (T2M, SATO, ParCo) and text-to-text models (GPT4o, GPT4, Gemini) in simulating realistic fall scenarios. We generate synthetic datasets and integrate them with four real-world baseline datasets to assess their impact on fall detection performance using a Long Short-Term Memory (LSTM) model. Additionally, we compare LLM-generated synthetic data with a diffusion-based method to evaluate their alignment with real accelerometer distributions. Results indicate that dataset characteristics significantly influence the effectiveness of synthetic data, with LLM-generated data performing best in low-frequency settings (e.g., 20Hz) while showing instability in high-frequency datasets (e.g., 200Hz). While text-to-motion models produce more realistic biomechanical data than text-to-text models, their impact on fall detection varies. Diffusion-based synthetic data demonstrates the closest alignment to real data but does not consistently enhance model performance. An ablation study further confirms that the effectiveness of synthetic data depends on sensor placement and fall representation. These findings provide insights into optimizing synthetic data generation for fall detection models.

[Arxiv](https://arxiv.org/abs/2505.04660)