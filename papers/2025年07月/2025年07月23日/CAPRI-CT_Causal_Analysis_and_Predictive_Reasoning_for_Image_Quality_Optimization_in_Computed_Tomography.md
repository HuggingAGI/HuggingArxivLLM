# CAPRI-CT：CT图像质量优化的因果分析与预测推理

发布时间：2025年07月23日

`其他` `医学影像` `因果分析`

> CAPRI-CT: Causal Analysis and Predictive Reasoning for Image Quality Optimization in Computed Tomography

# 摘要

> 在CT成像中，如何在降低辐射剂量的同时提升图像质量一直是临床领域的重要挑战。本文提出了一种名为CAPRI-CT的新型因果感知深度学习框架，专注于CT图像质量优化的因果分析与预测推理。该框架整合了CT图像数据和采集元数据（如管电压、管电流及对比剂类型），以建模影响图像质量的潜在因果关系。通过变分自编码器（VAEs）的集成，从CT图像及其相关参数中提取特征并生成因果表示。这些特征经过融合后，可预测信噪比（SNR）并支持反事实推理，从而实现假设情景模拟，如调整对比剂类型或浓度、改变扫描参数等。CAPRI-CT采用集成学习方法进行训练和验证，展现出优异的预测性能。通过其预测能力和可解释性，CAPRI-CT为放射科医生和技师提供了实用的见解，助力他们设计更高效的CT扫描方案，而无需反复进行物理扫描。本研究的源代码和数据集已公开，访问地址为https://github.com/SnehaGeorge22/capri-ct。

> In computed tomography (CT), achieving high image quality while minimizing radiation exposure remains a key clinical challenge. This paper presents CAPRI-CT, a novel causal-aware deep learning framework for Causal Analysis and Predictive Reasoning for Image Quality Optimization in CT imaging. CAPRI-CT integrates image data with acquisition metadata (such as tube voltage, tube current, and contrast agent types) to model the underlying causal relationships that influence image quality. An ensemble of Variational Autoencoders (VAEs) is employed to extract meaningful features and generate causal representations from observational data, including CT images and associated imaging parameters. These input features are fused to predict the Signal-to-Noise Ratio (SNR) and support counterfactual inference, enabling what-if simulations, such as changes in contrast agents (types and concentrations) or scan parameters. CAPRI-CT is trained and validated using an ensemble learning approach, achieving strong predictive performance. By facilitating both prediction and interpretability, CAPRI-CT provides actionable insights that could help radiologists and technicians design more efficient CT protocols without repeated physical scans. The source code and dataset are publicly available at https://github.com/SnehaGeorge22/capri-ct.

[Arxiv](https://arxiv.org/abs/2507.17420)