# 大型语言模型校准的数据集测绘图谱：偏好数据的绘制与分析

发布时间：2025年05月29日

`LLM应用` `人工智能` `机器学习`

> Dataset Cartography for Large Language Model Alignment: Mapping and Diagnosing Preference Data

# 摘要

> 人类偏好数据在对齐大型语言模型（LLMs）与人类价值观方面起着关键作用。然而，收集此类数据往往成本高昂且效率低下，这构成了一个重大的可扩展性挑战。为了解决这一问题，我们引入了对齐数据图谱（Alignment Data Map），这是一个由GPT-4o辅助的工具，用于分析和诊断偏好数据。通过将GPT-4o作为LLM对齐的替代方案，我们根据现有偏好数据集中的指令计算LLM生成响应的对齐分数。然后，我们根据这些分数的均值和方差构建对齐数据图谱。实验表明，仅使用33%的数据，特别是高均值、低方差区域的样本，即可达到与使用整个数据集相当或更优的性能。这一发现表明，对齐数据图谱可以通过识别适合LLM对齐的高质量样本显著提升数据收集效率，而无需进行显式标注。此外，对齐数据图谱还可以诊断现有的偏好数据集。我们的分析表明，它能够有效检测到影响较小或可能标注错误的样本。源代码已在线提供。

> Human preference data plays a critical role in aligning large language models (LLMs) with human values. However, collecting such data is often expensive and inefficient, posing a significant scalability challenge. To address this, we introduce Alignment Data Map, a GPT-4o-assisted tool for analyzing and diagnosing preference data. Using GPT-4o as a proxy for LLM alignment, we compute alignment scores for LLM-generated responses to instructions from existing preference datasets. These scores are then used to construct an Alignment Data Map based on their mean and variance. Our experiments show that using only 33 percent of the data, specifically samples in the high-mean, low-variance region, achieves performance comparable to or better than using the entire dataset. This finding suggests that the Alignment Data Map can significantly improve data collection efficiency by identifying high-quality samples for LLM alignment without requiring explicit annotations. Moreover, the Alignment Data Map can diagnose existing preference datasets. Our analysis shows that it effectively detects low-impact or potentially misannotated samples. Source code is available online.

[Arxiv](https://arxiv.org/abs/2505.23114)