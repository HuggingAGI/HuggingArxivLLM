# GeoReg：通过权重约束的少量样本回归，利用大型语言模型实现社会经济估计。

发布时间：2025年07月17日

`LLM应用` `地理信息`

> GeoReg: Weight-Constrained Few-Shot Regression for Socio-Economic Estimation using LLM

# 摘要

> 社会经济指标（如地区GDP、人口和教育水平）对制定政策和促进可持续发展至关重要。本研究提出了GeoReg——一种整合卫星图像和网络地理空间信息的回归模型，即使在数据匮乏的发展中国家，也能有效估计这些指标。我们的方法利用大型语言模型（LLM）的先验知识，通过提取关键特征，在少量样本下实现精准估计。具体而言，模型能够识别数据特征与目标指标之间的正向、负向、混合或无关关系，并为每个类别设定权重约束。此外，模型还能捕捉非线性模式，识别特征交互并进行非线性变换。实验结果表明，GeoReg在三个不同发展阶段的国家中均优于基准模型，尤其在数据有限的低收入国家表现突出。

> Socio-economic indicators like regional GDP, population, and education levels, are crucial to shaping policy decisions and fostering sustainable development. This research introduces GeoReg a regression model that integrates diverse data sources, including satellite imagery and web-based geospatial information, to estimate these indicators even for data-scarce regions such as developing countries. Our approach leverages the prior knowledge of large language model (LLM) to address the scarcity of labeled data, with the LLM functioning as a data engineer by extracting informative features to enable effective estimation in few-shot settings. Specifically, our model obtains contextual relationships between data features and the target indicator, categorizing their correlations as positive, negative, mixed, or irrelevant. These features are then fed into the linear estimator with tailored weight constraints for each category. To capture nonlinear patterns, the model also identifies meaningful feature interactions and integrates them, along with nonlinear transformations. Experiments across three countries at different stages of development demonstrate that our model outperforms baselines in estimating socio-economic indicators, even for low-income countries with limited data availability.

[Arxiv](https://arxiv.org/abs/2507.13323)